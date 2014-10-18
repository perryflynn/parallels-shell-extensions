I'm try to make the ssh jail shell of paralels cloud server better.

Install
-------

* Create `/home` in jail
* Save all files to `/home`
* Make .profile and .bashrc executable (chmod a+x ...)
* Create symlink for profile: `ln -s /home/.profile /.profile`
* Logout
* Login

Features
--------

* Fake home directory for all config files (manipulates $HOME)
* Default vim configuration
* ~/bin/ folder for user defined scripts/binaries in $PATH
* ~/html/ symlink to /httpdocs/

More ideas? Feel free to make a pull request!
