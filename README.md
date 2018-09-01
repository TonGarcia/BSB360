# BSB 360
BSB360 Video in VR

Password: BSB123

	```bash
		$ cd Builds
		$ jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore release.keystore bsb360-android.apk alias_name
		$ rm -rf BSB360.apk && zipalign -v 4 bsb360-android.apk BSB360.apk
	```


