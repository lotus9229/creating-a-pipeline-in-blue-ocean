pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'docker pull node:alpine'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
  }
}