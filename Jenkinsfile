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
    stage("test"){
        if (env.BRANCH_NAME == "feat"){
            sh'echo "test stage"'
        }
        else{
            sh'echo "skip test stage"'
        }
    }
}            