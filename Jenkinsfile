node {
   stage('Clone') {
     git branch: 'main', url: 'https://github.com/Comoks/jenkins_lab.git'
    }
   stage('Build') {
        sh 'javac Main.java'
    }
   stage('Run') {
       sh 'java Main'
   
    }
}
