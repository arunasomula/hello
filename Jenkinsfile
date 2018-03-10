pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'dev'
          }
        }
        stage('git') {
          steps {
            echo 'git'
          }
        }
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
    }
  }
}