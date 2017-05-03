pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ansible.sh'
      }
    }
  }
  environment {
    stg = 'stg'
  }
}