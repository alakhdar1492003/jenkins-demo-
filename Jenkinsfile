node{
    git branch: 'main', url: 'https://github.com/alakhdar1492003/jenkins-demo-.git'
    stage('build'){
        
        try{
            sh'echo "build in progress"'
        }
        catch(Exception e){
            sh'echo "exception found"'
            throw e 
        }
    }
}            