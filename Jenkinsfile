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
        withAnt(installation: 'C:\\SoftwareAG101\\common\\lib\\ant\\lib', jdk: 'C:\\SoftwareAG101\\jvm\\jvm')
      }
    }
  }
}