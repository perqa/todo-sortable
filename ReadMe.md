# React Native draggable to-do list

This is a React Native app with a sortable, draggable to-do list, which supports the [new architecture](https://reactnative.dev/docs/the-new-architecture/use-app-template).

The app is described in more detail in a [blog post](https://blog.logrocket.com/react-native-draggable-flatlist/) over at LogRocket. Kudos to Shad Mirza for creating the [original repo](https://github.com/iamshadmirza/todo-sortable), which this was forked from.

This fork was created to fix some issues with the original code. All dependencies have been updated to newer versions, which got rid of issues with enabling the new architecture's JavaScript engine Hermes, and connecting to the debugger. Furthermore, there was an issue with clicking list items to mark them as done, which made the app crash.

