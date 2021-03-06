---
title: How to enable SSH using ncp-config (or ncp-web)
keywords: maintain ssh using ncp-config ncp-web network guide
tags: [maintain, ssh, using, ncp-config, ncp-web, network, guide]
#summary: ""
sidebar: en_sidebar
sidebar_folder: 'Maintain'
language: 'en'
permalink: en_How-to-enable-SSH-using-ncp-config-or-ncp-web.html
folder: en
---

In terminal type:

`sudo ncp-config` (used to be nextcloudpi-config)

or visit https://nextcloudpi.local:4443
and login with
user: ncp
password: Generated at activation (used to be: ownyourbits)

Scroll down nextcloudpi-config screen and select SSH:
![nextcloudpi-config screenshot](https://user-images.githubusercontent.com/8775469/34931799-c403a9bc-f9d0-11e7-9eaf-30864cdf657c.png)
Use arrow keys for up and down. Use tab key to move to select or cancel, enter to confirm.

![Extra ssh instructions screenshot](https://user-images.githubusercontent.com/8775469/34931804-c831be48-f9d0-11e7-9809-87d557677733.png)

Type yes to enable ssh and set the new password for pi.
In order to enable SSH, the password for user pi can not remain set to the default raspberry.
You HAVE to create a NEW password for pi if you want this program to enable SSH, it
will fail if you dont!
Note: Use normal AlphaNumeric, the only special characters allowed are .,@-_/

![Enable SSH yes screenshot](https://user-images.githubusercontent.com/8775469/34931808-cb1eaf30-f9d0-11e7-9494-0d51bfdc3a16.png)

Thanks for your comments, please ask questions [here](https://help.nextcloud.com/c/support/appliances-docker-snappy-vm) and report any technical issues [here](https://github.com/nextcloud/nextcloudpi/issues/356)

[A short video demonstrating enable ssh in ncp-web](https://youtu.be/mjt9wTef5AA)
