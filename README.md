# WindowsSecurityBookmarklet
Bookmarklet for posting to https://reddit.com/r/WindowsSecurity


Bookmarklet:

```javascript
javascript:location.href='http://www.reddit.com/r/WindowsSecurity/submit?url='+encodeURIComponent(location.href)+'&title='+encodeURIComponent(document.title)
```

Or, drag this link to your bookmarks:

<a href="javascript:location.href='http://www.reddit.com/r/WindowsSecurity/submit?url='+encodeURIComponent(location.href)+'&title='+encodeURIComponent(document.title)">Submit to /r/WindowsSecurity</a>
