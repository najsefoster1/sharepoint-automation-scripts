# SharePoint Automation Scripts

**Purpose**  
A collection of PowerShell scripts that automate common SharePoint Online tasks to save time and reduce errors.

**Business Value**  
- Eliminates repetitive manual work like bulk uploading documents and applying metadata.  
- Ensures consistency in document libraries and enhances compliance with retention policies.  
- Scales to thousands of files, freeing analysts to focus on higher‑value tasks.

**Tools & Frameworks**  
- **PowerShell**: Core scripting language for automation.  
- **PnP.PowerShell**: Microsoft Patterns & Practices cmdlets to interact with SharePoint Online.  
- **Microsoft Graph** (optional): For advanced operations like permission management.

**Scripts Included**  
- `BulkUpload.ps1`: Uploads documents from a local folder, sets metadata, and logs results.  
- `UpdateMetadata.ps1`: Batch edits metadata fields on existing library items.  
- `SiteProvisioning.ps1`: Creates modern SharePoint sites from a template.

**Usage**  
1. Install the PnP.PowerShell module.  
2. Connect to your SharePoint tenant (`Connect‑PnPOnline -UseWebLogin`).  
3. Run any script, supplying your site URL and parameters.

**Customization**  
Modify the JSON configuration files to tailor metadata fields, content types and site templates to your organization’s needs.
