pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('overview') {
      steps {
        sh 'python3 welcome.py'
      }
    }
  }
}
