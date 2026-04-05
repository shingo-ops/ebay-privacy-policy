# eBay Listing Manager - Privacy Policy

This repository hosts the Privacy Policy for the **eBay Listing Manager** application.

## 🔗 Live URL

**Privacy Policy URL:**
```
https://shingo-ops.github.io/ebay-privacy-policy/
```

## 📋 Purpose

This Privacy Policy page is used for:
- **eBay OAuth 2.0 RuName configuration** - Required by eBay Developer Portal when creating RuNames for OAuth authentication
- **User transparency** - Explains how the eBay Listing Manager application handles data

## 🔄 Reusability

This Privacy Policy URL can be **reused by multiple eBay applications and accounts**:
- Multiple clients can reference the same Privacy Policy URL when creating their RuNames
- Each client will have their own unique RuName, but they can all share this Privacy Policy URL
- This is a standard practice and complies with eBay's policies

## 📝 Usage Instructions

When setting up eBay OAuth authentication:

1. Go to **eBay Developer Portal** → Your Application → User Tokens
2. Click **"Add eBay Redirect URL"**
3. Enter the following:
   - **Privacy Policy URL**: `https://shingo-ops.github.io/ebay-privacy-policy/`
   - **Your auth accepted URL**: `https://localhost:3000` (or your preferred callback URL)
4. Save to generate your RuName
5. Use the generated RuName in your application's configuration

## 🛠️ Technical Details

- **Platform**: GitHub Pages
- **Build**: Automatic deployment on push to main branch
- **HTTPS**: Enforced by default
- **Content**: Static HTML page (no server-side processing)

## 📄 Content

The Privacy Policy covers:
- Information collection and use
- Data storage (Google Spreadsheet)
- Data security (OAuth 2.0, automatic token refresh)
- Third-party services (Google Apps Script, eBay API)
- User rights and data control
- Contact information

## 🔒 Security

- No server-side processing - static HTML page only
- No cookies or tracking
- No data collection
- HTTPS enforced

## 📞 Contact

For questions about this Privacy Policy:
- Contact your system administrator or the person who provided you with the eBay Listing Manager application
- Refer to eBay Developer Portal documentation for technical issues

## 📜 License

This Privacy Policy is provided as-is for use with the eBay Listing Manager application.

---

**Last Updated**: April 5, 2026
