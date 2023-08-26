# coturn_cygwin_build
Windows binaries build of coturn using cygwin
Using idea of: https://www.programmersought.com/article/89707325306/
Using updated cygwin and source from https://github.com/coturn/coturn

---------

How to config the turnserver.conf:
Normally it would be /var/usr etc, but not working in windows.

Use like this example: userdb="C:\turnserver\db\turndb" or pidfile="C:\tmp\turnserver.pid"

Or put in the working directory, it will find it like this example: cert="contoso-crt.pem" or pkey="contoso-key.pem"

---------

Please view the license here https://github.com/coturn/coturn/blob/master/LICENSE
