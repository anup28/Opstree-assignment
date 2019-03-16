  node{
   stage('SCM Checkout'){
     git 'https://github.com/anup28/Opstree-assignment'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
