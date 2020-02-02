Docker Wordpress Log Sql Queries Demo
===========================

1. `wp-config.php`: `define('SAVEQUERIES', true);`
2. `WordPress-5.3.2/wp-content/themes/twentytwenty/footer.php`: `$wpdb->queries` 

```
npm run up
```

会在页面最下方打印出所有运行的sql，包括select/update/...
