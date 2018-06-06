pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/huaqiangli/myegg.git', branch: 'master', credentialsId: 'github-lhq')
      }
    }
    stage('build') {
      steps {
        sh 'echo "build the package"'
      }
    }
  }
}