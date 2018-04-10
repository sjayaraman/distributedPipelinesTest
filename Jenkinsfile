pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Stage 1') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}