Be sure to run Chrome on MacOS with ([more info](https://stackoverflow.com/questions/35432749/disable-web-security-in-chrome-48)): `open -na Google\ Chrome --args --user-data-dir=/tmp/temporary-chrome-profile-dir --disable-web-security --disable-site-isolation-trials`

To get rid of the `component-preload.js not found (404 not found)` error add `?sap-ui-xx-componentPreload=off` to the end of the path so that the URL is `...index.html?sap-ui-xx-componentPreload=off`.
