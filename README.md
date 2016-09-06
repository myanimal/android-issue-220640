# android-issue-220640
Reproduction of http://b.android.com/220640

To reproduce the error run:
`./gradlew clean connectedCheck`

The avoid the error, comment out this classpath dependency (or upgrade to 3.0.0):
`classpath 'com.google.gms:google-services:2.1.2'`