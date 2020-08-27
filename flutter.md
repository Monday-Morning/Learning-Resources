FLUTTER TUTORIALS

**Set up your development environment:**

You can use your IDE/editor of choice. But we recommend using [VS Code](https://code.visualstudio.com/) because it has a lot of useful extensions which you may not find on Android Studio/Intellij IDEA. 

[Setup VS Code for Flutter](https://flutter.dev/docs/get-started/editor?tab=vscode)

The following is are a couple of useful extensions:

* Awesome Flutter Snippets(provides commonly used snippets so that you don’t need to type the whole code for those by yourself every time)

* Pubspec Assist(so that you don’t have to leave the comfort of your editor to get package names and versions)

* GitLens for Github  

[State Management:](https://flutter.dev/docs/development/data-and-backend/state-mgmt)

* InheritedWidget:
InheritedWidget is Flutter's way of making data available from widgets higher in the widget hierarchy to widgets lower in the hierarchy. This will help you get rid of the cumbersome way of accessing data down the widget hierarchy by passing it via parameters in all the constructors of the intermediate widgets.Provider builds on the concept of InheritedWidgets and makes them more reusable and easy to work with. Learning this will help you better understand the implementation of Provider.
1. [InheritedWidget documentation](https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html) - **DO** check out the video on this page to understand how to work with InheritedWidget.
2. [Understand the need for InheritedWidget](https://medium.com/@mehmetf_71205/inheriting-widgets-b7ac56dbbeb1)

* Provider:

1. [Provider introduction](https://www.youtube.com/watch?v=kDEflMYTFlk) 

2. [Provider with services](https://www.youtube.com/watch?v=dnW0NunWBTM)

3. [Dependency injection using Provider](https://www.youtube.com/watch?v=VgrK_LlQRJ4)

4. [Provider documentation](https://pub.dev/packages/provider)

* Stacked(This is exactly the things you will learn from the above tutorials, but now it’s in a package which takes care of the boilerplate for you and makes writing your code easier):

1. Stacked [playlist](https://www.youtube.com/playlist?list=PLdTodMosi-BwM4XkagNwe4KADOMWQS5X-) on FilledStacks youtube channel

2. [Stacked documentation](https://pub.dev/packages/stacked)

3. The stacked tutorials use code generation to remove the need for writing redundant code. Specifically, it uses two packages auto_route and injectable to generate code for routing and dependency injection respectively. You can check out the following videos:

* [Injectable](https://www.youtube.com/watch?v=KNcP8z0hWqs) ([Documentation](https://pub.dev/packages/injectable))

* [Auto_Route](https://www.youtube.com/watch?v=iVpVBmDhpJY) ([Documentation](https://pub.dev/packages/auto_route))

[//]: # (P.S.: We will stick to the stacked package and architecture for Monday Morning. These two videos are for understanding the packages better so that you can use them in your own # way where you want.) 

* Dependency Injection: Although provider can be used as a dependency injection solution as shown in the third video under the provider section, get_it is much simpler and easier to maintain the code.

1. [Dependency Injection using get_it](https://www.youtube.com/watch?v=vBT-FhgMaWM)

2. get_it  [documentation](https://pub.dev/packages/get_it)

[FlutterFire(Flutter & Firebase)](https://firebase.flutter.dev):

1. [FlutterFire documentation](https://firebase.flutter.dev/docs/)
2. [The Net Ninja's playlist on Firebase with Flutter](https://www.youtube.com/playlist?list=PL4cUxeGkcC9j--TKIdkb3ISfRbJeJYQwC) - This is a good playlist to get started with    Firebase in Flutter.
3. [Filledstacks' Firebase tutorial playlist](https://www.youtube.com/playlist?list=PLdTodMosi-Bzj6RIC2wGIkAxKtXPxDtca) - Firebase and Flutter using Provider and MVVM architecture. Knowledge of Provider and MVVM architecture is necessary to follow this playlist.
4. [Resocoder's Firebase tutorial playlist](https://www.youtube.com/playlist?list=PLB6lc7nQ1n4iS5p-IezFFgqP6YvAJy84U) - Firebase and Flutter using Bloc. Knowledge of Bloc is required to follow this playlist.

P.S.: It is NOT necessary to go through all the videos in a playlist or learn about everything on a topic to work with it. It is perfectly fine to start with one thing, implement it, solve the errors and then go for the next thing. 
