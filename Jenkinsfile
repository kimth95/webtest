pipeline {
  agent any
  stages {
    stage('Souce') {
      steps {
        git(url: 'https://github.com/kimth95/webtest.git', poll: true, branch: '*/main')
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