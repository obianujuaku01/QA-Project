pipeline{
        agent any
        stages{
            stage('Clone'){
                steps{
                   checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/obianujuaku01/QA-Project.git']]])
                }
            }
        }
}
