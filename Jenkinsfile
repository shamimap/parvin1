pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "Hello from shell script"'
          }
        }

        stage('stage2') {
          steps {
            sh 'echo "Hello from stage2"'
          }
        }

      }
    }

  }
}