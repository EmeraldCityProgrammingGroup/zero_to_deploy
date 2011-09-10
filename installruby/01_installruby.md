!SLIDE bullets
# Install Ruby - Prerequisites #
* Windows: Install Rails Installer from http://railsinstaller.org 
* Linux: Install development packages (see instruction repo.) 
* OS/X: XCode & Homebrew

!SLIDE bullets
# Install Ruby #
* Windows: Installed with Rails Installer
* Linux & OS/X: Install Ruby Version Manager

!SLIDE bullets
# Ruby Version Manager (rvm) #
* For Linux & OS/X
* Easily switch between versions of Ruby
* On Linux, people have issues with using Ruby via package manager
* On OS/X, system version is 1.8.7

!SLIDE commandline smaller
# RVM - Installation #
    $ bash < <(curl -s https://rvm.beginrescueend.com/install/rvm)
    $ echo '[[ -s "$HOME/.rvm/scripts/rvm" ]] && . "$HOME/.rvm/scripts/rvm"
                                    # Load RVM function' >> ~/.bash_profile
    $ rvm install 1.9.2
    $ rvm --create use 1.9.2@rails3tutorial
    $ rvm --default use 1.9.2@rails3tutorial

!SLIDE bullets
# Install Rails - Windows #

* Rails Installer installs Rails 3.1
* Rails community still catching up with Rails 3.1
* HTML, CSS, & JavaScript files in a different directory
* Everything else learned still applies to Rails 3.1
* Replace Rails 3.1 w/ Rails 3.0

!SLIDE commandline 
# Install Rails - Windows #

    $ gem uninstall rails
    $ gem install rails -v=3.0.10

!SLIDE commandline
# Install Rails - Linux & OS/X #

    $ gem install rails -v=3.0.10
