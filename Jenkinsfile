node{
    
    stage('SCM checkout'){
        git 'https://github.com/nrganta/my-app'
    }
    stage('Compile-Package'){
        
        sh 'mvn package'
    }
}
