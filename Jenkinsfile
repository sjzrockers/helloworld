pipeline {
  agent any
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