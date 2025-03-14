<div align="center">
  <img src="https://raw.githubusercontent.com/bocajthomas/SE-Extended/dev/images/logo/SE%20Extended%20Logo.png" height="250" />

![Maintainer](https://img.shields.io/badge/maintainer-bocajthomas-black)

# SE Extended Custom Themes
A catalog of custom snapchat themes.

Here you can upload your custom themes or download themes created by other users
</div>

## How to Download a Theme
1. **Add This Repository to SE Extended**:
    - Copy This Link `https://github.com/SE-Extended/custom-themes`.
    - Open `SE Extended`.
    - Head To The `Quick Actions`.
    - Click `Theming`.
    - Click `Catalog`.
    - Click `Manage repositories`.
    - Click `Add Repository`.
    - Paste the link you copied.
    - Click `Add`.
    - Go back to the `Catalog`.
2. **Browsing & Installing Themes**:
    - Browse Through the themes.
    - Click `Install`.
3. **Enabling a Theme**:
    - Click the toggle next to the theme.
    - Close `Snapchat` from the recent tabs.
    - Open `Snapchat`.

## How to Create a Theme

1. **Theming Quick Action**:
    - Open `SE Extended`.
    - Scroll down to `Quick Actions`.
    - Tap `Theming`.
2. **Creating a Theme**:
   - Click `+ New theme`.
    - **Adding MetaData**:
       - Give the Theme a name.
       - Click the `arrow down` icon.
       - Give the Theme a `description`.
       - `Version` the theme.
       - Add your name as `Author`.
    - **Adding Colors**:
       - Click `+`.
       - Click on a attribute, E.G. `Main Text Color(sigColorTextPrimary)`.
       - Click the white circle.
       - Pick a color.
       - Back out of the color picker.
       - Click the `save` icon. 
3. **Enabling the Theme**:
    - Click the toggle next to a theme.
    - Close `Snapchat` from the recent tabs.
    - Open `Snapchat`.
4. **Exporting the Theme**:
    - Click the settings icon.
    - Click `Export`.
    - Click Save.

## How to Contribute a Theme

1. **Fork this Repository**: Click the 'Fork' button at the top right of this page to create a copy of this repository on your account.
2. **Upload Your Theme**:
    - Go to your forked repository.
    - Navigate to the `Themes/` directory.
    - Click on `Add file` and select `Upload files`.
    - Upload your theme JSON file.
    - Commit the changes.
3. **Updating the index**:
   - Navigate to The `index.json`.
   - Scroll down to the bottom.
   - Add the following:
    ```
    {
      "name": "Name of theme",
      "author": "Your name or Github name",
      "description": "Short description of the theme",
      "version": "version of the theme",
      "filepath": "Themes/themefilename.json"
    }
    ```
   - Commit the changes.
4. **Create a Pull Request**:
    - Go back to [SE-Extended/Themes](https://github.com/SE-Extended/custom-themes)
    - Click on `Pull Requests` and then click `New Pull Request`.
    - Select your forked repository and the branch with your theme.
    - Create the pull request.

Your theme will be reviewed and merged into the repository.
## Guidelines

- Ensure your theme file is in JSON format (Themes can be exported via the `Theming` Quick Action).
- In the Pull requests title Type `feat(theme): "theme name"`.

Thank you for contributing!
