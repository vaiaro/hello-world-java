pipeline {
   agent any

   stages {
      stage('Checkout') {
         steps {
            git 'https://github.com/AnjuMeleth/hello-world-java.git'
         }
      }
      stage('Build'){
        steps {
            bat 'javac HelloWorld.java'
        }
      }
   }
}
