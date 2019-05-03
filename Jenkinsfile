pipeline {
  agent {
    docker {
      image 'maven:3.39-jdk-8'
    }

  }
  stages {
    stage('Intialise') {
      steps {
        sh 'mvn clean'
      }
    }
  }
}