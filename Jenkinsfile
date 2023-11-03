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

    stage('Show') {
      steps {
        kubectl cluster-info
      }
    }
    
  }
}
