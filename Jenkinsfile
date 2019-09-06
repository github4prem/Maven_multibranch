node('master')
{
    stage('ContinuousDownload')
    {
       git 'https://github.com/github4prem/Maven_multibranch.git'
    }
    stage('ContinuousBuild')
    {
        sh label: '', script: 'mvn package'
    }
}
