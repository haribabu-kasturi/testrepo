pipeline {
  agent any
  stages {
    stage('Sleep') {
      steps {
        sleep 10
      }
    }
    stage('print') {
      steps {
        echo 'hello'
      }
    }
    stage('mail') {
      steps {
        mail(subject: 'testing', body: 'test', to: 'swakriti.kumari@cgi.com', from: 'anuradha.bhattacharya@cgi.com')
      }
    }
  }
  environment {
    USER_NAME = 'HARIK'
  }
}