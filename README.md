# Z-plugin for symfony-related tasks

Provides some tasks and hooks related to Symfony.

Defaults are set for a Symfony <= v3 stucture with the console, cache and logs residing in app/

Add the following configuration to you Z YAML file to use a Symfony >= v3 style structure:

```yaml
symfony:
    console: bin/console
    cache: var/cache/
    logs: var/logs/
    web: public
```

# Maintainer(s)
* Jochem Klaver <jochem@zicht.nl>

