# simplest-authentication

Using .htaccess and .htpasswd will give a quick authentication for a given folder.

You should use the pwd command to figure out the path to the .htpasswd file.

You can generate htpasswd files using 

    htpasswd -c .htpasswd username

for the first time and

    htpasswd .htpasswd username

for any future users.

If you don't have `htpasswd`  (like on cloud9) then you can use a tool like [this htpasswd generator](http://www.htaccesstools.com/htpasswd-generator/)
