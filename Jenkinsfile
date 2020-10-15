pipeline { 
    agent any
    stages {
        stage('First Stage 1') {
            agent{label 'agent_maven'}
            
            steps {
                sh 'ls -la'
            }
        }
                stage('Second Stage 1') {
            agent{label 'agent_maven'}
            
            steps {
                sh 'pwd'
            }
        }
     }    
}
