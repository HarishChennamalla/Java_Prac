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
       stage('welcome1')
       {
           steps
           {
               sh '''
               echo welcome2
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