# 🌐 Dot Pages - Collection

Welcome to the Dot Pages Collection! This is a **community-driven** project where you can showcase your personal landing page, portfolio, or mini-site hosted right here.

Submissions are managed via **Pull Requests**. Once submitted, our automated system validates your files to ensure everything looks great for the showcase.

---

# 🚀 How to Add Your Page
**Follow these steps to get your site listed:**

**1. Fork** this repository to your own profile and clone it locally.

**2. Create Your Folder**  
Inside the `pages/` directory, create a new folder.
   
**📂 Folder Structure**
Your submission must follow this exact structure to pass the automated validation:
```
pages/
└── your-page-name/
    ├── config.json
    └── src/
        ├── index.html  <-- index.html
        ... optional    <-- optional files (css, js, images...)
```

**📝 `config.json` example**  
*The fields `cardColor`, `author.url`, and `author.pfp` are optional. You can either leave them as empty strings ("") or omit them from the JSON file entirely.*
```json
{
  "name": "My Page Name",
  "route": "/your-my-name",
  "cardColor": "#6366f1",
  "author": {
    "name": "Your Name",
    "url": "https://yourwebsite.com",
    "pfp": "https://github.com/your-username.png"
  }
}
``` 

**⚠️ Warning:** Do not modify or delete other people's pages; doing so will result in your Pull Request being instantly invalidated.



**3. Submit** your Pull Request  
Push your changes to your fork and open a **Pull Request** to our main branch.