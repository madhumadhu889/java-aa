
pipeline{

  agent any
      
  
  stages{

      stage('git scm'){
        steps{
            echo " download the repo into workspace"
          git 'https://github.com/madhumadhu889/java-aa.git'
        }
      }
    stage('package'){
        steps{
          echo "package is crated"
          sh 'mvn package'
        }
      }

      stage('deploy to tomcat'){
        steps{
          echo 'deploy to tomcat'
        }
      }


  }
  




}
