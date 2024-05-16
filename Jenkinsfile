pipeline{
     agent any
    
    tools{
        nodejs '18.14.2'
    }

    stages{
        stage('test node'){
            steps{
                sh 'npm version'
            }
        }
         stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}