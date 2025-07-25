---
title: Gradia
categories: ['python', 'gradient', 'gtk']
---
## [Gradia](https://github.com/AlexanderVanhee/Gradia)

### Make your screenshots ready for all


If you'd like Gradia to **open automatically** after taking a screenshot, you can set up a custom keyboard shortcut:

1. Go to **Settings** → **Keyboard** → **View and Customize Shortcuts** → **Custom Shortcuts**.
2. Click the **+** button to create a new shortcut.
3. Set the **Name** to something like *Open Gradia with Screenshot*.
4. For the **Command**, enter:

   ```
   flatpak run be.alexandervanhee.gradia --screenshot=INTERACTIVE
   ```
   (You can also use `--screenshot=FULL` to take a screenshot of all existing screens instantly.)
5. Assign a keyboard shortcut of your choice (`Ctrl + Print` should be free by default).
