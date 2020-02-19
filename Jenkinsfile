pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        retry(count: 3) {
          echo 'hhh'
        }

      }
    }

  }
}