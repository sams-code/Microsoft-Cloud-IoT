# Microsoft-Cloud-IoT

It is realy cool!
You can use these instruction to get your sensor data to a Azure hosted web page and monitor what is going on in real time from anywhere in the world.
The sensor data goes to the Azure server via a secured MQTT message.

<img src="images/plot1.jpg" width="800">

After setting up the webapp on Azure run the below commands.

git clone https://github.com/Azure-Samples/web-apps-node-iot-hub-data-visualization.git
cd web-apps-node-iot-hub-data-visualization
git remote add webapp <Git clone URL>
git push webapp master:master

There is also an example of C code to push to Azure Cloud

