pipeline
{
    agent any
    tools
    {
        maven 'MAVEN'
    }
    stages
    {
        stage('checkout')
        {
            steps
            {
                 checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/HarishChennamalla/java_repo.git']]])
            }
 
        }
        stage('Build')
        {
            steps
            {
                sh ' mvn clean package'
            }
        }
    }
}