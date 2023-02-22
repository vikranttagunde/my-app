node{
  stage('SCM Checkout'){
    git 'https://github.com/vikranttagunde/my-app'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: 'maven-3', type: 'maven'
    bat "${mvnHome}/bin/mvn package"
  }
}
