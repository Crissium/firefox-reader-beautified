# Firefox Reader View Beautified

Firefox's Reader View does an excellent job of stripping away the clutter from web pages, but the UI isn't quite as polished as it could be.

This simple userstyle (~100 lines) aims to improve the readability and aesthetics of Reader View. It is highly opinionated, but should be a good starting point for anyone looking to customise Reader View to their liking.

# Screenshots

![1](/screenshots/1.png)
![2](/screenshots/2.png)
![3](/screenshots/3.png)

# Usage

1. Go to `about:profiles` in Firefox.
2. Open your profile folder.
3. Create a folder called `chrome` if it doesn't already exist.
4. Save [`userContent.css`](userContent.css) to the `chrome` folder.
5. Go to `about:config` in Firefox.
6. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
7. Restart Firefox.