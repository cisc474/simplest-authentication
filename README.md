# simplest-authentication

Using .htaccess and .htpasswd will give a quick authentication for a given folder.

You should use the pwd command to figure out the path to the .htpasswd file.

You can generate htpasswd files using 

    htpasswd -c .htpasswd username

for the first time and

    htpasswd .htpasswd username

for any future users.

If you don't have `htpasswd`  (like on cloud9) then you can use a tool like [this htpasswd generator](http://www.htaccesstools.com/htpasswd-generator/)

#### This method is a simple way to protect static sites.  It doesn't allow users to register (although you could do it) and (as far as I know) it doesn't allow AJAX requests through
