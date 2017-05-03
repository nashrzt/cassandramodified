pipeline {
  agent any
  stages {
    stage('workspace to new') {
      steps {
        ws(dir: 'nishan')
      }
    }
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}