@Library('mylib')_

pipeline
{
    agent any
    stages
    {
        stage('contDown')
        {
            steps
            {
                script
                {
                    cicd.newDownload("maven.git")
                }
            }
        }
        stage('contBuild')
        {
            steps
            {
                script
                {
                    cicd.newBuild()
                }
            }
        }
    }
    
}
