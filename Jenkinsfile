pipeline {
  
  agent { label 'nodejs-agent'}

  stages {

    stage('Test') {
      steps {
        sh 'node --version'
      }
    }

    stage('Docker') {
      agent { label 'docker-agent' }
      steps {
        sh 'docker --version'
      }
    }
    
  }

}
