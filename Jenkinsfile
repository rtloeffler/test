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
        git(branch: 'master', url: 'https://github.com/rtloeffler/test')
      }
    }
  }
}
