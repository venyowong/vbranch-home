# vbranch-home

- hugo new site vbranch
- cd vbranch
- git clone https://github.com/StefMa/hugo-fresh themes/hugo-fresh
- 拷贝 config.yaml
- 替换 vbranch\themes\hugo-fresh\static\images\favicon.png
- 拷贝 user_module.svg、tourist_guide.svg 到 vbranch\themes\hugo-fresh\static\images\illustrations\icons
- vbranch\themes\hugo-fresh\assets\fresh\partials\_navbar.scss .navbar.is-fresh.navbar-brand img 添加 display: none;
- vbranch\themes\hugo-fresh\assets\fresh\partials\_footer.scss footer.footer-dark.footer-logo img 添加 display: none;
- hugo server
- hugo -D