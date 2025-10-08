# Flutter Theming Study Plan

This plan will guide you through the concepts of theming in Flutter, from the basics to more advanced topics. We will follow this plan and build a simple demo application to apply what we learn.

## 1. Understanding the Basics

*   **What is Theming?** Why it's crucial for brand consistency and user experience.
*   **`Theme` Widget:** The ancestor widget that provides theme data to its descendants.
*   **`ThemeData` Class:** The heart of Flutter theming. It holds all the visual properties of your application's theme.
*   **`Theme.of(context)`:** How to access the `ThemeData` from any widget in the subtree.

**Hands-on:**
*   Create a new Flutter project.
*   Wrap the `MaterialApp`'s `home` with a `Theme` widget and observe the changes.
*   Use `Theme.of(context)` to access and print some theme properties.

## 2. Colors and Schemes

*   **`ColorScheme`:** A set of colors that work well together. Understanding the different color properties like `primary`, `secondary`, `surface`, `background`, `error`, etc.
*   **`ThemeData.from(colorScheme: ...)`:** The modern way to create a `ThemeData` from a `ColorScheme`.
*   **Material 3 vs Material 2:** Briefly touch upon the differences and why Material 3 is the future.

**Hands-on:**
*   Define a `ColorScheme` for our demo app.
*   Create a `ThemeData` using the `ColorScheme`.
*   Apply the theme to the `MaterialApp`.

## 3. Typography and Text Themes

*   **`TextTheme`:** Defining a consistent set of text styles for headlines, subtitles, body text, etc.
*   **Applying Text Styles:** How to use the defined text styles throughout the app.
*   **Custom Fonts:** How to add and use custom fonts in your theme.

**Hands-on:**
*   Define a `TextTheme` for our app.
*   Apply different text styles to `Text` widgets.

## 4. Customizing Component Themes

*   **`AppBarTheme`, `ElevatedButtonTheme`, `CardTheme`, etc.:** How to define styles for specific widgets.
*   **`InputDecorationTheme`:** Styling text fields.

**Hands-on:**
*   Customize the `AppBar`'s appearance.
*   Create a custom style for `ElevatedButton`.
*   Style the `TextField`s in our app.

## 5. Light and Dark Themes

*   **`theme` and `darkTheme` properties of `MaterialApp`:** Providing both a light and a dark theme.
*   **`themeMode` property:** Controlling which theme to use (`ThemeMode.light`, `ThemeMode.dark`, `ThemeMode.system`).
*   **Switching Themes:** Building a UI to allow the user to switch between themes.

**Hands-on:**
*   Create a dark theme for our app.
*   Add a switch to the app to toggle between light, dark, and system theme modes.

## 6. Using `flex_color_scheme`

*   **Introduction:** What is `flex_color_scheme` and why it is a powerful tool for creating beautiful and consistent themes.
*   **Installation:** Adding the package to `pubspec.yaml`.
*   **Creating Themes:** Using `FlexThemeData.light` and `FlexThemeData.dark` to quickly create well-designed themes.
*   **Customization:** Exploring properties like `scheme`, `surfaceMode`, `blendLevel`, and `subThemesData` for fine-grained control.

**Hands-on:**
*   Add the `flex_color_scheme` dependency.
*   Refactor our demo app to use `flex_color_scheme` for both light and dark themes.
*   Experiment with different pre-built color schemes.
*   Customize the sub-themes for widgets like `AppBar` and `ElevatedButton`.

## 7. Advanced Theming (Optional)

*   **Theme Extensions:** Creating your own custom theme properties.
*   **Third-party packages:** Briefly mention packages like `dynamic_color` for Material You theming.

**Hands-on (if time permits):**
*   Create a simple theme extension to demonstrate the concept.

## Demo App Plan

We will build a simple app with the following screens:

*   **Home Screen:** Displays various themed widgets like `AppBar`, `Text`, `ElevatedButton`, `Card`, and a `FloatingActionButton`.
*   **Settings Screen:** Contains a switch to toggle between light and dark themes.
*   **Theming Approach:** We will start with the standard `ThemeData` and then refactor to use `flex_color_scheme` to see the benefits.

This hands-on approach will help solidify your understanding of Flutter theming. Once you approve this plan, we can start with the first step.
