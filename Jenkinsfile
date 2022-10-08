pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        sh 'df -h'
      }
    }

    stage('final') {
      parallel {
        stage('final') {
          steps {
            sh 'java helloworld.java'
          }
        }

        stage('') {
          steps {
            sh 'free h'
          }
        }

      }
    }

  }
}