node{
  stage ('SCM Checkout'){
   git 'https://github.com/mohitK-kapoor/CI-with-Jenkins-in-AWS-Demo'
   }
  stage ('Compile Package'){
    def mvnHome = tool name: '', type: 'maven'
    sh"${mvnHome}/bin/mvn package"
  }
}
