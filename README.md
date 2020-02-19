# Municipio Standard Boilerplate

Boilerplate for a standard setup of Wordpress with Municipio

## How to install

1. Create project with Composer
   ```bash
   composer create-project municipio/municipio-boilerplate-standard <folder>
   ```
2. Update package name, author and description in _composer.json_ and
   _package.json_.
3. Duplicate all example files in /config and update them to match your setup.
4. Create your empty database.
5. Run `valet link`.
6. Run `valet open` and then the Wordpress install wizard.
