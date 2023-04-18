# Working with email rules<a name="email-rules"></a>

You use inbox rules to route emails from your mailbox in Amazon WorkMail\. You can forward or redirect emails to external email addresses and to Amazon WorkMail users, resources, or groups, but not to personal distribution lists in your **Contacts** folder\. 

**To create an email rule**

1. In the Amazon WorkMail web application, choose the gear icon in the upper\-right corner of the screen\.

1. Choose **Email rules**, then **New**\.

1. In the **Rule name** box, enter a name and ensure that the **Active rule** check box is selected\.

1. Under **Conditions**, open the **When the message** list and choose a condition, such as **is sent only to me**\.

   To add conditions, choose **Add** and select another condition from the second list\.
**Note**  
To match a string with special HTML characters for the condition **Includes these rules in the body**, remove any left angle brackets from the string\. This allows matching against email body text that contains HTML markup\.

1. Under **Actions**, open the **Then** list and choose an action, such as **Move message to folder**\.

   To add an action, choose **Add** and select an action from the second list\.

1. Choose **OK**, **Save changes**\.

**Note**  
To use the **is sent to** email rule, the **To:** or **CC:** fields of the email message must list the recipients\.

**To create an email forwarding rule**

1. In the Amazon WorkMail web application, choose the gear icon in the upper\-right corner of the screen\.

1. Choose **Email rules**, then **New**\.

   The **New email rule** dialog box appears\.

1. In the **Rule name** box, enter a name for the rule and ensure that the **Active rule** check box is selected\.

1. Under **Conditions**, open the **When the message** list and choose **is received from**\.

   The **Select sender\(s\)** link appears\.

1. Choose **Select sender\(s\)**, choose the sender whose messages you want to forward, choose **To**, ensure that the sender's email address appears in that box, then choose **Ok**\.
**Note**  
To select multiple senders, press **Shift** and choose the additional senders\. If you need more conditions, choose **Add** and select another condition from the list that appears\.

   When done, you return to the **New email rule** dialog box, and the sender or senders' email addresses appear in place of **Select sender\(s\)**\.

1. Under **Actions**, open the **Then** list and choose **Forward the message to**, then choose the **Select recipient\(s\)** link\. Choose the recipient that you want to forward to, choose **To**, then **Ok**\. 

   That returns you to the to the **New email rule** dialog box, and the sender or senders' email addresses appear in place of **Select recipient\(s\)**\.
**Note**  
To add an action, choose **Add** and select a condition from the second list\.

1. Choose **Ok** to accept the new rule\. The rule then appears on your **email rules** page\.

The recipients see that you forwarded the messages, and the system copies forwarded messages to your mailbox\. Finally, Amazon WorkMail doesn't forward bounced messages, messages rejected by a recipient's email server\.

**To create an email redirect rule**

1. Repeat steps 1 through 3 in the previous procedure\.

1. Under **Conditions**, open the **When the message** list and choose **is received from**\. Choose **Select sender\(s\)** and follow the steps in the previous procedure to select one or more senders\. You can also add conditions as needed\.

1. Under **Actions**, choose **Redirect the message to**, then **Select recipient\(s\)** and follow the steps in the previous procedure to add one or more recipients\. You can also add actions as needed\.

1. Follow the remaining steps in the previous procedure to save the rule\.

The recipient of the redirected email sees it as coming from the original sender\. Also, Amazon WorkMail does not redirect bounced emails—messages rejected by a recipient's email server—unless they pass certain checks\. For more information about those checks, contact your system administrator\.
