pipeline {
  
  agent {
      docker {
          image 'python'
      }
  }
  
  triggers {
        githubPush()
    }
  
  stages {
    stage('setup dependencies') {
      steps {
          sh 'python --version'
      }
    }
  }
}
