pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'cpr * /ebs/'
      }
    }
  }
  environment {
    stg = 'stg'
  }
}