pipeline {
  agent {
    docker { image 'node:20-alpine' }
  }

  stages {
    stage('Build') {
      steps {
        sh 'node -v'
        sh 'npm -v'
        sh 'npm install'
      }
    }
  }
}