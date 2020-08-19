# flutter_login_demo

Quick Flutter app to showcase Login Authentication using Firebase.

## Details

Initial commit is code from article: "Flutter Authentication" by Rajat Palankar.  Excellent explanation, Rajat:
https://protocoderspoint.com/flutter-login-and-registration-page-using-firebase-authentication/

Second commit contains changes noted by FlutterFire package author: 
https://firebase.flutter.dev/docs/overview/#initializing-flutterfire

These changes are needed in order to make the Android demo app work (as of 2020-08-19).  Short explanation: await Firebase.initializeApp() needs to be called before invoking FirebaseAuth.instance.  Otherwise you'll get a missing [DEFAULT APP] firebase error.

Not surprised error occurs since underlying technology often changes once the tutorial has been written.


