node{
    
    stage('SCM checkout'){
        tool name: '/opt/maven/apache-maven-3.6.1', type: 'maven'
        git 'https://github.com/nrganta/my-app'
    }
    stage('Compile-Package'){
        
        sh 'mvn package'
    }
}
