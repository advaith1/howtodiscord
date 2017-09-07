# Finding your Version and Build

When reporting and reproducing bugs, you should include your Discord release channel, version, and build.
Here's how to get them:

1. Press `Ctrl+Shift+I` (`Command+Shift+I` on macOS)
2. click Console
3. Scroll down
4. Paste this in:
`js
var v=new Date().getTime();webpackJsonp([],{[v]:(a,b,d)=>{for(let f=0,g={};;){g=d(f++)||{};let h=g._globalOptions;try{k=require("electron").remote.app.getVersion()}catch(l){k="Web"};if(h){if(h.environment==="ptb"){relchannel="PTB"}else{relchannel=h.environment.charAt(0).toUpperCase()+h.environment.slice(1)};console.info("Current environment info:\nRelease channel: "+relchannel+"\nApp Version: "+k+"\nBuild Number: "+h.release);if((k=="Web"&&((h.environment=="canary")||(h.environment=="ptb")))==!0){console.warn("Running on Canary web /PTB web is not supported, please do not submit bugs specific to these platforms!")};break}}}},[v])
`
