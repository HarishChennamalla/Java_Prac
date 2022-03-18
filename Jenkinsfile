pipeline
{
    agent any
    tools
    {
        maven 'MAVEN'
    }
    stages
    {
        stage('Welcome')
        {
            steps
            {
                sh '''
                echo Welcome to multi branch pipeline-1
                '''
            }        
        } 
        stage('welcome1')
        {
            steps
            {
                sh '''
                echo welcome 2
                '''
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
