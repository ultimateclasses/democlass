pipeline { 
    agent any
    stages {
        stage('call this job only') { 
            steps { 
                sh 'echo "this is first job"'
                sh 'echo "this is second job"' 
                sh 'echo "this is third job"' 
                sh ""
 
            }
        }
        stage('2nd job') { 
            steps { 
                sh 'python3'
            }

        }
        stage('how are you') { 
            steps { 
                sh 'ram ram'
            }
            
        }
    }
}
