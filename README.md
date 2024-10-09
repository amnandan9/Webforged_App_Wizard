This is a template project for Android Studio that allows you to create an android webview application in minutes. You can use it to create a simple app for your website or as a starting point for your HTML5 based android app.

### Getting started

[Download](https://github.com/amnandan9/Webforged_App_Wizard/archive/refs/heads/main.zip) or clone this repository and import it into Android Studio.

### Using a remote source

1. Open the`app/src/main/res/values/strings.xml` file and modify the `app_name` and `web_url` string values as needed.
   
2. Navigate to the `app/scr/main/java/com.example.app/MyWebViewClient.java` file and replace `"example.com"` on line 16 with your specific hostname.

```java
	String hostname = "example.com";
```
3. If you need to change the package name, edit it in the `app/build.gradle` file at line 7.

Example:

```java
	applicationId "com.example.app"
```

Using a Local Source
To create a local HTML5 Android app, place all your files `(including index.html)` inside the `assets` directory.

Branding
If you want to change the package name, update it in the `app/build.gradle` file on line 7.
Example:

```java
	applicationId "com.example.app"
```

To update the application icon, replace the files in the `app/src/main/res/mipmap-*` directories with your new icon.
