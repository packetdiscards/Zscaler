# Zscaler Bookmarks List

Also published at https://packetdiscards.blogspot.com

Hopefully this list of bookmarks will help provide a quick reference for those who are new to the Zscaler platform. I will try to keep these up-to-date as new resources are discovered:

_**Zscaler Documentation**_

[Zscaler Docs](https://support.zscaler.com/hc/en-us/?filter=documentation): The starting point for any question that you may have about the service.

[Zscaler App Release Notes](https://support.zscaler.com/hc/en-us/sections/201862943-Zscaler-App-Release-Notes): Zscaler App continues to see wider deployments etc - the release notes document all of the latest updates and fixes etc.

_**Zscaler Training & Certification Portal**_

[Online training Portal](https://zscaler.myabsorb.com): Note, you will need a passcode to register on the training portal. If you have purchased training credits, a passcode can be requested via contacting training@zscaler.com

[Training & Certfication Overview](https://www.zscaler.com/resources/training-certification-overview): Information about all of the current Zscaler Training & Certification offerings.

_**Zscaler Support**_

[Zscaler Support](https://support.zscaler.com/hc/en-us): The Zscaler support portal. Allows you to create support tickets for new provisioning requests, support cases or other technical enquiries.

_**Service Level Agreement Info and other key aspects of the Zscaler service**_

[Zscaler End-user Subscription Agreement](https://www.zscaler.com/legal/end-user-subscription-agreement): This provides all of the details about the contractual aspects of the Zscaler service.

_**Data Privacy at Zscaler**_

[Information on Data Privacy at Zscaler](https://www.zscaler.com/dataprivacy): This provides all of the latest information on data protection and privacy policies.

_**Trust @ Zscaler**_

Allows you to view real-time status, scheduled maintenance events, and recent incidents across the different Zscaler clouds. If you do not know your cloud name, please browse to your Zscaler Administration site and note the domain in the URL. You also have the option of signing up for alerts via email or RSS to receive this information from this site too.

*   [Trust.zscaler.net](http://trust.zscaler.net)
*   [Trust.zscalerone.net](https://trust.zscalerone.net)
*   [Trust.zscalertwo.net](https://trust.zscalertwo.net)
*   [Trust.zscloud.net](https://trust.zscloud.net)

_**Firewall IP & Ports for provisioning of the Zscaler service**_

As part of the deployment of the Zscaler service, you may have to enable your firewall to allow certain communications with Zscaler infrastructure. The exact IP addresses and port numbers etc that need to be allowed are documented at:

*   [zscaler.net](https://ips.zscaler.net)
*   [zscalerone.net](https://ips.zscalerone.net)
*   [zscalertwo.net](https://ips.zscalertwo.net)
*   [zscloud.net](https://ips.zscloud.net)

_**Security Preview**_

[Security Preview](http://securitypreview.zscaler.com/): Security preview is an instant risk assessment to see how effectively you're stopping threats, protecting your users and safeguarding your company's intellectual property. You'll also get recommendations for closing any gaps. Note the tool itself is safe to use as it will perform a number of transactions in your browser to ascertain how susceptible you would be to unsafe content - but stops as far as actually opening or consuming this content.

_**Site Review**_

[Site Review](https://www.zscaler.com/sitereview/help.html): Provides a table of URL categories and some examples in the way of giving an indication as to what kind of URL is likely to fall into what category.

e.g. Job / Employment Search
Sites that provide employment services, assistance in finding employment, or tools for locating employers. Examples:

*   www.monster.com
*   www.kellyservices.com

_**Zulu**_

[Zulu](http://zulu.zscaler.com/): Zulu is a dynamic risk scoring engine for web based content. For a given URL, Zulu will retrieve the content and apply a variety of checks in three different categories:

*   Content Checks – Inspection of page content to identify potentially malicious code in a variety of categories
*   URL Checks – Inspection of the full URL to identify malicious patterns and check the URL/FQDN/TLD against third party and Zscaler block lists
*   Host Checks – IP, DNS and netblock reputation checks

All algorithms generate both a risk score between 0-100 and a risk categorization (Low, Medium, High). Individual scores are then consolidated and weighted to calculate an overall page score and deliver a final categorization of Benign, Suspicious or Malicious based on overall page risk. Meta data for the page is also provided along with a history of past scans.

_**Cloud Sandbox Scanning Portal**_

[Cloud Sandbox Scanning Portal](http://filecheck.zscaler.com/): You can only access the Sandbox Scanning Portal if you are forwarding traffic to the Zscaler service. Your company must also have the Cloud Sandbox subscription enabled.

With the Cloud Sandbox subscription, you can manually submit suspicious files for analysis by uploading it to the Sandbox Scanning Portal.

After you upload a file, the Sandbox engine does the following:

*   Executes and monitors suspicious objects in a controlled sandbox
*   Records and analyzes any malicious behaviors

_**Troubleshooting tools**_

[ip.zscaler.net](https://ip.zscaler.com/cgi-bin/index.cgi): This allows you to check which proxy you are currently using and the user you are logged in as.

[Zscaler analyzer](https://zmtr.zscaler.com/): The Zscaler Analyzer app allows for analysis of the path between your location and a target Zscaler Enforcement Node (ZEN), or to analyze the time it takes for your browser to load a web page, so the Zscaler Support team can detect potential issues. The app performs an MTR (Z-Traceroute) and a full web page load test (Z-WebLoad). The results provide the Zscaler Support team with all the information they need to debug network issues quickly.

[Zscaler tools](https://www.zscaler.com/tools): This includes a number of helpful plugins and integrations with popular browsers.

_**Third party integrations**_

The following are links to helpful docs and references for third party solution integration with Zscaler:

*   [Configure Chome Devices with Zscaler](https://support.google.com/chrome/a/answer/3504945?hl=en)
*   [How to setup Google for Work credentials for Single Sign-On (SSO) via SAML for Zscaler](https://support.google.com/a/answer/6367909?hl=en)
*   [Okta Zscaler Integration Guide](https://support.okta.com/help/articles/Knowledge_Article/38950347-Zscaler-Integration-Guide?id=kA0F0000000AY3m&q=Zscaler&l=en_US&fs=Search&pn=1)
*   [Configuring Okta for Admin SAML SSO](https://support.zscaler.com/hc/en-us/articles/205367175-Configuring-Okta-for-Admin-SAML-Single-Sign-On)
*   [Azure Active Directory Integration with Zscaler](https://azure.microsoft.com/en-us/documentation/articles/active-directory-saas-zscaler-zscloud-tutorial/)
*   [Configuring SSO between OneLogin and Zscaler](https://support.onelogin.com/hc/en-us/articles/201174084-Configuring-SAML-for-Zscaler)
*   [Configuring SAML for Zscaler Private Access](https://support.onelogin.com/hc/en-us/articles/218365083-Configuring-SAML-for-Zscaler-Private-Access)
*   [Configuring Centrify with the Zscaler Cloud Security Platform](https://docs.centrify.com/en/centrify/appref/index.html#page/cloudhelp%2Fo-z%2FSAML_Zscaler.3.html%23wwconnect_header)

_**Other helpful references**_

[FindProxyForUrl](http://findproxyforurl.com): This is a great resource from Peter Hayes, if you need to know more about Proxy Auto Configuration (PAC) files.

[Zscaler Corporate Blog](https://www.zscaler.com/blogs): The Zscaler blog, capturing all of the latest Zscaler news and information.

[Zscaler ThreatLabz Security Research Blog](https://www.zscaler.com/blogs/research): This is the blog from the threatlabz team which contains all of the latest information on current cyber threats and issues.

