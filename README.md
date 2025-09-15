# MindWell Legal Documents for GitHub Pages

This repository contains the legal documents required for MindWell App Store submissions.

## Setup Instructions

### 1. Create GitHub Repository
```bash
# Create a new public repository named "mindwell-legal"
# Upload these files to the repository
```

### 2. Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click Save

### 3. Access URLs
After GitHub Pages is enabled, your legal documents will be available at:
- Main page: `https://yourusername.github.io/mindwell-legal/`
- Privacy Policy: `https://yourusername.github.io/mindwell-legal/privacy.html`
- Terms of Service: `https://yourusername.github.io/mindwell-legal/terms.html`
- Support Center: `https://yourusername.github.io/mindwell-legal/support.html`
- HIPAA Notice: `https://yourusername.github.io/mindwell-legal/hipaa.html`

### 4. Update App Configuration
Replace all `mindwell.app` references in your app with your GitHub Pages URLs:

```javascript
// Example configuration update
const LEGAL_URLS = {
  privacy: 'https://yourusername.github.io/mindwell-legal/privacy.html',
  terms: 'https://yourusername.github.io/mindwell-legal/terms.html',
  support: 'https://yourusername.github.io/mindwell-legal/support.html',
  hipaa: 'https://yourusername.github.io/mindwell-legal/hipaa.html'
};
```

## Files Included

- `index.html` - Main legal documents page
- `privacy.html` - Privacy Policy (HIPAA-compliant)
- `terms.html` - Terms of Service
- `support.html` - Support Center
- `hipaa.html` - HIPAA Notice of Privacy Practices
- `README.md` - This setup guide

## App Store Requirements

### iOS App Store
- Privacy Policy URL: **Required**
- Support URL: **Required**
- Terms of Service URL: Recommended

### Google Play Store
- Privacy Policy URL: **Required**
- Developer Contact: **Required**

## Important Notes

1. **Email Addresses**: Update all `mindwell-app.com` email addresses to your actual support emails
2. **Legal Review**: Have these documents reviewed by a legal professional
3. **HIPAA Compliance**: Ensure all business associate agreements are in place
4. **Updates**: Keep documents current with app features and regulations

## Cost
GitHub Pages hosting is **completely free** for public repositories.

## Professional Recommendation
While these templates provide a solid foundation, it's recommended to have a legal professional review these documents before app store submission, especially for a mental health application with HIPAA requirements.