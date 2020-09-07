## MacBook Development Environment Setups
**Primary Installation Steps**

*Xcode tools*: 
`xcode-select —install`

*Homebrew*: 

[HomeBrew](https://brew.sh/) is an Open-Source software pakage manager. It is Very handy and essential for mac terminal to install\uninstall open source softwares 

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

basic command for installing softwares via homebrew package manager: 

* `brew install [package_name]`

* `brew uninstall [package_name]` for uninstalling purpose`

*CASK*:

[CASK](https://formulae.brew.sh/cask/) `brew cask` is an extension of `brew` install GUI based application. 

Basic steps for CASK usages - 
* `brew install cask`
* `brew search --casks` this for searching apps under cask`
* `brew search [package_name]`
* `brew cask update` for updating packages
* `brew cask help` for checking advance option for cask

*Other Utilities*

If you are a [Linux](https://www.linux.org/) user, you must have used `htop` for inspecting CPU usages. Well you can use the same in Mac as well.

to install `htop` - `brew install htop`
`run` by `sudo htop` as this application will need to access hardware info from the kernals 


Another must have utility is `SPEEDTEST`. I use it all the time via browser. But `CLI` application is much cooler. 
to install `speedtest` - `brew install speedtest-cli`
`run` by `speedtest-cli`


## References: 

1. https://apple.stackexchange.com/questions/125468/what-is-the-difference-between-brew-and-brew-cask
2. https://www.youtube.com/watch?v=Ym2pxzWpTNw&ab_channel=SnazzyLabs

