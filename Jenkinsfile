pipeline {
	agent {
    docker {
      image 'maven:3.6.3'
    }
  } 
  stages {
    stage('Build') {
      steps {
        sh 'mvn --version'
        echo "Build"
      }
    }
    stage('Test') {
      steps {
        echo "Test"
      }
    }
    stage('Integraction Test') {
      steps {
        echo "Integraction Test"
      }
    }
  }
  post {
    always {
      echo 'Correr siempre'
    }
    success {
      echo 'Correr cuando tienes exito'
    }
    failure {
      echo 'Correr cuando ocurre un fallo'
    }
  }
}
