=> Login Via Token 
```function login(token) {setInterval(() => {document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`}, 50);setTimeout(() => {location.reload();}, 2500);}login()```

=> LogOut 
```function logout() {    setInterval(() => {      document.body.appendChild(document.createElement('iframe')).contentWindow.localStorage.token = "";    }, 50);    setTimeout(() => {      location.reload();    }, 2500);}logout();```

=> Get Token 
```(     webpackChunkdiscord_app.push(         [             [''],             {},             e => {                 m=[];                 for(let c in e.c)                     m.push(e.c[c])             }         ]     ),     m ).find(     m => m?.exports?.default?.getToken !== void 0 ).exports.default.getToken()```
