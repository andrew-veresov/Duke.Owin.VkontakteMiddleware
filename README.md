VkontakteMiddleware
===================

mvc 5 owin module for vk.com (vkontakte.ru)

How to use?
-------------
1) Add nuget package - search for "Duke.Owin.VkontakteMiddleware"
2) Add module in Startup.Auth.cs of your mvc 5 project

app.UseVkontakteAuthentication("{AppId}", "{AppSecret}", "{PERMISSIONS}");

{PERMISSIONS} - it is the comma-separated string. For example "music,audio"
More info here http://vk.com/dev/permissions

How to register app in vk.com?
-------------
Info here http://vk.com/dev

Live example 
-------------
http://freemusiclib.com/Account/Login

Contacts
-------------
skype - duke_nuken23


 