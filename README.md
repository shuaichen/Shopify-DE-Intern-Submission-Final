# Shopify Data Engineer Intern Challenge
### By Shuaichen Wu

This is my submission for the Data Engineer intern challenge. The site can be accessed [here]((https://shuaichen.github.io/data-intern-challenge-test1/).

This was built with the following frameworks:
* GitHub Pages for its ease of use.
* Jekyll for local and fast web development.
* Google FireBase for uploading and accessing cloud storage.

Besides these frameworks, the code is fairly minimal and mostly contained in `index.html`.

## User features
* Upload images via a simple UI.
* View uploaded images via the GCS interface.
* Add, modify, and delete images via the GCS interface.

## Future features to add
This website is very minimalistic. There are a couple main improvements that could be explored:
* Beautify the UI.
* Be able to view, modify, and delete images directly through the website UI rather than the GCS UI.
* Implement search via 
    * User-inputed tags.
    * Search by image via Machine Learning image representation embedding. The image with the closest embedding would be returned.
* Security checks and robustness:
    * Account creation and managed access to images. E.g. only be able to delete the images that were uploaded by your account.
    * Restrict uploaded files to images only.
    
Overall, this challenge was fun and developed my web development and data backend skills!
