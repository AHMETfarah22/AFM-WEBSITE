# AFM-WEBSITE
Kani waa websiti an u sameyay AFMcoding COMPANEY kaso o lo sameayy si khatar ah

{
  "name": "AFM CODING Tools",
  "description": "Developer tools and enhancements by Ahmed Farah (AFM CODING)",
  "version": "1.0",
  "manifest_version": 3,
  "permissions": ["storage", "notifications", "activeTab"],
  "background": {
    "service_worker": "background.js"
  },
  "action": {
    "default_popup": "popup.html",
    "default_icon": {
      "16": "/icons/icon-16x16.png",
      "48": "/icons/icon-48x48.png",
      "128": "/icons/icon-128x128.png"
    }
  },
  "content_scripts": [
    {
      "matches": ["<all_urls>"],
      "js": ["content.js"]
    }
  ],
  "icons": {
    "16": "/icons/icon-16x16.png",
    "48": "/icons/icon-48x48.png",
    "128": "/icons/icon-128x128.png"
  }
}
