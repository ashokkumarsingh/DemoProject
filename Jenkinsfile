pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo "First Step initialzed"'
      }
    }
    stage('Test') {
      steps {
        bat 'echo "Testing is being here"'
      }
    }
    stage('deploy') {
      steps {
        mail(subject: 'Test', body: 'Hello', bcc: '1975deepak@gmail.com', cc: '1975deepak@gmail.com', from: 'ashokkumarsingh.jilit@gmail.com', to: '1975deepak@gmail.com')
      }
    }
  }
}