pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        ws(dir: '/ebs')
      }
    }
  }
  environment {
    stg = 'stg'
  }
}