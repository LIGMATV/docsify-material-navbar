# Docsify Material Navbar

> The bolder Material with adding navbar functionality.

## Installation

Docsify Material Navbar was still using [vue.css](https://cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css) for all compatibility.  
This is how to make Docsify Material Navbar will work in your docs

```index.html
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css">
<link rel="stylesheet" href="//cdn.jsdelivr.net/gh/LIGMATV/docsify-material-navbar/material.css">
```

> [!IMPORTANT]
> Just to be safe, please use your downloaded version.  
> You can download the material.css <a href="https://cdn.jsdelivr.net/gh/LIGMATV/docsify-material-navbar/material.css">here</a>.

Every ⭐ star is expensive. If you can star this repository, you absolutely rich!

## Configuration

- Navbar  ``_navbar.md``
  - Logo
    ```_navbar.md
    <!-- Logo -->
    ![](https://docsify.js.org/_media/icon.svg ':class=logo')
    ```
    Change the image based in your URL, do not remove ``':class=logo'``.
  - Title
    ```_navbar.md
    <!-- Title -->
    docsify
    ```
    The title code must be below the logo code!

- Things you need to enable  
Go to index.html, and edit the ``<script>`` part
```index.html
<script>
  window.$docsify = {
    search: 'auto',
    coverpage: true,
    loadSidebar: true,
      subMaxLevel: 4, // Optional
      name: 'docsify', // Optional
    loadNavbar: true,
    themeColor: '#3F51B5', // Optional
  }
</script>
```

You are done!
