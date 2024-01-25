# CI/CD Pipelines for M1 Mac Mini

## Plan

- [x] Install Jenkins on Mac
- [x] Run a Basic Pipeline
- [x] Read [Fastlane Jenkins Docs](https://docs.fastlane.tools/best-practices/continuous-integration/jenkins/)
- [x] Setup Multibranch Pipeline with initial Jenkinsfile [step-by-step tutorial for setting Jenkins](https://medium.com/@sumit16.kumar/ci-cd-using-fastlane-jenkins-ios-69c86ae0cdcc)
- [ ] Select dummy project to build
- [ ] Update Jenkinsfile with [Fastlane](https://www.youtube.com/watch?v=yNqCpMLmJqE)
- [ ] Create Build Step which installs all the necessary packages etc. on the Mac system
- [ ] Explore [parallel test execution in fastlane](https://dilshan-fdo.medium.com/ios-mobile-testing-parallel-execution-with-fastlane-bb92d5eef997)
- [ ] Parametrize steps to create a [smooth build experience with FastLane](https://www.runway.team/blog/how-to-build-the-perfect-fastlane-pipeline-for-ios#configuring-fastlane-for-a-project)
- [ ] 

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

### Install XCode Command Line Tools

```
xcode-select —-install
```

### Install Fastlane

Fastlane is the 

- Install Ruby because fastlane is installed as a ruby gem
```
brew install ruby
```

- Install bundler cuz that's always nice
```
gem install bundler
```

- Install fastlane 
```
gem install fastlane
```

#### Plugins for Mac

https://plugins.jenkins.io/xcode-plugin/
