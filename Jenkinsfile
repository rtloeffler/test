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
        git(branch: 'master', url: 'https://github.com/rtloeffler/test', credentialsId: '4830f0ac7739cc5675c19f7d7be38d7feb14b1bc')
      }
    }
  }
}