!SLIDE bullets
# Install Ruby - Prerequisites #
* Windows: Install Rails Installer from http://railsinstaller.org 
* Linux: Install development packages 
* OS/X: XCode 3.x or 4.x

!SLIDE bullets
# Install Ruby #
* Windows: installed with Rails Installer
* Linux & OS/X: install Ruby Version Manager (rvm)

!SLIDE bullets
# Ruby Version Manager #
* For Linux & OS/X
* Easily switch between versions of Ruby
* On Linux, people have issues with using Ruby via package manager
* On OS/X, system version is 1.8.7

!SLIDE code
# RVM - Installation #
    $ bash < <(curl -s https://rvm.beginrescueend.com/install/rvm)

!SLIDE code
# Install Rails #

## Windows: Replacing Rails 3.1 installed by Rails Installer ##
    $ gem uninstall rails
    $ gem install rails -v=3.0.10

## Linux & OS/X: ##
    $ gem install rails -v=3.0.9
