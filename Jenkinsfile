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
        stage('Build')
        {
            steps
            {
                sh ' mvn clean package'
            }
        }

    }
}
