# Setting up mobile device clients for Amazon WorkMail<a name="mobile-client"></a>

Use Exchange ActiveSync to connect your Android or iOS mobile device to Amazon WorkMail\.

**Note**  
Amazon WorkMail does not support draft synchronization with Android or iOS mobile devices\.

**Topics**
+ [Connect your Android device](#connect_android_device)
+ [Connect your iOS device](#connect_ios_device)
+ [Manually connect your mobile device](#manually_connect_device)
+ [Setting up Microsoft Outlook for Android and iOS](#setting_up_microsoft_outlook)

## Connect your Android device<a name="connect_android_device"></a>

Amazon WorkMail supports Exchange ActiveSync for integration with Android devices\. To connect your Android device to your Amazon WorkMail email account, you need your Amazon WorkMail email address and password\.

**To connect your Amazon WorkMail account to your Android device**

1. On your Android device, open the **Settings** page\.

1. Choose **Accounts**, and then choose **Add accounts**\.

1. Choose **Exchange**, then enter your email address and choose **Next**\.

1. Enter your password\. After your device connects with the mail server, choose **Save**\.

   

## Connect your iOS device<a name="connect_ios_device"></a>

Amazon WorkMail supports Microsoft Exchange ActiveSync for integration with iOS devices\. To connect your iOS device to your Amazon WorkMail email account, you need your Amazon WorkMail email address and password\.

**Note**  
If your organization has enabled mobile device management, you may be required to set a password when you connect your device\.

**To connect your Amazon WorkMail account to your iOS device**

1. On your iOS device, choose **Settings**\.

1. Scroll down to **Mail**\.

1. Choose **Accounts**, **Add Account**, and then choose **Microsoft Exchange**\.

1. Do one of the following:
   + In iOS 11 and later, enter your Amazon WorkMail email address and a description for the account\. Choose **Next**, **Sign in**, and then enter the password associated with your email address\.
   + In versions of iOS earlier than iOS 11, enter your Amazon WorkMail email address, password, a description for the account, and then choose **Next**\.
**Note**  
In iOS 11 and later, automatic configuration works if you use your organization's *alias*\.awsapps\.com complementary domain, or if you use a custom domain with AutoDiscover Phase 2 that is configured for the domain\. For more information, see [Use AutoDiscover to configure endpoints](https://docs.aws.amazon.com/workmail/latest/adminguide/autodiscover.html)\.

1. Do one of the following:
   + In the Exchange confirmation dialog box, select the items to synchronize with your device, and then choose **Save**\.
   + If your account can't be found, you are prompted to provide the name of your Exchange server, the server's domain, your user name, and your password\. For more information, see [Manually connect your mobile device](#manually_connect_device)\.

## Manually connect your mobile device<a name="manually_connect_device"></a>

If your mobile device doesn't support AutoDiscover, or if automatic configuration failed, you can manually configure the client by providing the following information\.


| Required Information | Description | 
| --- | --- | 
|  **Type of account**  |  Exchange  | 
|  **Protocol**  |  ActiveSync  | 
|  **Domain**  |  Empty  | 
|  **User name** or **Domain/User name**  |  Email address associated with your Amazon WorkMail account  | 
|  **Password**  |  Your password  | 
|  **Server**  |  The endpoint matching the AWS Region where your mailbox is located: [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workmail/latest/userguide/mobile-client.html)  If you don't know the AWS Region where your mailbox is located, contact your system administrator\.   | 

## Setting up Microsoft Outlook for Android and iOS<a name="setting_up_microsoft_outlook"></a>

You can use your Amazon WorkMail account to setup and use Microsoft Outlook on your Android or iOS devices\.

**To use your Amazon WorkMail to configure Microsoft Outlook**

1. Open the Microsoft Outlook app on your device\.

1. Choose **Accounts**\. Enter your Amazon WorkMail address and choose **Add Account**\.
**Note**  
If you are asked to select a service or protocol, choose **Exchange**\.

1. On the configuration screen, do the following:
   + **Password** –Enter your Amazon WorkMailaccount password\.
   + **Server** – Enter the Exchange ActiveSync URL for your AWS Region\. For a list of available Exchange ActiveSync URLs, see [Amazon WorkMail endpoints and quotas](https://docs.aws.amazon.com/general/latest/gr/workmail.html)\.
   + **Domain** – Enter your Amazon WorkMail address' domain\.
   + **Username** – Enter your Amazon WorkMail address

1. Choose **Sign\-in**\.