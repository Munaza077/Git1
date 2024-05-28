hpipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Allication build stage...' 
                echo"This ismy IP"
                curl -s ifconfig.com}
                echo "This is my Hostname"
                hostname -f
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
