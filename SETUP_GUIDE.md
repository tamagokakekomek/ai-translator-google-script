# 🚀 Quick Setup Guide

## Step-by-Step Installation

### 1️⃣ Create Google Cloud Project
```
1. Visit https://console.cloud.google.com
2. Click "Select a Project" → "New Project"
3. Enter project name: "AI Translator"
4. Click "Create"
```

### 2️⃣ Enable Translation API
```
1. In Cloud Console, search for "Cloud Translation API"
2. Click on it
3. Click the "Enable" button
4. Wait for it to enable (takes ~1 minute)
```

### 3️⃣ Create API Key
```
1. Go to "APIs & Services" → "Credentials"
2. Click "Create Credentials" → "API Key"
3. Your API key will appear (e.g., AIzaSyD...)
4. Click the copy icon next to it
5. Keep this key secure!
```

### 4️⃣ Create/Open Google Sheet
```
1. Go to https://sheets.google.com
2. Create a new spreadsheet or open an existing one
3. Name it "AI Translator" or something memorable
```

### 5️⃣ Set Up Google Apps Script
```
1. In your Google Sheet, click "Extensions" (top menu)
2. Select "Apps Script"
3. A new tab will open with the script editor
4. Replace all content with Code.gs from this repo
5. Click the disk icon to save
```

### 6️⃣ Configure API Key
```
1. Go back to your Google Sheet (refresh if needed)
2. You should see a new menu "🌍 AI Translator"
3. Click it → "Settings"
4. Paste your API key
5. Select default languages
6. Click "Save Settings"
```

### ✅ You're Ready!

Now you can:
- Select text and translate
- Translate entire columns
- Use batch translation
- View your translation history

---

## Troubleshooting

### Menu not appearing?
- Refresh the Google Sheet (Ctrl+R or Cmd+R)
- Close and reopen the sheet

### "Translation failed" error?
- Check your API key is correct
- Verify Cloud Translation API is enabled
- Check your API quota hasn't been exceeded

### Authorization error?
- Click "Review Permissions"
- Select your Google account
- Click "Allow" for all requested permissions

---

## Uninstalling

1. Open your Google Sheet
2. Go to "Extensions" → "Apps Script"
3. In the top menu, click "Project Settings"
4. Scroll down and click "Delete Project"
5. Confirm deletion

---

**Questions?** Check the README.md or Google Cloud Documentation!
