
node {

  stage ('SCM checkout') {
    git 'https://github.com/Omqarrr/my-app'
  }
         
         stage ('Maven Package') {          
           sh 'mvn package'          
         }

}
