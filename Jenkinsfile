pipeline {

  agent any

  stages {
    stage('Load environment variables') {
      steps {
        script {
          load 'environmentVariables.groovy'
        }
      }
    }

    stage('Build') {
      steps {
        container('maven') {
          sh 'mvn clean verify -B --settings /opt/maven/settings.xml'
        }
      }
    }

  }

}
