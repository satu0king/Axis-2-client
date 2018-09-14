pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'cat README.md'
        echo 'Build Message'
      }
    }
    stage('Test') {
      steps {
        echo 'Test stage'
      }
    }
  }
}