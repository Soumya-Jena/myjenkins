node{
  stage('SCM Checkout'){ // Give the name of your stage here 
    git 'https://github.com/Soumya-Jena/myjenkins.git'
  }
  stage ('Compile-package'){
    //sh 'mvn package' // sh is for shell script
    sh './myScript.sh'
  }
}
