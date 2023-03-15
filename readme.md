# Render Examples - Gotenberg

https://github.com/gotenberg/gotenberg

## Deploying

Fork this repo and then deploy your fork as a Blueprint to Render

Test with:

```
curl \
--request POST 'https://<RENDER_URL>/forms/chromium/convert/url' \
--form 'url="https://sparksuite.github.io/simple-html-invoice-template/"' \
-o my.pdf
```

and then open `my.pdf`
