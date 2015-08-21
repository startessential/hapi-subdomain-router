# hapi-subdomain-router
Simple router for subdomains in hapi.js

## Example Plugin Register
```javascript
register: require('hapi-subdomain-router'),
options: {
  subdomain: 'api',
  excludePath: ['css', 'js', 'images', 'fonts'],
  destination: '/api'
}
```
