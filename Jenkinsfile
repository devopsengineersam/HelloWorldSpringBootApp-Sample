pipeline{
    agent{
        label 'jenkins-slave'
    }
    stages{
        stage('Git clone'){
            steps{
                git branch: 'main', url: 'https://github.com/netengineersam/HelloWorldSpringBootApp-Sample.git'
            }
        }
        stage('test'){
            steps{
                echo "Testing complete"
            }
        }
        stage('Build'){
            steps{
                sh 'bash bash.sh'
            }
        }
    }
}