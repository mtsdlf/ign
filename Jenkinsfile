pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/mtsdlf/ign/', branch: 'dev')
      }
    }

    stage('log') {
      steps {
        sh 'ls -ls'
      }
    }

  }
}