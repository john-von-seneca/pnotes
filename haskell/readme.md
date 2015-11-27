


this is the dude
https://github.com/gibiansky/IHaskell

Dependencies
==============

1. zeromq
  1. **ubuntu**: ```sudo apt-fast -y install libzmq3-dev```
  1. **mac**: ```brew install zeromq```
  
1. libmagic
  1. **ubuntu**: ```sudo apt-fast -y install libmagic-dev```
  1. **mac**: ```brew install libmagic```
  
1. stack
  1. **ubuntu**: [Instructions](http://docs.haskellstack.org/en/stable/install_and_upgrade.html#ubuntu)
  1. **mac**: ```brew install haskell-stack```
  1. post installation
      ```
      stack setup
      ```

Main thing
==========

```
git clone https://github.com/gibiansky/IHaskell
cd Ihaskell
stack install
ihaskell install
```
