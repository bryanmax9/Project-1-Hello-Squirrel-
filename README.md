<!-- (This is a comment) INSTRUCTIONS: Go through this page and fill out any **bolded** entries with their correct values.-->

# AND101 Project 1 - Hello, Squirrel!

Submitted by: **Bryan Tineo**

Time spent: **4** hours spent in total

## Summary

**Bryan's Computer Science Bio** is an android app that recreates the common "Hello, World!", to introduce ourselves to the neighborhood squirrel 🐿.  **This App shows my abilities on Android Studio as well as on Kotlin. Also, it showcases my hobbies and a brief explanation about myself**

If I had to describe this project in three (3) emojis, they would be: **🧑‍💻👻🎸**

## Application Features

<!-- (This is a comment) Please be sure to change the [ ] to [x] for any features you completed.  If a feature is not checked [x], you might miss the points for that item! -->

The following REQUIRED features are completed:

- [X] Change profile name to your name
- [X] Change profile bio text to a personal bio about yourself
- [X] Modify hobby section to include your top three (3) hobbies

The following STRETCH features are implemented:

- [X] Re-brand the app by modifying the UI
- [X] Modify the profile image by uploading a new image drawable

The following EXTRA features are implemented:

- [ ] List anything else that you added to improve the app!

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<img src='http://i.imgur.com/e3VzlGN.gif' title='Video Demo' width='' alt='Video Demo' />

GIF created with **[ScreenToGif](https://www.screentogif.com/)**

<!-- Recommended tools:
- [Kap](https://getkap.co/) for macOS
- [ScreenToGif](https://www.screentogif.com/) for Windows
- [peek](https://github.com/phw/peek) for Linux. -->

## Notes

Here's a place for any other notes on the app, it's creation process, or what you learned this unit!
- For the creation Process, I had to learn the Kotlin programming language on CodeAcademy in order to than make changes to the overall project. In order to implement the bio Photo I had to add the photo to the "res > drawable directory" to than programmatically add that image on the file named "MainActivity.kt"(in order to find the file i hod to do double shift and search the file). Once on "MainActivity.kt", I changed the code block of the function "configureImage" and select the correct image i uploaded. For the **Theme** I used the "colors.xml" that was already created, and also by creating a file named "styles.xml" on "main > res > values" where i added my theme for the app. Than in order to set the theme i had to use the file named "AndroidManifest.xml" and change to this "android:theme="@style/BryanTheme" inside the <application>.


## License

Copyright **2024** **Bryan Tineo**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
