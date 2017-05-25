pipeline {
  agent {
    docker {
      image 'node:6.3'
    }
    
  }
  stages {
    stage('error') {
      steps {
        sh 'echo \'hello\''
      }
    }
  }
}