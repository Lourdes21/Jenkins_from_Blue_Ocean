pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'first print with blue ocean'
      }
    }

    stage('') {
      steps {
        timeout(time: 2, unit: 'SECONDS') {
          echo 'hello'
        }

        echo 'this is a message'
      }
    }

  }
}