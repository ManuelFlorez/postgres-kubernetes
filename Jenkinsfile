pipeline {
  
  agent {
    label 'nodejs-agent'
  }
  
  stages {

    stage('Test') {
      steps {
        echo 'Hello World'
      }
    }
    
  }

  agent {
    label 'docker-agent'
  }

  stages {
    stage('Docker') {
      steps {
        sh 'docker --version'
      }
    }
  }

}
