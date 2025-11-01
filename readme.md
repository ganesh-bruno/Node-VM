# Bruno Node VM Collection

This Bruno collection demonstrates the new **Node VM** feature, which allows you to run Node.js libraries (like `mysql2` and `pdf2json`) directly inside Bruno scripts.

Clone this repo with `git clone` or simply click on the **Fetch in Bruno** button below to open this collection in Bruno:

[<img src="https://fetch.usebruno.com/button.svg" alt="Fetch in Bruno" style="width: 130px; height: 30px;" width="128" height="32">](https://fetch.usebruno.com?url=https%3A%2F%2Fgithub.com%2Fganesh-bruno%2FNode-VM.git "target=_blank rel=noopener noreferrer")

## 🎯 What's New?

Previously, Bruno used a VM sandbox that had limited support for JavaScript library packages. Now with **Node VM** (Node.js built-in), you can use powerful libraries that were not available before!

## ⚠️ Beta Feature

Node VM is currently in **beta**. To enable it:

1. Go to **Preferences** → **Beta**
2. Check the **Node VM** checkbox

## 📦 Available Examples

### 1. MySQL2 (`mysql.bru`)
Run MySQL database queries directly from Bruno.

**Requirements:**
- Properly configure your connection settings in the script:
  - `host` - Your database host
  - `port` - Database port (default: 3306)
  - `user` - Database username
  - `password` - Database password
  - `database` - Database name

Make sure all credentials are correctly set up before running the script.

### 2. PDF2JSON (`pdf2json.bru`)
Parse PDF files and extract JSON data.

**Note:** Feel free to modify script added in `pdf2json` bru file. Currently the response returns the length of the binary data available in console.

## 🚀 Getting Started

1. Enable Node VM in preferences (see above)
2. Install dependencies:
   ```bash
   npm install
   ```
3. Update connection credentials in the `.bru` files for `mysql2`
4. Switch to `Developer Mode` in Bruno
4. Run your scripts!

## 📝 Important Notes

- Double-check all parameters and credentials before running scripts
- Ensure your MySQL server is running and accessible for `mysql.bru`
- Review each `.bru` file for specific configuration requirements

---

Happy testing with Node VM! 🎉

