# Free win10 tutorial
heres a way how to emulate windows 10 in browser without install
1. open browserling.com
2. copy this string: `file://C:/Windows/System32/cmd.exe`
3. paste it into urllbar which has `http://`
4. press test now
5. wait
6. download cmd.exe from emulated chrome
7. open it
8. type explorer
9. open js console
10. type this into js console
```javascript
window.onerror = function() {};
Date = {};
```
11. you're done!
