[Portugues](https://github.com/elisioMassaqui/flutter_carousel_intro-robotgames-v/blob/main/Evitar%20conflitos.md)
|
[English](https://github.com/elisioMassaqui/flutter_carousel_intro-robotgames-v/blob/main/resources/translation/English/Avoid%20conflicts.md)

Firstly, I encountered difficulties when trying to execute the project.
That's why I chose to be the change I want to see in the world by creating this document.
The purpose of this document is to assist collaborators in ensuring that dependencies are updated effectively, regardless of the Flutter version you are using.
This is applicable not only to Flutter projects; you can apply this method to other types of projects, but the commands will be different, of course.

# Instructions for Dependency Update:

To ensure that your dependencies are up to date, follow the steps below:

This command will remove temporary files and caches generated by Flutter in the project.
```dart
flutter clean
```
Next, use the command:
This will make Flutter fetch the project's dependencies again, ensuring there are no cache issues.
```dart
flutter pub upgrade
```
After following these steps, you will be ready to work on the project without worrying about dependency conflicts.
![Anotação (20)](https://github.com/elisioMassaqui/flutter_carousel_intro-robotgames-v/assets/145590545/32f237f6-1005-4d36-9c93-e91f37f6b463)

