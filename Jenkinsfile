pipeline{
  agent any
  stages{
    stage("Build"){
      steps{
        echo "GOGOGOGO it`s building"
        sh "./gradlew build --no-daemon"
        archiveArtifacts artifacts: "dist/trainSchedule.zip"
      }
    }
  }
}
