# Setting up Microsoft Outlook clients for Amazon WorkMail<a name="outlook-client"></a>

To get started with Microsoft Outlook, connect Microsoft Outlook to your Amazon WorkMail account\.

**Topics**
+ [Connecting Microsoft Outlook clients to your Amazon WorkMail account](#connect-outlook-client)
+ [Manually connect Microsoft Outlook to Amazon WorkMail](#manual-outlook-client)

## Connecting Microsoft Outlook clients to your Amazon WorkMail account<a name="connect-outlook-client"></a>

Amazon WorkMail uses AutoDiscover to configure your Outlook client\. To set up your Outlook client, you need your Amazon WorkMail email address and password\. Amazon WorkMail integrates with the following versions of Outlook:
+ **Windows clients** — Office Outlook 2007, Outlook 2010, Outlook 2013, Outlook 2016, and Outlook 2019
+ **Mac clients** — Outlook for Mac 2011, Outlook 2016 for Mac, and Outlook 2019 for Mac

**Note**  
If automatic configuration fails, you can manually configure most Outlook clients, except for Outlook 2016 and Outlook 2019 for Windows\. For more information, see [Manually connect Microsoft Outlook to Amazon WorkMail](#manual-outlook-client)\.

**To connect Microsoft Outlook to your Amazon WorkMail account**

1. In Windows, open **Control Panel**, and choose **Mail \(32\-bit\)**\.

1. In the **Mail Setup \- Outlook** dialog box, choose **Show Profiles**\. Then, in the **Mail** dialog box, choose **Add**\. 

1. In the **New Profile** dialog box, enter `WorkMail` in the **Profile Name** field, and choose **OK**\. 

1. In the **Add Account** dialog box, in the **E\-mail Address** field, enter your Amazon WorkMail email address and choose **Next**\. 
**Note**  
If you're prompted to enter your user name and password, make sure that you enter your full email address as your user name\.  
If you're prompted to configure server settings in the **Allow this website to configure** dialog box, select the **Don't ask me about this website again** check box, and choose **Allow**\.

1. Outlook will prompt you when it finishes setting up your account\. Choose **Finish**\.

1. In Outlook 2016 for Mac or Outlook 2019 for Mac, do one of the following:
   + If this is the first account you're creating in Outlook 2016 for Mac or Outlook 2019 for Mac: 

     1.  On the **Welcome** screen, choose **Add Email Account**\. 

     1. Enter your email address, and then choose **Continue**\. 

     1.  Under **Choose the provider**, choose **Exchange**\.
   + If you already have an email account for a different email address: 

     1.  In the **Tools** menu, choose **Accounts**\. 

     1. In the **Accounts** dialog box, choose **\+** \(plus sign\) and **New Account**\. 

     1.  Enter your **Email Address** and choose **Continue**\. 

     1.  Under **Choose the provider**, choose **Exchange**\. 

1. In the **Enter your Exchange account information** dialog box, for **Method**, choose **User Name and Password** and enter your email address\. 

1. For **Domain\\Username or Email**, enter your email address, and for **Password**, enter your password\. 

1. Choose **Add Account** to complete setup\. 
**Note**  
Microsoft Outlook will attempt to detect your email server settings\. If Outlook prompts you to allow the server to configure your settings, select the **Always use my response for this server** check box, and then choose **Allow**\.

   After your account is successfully set up, Outlook displays the account in the **Accounts** dialog box\.

For more information about adding accounts in Outlook 2016 for Mac and Outlook 2019 for Mac, see [Add an email account to Outlook](https://support.office.com/en-us/article/add-an-email-account-to-outlook-6e27792a-9267-4aa4-8bb6-c84ef146101b)

## Manually connect Microsoft Outlook to Amazon WorkMail<a name="manual-outlook-client"></a>

If automatic configuration fails, you can manually configure the following versions of Outlook:
+ **Windows clients** — Office Outlook 2007, Outlook 2010, and Outlook 2013
+ **Mac clients** — Outlook for Mac 2011, Outlook 2016 for Mac, and Outlook 2019 for Mac

**Note**  
Outlook 2016 and Outlook 2019 for Windows can only be configured by using AutoDiscover\.

**To manually configure Outlook**

Follow these steps to manually configure Office Outlook 2007, Outlook 2010, or Outlook 2013\.

1. In Windows, open **Control Panel**, and choose **User Accounts and Mail \(32\-bit\)**\.
**Note**  
If you don't see **User Accounts and Mail \(32\-bit\)**, open the **View by** list and choose either **Large icons** or **Small icons**\.

1. In the **Mail Setup \- Outlook** dialog box, choose **Show Profiles**\. Then, in the **Mail** dialog box, choose **Add**\. 

1. In the **New Profile** dialog box, enter a name for the profile in the **Profile name** field and choose **OK**\.

1. Select **Manual setup or additional server types**, and then choose **Next**\.

1. If it isn't already, select **Outlook\.com or Exchange ActiveSync compatible service**, and then choose **Next**\.

1. Complete the following fields in the **Server Settings** dialog box:
   + For **Your name**, enter the name that you want others to see\.
   + For **E\-mail Address**, enter your Amazon WorkMail address\.
   + For **Mail server**, enter the **outlook\.mail\.*aws\-region*\.awsapps\.com** server that corresponds to your mailbox's AWS Region
     + US West \(Oregon\)

       `outlook.mail.us-west-2.awsapps.com`
     + US East \(N\. Virginia\)

       `outlook.mail.us-east-1.awsapps.com`
     + Europe \(Ireland\)

       `outlook.mail.eu-west-1.awsapps.com`
**Note**  
If you don’t know your mailbox's AWS Region, contact your system administrator\.
   + For **User Name**, enter your Amazon WorkMail user name\.
   + For **Password**, enter your Amazon WorkMail password\.

1. \(Optional\) Choose **Remember password**\.

1. Choose **Next**\.

   Outlook tests the connection and displays a message saying that your account is ready for use\.

1. Choose **Finish**\.

**To manually configure Outlook for Mac 2011, Outlook 2016 for Mac, and Outlook 2019 for Mac**

Follow these steps to manually configure Outlook for Mac 2011, Outlook 2016 for Mac, and Outlook 2019 for Mac\.

1. In the **Tools** menu, choose **Accounts**\. In the **Accounts** dialog box, choose **\+** and **New Account**, type your **Email Address**, choose **Continue**, and under **Choose the provider**, choose **Exchange**\.
   + If you’re using Outlook for Mac 2011, uncheck **Configure automatically** in the **Enter your Exchange account information** dialog box\. For **Authentication**, choose **User Name and Password**\.

1. Type your **Email address**, **Password**, and **User name** where indicated\. Make sure to type your full password\.

1. For **Server**, type the endpoint matching the AWS Region where your mailbox is located\.
   + US West \(Oregon\)

     https://ews\.mail\.us\-west\-2\.awsapps\.com/EWS/Exchange\.asmx
   + US East \(N\. Virginia\)

     https://ews\.mail\.us\-east\-1\.awsapps\.com/EWS/Exchange\.asmx
   + Europe \(Ireland\)

     https://ews\.mail\.eu\-west\-1\.awsapps\.com/EWS/Exchange\.asmx
**Note**  
If you don’t know the AWS Region where your mailbox is located, contact your system administrator\.

1. Choose **Add Account** to complete setup\.

1. After your account is successfully set up, it displays in the **Accounts** dialog box\.

For more information about adding accounts in Outlook for Mac, see the following:
+ [Add an email account to Outlook for Mac 2011](https://support.office.com/en-us/article/Add-an-email-account-to-Outlook-for-Mac-2011-fdd33fab-b745-4762-a1c6-70ddba452983)
+ [Add an email account to Outlook](https://support.office.com/en-us/article/add-an-email-account-to-outlook-6e27792a-9267-4aa4-8bb6-c84ef146101b) \(Outlook 2016 for Mac, Outlook 2019 for Mac\)