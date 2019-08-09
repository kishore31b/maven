node('master')
{
    stage('ContinuousDownload') 
    {
         git 'https://github.com/kishore31b/maven.git'
    }
    stage('ContinuousBuild') 
    {
         sh label: '', script: 'mvn package'
    }    
}

