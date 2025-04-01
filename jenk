pipeline{

  agent{
      label 'madhu'
  }
  stages{

      stage('git scm'){
        steps{
            echo " download the repo into workspace"
          git 'https://github.com/ganesh1246/maven-java-web-project.git'
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
