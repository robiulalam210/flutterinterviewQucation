# flutterinterviewQucation

1)What is Flutter?
Flutter is an open-source framework by Google for building beautiful, natively compiled, multi-platform applications from a single codebase.
Flutter is not a language; it is an SDK. Flutter apps use the Dart programming language for creating an app. The first alpha version of Flutter was released in May 2017.

2) What is Dart?
It is open-source and developed by Google in 2011. The purpose of Dart programming is to create frontend user interfaces for the web and mobile apps.
Dart is a client-optimized language for developing fast apps on any platform. Its goal is to offer the most productive programming language for multi-platform development.

3)What are the Flutter widgets?
Flutter widgets are built using a modern framework that takes inspiration from React. The central idea is that you build your UI out of widgets. Widgets describe what their view should look like given their current configuration and state. When a widget’s state changes, the widget rebuilds its description, which the framework diffs against the previous description to determine the minimal changes needed in the underlying render tree to transition from one state to the next.

5) What is StatefulWidget LifeCycle?

The lifecycle has the following simplified steps:

createState(): When we build a new StatefulWidget, this one calls createState() right away and this override method must exist.
initState(): It is the first method called after the Widget is created.This is our equivalent to onCreate() and viewDidLoad()
didChangeDependencies() : This method is called immediately after initState() on the first time the widget is built.
build() : This is called right after didChangeDependencies(). All the GUI is rendered here and will be called every single time the UI needs to be rendered.
didUpdateWidget(): It’ll be called once the parent Widget did a change and needs to redraw the UI.
deactivate(): Framework calls this method whenever it removes this State object from the tree
dispose(): It is called when this object and its State are removed from the tree permanently and will never build again.
6) What is AppLifecycleState?

AppLifecycleState is as follows:

inactive — The application is in an inactive state and is not receiving user input. (iOS only).
paused — The application is not currently visible to the user, not responding to user input, and running in the background.
resumed — The application is visible and responding to user input.
suspending — The application will be suspended momentarily. (Android only).

7) What is pubspec.yaml file?
It is responsible for handling importing images/fonts/third-party packages which you want to include in your project.
The pubspec. yaml file is used to define the dependencies of your Flutter project. This metadata information is written in the YAML language. This file can have the following fields name, version, description, homepage, repository, documentation, dependencies, environment, and more about the pubspec.yaml file.

