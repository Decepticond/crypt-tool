## Cryptography tool
*Created by Lazaurus S*

Howdy and thanks for checking out `crypt-tool`. It's a set of commands made in rust aimed to aid furthered ethical education of cryptography in general.
This project is currently still very WIP, as is my knowledge of GitHub in general :skull:.

### Installation [WIP] 
**To install on MacOS/Linux, simply run:**

`curl -L https://raw.githubusercontent.com/Lazaurus/crypt-tool/master/install.sh | bash`

*Or if you would prefer another path*

`curl -L https://raw.githubusercontent.com/Lazaurus/crypt-tool/master/install.sh | bash -s mypath/`
* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *

**To install on Windows, [run as administrator], simply run:**

`Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`

*then run...*

`Start-BitsTransfer -Source https://raw.githubusercontent.com/Lazaurus/crypt-tool/master/install.ps1 -Destination $env:TMP/install_crypt-tool.ps1; Unblock-File $env:TMP/install_crypt-tool.ps1; Invoke-Expression $env:TMP/install_crypt-tool.ps1`


_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 

Congrats, crypt-tool should've been succesfully installed, run crypt-tool to start it up.


### Uninstalling crypt-tool
`rm -rf crypt-tool`
...
`cargo uninstall crypt-tool`


