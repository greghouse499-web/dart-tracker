# 🚀 Deploy Your Dart Competition Tracker

## Quick Setup with Vercel (5 minutes - FREE)

### Step 1: Get the Code
1. Copy the **App.jsx** code from the artifact above
2. Save it to your computer temporarily

### Step 2: Create a Vercel Account
1. Go to [vercel.com](https://vercel.com)
2. Click "Sign Up"
3. Use your GitHub, GitLab, or Bitbucket account (or create with email)

### Step 3: Deploy with Vercel
You have two options:

#### Option A: Simple Upload (Easiest)
1. Create a new folder on your computer called `dart-tracker`
2. Inside that folder, create a file called `index.html`
3. Paste this code into `index.html`:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Social Darts AU - Competition Tracker</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
  <div id="root"></div>
  <script type="module">
    import React, { useState, useEffect } from 'https://esm.sh/react@18';
    import ReactDOM from 'https://esm.sh/react-dom@18/client';
    import { Trophy, Users, Plus, X, Eye, EyeOff, RotateCcw, Target } from 'https://esm.sh/lucide-react@0.263.1';

    // PASTE YOUR App.jsx CODE HERE (the entire component)
    // Then at the bottom add:
    ReactDOM.createRoot(document.getElementById('root')).render(React.createElement(DartCompetitionTracker));
  </script>
</body>
</html>
```

4. In Vercel dashboard, click "Add New Project"
5. Choose "Deploy with Vercel CLI" or drag & drop your `dart-tracker` folder
6. Done! You'll get a URL like `your-project.vercel.app`

#### Option B: GitHub Deploy (More Professional)
1. Create a GitHub account at [github.com](https://github.com) if you don't have one
2. Create a new repository called `dart-tracker`
3. Upload your files
4. In Vercel, click "Import Project"
5. Select your GitHub repository
6. Click "Deploy"

### Step 4: Get Your URL
- After deployment, Vercel gives you a URL like: `dart-tracker-abc123.vercel.app`
- This is your permanent link!

### Step 5: Create QR Code
1. Copy your Vercel URL
2. Go to any free QR code generator:
   - [qr-code-generator.com](https://www.qr-code-generator.com)
   - [qrcode-monkey.com](https://www.qrcode-monkey.com)
   - [QR Code Generator](https://www.the-qrcode-generator.com)
3. Paste your URL
4. Download the QR code image
5. Print it or share digitally!

---

## Alternative: Netlify (Also Free & Easy)

1. Go to [netlify.com](https://www.netlify.com)
2. Sign up (free)
3. Drag & drop your `dart-tracker` folder
4. Get your URL
5. Create QR code with that URL

---

## Important Notes

### Password Reminder
- **Current password:** `online2025`
- All users need this to access
- Same password for admin features

### Data Storage
- Uses browser localStorage
- Data persists on each device
- If someone clears their browser data, they'll lose local info
- For production use, consider adding a backend database

### Custom Domain (Optional)
- Both Vercel and Netlify allow custom domains
- Example: `darts.yourdomain.com`
- Usually costs $10-15/year for a domain

---

## Need Help?

If you get stuck:
1. Vercel has great documentation: [vercel.com/docs](https://vercel.com/docs)
2. Video tutorials on YouTube: Search "deploy react app to vercel"
3. Or share this with a tech-savvy friend!

---

## Your App Features Checklist ✅

- ✅ Password protection (`online2025`)
- ✅ Admin controls
- ✅ Player management (bulk add)
- ✅ Score tracking
- ✅ Weekly resets
- ✅ Competition (Race) resets
- ✅ Hidden points after 50
- ✅ Leaderboard
- ✅ Match history
- ✅ Mobile responsive

**Once deployed, your QR code will work forever and players can access it anytime!**