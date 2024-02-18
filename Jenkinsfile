pipeline {
  agent any
  stages {
    stage('welcome-message') {
      steps {
        sh 'echo "Welcome to DevOps !"'
      }
    }
    stage('devops-tools') {
      steps {
        sh 'python3 script.py'
      }
    }
  }
}
