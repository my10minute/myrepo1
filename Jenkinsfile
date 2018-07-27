pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        sh 'echo \'shell script123\''
        echo 'stage-task2'
      }
    }
    stage('stage2') {
      steps {
        sh 'echo \'stage2-step1\''
      }
    }
  }
}