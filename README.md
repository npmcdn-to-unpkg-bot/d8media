# d8media

A helper repository with libraries, modules, patches for our Drupal 8 media workshop.

Install a fresh Drupal 8.1.8 standard profile and then copy with overwrite the contents of this repository onto it.

on Linux or OS-X:

```
wget --no-check-certificate https://ftp.drupal.org/files/projects/drupal-8.1.8.tar.gz 
tar xzf drupal-8.1.8.tar.gz
wget --no-check-certificate https://github.com/brainsum/d8media/archive/master.zip
unzip master.zip
cd d8media-master && cp -a * ../drupal-8.1.8 && cd ../drupal-8.1.8
echo "Codebase ready for D8 media workshop. Install Drupal and join the workshop."
