# Arena Holdings - Oura Integration Documentation

This repository hosts the Privacy Policy and Terms of Service for Arena Holdings' internal Oura Ring integration.

## 🔗 Live URLs

Once deployed, these documents will be available at:

- **Main Page:** https://arenaholdings.github.io/oura-integration-docs/
- **Privacy Policy:** https://arenaholdings.github.io/oura-integration-docs/privacy-policy.html
- **Terms of Service:** https://arenaholdings.github.io/oura-integration-docs/terms-of-service.html

## 📋 Setup Instructions

### 1. Create Repository (if not already done)

Go to https://github.com/new and create:
- Repository name: `oura-integration-docs`
- Visibility: **Public** (required for free GitHub Pages)
- ✅ Add README file

### 2. Upload Files

Upload these three HTML files to the repository:
- `index.html` - Landing page with links to both documents
- `privacy-policy.html` - Privacy Policy
- `terms-of-service.html` - Terms of Service

**Option A: Via GitHub Web Interface**
1. Go to your repository
2. Click "Add file" → "Upload files"
3. Drag and drop all three HTML files
4. Commit with message: "Add privacy policy and terms of service"

**Option B: Via Git Command Line**
```bash
# Clone the repository
git clone https://github.com/arenaholdings/oura-integration-docs.git
cd oura-integration-docs

# Copy the HTML files to this directory
# (Copy index.html, privacy-policy.html, terms-of-service.html here)

# Add and commit
git add index.html privacy-policy.html terms-of-service.html
git commit -m "Add privacy policy and terms of service"
git push origin main
```

### 3. Enable GitHub Pages

1. Go to repository **Settings** → **Pages** (left sidebar)
2. Under "Source", select **Deploy from a branch**
3. Choose branch: **main** and folder: **/ (root)**
4. Click **Save**
5. Wait 2-3 minutes for deployment

### 4. Verify Deployment

After 2-3 minutes, visit:
- https://arenaholdings.github.io/oura-integration-docs/

You should see the landing page with links to both documents.

### 5. Provide URLs to Oura

Use these URLs in your Oura developer application:
- **Website:** https://arenaholdings.com/
- **Privacy Policy:** https://arenaholdings.github.io/oura-integration-docs/privacy-policy.html
- **Terms of Service:** https://arenaholdings.github.io/oura-integration-docs/terms-of-service.html

## ✏️ Before Going Live

**Update Contact Information** in both HTML files:

Search for `[contact email to be added]` and replace with actual contact email.

Search for `[State/Jurisdiction to be added]` in terms-of-service.html and replace with appropriate jurisdiction.

## 🔄 Making Updates

To update the documents:

1. Edit the HTML files locally or via GitHub web interface
2. Commit changes
3. Push to main branch
4. Changes will be live in 1-2 minutes

## 📝 Notes

- These documents are for **internal Arena Holdings employee use only**
- GitHub Pages requires public repositories for free hosting
- The documents themselves clearly state this is internal-only
- Repository contains no sensitive information, just policy documents

## 🛠️ Technical Details

- **Platform:** GitHub Pages (Jekyll)
- **Format:** Static HTML with embedded CSS
- **Update Time:** ~2 minutes after push
- **Cost:** Free (public repository)
- **Custom Domain:** Can be added later if desired

## 📧 Support

For questions about this integration, contact Arena Holdings IT team.
