# Bitrise.io public repositories & issues

> __Fun and simple development automation__

[![Slack channel](https://chat.bitrise.io/badge.svg)](https://chat.bitrise.io)

The purpose of this repository is to keep track of the most important public repositories related to [bitrise.io](https://www.bitrise.io).

If you want to **suggest a new feature**, you can submit it and vote on others' on [discuss.bitrise.io/c/feature-requests](https://discuss.bitrise.io/c/feature-requests), or if you want to **chat** with us and the Bitrise Community you can join [discuss.bitrise.io](https://discuss.bitrise.io) or Slack at [chat.bitrise.io](https://chat.bitrise.io/). Follow [@bitrise](https://twitter.com/bitrise) on Twitter for #status and step updates 🚀.

## Report an issue / bug

**If you want to report an issue** you can do that by creating a GitHub issue in the related repository.

1. If it's related to a specific Step, you should report it on the Step's GitHub page.
1. If it's a build issue, please report it at: [discuss.bitrise.io/c/issues/build-issues](https://discuss.bitrise.io/c/issues/build-issues)
1. If it's related to the Bitrise CLI you can do that on the [Bitrise CLI's GitHub page](https://github.com/bitrise-io/bitrise).
1. If you want to share private information with us, please contact us through email or through the on-site chat on [bitrise.io](https://www.bitrise.io) (You have to be logged in to see the chat icon at the bottom right corner. Note: some Ad Blockers might block the chat widget).

## Contribution to Bitrise (stack, tools & steps)

If you want to collaborate with us creating useful automation tools and steps please go to the [`contrib`](https://github.com/bitrise-io/bitrise-contrib) repository and follow the guides. You can keep track of others' projects there as well.

## Our build steps collection

We maintain a [library of Bitrise build steps](https://github.com/bitrise-io/bitrise-steplib), featuring all the [integrations](https://www.bitrise.io/integrations) we deploy to [bitrise.io](https://www.bitrise.io).

### Steps

A step is a script with a corresponding `yml` that conforms to the formatting and naming conventions of the StepLib.

You can find all our steps' `yml`s under [/steps](https://github.com/bitrise-io/bitrise-steplib/tree/master/steps).

The repositories of the steps which we maintain and provide support for can be found by searching for [steps-](https://github.com/bitrise-io?utf8=%E2%9C%93&q=steps-&type=&language=) in our [bitrise-io GitHub organization](https://github.com/bitrise-io), the newer ones in the [bitrise-steplib GitHub organization](https://github.com/bitrise-steplib), and the ones we maintain with the community in the [bitrise-community GitHub organization](https://github.com/bitrise-community).

We have most of our scripts written in `Go` and `bash`, but it's possible to write it in any language our machines have installed, like `Ruby` or `Node.js`.

> You can create a StepLib independently from Bitrise anytime, you will be able to use our CLI tools to maintain it, they are not tied to *our StepLib*.

## Bitrise CLI tools

Check out our [CLI's page](https://www.bitrise.io/cli) for a nice intro about why is it helpful to have Bitrise installed on your machine.

### `bitrise`

[The runner itself](https://github.com/bitrise-io/bitrise), you can install it to your machine with Homebrew:

`brew update && brew install bitrise`

Or `curl` down the latest version with the help of our guide on the [releases page](https://github.com/bitrise-io/bitrise/releases).

### `envman`

[`envman`](https://github.com/bitrise-io/envman) is our handy environment variable manager for switching between environment sets quick & easy.

### `stepman`

[`stepman`](https://github.com/bitrise-io/stepman) is our solution to manage decentralized StepLib step (script) collections.

You will run into `stepman` directly most probably when you are sharing your own step to a StepLib.

>We have a collection of useful tools under the [bitrise-io](https://github.com/bitrise-io) account. Not all of them part of the Bitrise CLI family, but are connected to our technology.

All Bitrise CLI tools are written in Go.

### Docker

We have a [base image](https://github.com/bitrise-io/bitrise-base) and an [Android version](https://github.com/bitrise-io/android) with pre-installed tools for Android builds.

>When a new version of a stack is available there will be a system report generated under the [system_reports](https://github.com/bitrise-io/bitrise.io/blob/master/system_reports) folder of this repository.


### Request a tool to be pre-installed on a build machine

* For our Docker based stack you can create an issue or pull request at:
    * [`bitrise-base`](https://github.com/bitrise-io/bitrise-base), for generic tools and configurations (which are not related to Android)
    * [`android`](https://github.com/bitrise-io/android), for Android related tools and configurations


## List of official Bitrise organizations on GitHub

* [bitrise-io](https://github.com/bitrise-io)
* [bitrise-steplib](https://github.com/bitrise-steplib)

### Aggregated Issue and Pull Request lists

Aggregated Issue and Pull Request lists, related to the Bitrise CLI tools, stacks and official steps (*You have to be logged in on GitHub to be able to access the aggregated lists / searches*):

* [Open Pull Requests across the Bitrise CLI tools, stacks and official steps](https://github.com/pulls?q=is%3Aopen+is%3Apr+user%3Abitrise-io+user%3Abitrise-steplib)
* [Open Issues across the Bitrise CLI tools, stacks and official steps](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Abitrise-io+user%3Abitrise-steplib)

## Sample Apps

Check out our sample app repositories.

**iOS**

- [iOS sample project (with UI Testing)](https://github.com/bitrise-io/Bitrise-iOS-Sample)
- [Quick sample project](https://github.com/bitrise-io/sample-test-ios-quick)
- [XCTest sample project](https://github.com/bitrise-io/sample-test-ios-xctest)
- [Specta sample project](https://github.com/bitrise-io/sample-test-ios-specta)
- [Kiwi sample project](https://github.com/bitrise-io/sample-test-ios-kiwi)

**Android**

- [Android sample project](https://github.com/bitrise-io/Bitrise-Android-Sample)
- [sample project with code sign](https://github.com/bitrise-io/android-sdk22-code-sign)

**React Native**

- [React Native sample project](https://github.com/bitrise-io/Bitrise-React-Native-Sample)

Or simply search our GitHub account page for [sample-](https://github.com/bitrise-io?utf8=%E2%9C%93&query=sample) to see all of our sample projects.

Feel free to fork and test them on [bitrise.io](https://www.bitrise.io) or locally with the [Bitrise CLI](https://www.bitrise.io/cli).
