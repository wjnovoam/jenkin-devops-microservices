node {
	agente any 
  stages {
    stage('Build') {
      steps {
        echo "Test"
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
