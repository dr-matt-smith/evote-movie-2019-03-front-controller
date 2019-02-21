# evote-movie-2019-03-front-controller

The project has been refactored as follows:

- move all display pages into folder `/templates`
- move images and css into new folder `/public`
- add Front Controller script `/public/index.php` to test for GET variable `action`
- change all navigation links to the form `/index.php?action=<PAGE>`

    - e.g. `/index.php?action=about` for link to about page
    
    - including the links in the sitemap page
    
    