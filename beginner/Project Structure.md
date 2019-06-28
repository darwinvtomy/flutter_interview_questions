## Project Structure

**Why are there Android and iOS folders in the Flutter project?**

There are three main folders in the Flutter project: lib, android and ios. ‘lib’ takes care of your Dart files. The Android and iOS folders exist to actually build an app on those respective platforms with the Dart files running on them. They also help you add permissions and platform-specific functionality to your project. When you run a Flutter project, it builds depending on which emulator or device it is running on, doing a Gradle or XCode build using the folders inside it. In short, those folders are entire apps which set the stage for the Flutter code to run.

**What are packages and plugins?**

Packages allow you to import new widgets or functionality into your app. There is a small distinction between packages and plugins. Packages are usually new components or code written purely in Dart whereas plugins work to allow more functionality on the device side using native code. Usually on DartPub, both packages and plugins are referred to as packages and only while creating a new package is the distinction clearly mentioned.

**What is the pubspec.yaml file and what does it do?**

The Pubspec.yaml allows you to define the packages your app relies on, declare your assets like images, audio, video, etc. It also allows you to set constraints for your app. For Android developers, this is roughly similar to a build.gradle file, but the differences between the two are also evident.

**Why does the first Flutter app build take so long?**

When building a Flutter app for the first time, a device-specific APK or IPA file is built. Hence, Gradle and XCode are used to build the files, taking time. The next time the app is restarted or hot-reloaded, Flutter essentially patches the changes on top of the existing app giving a blazing fast refresh.

**How do i add Images in my app?**

Images can be added in a folder in a project and the directory name should be updated under Image tag in Pubspec.yaml

**What is External Liberaries in Flutter Project?**

External Liberaries consists of packages which are defined as dependency in Pubspec.yaml file

**what is the purpose of test folder in Flutter Project Directory?**

The unit testing fies are added in the test folder and can be excuted by using "flutter test" command

**What is the purpose of build folder?**

The compiled code for android and IOS are found inside the build Folder

**What is cupertino_icons why are they called so?**

Cupertion Icons are Default icons asset used by Flutter's Cupertino widgets for Apple IOS Counter part. Cupertino is a city in California's Silicon Valley. Known as the headquarters of Apple.


