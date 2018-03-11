# Connect Your iOS Device<a name="connect_ios_device"></a>

Amazon WorkMail supports Microsoft Exchange ActiveSync for integration with iOS devices\. To connect your iOS device to your Amazon WorkMail email account, you only need your Amazon WorkMail email address and password\.

**Note**  
If your organization has enabled mobile device management, you may be required to set a password to connect your device\.

**To connect your Amazon WorkMail account to your iOS device**

1. On your iOS device, choose **Settings**, and then scroll down to **Accounts & Passwords** \(or in older versions, **Mail**\)\. 

1. Choose **Add Account** and **Exchange**\. 
**Note**  
In older versions, select **Accounts**, **Add Account**, **Exchange**\.

1. In iOS 11, enter your Amazon WorkMail email address and a description for the account, and choose **Next**\. In the dialog box, choose **Sign in** and enter the password of your email address\.
**Note**  
In older versions, enter your Amazon WorkMail email address, password, and a description for the account, and choose **Next**\.  
In iOS 11, automatic configuration works if you use a complimentary domain \(such as awsapps\.com\) or if you use a customer domain and Autodiscover Phase 2\. For more information, see [Use AutoDiscover to Configure Endpoints](http://docs.aws.amazon.com/workmail/latest/adminguide/autodiscover.html)\.  
If your account cannot be found, you are prompted to provide the name of your Exchange server, domain, user name, and password\. For more information, see [Manually Connect Your Mobile Device](manually_connect_device.md)\. In the Exchange confirmation dialog box, select the items to synchronize with your device, and then choose **Save**\. 

   You can now use your iOS device with your Amazon WorkMail account\.
**Note**  
Amazon WorkMail does not support draft synchronization with iOS devices\.