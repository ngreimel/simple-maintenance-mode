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

### Why is it important to send a 503 status code?

From: https://moz.com/learn/seo/http-status-codes

> 503 Service Unavailable

> The server is currently unable to handle the request due to a temporary overloading or maintenance of the server. The 503 should be used whenever there is a temporary outage (for example, if the server has to come down for a short period for maintenance). **This ensures that the engines know to come back soon because the page/site is only down for a short time.**

See also: https://googlewebmastercentral.blogspot.com/2011/01/how-to-deal-with-planned-site-downtime.html
