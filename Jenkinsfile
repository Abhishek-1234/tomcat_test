pipeline{
  agent any
  
  stages{
    stage('Build'){
      steps{
        echo 'This is build stage'
        bat 'Build.bat'
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
