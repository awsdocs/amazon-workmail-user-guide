# Getting Started with a Mobile Device<a name="mobile-start"></a>

Get started with Amazon WorkMail by connecting your Android or iOS mobile device\.

**Topics**
+ [Connect Your Android Device](#connect_android_device)
+ [Connect Your iOS Device](#connect_ios_device)
+ [Manually Connect Your Mobile Device](#manually_connect_device)

## Connect Your Android Device<a name="connect_android_device"></a>

Amazon WorkMail supports Exchange ActiveSync for integration with Android devices, so to connect your Android device to your Amazon WorkMail email account you need your Amazon WorkMail email address and password\.

**To connect your Amazon WorkMail account to your Android device**

1. On your Android device, choose **Apps**, **Email**, **Add Account**, **Exchange**\.

1. In the **Exchange** dialog box, type your Amazon WorkMail email address, password, a description for the account, and then choose **Next**\.
**Note**  
If your account cannot be found, you are prompted to provide the name of your Exchange server, domain, user name, and password\. For more information, see [Manually Connect Your Mobile Device](#manually_connect_device)\.

1. In the Exchange confirmation dialog box, select the items to synchronize with your device, and then choose **Save**\.

   You can now use your Android email app with your Amazon WorkMail email account\.
**Note**  
Amazon WorkMail does not support draft synchronization with Android devices\.

## Connect Your iOS Device<a name="connect_ios_device"></a>

Amazon WorkMail supports Microsoft Exchange ActiveSync for integration with iOS devices\. To connect your iOS device to your Amazon WorkMail email account, you need only your Amazon WorkMail email address and password\.

**Note**  
If your organization has enabled mobile device management, you may be required to set a password to connect your device\.

**To connect your Amazon WorkMail account to your iOS device**

1. On your iOS device, choose **Settings**, and then scroll down to **Accounts & Passwords** \(or in older versions, **Mail**\)\. 

1. Choose **Add Account** and **Exchange**\.
**Note**  
In older versions, select **Accounts**, **Add Account**, **Exchange**\.

1. In iOS 11, type your Amazon WorkMail email address and a description for the account, choose **Next**, **Sign in**, and type the password associated with your email address\.
**Note**  
In older versions, type your Amazon WorkMail email address, password, a description for the account, and choose **Next**\.  
In iOS 11, automatic configuration works if you use a complementary domain, such as awsapps\.com, or if you use a customer domain and Autodiscover Phase 2\. For more information, see [Use AutoDiscover to Configure Endpoints](http://docs.aws.amazon.com/workmail/latest/adminguide/autodiscover.html)\.  
If your account cannot be found, you are prompted to provide the name of your Exchange server, domain, user name, and password\. For more information, see [Manually Connect Your Mobile Device](#manually_connect_device)\. In the Exchange confirmation dialog box, select the items to synchronize with your device, and then choose **Save**\. 

   You can now use your iOS device with your Amazon WorkMail account\.
**Note**  
Amazon WorkMail does not support draft synchronization with iOS devices\.

## Manually Connect Your Mobile Device<a name="manually_connect_device"></a>

If your mobile device doesn't support auto\-discover or if automatic configuration failed, you can manually configure the client by providing the following information:


| Required Information | Description | 
| --- | --- | 
|  **Type of account**  |  Exchange  | 
|  **Protocol**  |  ActiveSync  | 
|  **Domain**  |  Empty  | 
|  **Username**  |  Email address associated with your Amazon WorkMail account  | 
|  **Password**  |  Your password  | 
|  **Server**  |  The endpoint matching the AWS Region where your mailbox is located: [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workmail/latest/userguide/mobile-start.html)  If you don't know the AWS Region where your mailbox is located, contact your system administrator\.   | 