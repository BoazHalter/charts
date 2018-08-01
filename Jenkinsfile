pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'echo ${RGISTRY}'
      }
    }
  }
  environment {
    REGISTRY = '10.0.0.26:5012'
  }
}