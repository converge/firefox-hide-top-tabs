## Firefox, Hide Top Tabs

This is a short tutorial to hide top tabs on Firefox and move the tabs feature to the left side of the brower with the Tree Style Tab extension.

![img](https://github.com/converge/firefox-hide-top-tabs/blob/master/screenshots/firefox-hidden-top-tabs.png)

### Tutorial

1. Open Firefox.
2. From the *Help* menu, choose *Troubleshooting Information*. The Troubleshooting Information tab will open.
3. Under the *Application Basics* section, click on Show in Finder. A window will open that contains your profile folder.
4. Create a new folder named *chrome*
5. Create a file named *userChrome.css*
6. In *userChome.css* file add these CSS properties:

```css
.tabbrowser-tab {
    display: none;
}

.tabs-newtab-button {
    display: none;
}
```
7. Restart Firefox.
8. Install [Tree Style Tab](https://addons.mozilla.org/en/firefox/addon/tree-style-tab/) extension
9. enjoy it :)
