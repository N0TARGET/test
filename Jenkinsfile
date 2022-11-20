pipeline {

  agent { docker { image 'maven:3.8.6-openjdk-11-slim' } }

  stages {

    stage('Build') {
      steps {
        echo 'AAA'
        sh 'mvn clean verify'
      }
    }

  }

}
