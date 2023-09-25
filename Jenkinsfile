pipeline { 
    agent any
    stages {
        stage('call this job only') { 
            steps { 
                sh 'echo "this is first job"'
                sh 'echo "this is second job"' 
 
            }
        }
        stage('2nd job') { 
            steps { 
                sh 'python3'
            }
        }
    }
}
