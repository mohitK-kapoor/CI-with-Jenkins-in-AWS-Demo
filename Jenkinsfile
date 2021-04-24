node{
  stage ('SCM Checkout'){
   git 'https://github.com/mohitK-kapoor/CI-with-Jenkins-in-AWS-Demo'
   }
  stage ('Compile Package'){
  def mvnHome = tool name: 'Maven 3.6', type: 'maven'
    sh "mvn package"
  }
}
