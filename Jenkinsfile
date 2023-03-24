pipeline {
  agent any
  stages {
    stage('Souce') {
      steps {
        git 'https://github.com/kimth95/webtest'
      }
    }

    stage('Build') {
      steps {
        tool 'gradle'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "TEST"'
      }
    }

  }
}