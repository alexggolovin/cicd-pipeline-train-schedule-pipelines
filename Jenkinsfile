pipeline {
  agent any
  stages {
    stage ('Freaking Build stage') {
    steps { 
      echo "damn train automation is running"
      sh './gradlew build --no-daemon'
      }
    }
  }
}
