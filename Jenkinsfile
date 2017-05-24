pipeline {
  agent {
    docker {
      image 'node'
      args 'latest'
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