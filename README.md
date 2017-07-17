# Mosquitto

Run `mosquitto -v -c mosquitto-custom.conf` to have a local mosquitto for this showcase.

This will run the broker listening on port 9001 for _websocket_ connections, and on port 9000 for _mqtt_ connections.

# Browser

Just open `index.html` in a browser and you will receive messages on the topic `my_topic`.

## Why?
The mqtt.js library is already prepared for this showcase to work out-of-the-box.

See [https://www.npmjs.com/package/mqtt#webpack](https://www.npmjs.com/package/mqtt#webpack) for a tutorial how to build it with `webpack`.