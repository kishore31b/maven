node('master')
{
    stage('ContinuousDownload') 
    {
         git 'https://github.com/kishore31b/maven.git'
    }  
    stage('Parser test') 
    {
        logParser projectRulePath: '/home/ubuntu/parsing_rule.txt', showGraphs: true, useProjectRule: true
    }
}

