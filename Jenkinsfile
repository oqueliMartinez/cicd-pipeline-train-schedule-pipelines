pipeline {
  agent any
  stages {
    stage ('Build'){
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifatcs: 'dist/trainSchedule.zip'
      }    
    }
  }
}
