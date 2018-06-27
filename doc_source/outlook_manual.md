# Manually Connect Microsoft Outlook to Amazon WorkMail<a name="outlook_manual"></a>

If automatic configuration fails, you can manually configure the following versions of Outlook:
+ Microsoft Office Outlook 2007
+ Microsoft Outlook 2010
+ Microsoft Outlook 2013
+ Microsoft Outlook for Mac 2011
+ Microsoft Outlook 2016 for Mac

**Note**  
Outlook 2016 for Windows can be configured only by using auto\-discover\.

**To manually configure Microsoft Outlook**

Follow these steps to manually configure Office Outlook 2007, Outlook 2010, or Outlook 2013\.

1. In Windows, open **Control Panel**, and choose **User Accounts and Mail \(32\-bit\)**\.

1. In the **Mail Setup \- Outlook** dialog box, choose **Show Profiles**, and in the **Mail** dialog box, choose **Add**\. 

1. In the **New Profile** dialog box, in the **Profile Name** field, type `WorkMail`, and choose **OK**\.

1. Choose **Manual configure server settings or additional server types**, then choose **Next**\.

1. For **Server**, type the endpoint matching the AWS Region where your mailbox is located\.
   + us\-west\-2

     `outlook.mail.us-west-2.awsapps.com`
   + us\-east\-1

     `outlook.mail.us-east-1.awsapps.com`
   + eu\-west\-1

     `outlook.mail.eu-west-1.awsapps.com`
**Note**  
If you don’t know the AWS Region where your mailbox is located, contact your system administrator\.

1. For **User name**, enter your Amazon WorkMail email address, then choose **More settings**\.

1. On the **Security** tab, for **Logon network security**, choose **Anonymous authentication**\.

1. From the **Connection** tab, choose **Connect to Microsoft Exchange using HTTP**\.

1. Choose **Exchange proxy settings**, and type the same endpoint matching the AWS Region where your mailbox is located, as you typed in step 5\.

1. Select **On fast network connect use HTTP first, then connect using TCP/IP**\.

1. For **Proxy authentication settings**, choose **Basic authentication**, choose **OK**, then choose **OK** again\.

1. Choose **Check name**, type your Amazon WorkMail email address and password, then choose **Next**\.

1. After Outlook sets up your account, you’ll see a message that says your account is ready for use\. Choose **Finish**\.

   For more information about adding accounts in Outlook, see [Set Up E\-Mail in Outlook 2010 or Outlook 2013](http://help.outlook.com/en-us/140/dd253202.aspx)\.

**To manually configure Outlook for Mac 2011 and Outlook 2016 for Mac**

Follow these steps to manually configure Outlook for Mac 2011 and Outlook 2016 for Mac\.

1. In the **Tools** menu, choose **Accounts**\. In the **Accounts** dialog box, choose **\+** and **New Account**, type your **Email Address**, choose **Continue**, and under **Choose the provider**, choose **Exchange**\.
   + If you’re using Outlook for Mac 2011, uncheck **Configure automatically** in the **Enter your Exchange account information** dialog box\. For **Authentication**, choose **User Name and Password**\.

1. Type your **Email address**, **Password**, and **User name** where indicated\. Make sure to type your full password\.

1. For **Server**, type the endpoint matching the AWS Region where your mailbox is located\.
   + us\-west\-2

     `https://ews.mail.us-west-2.awsapps.com/EWS/Exchange.asmx`
   + us\-east\-1

     `https://ews.mail.us-east-1.awsapps.com/EWS/Exchange.asmx`
   + eu\-west\-1

     `https://ews.mail.eu-west-1.awsapps.com/EWS/Exchange.asmx`
**Note**  
If you don’t know the AWS Region where your mailbox is located, contact your system administrator\.

1. Choose **Add Account** to complete setup\.

1. After your account is successfully set up, it displays in the **Accounts** dialog box\.

   For more information about adding accounts in Outlook for Mac 2011, see [Add an email account to Outlook for Mac 2011](https://support.office.com/en-us/article/Add-an-email-account-to-Outlook-for-Mac-2011-fdd33fab-b745-4762-a1c6-70ddba452983)\. For more information about adding accounts in Outlook 2016 for Mac, see [Add an email account to Outlook 2016 for Mac](https://support.office.com/en-GB/article/Add-an-email-account-to-Outlook-2016-for-Mac-60a03300-9f45-49a8-ade8-a23285ace6e2)\.