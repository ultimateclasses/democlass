pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('call this job only') { 
            steps { 
                sh 'http://13.126.236.58:8080/job/jenkinspipejob/build?token=chetan' 
            }
        }
    }
}
