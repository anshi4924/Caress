## Introduction:
  As we all know, the health status of many is getting worst due to work stress and anxiety. Depression has become the biggest problem for people. Most of the youth responsible for the growth of a country are crippled in the chains of depression and anxiety, thus slowing down developmental activities. Sadly, the problem is suffered by many yet not discussed openly. So here we bring a caretaker "CARESS" for all of them who suffer from the same but hesitate to tell.

# Table of Contents:

## Technology Stack:
  1) Flutter
  2) Dart
  3) Firebase
  4) Flask API
  5) Google Fit API
  6) NewsAPI
  7) scikit-learn
  8) Pandas



### Note - This app is currently in test mode and only users allowed by the admin who have a google account can use the app properly. The two possible publishing modes of the app are given below<br>

Publishing Status ( Important )<br>
<li>In Production:
Once you set your app status as "In production," your app will be available to anyone with a Google Account. Depending on how you configure your OAuth screen, you may have to submit your app for verification .<br>
<li>Testing:
If your app is still being tested and built, you can set your status to "testing". In this state, you can test your app with a limited number of users.<br>
Courtesy - https://console.cloud.google.com/apis


## Functioning and User Flow
1. Firstly the user sign up and login in the application.<br>
2. Basic Information of user, his friend/well wisher/guardian or any specialist doctor is taken for future use and profile display.<br>
3. Instructions are given to connect the app with the smart watch.<br>
4. After submitting the details and setting up the watch with app, the application ask for various permissions such as track activity, phone usage and personalized    google account permissions<br>
5. As soon as you give your google account access, data of your current vitals is shown on the screen which is updated after every 2 minutes.<br>
6. If there is a spike in the heart rate(>100), user recieves an alert notification.The alert notification suggests you to stop using an particular app(correctly 70% of the time) and provides you the facility to call your friend on a single tap. Also an email about the same is delivered to the friend/well wisher or specialist whose information was collected previously.Emails are sent after a duration of 3 hours only.<br>
7. Application also consists of articles page(contains articles related to mental health) and profile page which consits the data of user which can be updated frequently.<br>
8. Application also provides you with facility of self assessment of various mental health disorders such as Depression, PTSD, schizophrenia, addiction and anxiety. After taking the self assessment tests the results are shared with the specialist/doctor via an email.
9. Helpline page is there in the application which includes helpline numbers and website links of 11 mental health healing websites for support. Call to any organisation can be just made by a single tap on the contact tile.
10. One differentiating feature of the app is the smart stress analysis which works on a backend based ML model integrated using flask REST API. This smart stress analysis takes two inputs which is body temperature and no of steps you walked in past 30 minutes and based on these values and dataset which we are using in the backend, Application determines the probability level of stress you are having.


## Flutter dependecies used :
  cupertino_icons: ^1.0.2<br>
  permission_handler: ^10.2.0<br>
  health: ">=4.4.0 <5.0.0"<br>
  firebase_auth: ">=4.2.8 <4.2.9"<br>
  firebase_core: ^2.7.0<br>
  cloud_firestore: ^4.4.3<br>
  shared_preferences: ^2.0.18<br>
  flutter_local_notifications: ^13.0.0<br>
  firebase_messaging: ^14.2.5<br>
  timezone: ^0.9.1<br>
  persistent_bottom_nav_bar: ^5.0.2<br>
  image_picker: ^0.8.7<br>
  firebase_storage: ^11.0.16<br>
  http: ^0.13.5<br>
  url_launcher: ^6.1.10<br>
  usage_stats: ^1.2.0<br>
  flutter_phone_direct_caller: ^2.1.1<br>
  email_validator: '^2.1.16'<br>
  intro_screen_onboarding_flutter: ^1.0.0<br>
  intl: ^0.17.0<br>
  percent_indicator: ^4.2.3<br>
  font_awesome_flutter: ^10.4.0<br>
