# Documentation

## troubleshooting

### Flipbook pages are not visible/defective in PDF
Check the pdf if using the link Make sure that cross-origin resource sharing is enabled 

## File Structure

This flipbook plugin is jQuery-based. Basically, you can copy the files in folder to your working directory. You don't need to include the lib folder..

```
lib/ 
    ├── css/
    │   ├── dflip.css
    │   └── themify-icons.css
    │
    ├── fonts/
    │   ├── themify.eot
    │   ├── themify.svg
    │   ├── themify.ttf
    │   └── themify.woff
    │
    ├── images/
    │   └── loading.gif
    │
    ├── book/
    │   └── your-pdf.pdf
    |
    ├── sound/
    │   └── turn2.mp3
    │
    └── js/
        ├── dflip.js
        ├── dflip.min.js
        └── libs/
            ├── jquery.min.js
            ├── pdf.min.js
            ├── pdf.worker.min.js
            ├── three.min.js
            └── mockup.min.js

}
```

## File Template
And ensure the following files are included in the html.
