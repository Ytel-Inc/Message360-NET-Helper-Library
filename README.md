# Message360-NET-Helper-Library

![](http://message360.com/wordpress/wp-content/uploads/2014/08/message360.png)

### Welcome to the Message360 .NET Helper Library
This is home to the Official .NET Message360 REST API. 

```C#
Msg360APIRestClient Client = new Msg360APIRestClient("YT10ff38384xyz", "1acff58abc", ".xml");
var random = new Random();
var newSms = Client.SMS_SendSMS("5552221133", "6203345599", "test sms " + random.ToString(), "1", "1");
Console.WriteLine(newSms.ToString());
Console.ReadLine();
```
##### Below are the required Dependencies:
https://www.nuget.org/packages/Newtonsoft.Json/

https://www.nuget.org/packages/RestSharp/
Install-Package RestSharp -Version 103.4


### About Message360

An account for Message360 is free to sign up for at [https://api.message360.com](https://api.message360.com)

Empowering technology to meet modern day communication needs. Through a simple to use API, developers can build, connect, and manage all communications platforms in one system. 

Communicating with prospects, leads and customers is the single most important thing when protecting and growing your business. Now, take it to the next level by imagining the possibilities and how your business can communicate with these people.

More information can be obtained about message360 at [http://www.message360.com](http://message360.com/)

### Support or Contact
Having trouble with Pages or the library?  Visit [https://api.message360.com](https://api.message360.com) and click the Help button in the bottom right corner or [contact support](mailto:support@ytel.com) and we’ll help you sort it out.

### Company Information
© 2015 Ytel, Inc. | Ytel™ All Rights Reserved. | 800.382.4913 | www.ytel.com
