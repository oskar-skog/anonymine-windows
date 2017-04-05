NOTICE:   This has never been properly tested.

I'd appreciate feedback and bugfixes.



Installation instructions for Windows
=====================================
    
    Notes
    =====
    
        - It is known that certain anti-virus programs can interfere with
          Cygwin. https://cygwin.com/faq/faq.html#faq.using.bloda
        
        - Cygwin will require approx 200 MB of disk space.
        
        - There seems to be some issue with resizing, possibly the terminals
          fault.

        - Do not remove, move or rename the extracted directory.
          It is needed for updating and uninstalling Anonymine.
        
        - There is a log file in case something goes worng.
    
    
    1.  Extract the directory "anonymine-windows" from the zip file.
    
    2.  Enter that extracted folder and start Windows-admin[.bat] or
        Windows-user[.bat]. (Windows-user.bat will install Cygwin in your home
        directory and doesn't require administrator privileges.)
    
    3.  After a while, the Cygwin installer will launch and ask you to select
        a mirror to download Cygwin from.  After choosing the mirror you will
        only have to click "next" a few times.
        (This will only happen the first time you install the game.)
    
    4.  Answer the questions that appear in the terminal window.
    
    5.  Do not remove, move or rename the extracted directory.
        It is needed for updating and uninstalling Anonymine.



Foo bar baz quux lorem ipsum
----------------------------

    The game doesn't work on native Windows, so it will install Cygwin
    automatically.
    
      Winows-user.bat       Cygwin in home directory, shortcuts for this user
      Windows-admin.bat     Cygwin in C:\, shortcuts for all users
      foo                   The script that does everything, with Cygwin
      icon.ico              Self-explanatory
    * anonymine/            Cloned from reoo
    * log                   git pull|clone, ./update, make, make install
