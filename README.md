Homebrew Cask Puppet Module for Boxen
=====================================

A module which installs [homebrew-cask](https://github.com/caskroom/homebrew-cask), and `brewcask` provider for Puppet's `package` type.

## Usage

```puppet
include brewcask # taps homebrew-cask / installs brew-cask

# now you can install packages using homebrew-cask
package { 'adium': provider => 'brewcask' }
package { 'firefox': provider => 'brewcask' }
```

## Required Puppet Modules

 - `homebrew`

## Work in progress

Please contribute by reporting issues and submitting pull requests!
