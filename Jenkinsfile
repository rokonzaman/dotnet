pipeline {
 agent{
     label "kubernetes"
 }
  stages {
    stage('build_image') {
   steps {
	sh "docker build -t rokonzaman/dotnetproject:latest /root/jenkins_agent/workspace/netcore_multi_master/."
   }
  }
 }
}