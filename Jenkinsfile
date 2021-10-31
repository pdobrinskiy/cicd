pipeline {
  agent { yamllint -s . } }
  stages {
    stage('Log Jenkins Maven Docker Git and Java version info') {
      steps {
        sh 'uname -a'
      }
    }
    
  }
}
