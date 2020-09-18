####STEP 1

```ssh
git clone https://github.com/vyshakhbabji/simpleRC-OAuth-JS.git

> cd [srcDir] 
> npm install
```

####STEP 2
Edit ClientID and ClientSecret on login.html

####STEP 3
Setup redirect URL for your app as `http://localhost:[$PORT-NUMBER]/src/oauth/redirect.html`

####STEP 4
```ssh
> http-server [$PORT-NUMBER] or npm start [$PORT-NUMBER]
```