# Node-RED Starter

### Open IBM Cloud Service Catalog:

> [Click to create the Node-RED boilerplate starter](https://console.bluemix.net/catalog/starters/node-red-starter).

<hr>

![](https://raw.githubusercontent.com/hovig/mic-sts-nlu-weather-tone-analyzer/master/img/node-red-catalog.png)

<hr>

![](https://raw.githubusercontent.com/hovig/mic-sts-nlu-weather-tone-analyzer/master/img/node-red-running-instance.png)

<hr>

* Click on the `Visit App URL`
* Open the Node-RED editor and setup your own `username` and `password`
* On the top right side of the editor, click on: `Burger Menu` -> `Import` -> `Clipboard`
* Copy the code from the [scripts/flow.json](https://raw.githubusercontent.com/hovig/mic-sts-nlu-weather-tone-analyzer/master/scripts/flow.json) in Github
* Paste the code in the `Clipboard` in the Node-RED editor

![](https://raw.githubusercontent.com/hovig/mic-sts-nlu-weather-tone-analyzer/master/img/mic-audio-full-code.png)

<hr>

### Important Notes that are needed for the service nodes in Node-RED editor:

* Each service will automatically create its credentials: `Username` and `Password`
* If you don't see the service credentials, you can create a new one: `Create Credentials`
* Internet of Things Platform will require to create an `api key` and `api token`. There's an how-to guide included on [IoT page](https://github.com/hovig/mic-sts-nlu-weather-tone-analyzer/blob/master/steps/iot.md#how-to).
* For the missing nodes (dashed), click on: `Burger Menu` -> `Manage Palette` -> `Install`
  <br>Then, type in the search field (search modules) to install the `microphone`, `play-audio`, `bluemix-dashboard`
