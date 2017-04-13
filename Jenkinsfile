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
      }
    }
  }
}