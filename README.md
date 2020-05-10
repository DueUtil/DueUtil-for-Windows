# DueUtil-for-Windows
Host a private version of [DueUtil](https://dueutil.tech/) locally on up to 3 servers!

## Setup

Head over to the [releases tab](https://github.com/DueUtil/DueUtil-for-Windows/releases).  
[![Releases tab](./setup/1.png)](https://github.com/DueUtil/DueUtil-for-Windows/releases)

Find the latest version and download the ``dueutil_for_windows.zip``  
![dueutil_for_windows.zip](./setup/2.png)

Extract that zip somewhere. The desktop is fine.  
![Extract zip](./setup/3.png)

Now before you can run the bot you've got to setup Postgres. Head to [this page](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) and download the Windows x86-64 installer.  
Don't change any of the defaults (unless you know what they mean) and make note of the password you've picked. You'll need it later.  
[![](./setup/4.png)](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)


Now head over to the start menu and search for pgAdmin. Expand the servers view and right click "Postgres 12" then Create > Database.  
![](./setup/5.png)

Create a database called "dueutil_db".  
![](./setup/6.png)

Now back in the ``dueutil_for_windows`` folder you extracted earlier open the ``bin`` folder.  
![](./setup/7.png)

Inside bin edit ``dueutil.json``  
![](./setup/8.png)

Insert the bot token and your Postgres password in the places indicated.
![](./setup/9.png)

You're done! Double clicking ``run.bat`` should launch the bot!  
![](./setup/10.png)

![](./setup/11.png)