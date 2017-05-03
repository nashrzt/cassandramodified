pipeline {
  agent {
    node {
      label 'test'
    }
    
  }
  stages {
    stage('build') {
      steps {
        ws(dir: 'workspace/nn') {
          sh 'sh ansible.sh'
        }
        
      }
    }
  }
  environment {
    stg = 'stg'
  }
}