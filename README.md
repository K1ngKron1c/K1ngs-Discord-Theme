# 🌙 Installing K1ng'sTheme

**K1ng'sTheme** is a purple Tokyo-moon glass theme featuring radial status rings, designed to give Discord a custom look.

To use this theme, you'll need a Discord client mod that supports custom CSS themes. Choose **one** of the installation methods below.

> [!WARNING]
> BetterDiscord and Vencord are third-party Discord modifications. Using them may carry account or security risks, and Discord updates can occasionally break theme compatibility. Use them at your own discretion.

## 📁 Requirements

- The `K1ng'sTheme v1.4.0`  zip file
- One of the following:
  - [BetterDiscord](https://betterdiscord.app/)
  - [Vencord](https://vencord.dev/)

> [!IMPORTANT]
> **Keep the `.theme.css` file extension.** Do not rename the file to `.css` or `.txt`, as this may prevent the theme from being detected.

---

## 🅰️ Option A: BetterDiscord

### 1. Install BetterDiscord

1. Completely close Discord, including its system tray process.
2. Download the installer from [betterdiscord.app](https://betterdiscord.app/).
3. Run the installer and accept the terms.
4. Select your installed Discord version and complete the installation.
5. Reopen Discord and open **User Settings**.
6. Confirm that the **BetterDiscord** section appears.

### 2. Install the theme

1. Open **User Settings** (`Ctrl + ,`).
2. Navigate to **BetterDiscord → Themes**.
3. Click **Open Themes Folder**.
4. Copy `K1ng'sTheme.theme.css` into the folder that opens. The default location is:

   ```text
   %appdata%\BetterDiscord\themes
   ```

5. Return to Discord.
6. Enable **K1ng'sTheme** in your themes list.

✅ The theme should now be active.

---

## 🅱️ Option B: Vencord

### 1. Install Vencord

1. Completely close Discord.
2. Download the installer from [vencord.dev](https://vencord.dev/).
3. Run the installer and select your Discord installation.
4. Click **Install** and wait for it to finish.
5. Reopen Discord and open **User Settings**.
6. Confirm that the **Vencord** section appears.

> [!TIP]
> Prefer a standalone client instead of modifying your existing Discord installation? [Vesktop](https://github.com/Vencord/Vesktop) is a standalone Discord client built around Vencord that supports themes and plugins.

### 2. Install the theme

1. Open **User Settings → Vencord → Themes**.
2. Under **Local Themes**, click **Open Themes Folder**.
3. Copy `K1ng'sTheme.theme.css` into the folder that opens.

   The default location on Windows is:

   ```text
   %AppData%\Vencord\themes
   ```

4. Return to Discord.
5. Open **User Settings → Vencord → Themes**.
6. Click **Load missing Themes** if the theme isn't listed.
7. Enable **K1ng'sTheme**.

✅ The theme should now be active.

---

## ✨ After Installation

### Disable conflicting themes

For the best results, disable any older versions of K1ng'sTheme and the standalone **RadialStatus** theme.

Radial status rings are already integrated into K1ng'sTheme. Running both versions may cause duplicate effects or visual conflicts.

### Update the theme

To install an updated version:

1. Disable K1ng'sTheme in your theme settings.
2. Replace the existing theme file with the updated `K1ng'sTheme.theme.css`.
3. Re-enable the theme.

If the changes don't appear, restart Discord.

### Customize your theme

You can edit the theme file using a text editor such as Visual Studio Code or Notepad++.

- **Section 1 — Settings:** Adjust the theme's configurable options.
- **Section 12 — Custom CSS:** Add your own CSS overrides and customizations.

Save your changes and check whether they apply automatically. If they don't, toggle the theme off and on again.

> [!NOTE]
> The available settings depend on the version of the theme you're using. Keep a backup of your original file before making extensive changes.

---

## 🛠️ Troubleshooting

<details>
<summary><strong>The theme doesn't appear in the theme list</strong></summary>

- Confirm the filename ends in `.theme.css`.
- Make sure the file is in the correct themes folder.
- In Vencord, click **Load missing Themes**.
- Verify that your client mod is installed correctly.

</details>

<details>
<summary><strong>The theme broke after a Discord update</strong></summary>

1. Disable K1ng'sTheme.
2. Restart Discord completely.
3. Re-enable the theme.
4. If a specific element still looks incorrect, report the issue with a screenshot and your Discord client mod version.

Discord updates can change the CSS selectors used by themes, requiring compatibility fixes.

</details>

<details>
<summary><strong>Something looks wrong after customizing the theme</strong></summary>

Temporarily comment out or remove your custom CSS in **Section 12**. If the issue disappears, one of your overrides is likely causing the problem.

</details>

<details>
<summary><strong>How do I check for errors?</strong></summary>

1. Open Discord.
2. Press `Ctrl + Shift + I` to open Developer Tools, if supported by your client.
3. Select the **Console** tab.
4. Look for errors related to the theme or its CSS.

</details>

<details>
<summary><strong>How do I uninstall the theme?</strong></summary>

You can either:

- Disable K1ng'sTheme in your theme settings.
- Delete `K1ng'sTheme.theme.css` from your themes folder.

To remove BetterDiscord or Vencord entirely, use the appropriate uninstall option provided by the installer.

</details>

---

## 🔒 Safety & Privacy

K1ng'sTheme is a CSS theme and **does not load external resources from the web**.

For your safety:

- Only install theme files from sources you trust.
- Review modifications before using unofficial theme files.
- Keep your client mod and theme updated.
- Remember that third-party Discord modifications are not officially supported by Discord.

---

## 💜 Enjoy K1ng'sTheme!

Questions, issues, or suggestions? Visit the [I Need Help channel](https://discord.com/channels/1546396741018853417/1561645701627387986) in the community.

**K1ng'sTheme** · Made by **K1ngKron1c**

