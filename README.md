# Aspen WASM

This repo demonstrates the following capabilities of Blazor WebAssembly

- OIDC authentication
  - note the difference between the wwwroot/appsettings.json and wwwroot/appsettings.Development.json files.  the '.Development' version overrides the callback urls to use localhost.
- [Automatic GitHub Pages publishing / hosting](https://blog.zhaytam.com/2020/06/08/deploy-blazor-wasm-github-pages-using-actions/)
  - Update the wwwroot/404.html page
    - Make sure you change the `<title>` element
    - Check to see if you need to modify the `segmentCount` value
  - add a script to wwwroot/index.html
  - create the wwwroot/.nojekyll file
  - create the gh-pages branch
  - add the workflow file


