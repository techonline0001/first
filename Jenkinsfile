pipeline{
  agent any
  stages{
   stage('clone'){
    steps {
       echo "this is cloning"
     }
    }
   stage('build'){
       steps{
         echo "build with maven"
      }
     }
   stage('test'){
     steps{
       echo "test result"
     }
   }
   stage('deploy'){
    steps{
   echo "deploy"
    }
  }
 }
}
