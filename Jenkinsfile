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
        stage('input') {
          steps {
            input(message: 'test', id: 'tetrerfrc', ok: 'ok', submitter: 'trtrtrvr', submitterParameter: 'rvfv')
          }
        }
        stage('i2') {
          steps {
            input(message: 'ttttt', id: 'btgbtgbtgbt', ok: '1')
          }
        }
      }
    }
  }
}