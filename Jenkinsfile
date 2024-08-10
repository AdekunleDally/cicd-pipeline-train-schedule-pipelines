pipeline{
  agent any
  stages {
    stage('build') {
      step 'Build automation stage'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
