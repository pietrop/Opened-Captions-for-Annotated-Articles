# Connect google doc app script to intermediate server


## Setup


- Open [Demo google doc](https://docs.google.com/document/d/1kWFMixw7gVrzi3qsSQz9BnS-pEUSq3QL-O_-f_SNtJ0/edit?usp=sharing)

-  **Tools** → **script editor**


![google_app_script_editor](/assets/google_app_script_editor.png)

- Get [Google doc script](https://github.com/voxmedia/c-span_opened_captions_server/blob/master/google_app_script/main.js) to add to it.

  - click on **raw**, select all, copy and paste in script `editor`.
  - Line 27 edit URL.

    ```js
    var capServer = 'http://8f209ae3.ngrok.io';
    ```


- Click **save**.
  - Click **run** to test it out.
  ![](/assets/google_app_script_run.png)
  
  - [Authorise permissions](https://developers.google.com/apps-script/guides/client-verification)


## Setup time trigger


- Setup a 1 minute triggered event in google app script for `appendToDocument` function under 

 - **Edit** -> **All your triggers**

![google_app_script_funciton_time_trigger](/assets/google_app_script_funciton_time_trigger.png)
.




## Documentation

- [see readme of repository](https://github.com/OpenNewsLabs/c-span_opened_captions_server#connect-google-doc-app-script-to-ngrok-server)
- [Google documentation on how to use google app scripts](https://developers.google.com/apps-script/overview)
- [Google OAuth, client verification](https://developers.google.com/apps-script/guides/client-verification)
- [Google app script time triggered events](https://deveopers.google.com/apps-script/guides/triggers/installable#time-driven_triggers)





