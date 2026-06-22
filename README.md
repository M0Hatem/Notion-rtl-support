# Notion Content Only RTL (UserCSS)

A lightweight and elegant UserCSS style that enables full **Right-to-Left (RTL)** support and right-alignment for page content inside **Notion** (`notion.so`, `notion.site`, and `notion.com`), while keeping the Notion sidebar, navigation, menus, and editor UI controls strictly **Left-to-Right (LTR)**. 

This ensures that your documents, lists, databases, quotes, and AI chats read naturally in RTL languages (such as Arabic, Hebrew, Persian, and Urdu) without messing up the app's user interface.

---

## Features
- **UI Stays LTR:** The sidebar, top bar, buttons, and block menus remain LTR for a consistent app layout.
- **Content is RTL:** Targets titles, paragraphs, bullet/numbered lists, callouts, and toggle blocks.
- **Bidi Isolated Inputs:** Ensures proper text cursors and directional typing.
- **RTL Quote Blocks:** Flips quote borders to the right side and adjusts padding.
- **Fixed Lists & Checkboxes:** Corrects bullet, number, and checkbox margins so they display correctly on the right.
- **Strict LTR for Code Blocks:** Ensures programming language syntax remains LTR.
- **RTL Database Tables:** Aligns table cell content to the right without breaking the database controls.
- **RTL Notion AI Chat:** Formats AI chat responses to right-to-left layout.

---

## 🛠️ Step 1: Install the Stylus Extension

To use this style, you need the **Stylus** extension. Stylus is a clean, open-source user-style manager.

Select your browser to download and install:
*   [Stylus for Google Chrome / Brave / Edge](https://chromewebstore.google.com/detail/stylus/clngdbnookpehhhmjoccloknnmcbjbgl)
*   [Stylus for Mozilla Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
*   [Stylus for Opera](https://addons.opera.com/en/extensions/details/stylus/)

---

## 🚀 Step 2: Choose an Installation Method

Once Stylus is installed, you can choose one of the following methods to install this style:

### Method A: One-Click Install from GitHub (Recommended)
Because this stylesheet is configured as a standard UserCSS (`.user.css`), you can install and get automatic updates directly from your GitHub repository!
1. Upload `notion-rtl.user.css` to your public GitHub repository.
2. Click on the file in GitHub, and then click the **"Raw"** button at the top-right of the code block.
3. The URL will look like: `https://raw.githubusercontent.com/<username>/<repo>/main/notion-rtl.user.css`.
4. Navigate to this raw URL or click it. **Stylus will automatically detect the style and open an installation tab.**
5. Click **Install Style** on the left. You will receive automatic updates whenever you push changes to GitHub!

### Method B: Hosting on UserStyles.world (Click-to-Install Page)
To host the style publicly so anyone can install it with a single click (like [this style](https://userstyles.world/style/17309/notion-rtl)):
1. Go to [userstyles.world](https://userstyles.world/) and **Log In** (usually via GitHub).
2. Click **Create** in the top navigation.
3. Fill out the form:
   * **Name:** `Notion Content Only RTL`
   * **Description:** `RTL support for Notion page content only (keeps UI LTR).`
   * **Code:** Paste the entire contents of [notion-rtl.user.css](notion-rtl.user.css).
4. Click **Create Style**.
5. You will be given a public URL (e.g. `https://userstyles.world/style/XXXXX/notion-content-only-rtl`). 
6. Anyone who visits your page can click the **Install** button to add it to their Stylus extension instantly.

### Method C: Hosting on UserStyles.org
If you prefer to host it on the older directory (UserStyles.org / Restyle):
1. Sign up/log in to [userstyles.org](https://userstyles.org/).
2. Click **Upload a New Style** or navigate to the creator dashboard.
3. Set the Title, Description, and paste the code from [notion-rtl.user.css](notion-rtl.user.css).
4. Save and publish.
*(Note: userstyles.world is generally faster and preferred by the community over userstyles.org due to performance and usability).*

### Method D: Manual Installation
If you want to use it privately without hosting it:
1. Click the **Stylus extension icon** in your browser toolbar.
2. Click **Manage** to open the dashboard.
3. Click **Write new style** on the left.
4. Paste the content of [notion-rtl.user.css](notion-rtl.user.css) into the editor.
5. Click **Save** on the left.

---

## 🔧 Customizing the Style
If you wish to modify the style:
1. Open the Stylus dashboard.
2. Find **Notion Content Only RTL** and click the edit/pencil icon.
3. Make your CSS modifications and save.
