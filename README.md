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
```js
{
  "name": "My Page Name",
  "route": "/your-my-name",             //<-- must be the same name of the folder
  "cardColor": "#6366f1", //(optional)  <-- must be a valid hexadecimal color
  "author": {
    "name": "Your Name",
    "url": "https://github.com/your-username", //(optional)     <-- must be a valid url
    "pfp": "https://github.com/your-username.png" //(optional)  <-- must be a valid url
  }
}
```

**⚠️ Warning:** Do not modify or delete other people's pages; doing so will result in your Pull Request being instantly invalidated.



3. **Submit** your Pull Request  
Push your changes to your fork and open a Pull Request to our main branch.