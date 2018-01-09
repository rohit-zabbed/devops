pipeline {
  agent {
    docker {
      image 'gradle:jre8-alpine'
    }
    
  }
  stages {
    stage('Clean') {
      steps {
        sh 'echo \'doing clean\''
      }
    }
  }
  environment {
    label = 'build'
  }
}