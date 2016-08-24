#uBlock Origin Edge Support

<img src="https://github.com/devanshdesai/uBlock/blob/master/ublock.png">


I added Microsoft Edge support for uBlock Origin. Chrome doesn't have good touchpad support on Windows 10 but Edge does so I decided to port uBlock Origin over to Microsoft Edge.

### Instructions for Installation

1. In Microsoft Edge, go to the URL 'about:flags'.
2. Scroll down and enable 'Enable extension developer features'.
3. Go to the extensions menu in Edge and click on 'Load extension' at the bottom.
4. Browse to 'platform > chromium' from this repository's main directory and click 'Select folder'.
5. Click on the gear next to the uBlock Origin extension in the extensions list and enable it.
6. Right click on the extension in the extensions menu and click 'Show button next to the address bar'.
7. Enjoy uBlock Origin on Microsoft Edge!

You will have to complete steps 5 and 6 every time you start up Edge. This is an issue with Edge because it doesn't allow sideloaded extensions to automatically start up. Once Microsoft opens up the Edge platform to allow 3rd party extensions in the Windows 10 Store application, you will be able to install uBlock Origin much faster.

A solution is to always keep Edge open as I usually do and just put your computer to sleep when you're not using it. This removes the need to enable uBlock Origin every time.


## License

[GPLv3](https://github.com/gorhill/uBlock/blob/master/LICENSE.txt).
