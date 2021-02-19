pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Running build automation'
        sh './gradelew build --no-daemon'
        archiveArtifacts articacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
