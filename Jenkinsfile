pipeline {
  agent any
  stages {
    stage('Another Output Text') {
      parallel {
        stage('Output Text') {
          steps {
            sh 'echo \'Hello World\''
          }
        }
        stage('') {
          steps {
            sh 'echo "Step 2"'
          }
        }
      }
    }
    stage('') {
      steps {
        sh 'echo "Third Step"'
      }
    }
  }
}