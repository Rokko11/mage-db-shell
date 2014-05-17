mage-db-shell
=============

Simple Mage_Shell-Script to dump the database.


## Dependencies

This modules offers the possibility to dump the database remotely via capistrano. So it depends on capistrano

## Installation

Install it via modman. If your capistrano or magento is located somewhere else, just edit modman-file.

## Use Case
 
You can't do much with it. Use

```
php shell/database.php help
```

for a list of all available commands. At the moment, the output would be like this:

```
  dump                          Dump a predefined selection of tables excluding log-tables
  export                        Dump all tables. Full dump.
  overwrite                     Overwrites database with dump
  deleteurl                     Deletes the base_url-Entry from core_config_data
  help                          This help
```
