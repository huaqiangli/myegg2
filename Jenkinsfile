pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        sh '''echo "checkout the code"
ls -l '''
      }
    }
    stage('build') {
      steps {
        sh 'echo "build the package"'
      }
    }
  }
}