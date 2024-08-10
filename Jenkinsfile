pipeline{
  agent any
  stages {
    stage('build') {
      step 'Build automation stage'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifact: 'dist/trainSchedule.zip'
    }
  }
}
