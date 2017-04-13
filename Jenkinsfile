pipeline {
  agent any
  stages {
    stage('Step 1') {
      steps {
        echo 'Starting Deploy'
        git(url: 'https://github.com/rtloeffler/test', branch: 'master')
      }
    }
    stage('Last Step') {
      steps {
        echo 'Last stage'
        sh 'mv /var/lib/jenkins/workspace/rtloeffler_test_master-JI757GB3H5UKRID4J7XXPN5M6QSMBY56Y5SNG7H5XASDNKFHI3KQ/* /var/www/html/;'
      }
    }
  }
}