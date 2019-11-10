pipeline {
  agent {
    docker {
      image 'opengamer/android-sdk-gradle-fastlane'
    }

  }
  stages {
    stage('init') {
      steps {
        dockerNode(image: 'opengamer/android-sdk-gradle-fastlane')
      }
    }

  }
}