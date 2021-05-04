pipeline {
  agent {
    node {
      label 'ritsuko'
    }

  }
  stages {
    stage('Release') {
      steps {
        sh 'cat /etc/*-release*'
      }
    }

  }
}