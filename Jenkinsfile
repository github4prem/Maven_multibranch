node('master')
{
    stage('ContinuousDownload')
    {
       git 'https://github.com/github4prem/maven.git'
    }
    stage('ContinuousBuild')
    {
        sh label: '', script: 'mvn package'
    }
}
