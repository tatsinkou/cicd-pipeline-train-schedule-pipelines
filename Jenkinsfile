pipeline{
  agent any
  stages{
    stage('Build stage'){
      steps{
        echo '########### Running Build Automation #############'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    } 
 }
}