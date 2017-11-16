pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Step1') {
          steps {
            echo 'Hello'
          }
        }
        stage('Stage2') {
          steps {
            echo 'Message 2'
          }
        }
      }
    }
    stage('Stage 3') {
      steps {
        pwd(tmp: true)
      }
    }
  }
}