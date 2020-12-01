# Performance Boosting for Wordpress :bowl_with_spoon:

Wordpress-Installation mit eigener OPCache.ini und PHP-FPM Konfiguration. Steuerbar über Umgebungsvariablen.

## Basis
Als Basisimage dient Wordpress 5.3.3 mit PHP 7.4 und FPM.

## Änderungen testen
Getestet werden können die OPCache Einstellungen mit `php-fpm -i` im gebauten Container.

Die PHP-FPM Einstellungen können mit `php-fpm -tt` überprüft werden.

## Docker Image bauen
`docker build -t <USER>/<IMAGENAME>:<TAG> .`

## Docker Image ausführen
`docker run -it <USER>/<IMAGENAME>:<TAG> bash`