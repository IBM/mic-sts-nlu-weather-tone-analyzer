# Watson Assistant (formerly Conversation)

![](https://raw.githubusercontent.com/hovig/mic-sts-nlu-weather-tone-analyzer/master/img/assistant-catalog.png)

<hr>

### Open IBM Cloud Service Catalog:

> [Watson Assistant catalog](https://console.bluemix.net/catalog/services/watson-assistant-formerly-conversation)

### Setting up the Assistant service:

* In your IBM Cloud console, open the Conversation service instance where you imported the workspace.
* This project uses an existing workspace called `Car Dashboard` that has already defined the intents, entities and the dialog flow. From more information check [here](https://console.bluemix.net/docs/tutorials/android-watson-chatbot.html#build-a-voice-enabled-android-chatbot).
* Click the menu icon in the upper-right corner of the workspace tile, and then select **View details**.

    ![Car dashboard workspace id](https://raw.githubusercontent.com/hovig/mic-sts-nlu-weather-tone-analyzer/master/img/assistant-workspace_id.png)

* Click the ![Copy](https://raw.githubusercontent.com/hovig/mic-sts-nlu-weather-tone-analyzer/master/img/copy_icon.png) icon to copy the workspace ID to the clipboard.

* In your Node-RED editor, paste the workspace ID into the WORKSPACE_ID variable in the `Assistant` node. Save it and deploy Node-RED.
* In your Node-RED editor also, you can choose from the list of different voices in the `Assistant` node that come with a `name`, a `language` and a `gender`.
