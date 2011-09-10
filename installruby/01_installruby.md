!SLIDE bullets
# Install Ruby - Prerequisites #
* Windows: Install Rails Installer from http://railsinstaller.org 
* Linux: Install development packages (see instruction repo.) 
* OS/X: XCode 4.x or XCode 3.x & Homebrew

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

!SLIDE code smaller
# RVM - Installation #
    $ bash < <(curl -s https://rvm.beginrescueend.com/install/rvm)
    $ echo '[[ -s "$HOME/.rvm/scripts/rvm" ]] && 
            . "$HOME/.rvm/scripts/rvm" # Load RVM function' 
                                         >> ~/.bash_profile
    $ rvm install 1.9.2
    $ rvm --create use 1.9.2@rails3tutorial
    $ rvm --default use 1.9.2@rails3tutorial

!SLIDE code
# Install Rails - Windows #

## Replacing Rails 3.1 installed by Rails Installer ##
    $ gem uninstall rails
    $ gem install rails -v=3.0.10

!SLIDE smaller code
# Install Rails - Linux & OS/X #

    $ gem install rails -v=3.0.10
