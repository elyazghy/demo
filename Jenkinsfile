pipeline {
            agent any 
            stages {
                stage("Build"){
                  steps {
                    sh '/opt/apache-maven/apache-maven-3.6.3/bin/mvn clean install'
                  }
                }
                stage('Test') {
                  steps {
                    sh '/opt/apache-maven/apache-maven-3.6.3/bin/mvn test'
                  }
                }
            }
        }
