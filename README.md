# Simple Maintenance Mode

This simple .htaccess rule tells browsers that your site is currently
undergoing maintenance. Turn maintenance mode **ON** by creating a file
called `.maintenance`. Turn it off by removing the file.

### Example

```
$ touch .maintenance
$ git pull origin production
$ rm .maintenance
```

