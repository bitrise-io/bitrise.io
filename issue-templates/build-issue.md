# Bitrise Build Issue Report template

## Description of the issue

Please describe the issue here


## Environment:

Where did the issue happen?

- If on Bitrise.io: which stack?
- If not on Bitrise.io: on what operating system? (Plus any other information you can share)

Which build Step causes the issue and which version of the step?


## Reproducibility

- Does a "Rebuild" help? (You can trigger a rebuild from the Build's page, by clicking the "Rebuild" button in the top right corner of a finished build)
- If it's an issue which happens sporadically, what's the frequency? (e.g. Once a day ; about x% of the builds)
- Does upgrading the build Step to the latest version help?
- When did the issue start?

### Linux/Android stack builds

- Can it be reproduced by running the build locally with Docker (using the same docker images we use on bitrise.io), after doing a clean git clone (git clone the repository, into a new directory, somewhere on your Mac/PC) and running the build from there? (Related guide: http://blog.bitrise.io/2016/08/08/debug-your-android-linux-builds-locally-with-docker.html )

### All / other stacks

- Can it be reproduced by running the build locally with our CLI ( https://www.bitrise.io/cli ), after doing a clean git clone (git clone the repository, into a new directory, somewhere on your Mac/PC) and running the build from there with the CLI?

## Build log

Please attach the build log (you can download the build log from the build's page, once the build is finished, using the "Download log" button - floating at the bottom right corner of the log viewer).
