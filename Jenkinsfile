pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'Echo "I am Trying to Build the file"'
        git(url: 'https://github.com/ashokkumarsingh/DemoProject.git', branch: 'master', poll: true)
      }
    }
    stage('Release') {
      steps {
        bat 'echo "Its now ready to release"'
      }
    }
  }
}