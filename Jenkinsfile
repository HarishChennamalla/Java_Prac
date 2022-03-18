pipeline
{
    agent any
    tools
    {
        maven 'MAVEN'
    }
    stages
    {
       stage('welcome')
       {
           steps
           {
               sh '''
               echo welcome harish
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
