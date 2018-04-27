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
    stage('deploye') {
      steps {
        bat 'echo "Deploy"'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_144'
    MAVEN_HOME = 'D:\\apache-maven-3.5.3'
  }
}