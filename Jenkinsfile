pipeline {
   agent any

   stages {
      stage('UAT') {
         steps {
           git credentialsId: 'db541dcb-7df4-4db4-83ed-bb9f1e1f83ee', url: 'https://github.com/rkyadav1989/DevopsLearning.git'
         }
      }

      stage('Prod') {
         steps {
          sh label: '', script: 'chmod u+x script.sh; sh script.sh'
         }
      }      

      
   }

    
}
