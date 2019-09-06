node('master')
{
    stage('ContinuousDeployment')
    {
        sh label: '', script: 'scp /home/ubuntu/.jenkins/workspace/scmpipeline/webapp/target/webapp.war ubuntu@172.31.42.164:/var/lib/tomcat8/webapps/testapp99.war'
    }
}
