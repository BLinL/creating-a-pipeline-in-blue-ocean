pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node-alpine:12.18.4'
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
