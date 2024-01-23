# CI/CD Pipeline Examples running on Mac

## Prerequisites

### Enable remote connection to your MacOS
- In the MacOS settings search for Sharing.
- Under Sharing enable Remote Login and Remote Management and select the users who have access to the server.

### Install Jenkins

- Install jenkins 
```
brew install jenkins-lts
```

- Start Jenkins Service
```
brew services start jenkins-lts
```
You will get a notification which says that a "java" app is running in the background.

#### Plugins for Mac

https://plugins.jenkins.io/xcode-plugin/
