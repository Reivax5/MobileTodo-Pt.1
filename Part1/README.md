# Part 1

---

After having initialized the project, we can start working on the `app`. You now have a folder with the name you gave.
This is now the **root of your project**. In this **folder** you have a `App.js` file, it is the main file of your app. You can modify it to change the app.
Right now the file looks like this:
```bash
```javascript
import { StatusBar } from 'expo-status-bar';
import { StyleSheet, Text, View } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text>Open up App.js to start working on your app!</Text>
      <StatusBar style="auto" />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
});
```

This is the default code that is generated when you create a new expo project. We will now modify it to create our todo app.
As you might already know, React Native uses a **component based** approach. This means that we will have to create a component for each part of our app.
As we can see in the code, we have a `View` component. This is a **container** that will contain all the other components.
In it for example, we have a `Text` component. This is a component that will display text on the screen. We can modify the text by changing the text inside the `Text` component.
Modify the code so that when the app is started, a welcome text is displayed.

Well done, you have now created your first component. You can now create a component for each part of your app.

## **Components**

---

We will now create the components for our app. We will create a component for each part of our app.
We will start by creating a search bar. This will allow us to search for a todo.
To do so you will just have to add some new components into the `View` component.
To create a `SearchBar` component, you will probably need to use the `TextInput` component. This component will allow us to type text.
You can find more information about the `TextInput` component [here](https://reactnative.dev/docs/textinput).

Now that we have a search bar, we will create a `TodoList` component. This component will display all the todos.
To do so, you will need to use the `FlatList` component. This component will allow us to display a list of items.
You can find more information about the `FlatList` component [here](https://reactnative.dev/docs/flatlist).

Now that we have a `TodoList` component, we will create a `Todo` component. This component will display a single todo.
To do so, you will need to use the `View` component. This component will allow us to create a container.
You can find more information about the `View` component [here](https://reactnative.dev/docs/view).
