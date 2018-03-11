# Troubleshooting the Amazon WorkMail Web Application<a name="troubleshooting"></a>

Solutions to the most commonly encountered Amazon WorkMail web application errors are listed below\.

**Connection Loss**  
If you lose connection to the server due to a network error, Amazon WorkMail displays a warning message at the top of the screen\. You cannot retrieve data from the server, but you can continue working with items that are currently open\. In the warning message, the timeout is shown for the next time the Amazon WorkMail web application will try to connect to the server\. To skip this timeout, and immediately retry, you can click the warning message\. If the connection has been reestablished, the warning message is removed, and you can continue working\. 

**Session Expired**  
If your session has expired on the server and you are no longer logged in to the server, Amazon WorkMail displays a warning message\. You can return to the login screen, or you can keep the Amazon WorkMail web application open \(without being allowed to open or save any data\)\.

**Mail cannot be saved**  
If your email gets stuck in your outbox and doesn't get sent, Amazon WorkMail displays this error message\. This may be due to a network issue\. Try saving the email again to resolve this error\.

**Email redirection is not working**  
If your email redirection is not working, you may need to update the domain sending authorization policy\. A new API operation allows you to redirect email to any address, regardless of whether it's part of your domain\. This needs to be done manually for domains added before October 13, 2016\. For more information, see [Editing Domains](http://docs.aws.amazon.com/workmail/latest/adminguide/editing_domains.html)\.