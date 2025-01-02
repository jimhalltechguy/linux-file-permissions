<h1>Linux File Permissions</h1>
File permissions are a core in the security model used by Linux systems. They determine who can access files and directories on a system and how</b>.<br/>
<h1>How do you view Linux file permissions?</h1>
The ls command along with its -l (for long listing) option will show you metadata about your Linux files, including the permissions set on the file</b>.<br/>
	<h2>“ls -l “</h2> (FYI - that is the letter “L”) 
 Shows the permissions on a given file</h2>
	<h2>“chmod 660 test.txt”</h2> 
 <p><b>"Chmod"</b> changes the file permissions for the text.txt file</p>
		<p>First 6 - gives read & write permissions to the Owner</p>
		<p>Second 6 - does the same, but for the Group</p>
		<p>The 0 - gives no permissions to everyone else</p>
	<h2>“chown root test.txt”</h2> - this would change the owner of the test.txt file to root</h2>
		NOTE - would have to use “sudo” at the beginning to make this change
	<h2>“sudo chgrp root text.txt”</h2> - would change the owner of this file to root; would take away 
the ability to read the file from the Everyone group</h2>



<h1>Local and Domain Accounts</h1>
This repo outlines key elements of <b>Windows Local and Domain Accounts</b>.<br/>
	<h2>Local Account</h2> 
 		One user on one PC, with one username and one password</h2>
	<h2>Domain Account</h2> 
 		Allows many users to log onto a PC by using a Domain Controller (server) to store all of the many different Users and their Usernames and Passwords</h2>
	<h2>Domain Controller Directory</h2> 
 		Acts like a phone book to record all of the different Users and their Permissions, along with their Usernames and Passwords</h2>
	<h2>Administering Local User Accounts</h2>	
 		This link is a very helpful resource for implementing and maintaining Local User Accounts</h2>
   		<p>https://learn.microsoft.com/en-us/windows/security/identity-protection/access-control/local-accounts</p>
	<h2>Administering Local User Accounts</h2>
		<p>Click on <b>Start</b> (blue box at bottom left of task bar on Windows 11)</p>
		<p>Type “<b>control panel</b>” in <b>Search Box</b></p>
		<p>Click on <b>Control Panel</b> -> <b>User Accounts</b></p>
		<p>Then make user account changes you want</p>
    	<b><p>OR</b></p>
		<p>Click on <b>Start</b> (blue box at bottom left of task bar on Windows 11)</p>
		<p>Type “<b>run</b>” in <b>Search Box</b> and click on <b>Run</b></p>
		<p>Click “<b>Ok</b>” when “lusrmgr.msc” pop-up box appears and make account setting changes</p>
