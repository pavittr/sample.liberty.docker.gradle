# Using Gradle and Docker to build apps with Liberty

This is a simple application to show setting up an application that uses JAX-RS and runs on LIberty. The application uses Gradle to build and can be deployed in a Docker container.

## Deploying to Bluemix

You can also deploy this aplication to Bluemix using Bluemix's IBM Container Service.

**Please note** that before you deploy, you need to have created a Container Namespace in Bluemix. This can only be set once and so should be done manually before you run this sample. To do this login to bluemix at (https://new-console.ng.bluemix.net/#overview) and select `Compute`. During the wizard you will be asked to provide a namespace. This namespace will be used as an area to store your built Docker images inside the ICS registry. Once this has been completed, you can come back here and use the Deploy to Bluemix button.

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy)

## Testing the application is running

Once you have the application running, you will be able to go to [your dashboard](https://new-console.ng.bluemix.net/dashboard/compute#container) and see the application running. The application will be available at `http://<appName>:9080/myApp`.
