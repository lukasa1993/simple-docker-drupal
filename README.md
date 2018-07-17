# simple-docker-drupal


### prerequisite 

1. `db.env` file
  1. ```
      POSTGRES_USER=user
      POSTGRES_PASSWORD=password
     ```
1. `settings.php` file 
    1. `sites/default/default.settings.php` copy this to `sites/default/settings.php`
      1. for defualt you are good to go
    1. for local development add this
      1. ```php
          $settings['trusted_host_patterns'] = [
            '^localhost$',
            '^127\.0\.0\.1$',
          ];
         ```
