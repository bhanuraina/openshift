pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        echo 'now'
        docker ps
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
