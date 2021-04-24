node{
  stage ('SCM Checkout'){
   git 'https://github.com/mohitK-kapoor/CI-with-Jenkins-in-AWS-Demo'
   }
  stage ('Compile Package'){
    def mvnHome = tool name: 'maven-plugin-3.10', type: 'maven'
    sh "mvn package"
  }
}
