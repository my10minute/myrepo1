pipeline {
  agent any
  stages {
    stage('Build-Stage1') {
      parallel {
        stage('Build-Stage1') {
          steps {
            sh 'echo \'shell script123\''
            echo 'stage-task2'
          }
        }
        stage('parallelstage1') {
          steps {
            echo 'parallelstage1-task1'
          }
        }
        stage('parallelstage1-2') {
          steps {
            sh 'echo \'ps1-2\''
          }
        }
      }
    }
    stage('stage2') {
      steps {
        sh 'echo \'stage2-step1'
      }
    }
    stage('test-stage3') {
      steps {
        sh 'echo "stage3-step1"'
      }
    }
  }
}