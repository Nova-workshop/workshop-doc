Logging in to the instance in jetstream from your local terminal
================================================================

These materials will show you how to log in using SSH through your local terminal.

Concerning local terminal
^^^^^^^^^^^^^^^^^^^^^^^^^

On MacOS/Linux
""""""""""""""

These systems have their own terminal by default. Find and open your terminal: on MacOS, you can
search for Terminal in finder. Or you could download and install the terminal, e.g. 
iTerm2 in the `Dropbox <https://www.dropbox.com/home/NSU%202019%20Bioinformatics%20Workshop/terminal/iTerm2_for_Mac>`_ for our workshop.

On Windows
""""""""""

For Windows, we need to actually *install* a terminal.

Download Putty in our `Dropbox <https://www.dropbox.com/home/NSU%202019%20Bioinformatics%20Workshop/terminal/Putty_for_Windows>`_ and run it.

Login with SSH
^^^^^^^^^^^^^^

On MacOS/Linux
""""""""""""""

To log in we need to use the `ssh` command, and the your account ID and the IP address (149.165.169.102).::

        ssh YOUR_ACCOUNT_ID@149.165.169.102
        >>The authenticity of host '149.165.168.102 (149.165.168.102)' can't be established.
        >>ECDSA key fingerprint is SHA256:+gXkq4hC8LY7wAuG3FUI42fzIng48S13E7+oHLnRx1Q.
        >>ECDSA key fingerprint is MD5:74:c6:3c:09:bb:d5:c0:e5:6d:5a:d8:3a:0d:63:e5:5c.
        >>Are you sure you want to continue connecting (yes/no)?

Input `yes` and click Enter.::

        yes
        >>Warning: Permanently added '149.165.168.102' (ECDSA) to the list of known hosts.
        >>YOUR_ACCOUNT_ID@149.165.169.102's password:

Input the password (it won't show on the screen so just input) and click Enter.

Success!

On Windows
""""""""""

Success!
