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
        stage('i2') {
          steps {
            input(message: 'ttttt', id: 'btgbtgbtgbt', ok: '1')
          }
        }
      }
    }
    stage('bgvf') {
      parallel {
        stage('bgvf') {
          steps {
            input(message: 'start', id: 't6y7u', ok: 'ok')
            echo 'done'
          }
        }
        stage('deploe prod') {
          steps {
            input(message: 'ok?', id: 'dsfgdf', ok: 'ok')
            echo 'done'
          }
        }
      }
    }
  }
}