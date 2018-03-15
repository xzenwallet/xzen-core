XZEN Core
==============
* [Getting Started](#getting-started)
* [License](#license)

XZEN Core is the XZEN blockchain implementation and command-line interface.

Visit [xzen.io](https://xzen.io) to learn about XZEN.

**NOTE:** The official XZEN git repository location, default branch, and submodule remotes were recently changed. Existing
repositories can be updated with the following steps:

    git remote set-url origin https://github.com/xzenwallet/xzen-core.git
    git checkout master
    git remote set-head origin --auto
    git pull
    git submodule sync --recursive
    git submodule update --init --recursive
 
License
-------
XZEN Core is under the MIT license. See [LICENSE](https://github.com/GrapheneLab/xzen-core/blob/master/LICENSE.txt)
for more information.
