pipeline{
    agent any
    stages{
        stage('1-repo clone'){
            steps{
                sh 'df -h'
            }
        }
        stage('2-CpuAnalysis'){
            steps{
                sh'lscpu'
            }
        }
        stage('3-MemoryCheck'){
            steps{
                sh 'free -g'
            }
        }
        stage('4-os-stat'){
            steps{
                sh 'cat /etc/os-release'
            }
        }
        stage('5-welcome vivian'){
            steps{
                echo 'welcome to pipeline code'
            }
        }
    }
}
by vivian umeh