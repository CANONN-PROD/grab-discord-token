bookmark version:
## Installation

> [!TIP]
> Make sure your Bookmarks Bar is visible! 
> Press `Ctrl + Shift + B` (Windows/Linux) or `Cmd + Shift + B` (Mac) to toggle it on.


1. **Copy** the code below:
   ```javascript
   javascript:(function(){let t,w=webpackChunkdiscord_app;w.push([[Symbol()],{},o=>{try{Object.values(o.c).some(e=>e.exports?.setToken&&(t=e.exports.getToken()))}catch{}}]);if(!t){alert('Token not found. Are you on Discord?');return;}let n=document.createElement('div');n.id='tkn-notify';n.innerHTML=`<div style="position:fixed;top:0;left:0;right:0;background:#5865F2;color:#fff;padding:15px 20px;font-family:sans-serif;font-size:14px;z-index:999999;box-shadow:0 4px 12px rgba(0,0,0,0.3);display:flex;align-items:center;justify-content:space-between;"><div><strong>Discord Token:</strong> <code style="background:rgba(0,0,0,0.2);padding:4px 8px;border-radius:4px;font-family:monospace;user-select:all;cursor:text;">${t}</code></div><button id="tkn-close" style="background:rgba(255,255,255,0.2);border:none;color:#fff;padding:8px 16px;border-radius:4px;cursor:pointer;font-size:12px;">Dismiss</button></div>`;document.body.appendChild(n);document.getElementById('tkn-close').onclick=function(){document.getElementById('tkn-notify').remove()};})();

2. Right click on your bookmarks bar

3. Press new site or add site

4. Paste the code

5. Go to <a href="https://discord.com/channels/@me"><b>Discord</b></a> and click on the bookmark

dev console version:

> [!TIP]
> Make sure that you have pasting allowed in your console first.
> Type `allow pasting` into your console for this to work

1. press `Ctrl+Shift+I` and enter this code into the console: 
  ```javascript
  javascript:(function(){let t,w=webpackChunkdiscord_app;w.push([[Symbol()],{},o=>{try{Object.values(o.c).some(e=>e.exports?.setToken&&(t=e.exports.getToken()))}catch{}}]);if(!t){alert('Token not found. Are you on Discord?');return;}let n=document.createElement('div');n.id='tkn-notify';n.innerHTML=`<div style="position:fixed;top:0;left:0;right:0;background:#5865F2;color:#fff;padding:15px 20px;font-family:sans-serif;font-size:14px;z-index:999999;box-shadow:0 4px 12px rgba(0,0,0,0.3);display:flex;align-items:center;justify-content:space-between;"><div><strong>Discord Token:</strong> <code style="background:rgba(0,0,0,0.2);padding:4px 8px;border-radius:4px;font-family:monospace;user-select:all;cursor:text;">${t}</code></div><button id="tkn-close" style="background:rgba(255,255,255,0.2);border:none;color:#fff;padding:8px 16px;border-radius:4px;cursor:pointer;font-size:12px;">Dismiss</button></div>`;document.body.appendChild(n);document.getElementById('tkn-close').onclick=function(){document.getElementById('tkn-notify').remove()};})();

