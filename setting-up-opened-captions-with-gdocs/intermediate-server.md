# Setting up opened captions // intermediate server

[github repository ](https://github.com/voxmedia/c-span_opened_captions_server)


![intermediate_server_repo](/assets/intermediate_server_repo.png)





## Download the intermediate server


```bash
git clone git clone https://github.com/voxmedia/c-span_opened_captions_server.git 
```


```bash
cd c-span_opened_captions_server
```

```bash
npm install
```

```bash
npm start
```
check [`http://localhost:5000/`](http://localhost:5000/) to see if it’s working

##  Options for deployment

Chose between [ngrok (local)](/setting-up-opened-captions-with-gdocs/intermediate-server/ngrok.md) or [heroku (remote)](/setting-up-opened-captions-with-gdocs/intermediate-server/heroku.md).

<!-- more details, eg use ngrok in dev and heroku or EC2 in prod?-->


## Extra dev option
Intermedia server can be tweaked to customise the output.
For instance you could add auto punctuation [using punctuator](http://bark.phon.ioc.ee/punctuator).

## Resources

- [https://github.com/voxmedia/c-span_opened_captions_server ](https://github.com/voxmedia/c-span_opened_captions_server)