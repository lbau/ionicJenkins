pipeline {
   agent any
      environment {
         PATH=''
      }
   stages {
      stage('NPM Setup') {
      steps {
         cmd 'npm install'
      }
   }

   stage('IOS Build') {
   steps {
      start cmd 'npm install'
     } 
  }

   stage('Android Build') {
   steps {
      cmd.exe 'npm install'
   }
  }

   stage('APK Sign') {
   steps {
      sh 'jarsigner -storepass your_password -keystore keys/yourkey.keystore platforms/android/app/build/outputs/apk/release/app-release-unsigned.apk nameApp'
   }
   }

   stage('Stage Web Build') {
      steps {
        sh 'npm run build --prod'
    }
  }

   stage('Publish Firebase Web') {
      steps {
      sh 'firebase deploy --token "Your Token Key"'
   }
  }

   stage('Publish iOS') {
      steps {
       echo "Publish iOS Action"
    }
   }

   stage('Publish Android') {
     steps {
    echo "Publish Android API Action"
   }
  }

 }
}
