# 🪟 WinBlur (Windows 10 & Above)
WinBlur is a C#, VB, C++ .NET Library that allows developers to use modern blur types on their forms, (and maybe) controls.

**Getting Started: __3 easy steps__ to use WinBlur.**

- **Step 1.** Install "WinBlur" from NuGET.

```
Install-Package WinBlur
```

- **Step 2.** Head over to your form, and import the packages needed.

```cs
using WinBlur;
using static WinBlur.UI;
```

- **Step 3.** Create the `Form_Load` event, or head over to the form constructor and add the following code:

```cs

// cntrl: The form/control you are targetting.
// blurType: The blur type for the form/control.
// designMode: The design mode (or style) for the form/control.

// this.BackColor = Color.Black;
// The code on top is recommended, but is not necessary.
// In case the code below doesn't work by itself, please change the control/form BackColor to Black/White.

SetBlurStyle(cntrl: this, blurType: BlurType.Acrylic, designMode: Mode.DarkMode);
```

There you have it!
Your form now supports & uses **WinBlur**.

![image](https://user-images.githubusercontent.com/84229419/210150565-e05c47d0-7a63-4381-8cb2-5ba9ed278ffa.png)

## Open Source

This project is open-source, and free to use commercially & personally. I would not like any credit for this, enjoy using it.\
If you want to contribute, feel free to make a pull request and merge it.
