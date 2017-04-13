pipeline {
  agent none
  stages {
    stage('Step 1') {
      steps {
        echo 'Starting Deploy'
        dir(path: '/var/www/html') {
          sleep 2
        }
        
      }
    }
    stage('Step 2') {
      steps {
        writeFile(file: 'env.php', text: 'testing this text')
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