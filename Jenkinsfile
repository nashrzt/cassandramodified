pipeline {
  agent {
    node {
  label 'naash'
  customWorkspace '/var/lib/jenkins/naash'
    }
  }
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
