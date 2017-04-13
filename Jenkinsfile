pipeline {
  agent none
  stages {
    stage('Step 1') {
      steps {
        echo 'Starting Deploy'
      }
    }
    stage('Last Step') {
      steps {
        echo 'Last stage'
        sh '''cd /var/www/html/;
touch something.html;'''
      }
    }
  }
}