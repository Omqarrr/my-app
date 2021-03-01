
node {

  stage ('SCM checkout') {
    
      
    
    git branch: 'main', url: 'https://github.com/Omqarrr/my-app'
  }
         
         stage ('Maven Package') {    
           
            def mvnHome = tool name: 'Maven-CICD', type: 'maven'
           sh "${mvnHome}/bin/mvn package"           
         }

}
