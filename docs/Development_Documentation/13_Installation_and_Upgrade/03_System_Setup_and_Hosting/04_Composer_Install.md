# Install via [Composer](https://getcomposer.org/):

Pimcore also supports a Composer based install, if this is more suiteable for your development environment. 

If your're not required to use Composer to install Pimcore, we recommend using the install package instead. 

The result ist the same and of course your're still able to install 
[custom packages using Composer](../../10_Extending_Pimcore/01_Add_Your_Own_Dependencies_and_Packages.md) if choosing 
the package install.  

```bash
cd /your/working/directory
composer create-project pimcore/pimcore ./your-project-name
cd your-project-name
composer dumpautoload -o
```

To install specific release or the nightly build you can use:

```bash
composer create-project -s dev pimcore/pimcore ./your-project-name dev-master
```
