# openresty md renderer

Render markdown/md files in your browser. This works also for nginx.

Edit your nginx.conf

```conf
http {
    # ...
    server {
        # ...
        include    md-renderer.conf;
    }
}
```

place the `md-renderer.conf` into the openresty config folder and the `__special` folder with the contents, too.
