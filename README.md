# Using Gradle and Docker to build apps with Liberty

This is a simple application to show setting up an application that uses JAX-RS and runs on LIberty. The application uses Gradle to build and can be deployed in a Docker container.

## Deploying to Bluemix

You can also deploy this application to Bluemix using Bluemix's IBM Container Service.

[![Deploy To Bluemix](https://console.ng.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.ng.bluemix.net/devops/setup/deploy/)

## Testing the application is running

Once the deploy has completed you will be able to go to [your dashboard](https://new-console.ng.bluemix.net/dashboard/compute#container) and see the application running. In the `Container details` panel you will see port 9080 is bound to the container, click on the port number to see the Liberty Welcome Page. You can then append `/myApp` to the URL to access your application.
