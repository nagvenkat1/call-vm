pipeline{
    agent {label 'JDK11'}
    stages{
         stage('Vm Create'){
            steps{
                sh 'chmod 777 vmcli.sh'
                sh './vmcli.sh'
             }
        }
    }
}
