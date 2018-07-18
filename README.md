# Hugo JSON API Theme component

Theme Component to add a JSON API for your content

[View Demo](https://hardcore-knuth-fc0978.netlify.com/)

## Install

1. Install to `themes/` as a submodule:   
   ```
   git submodule add https://github.com/dwalkr/hugo-json-api-component themes/json-api
   ```  
2. Update the theme setting in your `config.toml`, e.g. `theme = ["your-current-theme","json-api"]` if you already use a theme or simply `theme = "json-api"` if you don't.
3. Enable the JSON output format for our list and single views in `config.toml`:

```toml
[outputs]
    page = ["html","json"]
    section = ["html","json"]
```

And you're done! Restart your Hugo server and you should be able to access the JSON data by adding `/index.json` to the end of section and page URLs.
