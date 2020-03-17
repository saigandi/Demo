pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Jenkins Demo Job'
      }
    }
    stage('ABE') {
      steps {
        withAnt(installation: 'C:/SoftwareAGW/common/lib/ant', jdk: 'C:\\Program Files\\Java\\jdk1.8.0_181\\bin')
      }
    }
  }
}