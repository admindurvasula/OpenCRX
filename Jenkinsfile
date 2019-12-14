pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/admindurvasula/OpenCRX.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        bat 'ant all'
      }
    }

  }
}