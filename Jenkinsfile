pipeline {
  agent any
  stages {
    stage('server UP') {
      steps {
        powershell 'get-date'
      }
    }
    stage('resize') {
      parallel {
        stage('resize') {
          steps {
            powershell 'get-date'
          }
        }
        stage('stop') {
          steps {
            powershell 'get-date'
          }
        }
      }
    }
  }
}