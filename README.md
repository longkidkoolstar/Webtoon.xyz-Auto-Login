# Webtoon.xyz+
---

## Webtoon.xyz Auto Login with User Settings

This userscript provides automatic login functionality for Webtoon.xyz and adds a **User Settings** tab to customize the script's behavior directly from the website.

### Features
- **Auto Login**: Automatically fills in and submits login credentials for Webtoon.xyz if enabled.
- **User Settings Tab**: Adds a "Userscript Settings" tab on the Webtoon.xyz user settings page to configure:
  - **Enable/Disable Auto Login**: Toggle automatic login on or off.
  - **Username and Password Update**: Directly update login credentials for automatic login.

### How It Works
1. **Auto Login**:
   - If auto login is enabled, the script checks for the "Sign In" button on the Webtoon.xyz page.
   - Automatically fills in saved username and password, checks "Remember Me," and submits the login form.

2. **User Settings Integration**:
   - On the URL `https://www.webtoon.xyz/user-settings/`, a new "Userscript Settings" tab is added to the navigation.
   - Selecting this tab opens a settings section where users can:
      - Enable or disable auto login.
      - Enter or update their username and password, which are stored securely using `GM.setValue`.
   - Changes to settings are saved immediately for a streamlined experience.

### Usage Instructions
1. Install the userscript on Greasy Fork or directly in your preferred userscript manager (e.g., Tampermonkey).
2. Visit the **User Settings** page on Webtoon.xyz to adjust userscript settings.
3. Toggle **Auto Login** as desired and enter your username and password to enable automatic login functionality.

### Technical Details
- The script uses `GM.getValue` and `GM.setValue` to securely store and retrieve user credentials.
- **Auto Login** runs only if enabled, and the **User Settings** tab allows in-page credential management.

---

