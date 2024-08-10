pipeline {
  agent any
  stages {
    stage('Build') {
      steps 'Build automation stage'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
