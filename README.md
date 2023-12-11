This is the repository for the Room 77 project.

There is a lot of CSS from the original page copied over, therefore I created an npm build script that will remove any unused css via PurgeCSS and place it in the `./build` directory.

Run the following command:

```
npm run build
```

For production, you'll want to further process the CSS with PostCSS to concatenate `site.css` and `custom.css` as well as add any css browser prefixing depending on your browser support requirements.
