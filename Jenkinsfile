pipeline {
  agent {
    kubernetes {
      label 'default'
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
