pipeline {
  
  agent {
      docker {
          image 'maven'
      }
  }
  
  triggers {
        githubPush()
    }
  
  stages {
    stage('hello world') {
      steps {
          sh 'mvn --version'
      }
    }
    
  }
  
}
