pipeline {
  agent {
    node {
      label 'test'
    }
    
  }
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