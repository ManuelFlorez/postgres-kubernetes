pipeline {
  
  agent { label 'nodejs-agent'}

  stages {

    stage('Test') {
      steps {
        sh '''
          node --version
          npm --version
        '''
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
