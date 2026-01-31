pipeline{
    agent {
        label 'slave'
    }

    stages{
        stage('Hostname'){
            steps{
                sh 'hostname'
            }
        }

        stage('Server Date'){
            steps{
                sh 'date'
            }
        }

        stage('CPU Details'){
            steps{
                sh 'lscpu'
            }
        }

        stage('Memory Usage'){
            steps{
                sh 'free -h'
            }
        }
        stage('Disk usage'){
            steps{
                sh 'df -kh'
            }
        }


    }
    
}
