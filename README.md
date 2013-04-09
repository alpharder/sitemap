Sitemap solution for Yii framework
==================================

Installation
------------
1.  Fetch files to directory named "sitemap" which is at your extensions dir. At this example I'll use following paths:
    * Application extensions path: ```application.protected.extensions```
    * Files of this extension are at: ```application.protected.extensions.sitemap```
2.  Add this alias to your application configuration:  

    ```php
    'aliases' => array(
      'yiiExtensions' => 'application.protected.extensions',
    ),
    ```
3.  Register application component:

    ```php
    'components' => array(
      'sitemap'            => array(
        'class' => 'yiiExtensions\sitemap\SitemapComponent',
      ),
    ),
    ```
