pipeline {
  agent {
    docker {
      image 'docker pull node'
      args '-p 3000:3000'
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