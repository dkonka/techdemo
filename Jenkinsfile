pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''nerdctl build -t deepthi_python:1.0 .
nerdctl run -d -p 5000:5000 deepthi_python:1.0
nerdctl container ls
'''
      }
    }

  }
}