pipeline {
  agent {
    node {
      label 'for testing'
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