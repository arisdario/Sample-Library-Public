# Sample-Library-Public
History:
* Version: 0.1, 2017/31/10


# What is this? :)
This repository hosts several source code example for Innovation Suite.
You can request a free of charge development environment on the BMC Developer Portal (https://developers.bmc.com/site/global/home/index.gsp).

# Content:



# Installation (using the zip file):
You can Just deploy the file "com.example.samplelibrary-1.0-SNAPSHOT.zip" on your development environment.
https://docs.bmc.com/docs/innovationsuite/cloud/importing-the-export-packages-to-deploy-tailoring-changes-of-applications-747679337.html


# Build and installation using the source code:
Please follow those steps:
Create your developer environment:
https://docs.bmc.com/docs/innovationsuite/cloud/setting-up-your-ide-and-installing-innovation-sdk-679716356.html
You will need nodeJs, maven and Java.

To deploy:
https://docs.bmc.com/docs/innovationsuite/cloud/creating-a-project-using-maven-and-the-archetype-679717111.html
https://docs.bmc.com/docs/innovationsuite/cloud/deploying-your-digital-service-application-for-the-first-time-to-start-working-in-innovation-studio-679716363.html

Here are the steps:
* Clone this repository,
* Change the content of the parent "pom.xml" file to insert your credentials:
```xml
    <!-- START: Bundle specific configuration. Verify and Change as per environment -->
    <developerUserName>developer</developerUserName>
    <developerPassword>password</developerPassword>
    <!-- Server name with Jetty port. -->
    <webUrl>https://developerXXXX.innovate.bmc.com</webUrl>
    <!-- END: Bundle specific configuration.-->
```
* Run the command "mvn clean install -Pdeploy" to deploy the application on your developer environment,


# Disclaimer:
These samples are released by Laurent Matheo and are released "as is" as code samples. There is no warranty, liability or support on those examples.


# Support:
Please find support on the Developer BMC Community if you have any questions or feel gree to use this git repo features (bug report etc...).


# Most important:
I hope it helps :)


# Links:
BMC Innovation Youtube channel (https://www.youtube.com/bmcdigitalinnovator),
BMC Developer portal (https://developers.bmc.com/site/global/home/index.gsp),
BMC Developer Community (https://communities.bmc.com/community/developer/content?filterID=contentstatus%5Bpublished%5D~objecttype~objecttype%5Bthread%5D),
BMC Documentation for Innovation Suite (https://docs.bmc.com/docs/innovationsuite/cloud/home-679716249.html),
