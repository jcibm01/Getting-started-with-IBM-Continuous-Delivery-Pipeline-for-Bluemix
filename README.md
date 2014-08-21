Getting-started-with-IBM-Continuous-Delivery-Pipeline-for-Bluemix
=================================================================

Getting started with IBM Continuous Delivery Pipeline for Bluemix

Tomado de https://www.ng.bluemix.net/docs/#services/DeliveryPipeline/index.html#gettingstartedtemplate

Configure a builder to automatically compile, run unit tests, and package apps. Then, configure a deployer to automatically deploy the built package to IBM® Bluemix™. Once configured, any successful build triggers a push of the application to Bluemix. Also, track changes, build artifacts, and test completion through the Delivery Pipeline.

The Delivery Pipeline provides you with a builder and deployer that you can configure. A configured builder compiles the source within Git and Jazz source code repositories and enables automated unit tests. Each time source code changes, a build is automatically triggered. A builder allows you to view build logs and work items included in a build, download the artifacts that are produced from the build, and view the test execution. A configured deployer pushes built packages to Bluemix. With each successful build, a push of the application to Bluemix is automatically triggered. With a deployer, view your active deployment, with information directly from your Bluemix application. Access the application URL, and drill directly into the Bluemix application dashboard.

There are two main use cases; starting from Bluemix with an application and connecting an Add-On named Delivery Pipeline and starting from the IBM DevOps Services Web IDE, accessing Build & Deploy and connecting an Add-On named Delivery Pipeline.
Starting from Bluemix

    Log in to Bluemix and select an organization and space for creating your application.
    Click CREATE AN APP in the Bluemix dashboard and select a boilerplate or a run time from the catalog.
    Create a Git-hosted project for the application from the Bluemix application dashboard. Click ADD GIT. Once you've done this for an application, you'll see CODE subsequently for this prompt.
    Add the Delivery Pipeline Add-On to the dashboard to configure and run an Ant or Grunt builder and a deployer to the application's Bluemix space.
        From the Bluemix application dashboard, click CONNECT AN ADD-ON and select Delivery Pipeline from the catalog.
        From the Delivery Pipeline page, click CREATE. The Delivery Pipeline dashboard opens with the application that you created earlier.
    From the Delivery Pipeline dashboard you can add a project for an application, go to applications, projects, builds, last deployment, and deployment state.

Starting from the DevOps Services Web IDE

    Sign in to DevOps Services.
    Create a project with the Deploy to Bluemix option selected. Or find an exemplary project and fork it. You must select an organization and space to connect your project to your Bluemix account. If you prefer to do this later clear the Deploy to Bluemix check box to continue.
    From Build & Deploy, select Simple for direct automated deployment to Bluemix whenever someone on the project pushes changes to the Git repository.
    From Build & Deploy, select Advanced for automated build and deployments to Bluemix whenever someone on the project pushes changes to the Git repository. You can configure and run an Ant or Grunt builder and a deployer to the application's Bluemix space.
    Log in to Bluemix.
    In Bluemix, add the Delivery Pipeline Add-On to the dashboard to configure and run an Ant or Grunt builder and a deployer to the application's Bluemix space.
        Navigate to the Bluemix organization and space that was selected in project creation.
        Under ADD-ONS click Connect an Add-On and select Delivery Pipeline from the catalog.
        From the Delivery Pipeline page, click CREATE. The Delivery Pipeline dashboard opens with the project that you created earlier.
    From the Delivery Pipeline dashboard you can add a project for an application, go to applications, projects, builds, last deployment, and deployment state.

