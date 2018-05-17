pipeline {
  agent {
    docker {
      image '10.0.0.163/ubuntu'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Build'
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
  }
}