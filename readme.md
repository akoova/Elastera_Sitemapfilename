![alt text](https://akoova.com/wp-content/uploads/2019/05/logo-retina-reduced.png "Akoova")  
[akoova.com](https://akoova.com) Email: [info@akoova.com](info@akoova.com) Twitter: [@akoova](https://twitter.com/akoova)  

# Description
This magento module will allow you to use other file names for the sitemap than just `sitemap.xml`  
Magento does allow you to use choose any file name for the sitemap.  
But the generation of the sitemap file will fail, if it is something else than "sitemap.xml".  
The filter that was added is `/*/*sitemap*.xml`.  
With this filter you can create a separate sitemap for every store.  
All sitemap files can no coexist in one folder.  
This folder can be synced between web nodes to get the sitemap cloud conform.  
Please keep in mind that the used folder(s) may need to be created, if they are not yet existing.  

# Installation
## using modman
To install the extension with [modman](https://github.com/colinmollenhour/modman) get the extension using  
`git clone git@github.org:elastera/Elastera_Sitemapfilename.git`  
Then execute `modman link ../vendor/elastera/Elastera_Sitemapfilename`

## download and move files
For a manual install you just need to copy two files into magento:  
`app/code/community/Elastera/Sitemapfilename/etc/config.xml` and  
`app/etc/modules/Elastera_Sitemapfilename.xml`
