Amplify for Flutter is distributed via **pub.dev**.

Open your **app**'s `pubspec.yaml` and add the following 3 dependencies below the line "sdk:flutter". 

```yaml
dependencies:
  flutter:
    sdk: flutter

  amplify_core: '<1.0.0'
  amplify_auth_cognito: '<1.0.0'
  amplify_analytics_pinpoint: '<1.0.0'
```

Run **Flutter Pub Get**

Android Studio requires you to sync your project with your new configuration. To do this, you can click **Flutter** in the notification bar above the file editor.  

![](~/images/lib/getting-started/flutter/set-up-android-studio-pub-get.png)

Alternatively, you can open a terminal window, cd into your project's root directory (where you pubspec.yaml is) and run: 

```bash
flutter pub get 
```

When complete, you will see *Process finished with exit code 0* in the output of the *Messages* tab at the bottom of your screen.

![](~/images/lib/getting-started/flutter/set-up-android-studio-configure-successful.png)