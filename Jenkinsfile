node{
   stage('Build') { 
        sh 'npm install'
    }
    stage('Test') { 
        sh './jenkins/scripts/test.sh'  
    }
    stage('Deliver') { 
        sh './jenkins/scripts/deliver.sh' 
    }
}