pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Allication build stage...' 
                echo"This ismy IP"
                
            
        }
       }
        stage('Test') {
            steps {
                echo 'Allication test stage' 
        }
        }
        stage('Run') {
            steps {
                echo 'Allication run stage' 
                sh'gcloud compute zones list'
            }
    }
}
}
