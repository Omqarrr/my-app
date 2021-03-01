
node {

  stage ('SCM checkout') {
    git branch: 'main', url: 'https://github.com/Omqarrr/my-app'
  }
         
         stage ('Maven Package') {          
           sh 'mvn package'          
         }

}
