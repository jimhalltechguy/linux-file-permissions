<h1>Linux File Permissions</h1>
File permissions are a core in the security model used by Linux systems. They determine who can access files and directories on a system and how</b>.<br/>
<h1>How do you view Linux file permissions?</h1>
The ls command along with its -l (for long listing) option will show you metadata about your Linux files, including the permissions set on the file</b>.<br/>
	<h2>“ls -l “</h2> (FYI - that is the letter “L”) 
 Shows the permissions on a given file</h2>
	<h2>“chmod 660 test.txt”</h2> 
 <p><b>"Chmod"</b> - changes the file permissions for the text.txt file</p>
		<p><b>First "6"</b> - gives read & write permissions to the Owner</p>
		<p><b>Second "6"</b> - does the same, but for the Group</p>
		<p><b>The "0"</b> - gives no permissions to everyone else</p>
	<h2>“chown root test.txt”</h2>
 	This would change the owner of the test.txt file to root. </h2>
		<b>NOTE</b> - would have to use “sudo” at the beginning to make this change
	<h2>“sudo chgrp root text.txt”</h2>
 	Would change the owner of this file to root; would take away 
the ability to read the file from the Everyone group</h2>
