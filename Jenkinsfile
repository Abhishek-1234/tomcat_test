pipeline{
  agent any
  
  stages{
    stage('Build'){
      steps{
        echo 'This is build stage'
        bat 'Build.bat'
        javac JavaFile.java
        java JavaFile
      }
    }
    stage('Test'){
      steps{
        echo 'This is test stage'
        bat 'Test.bat'
      }
    }
    
    stage('Deploy'){
      steps{
        echo 'This is deploy stage'
        bat 'Deploy.bat'
      }
    }
  }

}
