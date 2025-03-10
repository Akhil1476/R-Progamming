# 👋 Hi, I'm Akhil Akkenapally  

## 🚀 About Me  
- 🎯 Experienced **Business Analyst & Finance Professional** with expertise in **Treasury & Capital Markets, Balance Sheet Management, Cash Operations, and Compliance & Risk Domains**.  
- 🏦 Strong background in **Mortgage Analysis, Reinsurance, Financial Crime Compliance, and Data Analytics**.  
- 💡 Passionate about leveraging **data-driven insights** to optimize business processes and drive strategic decision-making.  

## 🔍 Interests & Learning  
- 🌱 Currently learning **Playwright for Python** to enhance test automation skills.  
- 🤝 Open to collaborations on **finance, compliance, automation, and data-driven projects**.  

## 📫 Connect with Me  
- 💼 LinkedIn: [Akhil Akkenapally](https://www.linkedin.com/in/akhil-a-538b771b5)  
- 📧 Email: Akhilakkenapally1@gmail.com  
- 💻 GitHub: [@Akhil1476](https://github.com/Akhil1476)  

---

## 📄 GitHub Actions Workflow for Deploying Static Content to GitHub Pages  

```yaml
name: Deploy Static Content to GitHub Pages  

on:  
  push:  
    branches: ["main"]  
  workflow_dispatch:  

permissions:  
  contents: read  
  pages: write  
  id-token: write  

concurrency:  
  group: "pages"  
  cancel-in-progress: false  
