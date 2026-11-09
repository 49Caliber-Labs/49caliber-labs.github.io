# 49Caliber Labs - Website Deployment Package

## Quick Deployment Options

### Option 1: Microsoft Azure Static Web Apps (Free with your ,000 credits)
1. Open the Azure Portal.
2. Search for Static Web Apps and click Create.
3. Choose your Subscription (Azure Credits), Resource Group (49Caliber-Labs), and Name (49caliber-labs-web).
4. Select GitHub as the source, pick your repository 49Caliber-Labs/website (or upload these files directly).
5. Click Review + Create. Azure will build, deploy, and assign a free HTTPS URL with SSL.

### Option 2: GitHub Pages (100% Free & Fast)
1. In your GitHub Organization 49Caliber-Labs, create a repository named website.
2. Upload index.html and 49caliber_logo_vector.svg.
3. Go to Settings -> Pages, set source to main branch / root.
4. Your site will be live instantly!

### Option 3: Google Cloud / Firebase Hosting
1. Install Firebase CLI: npm install -g firebase-tools
2. Run firebase login and firebase init hosting inside this folder.
3. Run firebase deploy.
