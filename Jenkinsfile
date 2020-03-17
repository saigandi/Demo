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
        withAnt(installation: 'C:\\SoftwareAG101\\common\\lib\\ant', jdk: 'C:\\SoftwareAG101\\jvm\\jvm')
        withAnt(installation: 'C:/SoftwareAGW/common/lib/ant', jdk: 'C:\\Program Files\\Java\\jdk1.8.0_181\\bin')
      }
    }
  }
}