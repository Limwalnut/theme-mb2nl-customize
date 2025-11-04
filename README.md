# 🧩 mb2nl - IMC Custom Theme

This project customizes the **New Learning** theme for IMC’s Moodle platform, providing branding alignment and improved user experience.

---

## 🚀 Installation

1. **Prepare the package**
   - Zip the entire project folder into a `.zip` file (e.g., `theme_mb2nl.zip`).  
   - **Important:** When uploading to Production, run:
     ```bash
     zip -r mb2nl.zip mb2nl -x "mb2nl/.git/*"
     ```
     to exclude `.git` files, which are not accepted on the Production site.

2. **Log in as Administrator**
   - Go to your Moodle site: [https://moodle.imc.edu.au/admin](https://moodle.imc.edu.au/admin)

3. **Install the plugin**
   - Navigate to:  
     `Site administration → Plugins → Install plugins`  
   - Upload the zipped file (`theme_mb2nl.zip`).

4. **Complete installation**
   - Follow the on-screen prompts to complete installation.  
   - After installation, select the theme in:  
     `Site administration → Appearance → Theme selector`.

5. **Purge caches**
   - Go to: `Site administration → Development → Purge all caches`  
     (This ensures the updated theme is fully applied.)

---

## 🛠️ Update or Reinstall

To update the theme:

1. Zip the latest version of the project.  
2. Reinstall it through the **Install Plugins** page.  
3. Moodle will detect it as an update.  
4. Purge caches after the update.

---

## 🧾 Changelog

All notable changes to this project will be documented here.

### [1.0.1] - 2025-11-03
#### Added
- Added **Guest Login** button on the login page.  
- Added **Guest Login** string in `theme_mb2nl.php`.

#### Changed
- Removed **continuewith** text on the SSO login button.

---

## 🧑‍💻 Author

IMC IT Team  
[https://moodle.imc.edu.au](https://moodle.imc.edu.au)