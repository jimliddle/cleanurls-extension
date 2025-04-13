# cleanurls-extension
A Chrome / Microsoft Edge extension that cleans affiliate tracking from URL's because I did not want an app store chrome extension tracking me.

When active, it cleans affiliate and tracking parameters from URLs as you browse. It works by intercepting web requests and stripping common tracker query parameters like utm_source, affid, ref, etc.

This is using declarativeNetRequest which is the the correct way to filter or redirect URLs 

To install:

- Enable Developer Mode

- Click Load unpacked and select the clean-urls-extension/ folder
