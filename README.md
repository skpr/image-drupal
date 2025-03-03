Drupal
------

Skpr images pre-packaged with Drupal for testing purposes.

## Images

```
ghcr.io/skpr/image-drupal:nginx-main
ghcr.io/skpr/image-drupal:php-fpm-main
```

## Docker Compose

```yaml
services:

  nginx:
    image: ghcr.io/skpr/image-drupal:nginx-main
    ports:
      - "8080:8080"

  php-fpm:
    image: ghcr.io/skpr/image-drupal:php-fpm-main
```
