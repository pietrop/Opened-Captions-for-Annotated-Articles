# Ngrok

>Secure tunnels to localhost
”I want to expose a local server behind a NAT or firewall to the internet.”


![Ngrok overview](/assets/ngrok_demo.png)

```bash
npm install -g ngrok
```

`cd` to folder

<!-- TODO: check if might need to start the server, `npm start` in separate terminal tab? -->

```bash
ngrok http 5000
```

This will give you a url like this `http://c8b8351d.ngrok.io/`   
which you can add to the google app script, 
[as described in next section](/setting-up-opened-captions-with-gdocs/google-app-script.md).

![Ngrok terminal](/assets/ngrok_terminal.png)



## Documentation
- [ngrok.com](http://ngrok.com) and [documentation](https://ngrok.com/docs)
