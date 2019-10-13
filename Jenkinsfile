node{
    
    stage('SCM checkout'){
        
        git 'https://github.com/nrganta/my-app'
    }
    stage('Compile-Package'){
        def mvnHome = tool name: '/opt/maven/apache-maven-3.6.1', type: 'maven'
        sh "${mvnHome}/bin/mvn pacakage"
    }
}
