# Issue Report template

## Environment:

Where did the issue happen?

- If on Bitrise.io: which stack?
- If not on Bitrise.io: on what operating system? (Plus any other information you can share)


## Reproducibility

- Did you try a rebuild? Did that help?
- If it's an issue which happens sporadically, what's the frequency? (e.g. Once a day ; about x% of the builds)
- When did the issue start?

Linux/Android stack builds:

- Can it be reproduced by running the build locally with Docker (using the same docker images we use on bitrise.io), after doing a clean git clone (git clone the repository, into a new directory, somewhere on your Mac/PC) and running the build from there? (Related guide: http://blog.bitrise.io/2016/08/08/debug-your-android-linux-builds-locally-with-docker.html )

All / other stacks: 

- Can it be reproduced by running the build locally, after doing a clean git clone (git clone the repository, into a new directory, somewhere on your Mac/PC) and running the build from there (preferably with our CLI: https://www.bitrise.io/cli )?

## Build log

Please attach the build log (you can download the build log from the build's page, once the build is finished, using the "Download log" button - floating at the bottom right corner of the log viewer).
