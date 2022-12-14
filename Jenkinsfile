node{
   stage('SCM Checkout'){
   git 'https://github.com/yvlokeshreddy/My_jenkinsApp'
   }
   stage('Compile_package'){
   def mvnHome = tool name: 'maven-3', type: 'maven'
   sh "${mvnHome}/bin/mvn package"
  }
}
