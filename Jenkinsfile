pipeline {
  agent {
    dockerfile true
     {
         stages{
        stage('Docker build'){
            steps{
      image 'image'
      args '-d -p 3000:3000 -D image'

            }

        }
    }
}
}
}