pipeline{
  tools{ 
    jdk 'jdk1.8'
    maven 'maven3'
  }
  stages{
    stage('git pull'){
     steps{
       echo 'this stage for pull repo'
       git 'https://github.com/durgaprasad20/devops.git'
    }
   }
    stage('mvn install'){
     steps{
      echo 'maven clean& install'
      sh 'mvn clean'
      sh 'mvn install'
     }
    }
 }
}




