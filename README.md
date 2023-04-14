# Todo App with React Native

## **Installation**

---

### For Ubuntu

We will use the apt package manager to install `nodejs` and `npm`.

```bash
sudo apt update                       // Update the package list
sudo apt install nodejs               // Install nodejs
sudo apt install npm                  // Install npm
```

Check if `nodejs` and `npm` are installed by running the following commands.

```bash
node -v                               // Check nodejs version
npm -v                                // Check npm version
```

We will then need to install `expo-cli` to be able to access our app directly from our phone easily

```bash
npm install -g expo-cli               // Install expo-cli
```

Next, you will have to install the **expo app** on your phone. You can find it on the **play store** or the **app store**.


### For Windows

First of all we will start by installing `nodejs` and `npm`.

Navigate to the following [link](https://nodejs.org/en/download/) and download the installer for your system

Check if `nodejs` and `npm` are installed by running the following commands.

```bash
node -v                               // Check nodejs version
npm -v                                // Check npm version
```

Finally, we will need to install **expo-cli** to be able to access our app directly from our phone easily

```bash
npm install -g expo-cli               // Install expo-cli
```

Next, you will have to **install** the **expo** app on your phone. You can find it on the **play store** or the **app store**.

### For Mac

If you have `homebrew` installed, you can install `nodejs` and `npm` by running the following commands.

```bash
brew install node                     // Install nodejs and npm
node -v                               // Check nodejs version
npm -v                                // Check npm version
```

If you don't have `homebrew` installed, you can install it by running the following command.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


## **Usage**

---

We will now set up our expo project.

```bash
npx create-expo-app --template      // Create a new expo project
```

You will then be prompted to choose a template. Choose the **blank** template.

```bash
 > Blank
   Blank (TypeScript)
   Navigation (TypeScript)
   Blank (Bare)
```

You will then be prompted to choose a name for your project. Choose a name for your project.

```bash
What would you like to name your app ? [todo-app]
```

Now the project is fully setup. You now have a folder with the name of your project. Navigate to that folder and use the following command to start the project.

```bash
expo start
```

This command starts your project. Go to your expo app on your phone and scan the QR code prompted in the terminal. This will open your app on your phone.

You are now able to modify your app in the `App.js` file.
