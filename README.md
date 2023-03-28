# ISPConfig3

Aprovisionamiento de ISPConfig3 con ciertas personalizaciones.

## Variables

- `default_php_open_basedir`, por defecto, se cogen los valores de ISPConfig3 ('[website_path]/web:[website_path]/private:[website_path]/tmp:/var/www/[website_domain]/web:/srv/www/[website_domain]/web:/usr/share/php5:/usr/share/php:/tmp:/usr/share/phpmyadmin:/etc/phpmyadmin:/var/lib/phpmyadmin:/dev/random:/dev/urandom'). Si queremos poder acceder a otros directorios se puede especificar `None`.
- `default_php_version`: Por defecto establecido a `7.3`, sobre lo que se basa el resto de infraestructura.
- `ispconfig_api`: Dividido en `user` (por defecto: `hostprovider`) y `password` (por defecto `Passw0rd`)