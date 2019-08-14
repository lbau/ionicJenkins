pipeline {
   agent any
      environment {
         //PATH='C:\Users\lesba_3nkrzb1\Documents\Proyectos\Banrural Guatemala\apks'
        echo "Prueba path"
      }
      /*
   stages {
      stage('NPM Setup') {
      steps {
         sh 'npm install'
      }
   }*/
    stage('Android Build') {
        steps {
      //sh 'ionic cordova build android --release'
      //sh 'node --max-old-space-size=8192 ./node_modules/@ionic/app-scripts/bin/ionic-app-scripts.js build --prod && cordova build android --release'
                echo "Prueba build android"
        }
    }
/*
   stage('IOS Build') {
   steps {
      sh 'ionic cordova build ios --release'
     } 
  }

   stage('Android Build') {
   steps {
      sh 'ionic cordova build android --release'
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
   */
 }
}
