<h1 align=center>Hugo PolyRhythmic | <a href="https://wonyoungjang.org/hugo-PolyRhythmic-demo/" rel="nofollow">Live Demo</a></h1>

<h4 align=center>Fast | Responsive | Material Design 3</h4>
<br>

<!-- **See documentation** here: [**Wiki**](https://github.com/wonyoung-jang/hugo-PolyRhythmic/wiki) -->

<!-- **See exampleSite** source here: [**exampleSite**](https://github.com/wonyoung-jang/hugo-PolyRhythmic-demo) -->

[![Minimum Hugo Version](https://img.shields.io/static/v1?label=min-hugo-version&message=v0.132.2&color=blue&logo=hugo)](https://github.com/gohugoio/hugo/releases/tag/v0.132.2)
[![GitHub](https://img.shields.io/github/license/wonyoung-jang/hugo-PolyRhythmic)](https://github.com/wonyoung-jang/hugo-PolyRhythmic/blob/main/LICENSE)
![code-size](https://img.shields.io/github/languages/code-size/wonyoung-jang/hugo-PolyRhythmic)

<p align="center">
  <kbd>
    <img 
      src="https://raw.githubusercontent.com/wonyoung-jang/hugo-PolyRhythmic/main/images/tn.png" 
      alt="Screenshot" 
      title="Screenshot"/>
  </kbd>
</p>

## Features

-   Pipeline, fingerprint, bundle and minify Hugo assets
-   Table of contents
-   Archives
-   Menu location indicator
-   Taxonomies
-   Cover images for each page
-   Light/Dark theme
-   SEO friendly
-   Multiple author support
-   Search with Fuse.js
-   Backlinks and related page suggestions
-   Code copy button

---

## Install

1. Install Hugo: [Hugo Docs's - Quick Start](https://gohugo.io/getting-started/quick-start/)
2. Create a new Hugo site
```bash
# replace YourSite with your website's name
hugo new site YourSite --format yaml
```
3. Add PolyRhythmic to your `YourSite/themes/` directory
- **Option 1: Clone git repository:**
```bash
git clone https://github.com/wonyoung-jang/hugo-PolyRhythmic themes/PolyRhythmic --depth=1
```
- **Option 2: Download and unzip:**
    - Download the PolyRhythmic source and extract the zip in your `YourSite/themes/PolyRhythmic` directory
- **Option 3: Use Hugo Modules**
    - Install [Go](https://go.dev/doc/install)
    - Intialize your own hugo module:
    ```bash
    hugo mod init YOUR_GIT_REPO
    ```
    - Add PolyRhythmic in your `config.yaml` or `module.yaml`
    ```yaml
    # config.yaml
    module:
        imports:
        - path: github.com/wonyoung-jang/hugo-PolyRhythmic
    
    # module.yaml
    imports:
        - path: github.com/wonyoung-jang/hugo-PolyRhythmic
    ```
4. In your `config.yaml` add:
```yaml
theme: ["PolyRhythmic"]
```

---

## Support

-   Star, share, and use this repository on [GitHub](https://github.com/wonyoung-jang/hugo-PolyRhythmic)
-   If you would like to sponsor me, you can through [Github Sponsors](https://github.com/sponsors/wonyoung-jang)
-   You may also donate on [Ko-Fi](https://ko-fi.com/wonyoung_jang)

---

## Thanks

-   [**Fuse.js**](https://github.com/krisk/fuse)
-   [**Material Symbols**](https://github.com/google/material-design-icons)
-   [**Material Design 3**](https://m3.material.io/)
-   [**Google Fonts**](https://fonts.google.com/)
