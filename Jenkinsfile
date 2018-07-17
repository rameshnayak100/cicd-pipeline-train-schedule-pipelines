pipeline {
  agent any 
    stages {
      stage('build'){
        steps {
          echo "jenkins Pipeline"
          sh './gradlew build --no-deamon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
      }
   }
}
