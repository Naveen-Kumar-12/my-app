  node{
   stage('SCM Checkout'){
     git 'https://github.com/Naveen-Kumar-12/my-app'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
   

