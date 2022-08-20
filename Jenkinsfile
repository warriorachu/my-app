node {
  stage ('SCM Checkout'){
    git 'https://github.com/warriorachu/my-app'  
     }
  stage ('Compile-Package'){
    sh 'mvn package'
  }

}
