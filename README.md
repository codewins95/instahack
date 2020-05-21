# Instagram Hacking Script by Bruteforce in Termux

<ol>
<li><p>Load up your android device.</p></li>
<li><p>Next click on your playstore app and search for “Termux” &amp; install it.</p></li>
<li><p>Open Termux app and type: “pkg install git”.</p></li>
<li><p>To update available packages type: “pkg update”.</p></li>
<li><p>Lets install python by typing ” pkg install python”</p></li>
<li><p>We will need to download the tool we will be using for this bruteforce exercise. To download, on your terminal…type: “git clone <a href="https://github.com/avramit/instahack" rel="nofollow noopener" title="This link will take you away from steemit.com">https://github.com/manish05s/instahack.git</a></p></li>
<li><p>Once the download is complete, type: “ls” to list the available folders/files in current directory</p></li>
<li><p>As you can see you have a folder call “instahack”, now make your way into that folder by typing “cd instahack”.</p></li>
<li><p>Type: “ls” to list the available files.</p></li>
<li><p>Ok we are nearly there. Next lets install an editor so we can edit the password file. To install nano, type : “pkg install nano” .</p></li>

<li><p>Fine so lets edit our password list. In instahack directory, type: ls.</p></li>
<li><p>As you can see there is a file named pass.txt. This is the file that you will need to place all the possible passwords in.</p></li>
<li><p>To edit the pass.txt, we will be using the nano editor that we just installed. Type: “nano pass.txt”.</p></li>
<li><p>Below you will see a small list of passwords that comes with it by default, you can now add as many words as possible for it to run against the target. You could use cupp.py to custom build password lists.</p></li>
</ol>
<p>16)When you are done , press ctrl+o tosave, than ckick ctrl+x to return command,y press(to edit save change).</p>
<ol>
<li><p>And now for the final installation, type : “pip install requests”.</p></li>
<li><p>We are ready!! Lets run the script, type: “python hackinsta.py” .</p></li>
<li><p>You will first be asked for your target username.</p></li>
<li><p>Next you will be given an option to use a proxy or not. I wont be using any for this tutorial</p></li>
<li><p>And lastly u can set the intervals between tries. I have set mine to 6.</p></li>
<li><p>Once you have it all keyed in, press enter.</p></li>
<li><p>As you can see upon enter, instahack starts running the pass.txt against the target username. If the password is incorrect it will show incorrect, otherwise as shown below, it will show the correct login credentials.
