pipeline {
  agent {
    node {
      label 'node'
    }

  }
  stages {
    stage('build') {
      steps {
        withGradle() {
          sh 'sh \'./gradlew build\''
        }

      }
    }

  }
}