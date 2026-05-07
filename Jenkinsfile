node {
    git branch: 'main' , url: 'https://github.com/ahmedrabe33/jenkins-lab.git'
    stage('build stage') {
       try {
        sh 'echo "build stage"'
    } catch (Exception e ) {
        sh 'echo "exception fount"'
        throw e 
       }
    }
    stage('test') {
        if (env.BRANCH_NAME == 'feat') {
            sh 'echo "test stage"' 
        
        }   else {
                sh ' echo "skip test stage"'
        }
    }
}