pipeline {	

    agent master

    stages {
    
				stage('cleanup tomcat app') {      		    			
                    steps {			                                			
                        sh 'rm -rf ${TOMCAT_HOME}/webapps/sample*'  
                    }			
                }
				
                //stage('Checkout (for Build)'){
                //    steps {
                //        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [[$class: 'RelativeTargetDirectory', relativeTargetDir: '/var/jenkins/workspace/tomcat-sample/load']], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/adinesh10/tomcat-sample.git']]])
                //    }
                //}        
     			
                
    }
}
