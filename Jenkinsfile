pipeline {
  agent any
  stages {
    stage('t1') {
      parallel {
        stage('t1') {
          steps {
            echo 't1'
          }
        }
        stage('t2') {
          steps {
            echo 't2'
          }
        }
      }
    }
  }
}