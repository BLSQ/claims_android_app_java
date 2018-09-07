# openIMIS Claim Android Application

The openIMIS Claim Android Application is the mobile client used by
the Health Facilities personnel to easily enter and post claims from anywhere
online or offline.

## Getting Started

These instructions will get you a copy of the project up and
running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

In order to use and develop the openIMIS Claim Android Application
on your local machine, you first need to install:

* [Android Studio with Android SDK](https://developer.android.com/studio)
* [openIMIS Web Services](https://github.com/openimis/web_service_vb)


### Installing

To make a copy of this project on your local machine, please clone
the repository.

```
git clone https://github.com/openimis/claim_android_app_java
```

### Configuring

In order to run the openIMIS Claim Android Application, you need to
know the openIMIS Web Services domain (DNS or IP address) and to configure it in the
com.exact.general.General java file.

```
private String _Domain = "http://132.148.151.32/";
```

For demo purposes, the default Web Services domain is set to the openIMIS
demo server: demo.openimis.org (IP: 132.148.151.32).  

### Running

After configuring the application, you can then compile and execute
on Android operated mobile devices.

<!--## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```-->

## Deployment

To deploy on a live environment, the previous steps have to be followed
and to build the APK. Manual deployment is required on each mobile device.

<!--For more information please read the [installation manual](http://openimis.readthedocs.io/en/latest/mobile_applications_configuration.html).-->

<!--## Built With

* [Visual Studio](https://visualstudio.microsoft.com/) - The web framework used
* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds
-->

<!--## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.
-->

<!--## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).
-->

<!--## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
-->

<!--## User Manual

The user manual can be read on [openimis.readthedocs.io](http://openimis.readthedocs.io/en/latest/user_manual.html).
-->
## License

Copyright (c) Swiss Agency for Development and Cooperation (SDC)

This project is licensed under the GNU AGPL v3 License - see the
[LICENSE.md](LICENSE.md) file for details.

<!--## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
-->
