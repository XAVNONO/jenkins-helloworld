node {
    stage('Clone') {
        git credentialsId: 'token-github', url: 'https://github.com/XAVNONO/jenkins-helloworld.git'    
    }   
    stage('Build') {
        sh 'javac Main.java'
    }  
    stage('Run') {
        sh 'java Main'    
    }
}
