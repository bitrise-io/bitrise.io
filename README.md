# Bitrise.io public repositories & issues

[![Slack channel](http://chat.bitrise.io/badge.svg)](http://chat.bitrise.io)

The purpose of this repository is to keep track of the most important public repositories related to [bitrise.io](https://www.bitrise.io).

If you want to **suggest a new feature** you can submit an issue here and vote on others' on [UserVoice](https://bitrise.uservoice.com/), or if you want to **chat** with us you can sign up for our Slack group at [chat.bitrise.io](http://chat.bitrise.io/).

## Our build steps collection

We maintain a [library of Bitrise build steps](https://github.com/bitrise-io/bitrise-steplib), featuring all the [integrations](https://www.bitrise.io/integrations) we deploy to [bitrise.io](https://www.bitrise.io).

You can find all of them under [/steps](https://github.com/bitrise-io/bitrise-steplib/tree/master/steps). To see how to contribute, check

You can find the Step repositories which we maintain and support by searching for [steps-](https://github.com/bitrise-io?utf8=%E2%9C%93&query=steps-) on our GitHub account page (github.com/bitrise-io).

## Sample Apps

Check out our sample app repositories for a starter.

**iOS**

- [Xcode 7 sample project (with UI Testing)](https://github.com/bitrise-io/sample-apps-ios-xcode7)
- [Quick sample project](https://github.com/bitrise-io/sample-test-ios-quick)
- [XCTest sample project](https://github.com/bitrise-io/sample-test-ios-xctest)
- [Specta sample project](https://github.com/bitrise-io/sample-test-ios-specta)
- [Kiwi sample project](https://github.com/bitrise-io/sample-test-ios-kiwi)

**Android**

- [with code sign](https://github.com/bitrise-samples/android-sdk22-code-sign)
- [without gradlew](https://github.com/bitrise-samples/android-sdk22-no-gradlew)

**Xamarin**

- [Android](https://github.com/bitrise-io/sample-apps-xamarin-android)
- [iOS](https://github.com/bitrise-io/sample-apps-xamarin-ios)

**React Native**

- [React Native sample project](https://github.com/bitrise-samples/ReactNativeSample)

Or simply search our GitHub account page for [sample-](https://github.com/bitrise-io?utf8=%E2%9C%93&query=sample-) to see all of our sample projects.

>We now started to move our Sample repositories to a dedicated GitHub account, check it out here: https://github.com/bitrise-samples

Feel free to fork and test them on [bitrise.io](https://www.bitrise.io) or locally with the [Bitrise CLI](https://www.bitrise.io/cli).

## Build machines

### OS X

We are working with [vSphere](https://www.vmware.com/products/vsphere), [Ansible](http://docs.ansible.com/) and [vagrant](https://www.vagrantup.com/docs/) to virtualize, bootstrap and fire up the OS X build machines for builds on [bitrise.io](https://www.bitrise.io).

You can find all of our bootstrap scripts on the [OS X bootstrap GitHub page](https://github.com/bitrise-io/osx-box-bootstrap).

### Docker

We have a [base image](https://github.com/bitrise-docker/bitrise-base) and an [Android version](https://github.com/bitrise-docker/android) with pre-installed tools for Android builds.

### Request a tool to be pre-installed on a build machine

* For OS X you can create an issue or pull request at [`osx-box-bootstrap`](https://github.com/bitrise-io/osx-box-bootstrap)
* For our Docker based stack you can create an issue or pull request at:
    * [`bitrise-base`](https://github.com/bitrise-docker/bitrise-base), for generic tools and configurations (which are not related to Android)
    * [`android`](https://github.com/bitrise-docker/android), for Android related tools and configurations


    ## Contribution to Bitrise stack tools & steps

    If you want to collaborate with us creating useful automation tools and steps please go to the [`contrib`](https://github.com/bitrise-io/bitrise-contrib) repository and follow the guides. you can keep track of others' projects there as well.
