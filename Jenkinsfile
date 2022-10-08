pipeline {
  agent any
  stages {
    stage('test1') {
      steps {
        sh 'df -h'
      }
    }

    stage('final') {
      steps {
        sh 'java helloworld.java'
      }
    }

  }
}