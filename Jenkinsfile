pipeline {

  agent any

  stages {

    stage('Build') {
      steps {
        container('maven') {
          echo 'AAA'
          sh 'mvn clean verify'
        }
      }
    }

  }

}
