# Setting up an IMAP client for Amazon WorkMail<a name="using_IMAP_client"></a>

You can connect any IMAP\-compatible client software to Amazon WorkMail by providing the following information\.

**Note**  
If you are using the web client, Microsoft Outlook, an Android or iOS mobile device, or a mail app for Windows 10 or macOS, see [Setting up email clients for Amazon WorkMail](clients.md) for guidelines specific to your client\.


| Required Information | Description | 
| --- | --- | 
|  **Type of account**  |  IMAP  | 
|  **Protocol**  |  IMAPS  | 
|  **Port**  |  993  | 
|  **Secure connection**  |  Required; SSL  | 
|  **Incoming username**  |  Email address associated with your Amazon WorkMail account  | 
|  **Incoming password**  |  Your password  | 
| **Incoming server** |  The endpoint matching the AWS Region where your mailbox is located: [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workmail/latest/userguide/using_IMAP_client.html)  If you don't know the AWS Region where your mailbox is located, contact your system administrator\.   | 

To send emails, you also need to configure an outgoing SMTP server in your client software\. 


| Required Information | Description | 
| --- | --- | 
|  **Protocol**  |  SMTPS \(SMTP, encrypted with TLS\)  | 
|  **Port**  |  465  | 
|  **Secure connection**  |  Required; SSL \(STARTTLS not supported\)  | 
|  **Outgoing username**  |  Email address associated with your Amazon WorkMail account  | 
|  **Outgoing password**  |  Your password  | 
| **Outgoing server** |  The endpoint matching the AWS Region where your mailbox is located: [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workmail/latest/userguide/using_IMAP_client.html) If you don't know the AWS Region where your mailbox is located, contact your system administrator\.   | 