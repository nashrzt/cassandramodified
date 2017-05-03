pipeline {
  agent {
    node {
      label 'test'
    }
    
  }
  stages {
    stage('build') {
      steps {
        ws(dir: 'nashrzt') {
          sh 'sh ansible.sh'
        }
        
      }
    }
  }
  environment {
    stg = 'stg'
  }
}