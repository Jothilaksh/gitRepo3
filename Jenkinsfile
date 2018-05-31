pipeline {
  agent none
  stages {
    stage('Packaging') {
      steps {
        echo 'Hello'
      }
    }
    stage('Alpha') {
      parallel {
        stage('Alpha') {
          steps {
            sh 'echo "Alpha "'
          }
        }
        stage('Form deploy ') {
          steps {
            sh 'echo "Form deployed"'
          }
        }
      }
    }
  }
}