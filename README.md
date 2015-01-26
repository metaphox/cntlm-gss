This is (Cntlm)[http://cntlm.sourceforge.net/] with Kerberos patch applied.

Dependency: (Kerberos)[http://web.mit.edu/kerberos/] .

If Kerberos is compiled to a different location, say, $HOME/usr, compile Cntlm with

`./configure --enable-kerberos`

`export LIBRARY_PATH=$HOME/usr/lib`

`export C_INCLUDE_PATH=$HOME/usr/include`

`make`

To run it, try `cntlm --help` or `cntlm -v` and fix whatever it complains.
