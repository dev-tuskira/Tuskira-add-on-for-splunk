# 🧩 Tuskira Add-on for Splunk

## Latest Version: 1.0.4

Built with UCC Framework 5.69.1

### What's New in v1.0.4
- ✅ Added: Splunk metadata fields for event traceability (sid, search_name, app, user, server_uri)
- ✅ Enhanced: Support for UUID generation on receiver side using sid/rid
- ✅ Improved: Notable event lookups via orig_sid/orig_rid for persistent event tracking
- ✅ Compatible: Works with Enterprise Security notable event framework

### Previous Releases

**v1.0.3**
- ✅ Fixed: Helper files now in correct location for proper execution
- ✅ Improved: Complete logging for all alert executions
- ✅ Added: Event count logging and zero-event handling
- ✅ Enhanced: Better error handling and exception logging
- ✅ Compatible: Works correctly in digest mode

---

## Installation Instructions

### Step 1. Download the App
Download the latest version of the Splunk Add-on:
**`Tuskira-Add-on-for-Splunk-1.0.4.spl`**

---

### Step 2. Log in to Splunk Web
1. Log in to your **Splunk Web UI**.
2. Navigate to the top menu and select **Apps → Manage Apps**.

---

### Step 3. Install the Add-on
1. Click **Install app from file**.
2. Click **Choose File** and select the downloaded file:
   **`Tuskira-Add-on-for-Splunk-1.0.4.spl`**
3. Click **Upload**.

---

### Step 4. Confirm Installation
Once the upload completes, the app will appear in your **Apps** list as
**Tuskira Add-on for Splunk**.

---

## Configuration

After installation:
1. Navigate to **Apps → Tuskira Add-on for Splunk**
2. Click the **Configuration** tab
3. Enter your **API URL** (e.g., `https://api.tuskira.ai/v2/alerts`)
4. Enter your **API Key**
5. Click **Save**

---

## Features

### Alert Actions
- **Tuskira Alert Action**: Send correlation search results to Tuskira for investigation
- **Tuskira Adaptive Response Action**: Send Enterprise Security notable events to Tuskira with CAM metadata

### Compatibility
- Splunk Enterprise 8.x, 9.x
- Splunk Enterprise Security (optional, for Adaptive Response)
- Python 3

---

✅ **You're ready!**
Configure alert actions in your correlation searches or ES notables to send events to Tuskira for automated investigation and enrichment.
