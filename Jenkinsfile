pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''docker build -t deepthi_python:1.0 .
docker run -d -p 5000:5000 deepthi_python:1.0
docker container ls
'''
      }
    }

  }
}