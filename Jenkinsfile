node{
  stage ('SCM Checkout'){
   git 'https://github.com/mohitK-kapoor/CI-with-Jenkins-in-AWS-Demo'
   }
  stage ('Compile Package'){
  sh "mvn package"
  }
}
