# JCC Trial Court install profile. 

# Install
1. `git clone git@github.com:zakiya/jcc-trial.git folder`

2. `composer install`

3. Create localhost and database and add to `settings.php` and/or `settings.local.php` and/or `services.local.yml`

4. `drush si mega`

7. Modify `/drush/drush.yml`

8. Add`/web/.htaccess`

# @Todo
- Create example settings.local.php and services.local.php files and scripts.
- Handle dev dependencies better.
- Delete composer.lock?
