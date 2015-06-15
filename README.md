#Sample Magento Project


##Key features

* Magento core is included as a submodule, preventing core file edits and promoting best practice module development
* Modules are installed using Composer


##Requirements

###[Composer](https://getcomposer.org/doc/00-intro.md)
For dependecy management. Install as follows:

```
curl -sS https://getcomposer.org/installer | php  
mv composer.phar /usr/local/bin/composer
sudo chmod +x /usr/local/bin/composer
```

##How to use  
* Create a fork of this repository and clone it on your local machine:

`git clone git@github.com:jharrisonau/magento-sample-project.git --reccursive ./my-magento-project`

* Make sure you use the --reccusive flag if you are cloning the repository
* A sample `composer.json` file has been provided that installs some common modules
* Open terminal and run `$ composer install` from within the project folder