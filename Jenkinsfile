node {
     stage('Git Clone') { 
     git 'https://github.com/kartikeyarise/kig.git'
      }
      stage ('Maven Clean'){
      sh 'mvn clean'
      }
      stage ('Maven compile'){
      sh 'mvn compile'
       }
      stage ('Maven Package'){
      sh 'mvn package'
      }
        }
