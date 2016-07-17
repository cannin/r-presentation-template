## RStudio Template Presentation

Presentation shows

* Quick Access to Font Sizes and Image Centering
* Simplified Positioning using CSS
* Highlight Elements in Images
* Embedding Presentations in Webpages
* Embedding Google Analytics into Presentations
* Generating PDF Versions of Presentations

## View presentation locally
docker run --name slides -p 8080:8080 -v $(pwd):/site -w /site -t cannin/nodejs-http-server:0.10.25

### Access console for container
docker exec -it slides bash

## Generate PDF
./bin/phantomjs ./decktape.js reveal http://localhost:8080/rpres.html ./rpres.pdf
