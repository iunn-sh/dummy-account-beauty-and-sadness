![presenterm](https://img.shields.io/badge/presenterm-0.15.1-orange?style=for-the-badge) ![weasyprint](https://img.shields.io/badge/weasyprint-67.0-mediumspringgreen?style=for-the-badge) ![GitHub License](https://img.shields.io/github/license/iunn-sh/dummy-account-beauty-and-sadness?style=for-the-badge)

# Dummy Account - Beauty and Sadness
人頭帳戶的美麗與哀愁

* Framework [mfontanini/presenterm](https://github.com/mfontanini/presenterm) 


```
# install
brew install presenterm
brew install weasyprint

# preview
presenterm presentation.md

# export
presenterm --export-pdf presentation.md
presenterm --export-html presentation.md

# export for Github Pages
mkdir public
presenterm --export-html presentation.md -o ./public/index.html
```
