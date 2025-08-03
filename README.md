# uBlockBypass
Manual for uBlock installation (Chrome) 

1.Go to [https://github.com/gorhill/uBlock/tree/master/dist#install](https://github.com/gorhill/uBlock/releases)
2. Download latest relase (file name ends with ".chromium.zip") <br/>
3. Unzip archive.
4. Rename the unzipped directory to ublock.

5. Open Chrome
6. In searchbar type "chrome://flags/" and press enter
7. Under "Temporarily unexpire M137 flags click enable
8. Relaunch Chrome
9. In searchbar type "chrome://flags/" and press enter
10. On top there is a search bar with "Search flags" hint text. Type "mv2" in that field.
11. There will be results:
 a)  Extension Manifest V2 Deprecation Warning Stage - set it to Disabled
 b)  Extension Manifest V2 Deprecation Disabled Stage - set it to Disabled
 c) Extension Manifest V2 Deprecation Unsupported Stage - set it to Disabled
 d) Allow legacy extension manifest versions - leave it on Default or set it to Enabled if its not in Default mode already.
12. Relaunch Chrome

13. In Chrome click 3 dots to open menu and go to Extensions.
14. Click to enable Developer mode.
15. Click Load unpacked extension....
16. In the file selector dialog:
Select the ublock directory you created in 4.
Click Open.

The extension will now be available in your Chromium/Chromium-based browser.
