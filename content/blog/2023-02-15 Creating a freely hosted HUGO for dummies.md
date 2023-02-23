---
title: "Creating a freely hosted HUGO for dummies"
date: 2023-02-15T14:01:21+01:00
draft: false
tags: ["blog"]
---

STeps to take to create a new blog site:

- Ensure to you have a free GitHub account called [yourusername] in example ALTrijssenaar
- Create a new repository on GitHub which is called [yourusername].github.io in example ALTrijssenaar.github.io
- Execute the following statements:

```console
   # Clone your new repository to your local machine
   git clone https://github.com/ALTrijssenaar/ALTrijssenaar.GitHub.io.git

   # Change directory to your new repository
   cd ALTrijssenaar

   # Install HUGO Extended on your machine
   choco install hugo-extended
```

hugo new site demo
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke themes/ananke
echo "theme = 'ananke'" >> config.toml
hugo server
