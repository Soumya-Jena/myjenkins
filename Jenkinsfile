node{
  stage('SCM Checkout'){ // Give the name of your stage here 
    git url: 'https://github.com/Soumya-Jena/myjenkins.git', branch: 'main'
  }
  stage ('Compile-package'){
    //sh 'mvn package' // sh is for shell script
    sh './myScript.sh'
  }
}
