pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        echo "checkout the code from test branch"
        //checkout scm
        sh 'ls -l'
      }
    }
    stage('build') {
      steps {
        sh 'echo "build the package"'
      }
    }
  }
}
