pipeline {
  agent {
    node {
      label 'v18.14.0'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }

    stage('run') {
      steps {
        sh 'npm start'
      }
    }

  }
}