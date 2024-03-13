# PHP plots machinery for EL9

cd into your web folder
```
 cd <my-path>
```

Clone this repository
```
 git clone https://github.com/musella/php-plots.git .
```
Copy the example/htaccess file into .htaccess and edit its content to suit your needs.
```
 cp -p example/htaccess .htaccess
 $EDITOR .htacces
```

Replace your index.php by the  index.php in this directory.

If you want to replace a lot of index.php saved in different folders then run the following script from your source directory

```
python3 copy_toDirectories4.py
```
