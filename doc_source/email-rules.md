# Working with Email Rules<a name="email-rules"></a>

You can use email rules to forward and redirect emails from your mailbox in Amazon WorkMail\. Emails can be forwarded or redirected to external email addresses and to Amazon WorkMail users, resources, or groups, but not to personal distribution lists in your **Contacts** folder\. 

**To create an email forwarding rule**

1. In the Amazon WorkMail web application, choose the gear icon\.

1. Choose **Email rules**, **New**\.

1. For **Rule name**, enter a name, and select **Active rule**\.

1. For **Actions**, choose **Forward the message to**, **Select recipient\(s\)**\. Enter the email addresses to forward email to, and choose **To**, **OK**\.

   1. Optionally, choose additional actions, such as **Delete the message** or **Move message to folder**\.

1. Choose **OK**, **Save changes**\.

1. The recipient of the forwarded email sees that it was forwarded from you, and a copy of the email remains in your mailbox\.

Bounced emails are not forwarded\.

**To create an email redirect rule**

1. In the Amazon WorkMail web application, choose the gear icon\.

1. Choose **Email rules**, **New**\.

1. For **Rule name**, enter a name, and select **Active rule**\.

1. For **Conditions**, choose **is sent to**, **Select recipient\(s\)**\. Enter the user account from which to redirect email, and choose **To**, **OK**\. 

   1. Optionally, choose additional conditions such as **received from** or **includes these words in the subject**\.

1. For **Actions**, choose **Redirect the message to**, **Select recipient\(s\)**\. Enter the email addresses to redirect email to, and choose **To**, **OK**\.

1. Choose **OK**, **Save changes**\.

1. The recipient of the redirected email sees it as coming from the original sender\.

Emails that bounce and do not pass Sender Policy Framework \(SPF\) and DomainKeys Identified Mail \(DKIM\) key checks are not redirected\.