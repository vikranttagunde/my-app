node{
  stage('SCM Checkout'){
    git 'https://github.com/vikranttagunde/my-app'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
