# Expo Applications - reset-project

Task 1: First Expo Mobile Application

---

## Objective
The goal of this task is to set up a mobile application  using the **Expo Router template**.
Explore the file structure of a React Native application with Expo, and make a simple modification to the home screen.

---

1. Initialize a New Expo Project
Run the following command to create a Expo project.
**npx create-expo-app@latest**

---

2. Modify the Home Screen
- Open the file: app/(tabs)/index.tsx
- Locate the default text: <Text>Welcome!</Text>
- Change it to: <Text>First App Created</Text>

---

3. Run and test the Application
**npx expo start**

---

4. Resetting the Application
**npm run reset-project**
Observations
- After running the reset command, expo provided an option: Do you want to move existing files to /app-example instead of deleting them? (Y/n):

- Selected Y → existing files were moved instead of deleted. A new directory were moved into /app-example.

📁 /app-example directory created.
➡️ /app moved to /app-example/app.
➡️ /components moved to /app-example/components.
➡️ /hooks moved to /app-example/hooks.
➡️ /constants moved to /app-example/constants.
➡️ /scripts moved to /app-example/scripts.

📁 New /app directory created.
📄 app/index.tsx created.
📄 app/_layout.tsx created.

✅ Project reset complete. Next steps:
1. Run `npx expo start` to start a development server.
2. Edit app/index.tsx to edit the main screen.
3. Delete the /app-example directory when you're done referencing it.