# App Store Connect Setup Checklist

Use this guide to complete the requirements for submitting ByeSwipe for review.

---

## 1. Host Your Privacy Policy & Support URLs

You need live URLs. Easiest options:

### Option A: GitHub Pages (Free)
1. Create a new GitHub repo (e.g. `byeswipe-app` or `ByeSwipe`)
2. Upload the `privacy-policy.html` and `support.html` from this folder
3. Enable GitHub Pages: Settings → Pages → Source: main branch
4. Your URLs will be:
   - **Privacy Policy:** `https://YOUR_USERNAME.github.io/REPO_NAME/privacy-policy.html`
   - **Support URL:** `https://YOUR_USERNAME.github.io/REPO_NAME/support.html`

### Option B: Your Own Website
Upload the HTML files to your existing site and use those URLs.

### Option C: Notion, Google Sites, etc.
Create simple pages and use the public share links.

---

## 2. App Store Connect Settings

### App Information
- **Privacy Policy URL:** [Your hosted privacy-policy.html URL]
- **Support URL:** [Your hosted support.html URL] — **Required for English (U.S.)**
- **Content Rights Information:**  
  - Go to App Information → Content Rights  
  - Select: **"No"** — the app does not contain third-party content  
  - If asked about encryption: select standard encryption (HTTPS, etc.) or "No" if not applicable

### App Privacy (Required)
An **Admin** must complete this in App Store Connect:

1. Go to **App Privacy** in the left sidebar
2. Click **Get Started** or **Edit**
3. For "Do you or your third-party partners collect data?" → **No** (ByeSwipe does not collect data)
4. If you select "No," you may still need to confirm. Some apps are asked to disclose:
   - **Photos or Videos** — Used for app functionality (displaying, deleting). Stored locally only.
   - **User Content** — If you consider favorites/kept items as user content, it's stored locally.

If Apple's flow requires at least one category even for "no collection":
- **Data Type:** Photos or Videos  
- **Purpose:** App Functionality  
- **Linked to User:** No  
- **Used for Tracking:** No  

### Choose a Build
1. Go to **App Store** → **iOS App** → your version
2. Under **Build**, click **"+"** or **Select a build**
3. Pick the build you uploaded (e.g. 1.0 from your archive)

---

## 3. Summary of URLs to Use

| Field | Where to Enter | Example |
|-------|----------------|---------|
| Privacy Policy URL | App Information | `https://dayvuhd.github.io/ByeSwipe/privacy-policy.html` |
| Support URL | App Store → Version Information → English (U.S.) | `https://dayvuhd.github.io/ByeSwipe/support.html` |

---

## 4. Update Support Email (Optional)

Edit `support.html` and change `dayvuhd@icloud.com` to your preferred support email before hosting.
