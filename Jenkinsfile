pipeline {
        agent any

        stages {
            stage('Checkout') {
                steps {
                         checkout scm

                        }}
                     stage('Build') {
                        steps {
                                sh '/home/devkanya/Documents/Devops-tools/apache-tomcat-9.0.73/bin/mvn install'

                               }}
                           stage('Deployment'){
                               steps {
                       
                                       sh 'cp target/Nykaa.war /home/devkanya/Documents/Devops-tools/apache-tomcat-9.0.73/webapps'
        }

}}}
