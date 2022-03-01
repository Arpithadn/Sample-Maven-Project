node{
   stage('SCM Checkout'){
     git 'https://github.com/Arpithadn/Sample-Maven-Project'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome = tool name: 'Maven1', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
}
