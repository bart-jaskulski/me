# Malware detection in Automattic

Each plugin submitted to woocommerce.com store has to pass their malware detection which is just `php-malware-finder` with some custom YARA rules.

You can easily check your plugin violations with following command:

```sh
docker run --rm $(pwd):/data ghcr.io/jvoisin/php-malware-finder
```

Custom rules from Automattic can be found in their GitHub repository[^1].

[^1]: <https://github.com/Automattic/php-malware-finder>
