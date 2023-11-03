pipeline {
  
  agent { label 'nodejs-agent'}

  stages {

    stage('Test') {
      // agent { label 'nodejs-agent'}
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
