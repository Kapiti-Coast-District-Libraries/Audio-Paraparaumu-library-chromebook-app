# Audio-Paraparaumu-library-chromebook-app
Audio Paraparaumu library chromebook app

npm init -y

npm install @capacitor/core @capacitor/cli @capacitor/android

npx cap init "Audio Scheduler" "com.library.audioscheduler" --web-dir www

npx cap add android

npx cap copy


npm install @capacitor-community/keep-awake

npx cap sync

npx cap open android


In Android Studio, navigate to:

app > java > com.library.audioscheduler > MainActivity.java

Replace the contents of MainActivity.java with file in repository



AndroidManifest.xml

replace with repo file
