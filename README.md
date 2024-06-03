# FRT-FE-Endpoint

## the server runs on node v18.13.0 and was not tested on lower versions

 - clone the repository
 - cd FRT-FE-Endpoint
 - npm i
 - npm run start

You should see server listening on port 3010, which notes that BE server was installed successfully and is ready to handle requests.

### Endpoints
  -  /brands - endpoint for all brands
  -  /categories - lists all categories (excluding all)
  -  /options - lists all available options
  -  /products - list of all products sorted by release date - descending order
  -  /products/:id - fetch data of a single product
  -  /checkout - dummy endpoint of checkout, approximately 20% of the requests will fail (does not mean there is something wrong with your request its there for error handling purposes)

### typescript declarations can be found in types directory

# DO NOT modify content of the BE application, your submission will be tested without your changes
