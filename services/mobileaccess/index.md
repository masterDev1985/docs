---

copyright:
  years: 2015, 2016

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# Getting started with {{site.data.keyword.amashort}}
{: #gettingstarted}
*Last updated: 28 January 2016*

Add security and monitoring functionality to your mobile app with the {{site.data.keyword.amafull}} service. You can configure client authentication and identity providers so that users can log in to the app with their existing Google or Facebook accounts. You can also add monitoring function to your app that enables both client logging and usage statistics.
{:shortdesc}

**Note:** The {{site.data.keyword.amashort}} service was previously known as Advanced Mobile Access.


To get up and running with the {{site.data.keyword.amashort}} service, follow these steps:

1. Set up your client-side development environment.
You can add the {{site.data.keyword.amashort}} SDK to your existing Android, Cordova, or iOS app. You can also download the HelloAuthentication sample application.
   * **Android**: ([SDK](getting-started-android.html)) ([Sample](https://github.com/ibm-bluemix-mobile-services/bms-samples-android-helloauthentication))
   * **Cordova**: ([SDK](getting-started-cordova.html)) ([Sample](https://github.com/ibm-bluemix-mobile-services/bms-samples-cordova-helloauthentication))
   * **iOS**: ([SDK](getting-started-ios.html)) ([Sample](https://github.com/ibm-bluemix-mobile-services/bms-samples-ios-helloauthentication))

1. Secure server-side resources. Protect your mobile backend resources that are running on Node.js or Liberty for Java&trade; runtimes with mobile-enabled OAuth security. For more information, see [Protecting resources](protecting-resources.html).

1. Optional: Configure an identity provider for your application. You can configure one identity provider per application. Configuring an identity provider enables the users of your mobile app to log in with their existing Facebook or Google+ account. Or, you can define how users log in by creating a custom authentication.
   * [Facebook](facebook-auth-overview.html)
   * [Google](google-auth-overview.html)
   * [Custom](custom-auth.html)
1. Configure app monitoring and logging.  For more information, see [App monitoring](app-monitoring.html).


# rellinks
## Overview
* [Overview](overview.html){: new_window}

## Tutorials and Samples
* [android-helloauthentication sample](https://github.com/ibm-bluemix-mobile-services/bms-samples-android-helloauthentication){: new_window}
* [ios-helloauthentication sample](https://github.com/ibm-bluemix-mobile-services/bms-samples-ios-helloauthentication){: new_window}

## SDK
* [Core SDK (Android)](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-android-core){: new_window}
* [Core SDK (Cordova plug-in)](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-cordova-plugin-core){: new_window}
* [Core SDK (iOS) ](https://hub.jazz.net/git/bluemixmobilesdk/imf-ios-sdk/archive?revstr=master){: new_window}

## API Reference
* [Android](https://www.{DomainName}/docs/api/content/api/mobilefirst/android/core-api-doc/overview-summary.html){: new_window}
* [iOS](https://www.{DomainName}/docs/api/content/api/mobilefirst/ios/IMFCore_api-doc/html/index.html){: new_window}
