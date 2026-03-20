# CipherRoom — Get Your Windows Installer

Follow these steps once. After that, anyone can download the `.exe` from a link.

---

## Step 1 — Create a free GitHub account
Go to https://github.com and sign up (free).

---

## Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `cipherroom`
3. Set it to **Public**
4. Click **Create repository**

---

## Step 3 — Upload these files
On your new repo page, click **"uploading an existing file"** (or drag and drop).

Upload ALL the files from this zip:
```
main.js
index.html
package.json
icon.ico
.github/workflows/build.yml   ← make sure this path is kept!
```

> ⚠️ For the `.github/workflows/build.yml` file, you need to create the folders:
> On GitHub click **"Create new file"**, type `.github/workflows/build.yml` as the filename,
> then paste the contents of the `build.yml` file.

Commit/save all files.

---

## Step 4 — Watch it build
1. Go to the **Actions** tab on your repo
2. You'll see a workflow called **"Build Windows Installer"** running
3. Wait ~3-5 minutes for it to finish (green checkmark ✓)

---

## Step 5 — Get the download link
1. Click the finished workflow run
2. Scroll to the bottom → **Artifacts**
3. Click **CipherRoom-Windows-Installer** to download the `.exe`

To share with others:
- Copy the URL of the Actions run page and send it — they click Artifacts → download
- Or re-run the workflow anytime to get a fresh build

---

## What the installer does
- One-click install, no prompts
- Creates a desktop shortcut + Start Menu entry
- App name: **CipherRoom**
- Uninstall via Windows Settings → Apps like any normal app

---

## Security reminder
Share the **room password** with your chat partner through a separate channel
(WhatsApp, in person, etc.) — never through CipherRoom itself.
