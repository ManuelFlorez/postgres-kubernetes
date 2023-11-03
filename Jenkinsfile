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

    agent {
      label 'docker-agent'
    }

    stage('Show') {
      steps {
        sh 'docker --version'
      }
    }
    
  }
}
