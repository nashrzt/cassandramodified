pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'sh ansible.sh'
      }
    }
  }
  environment {
    stg = 'stg'
  }
}