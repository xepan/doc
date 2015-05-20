TAB > Company Information

Company General Information: 
This Section deals with the Basic Information about the Company, just like you used to fill Personal Information about yourself in your academic forms.

	> Company Name : 
	Here you have to provide the name of your Company. 
	Example: Xavoc Technocrats Pvt. Ltd.
	> Owner Name   : 
	It ask you for the Name of Owner of the Company. In case, if, business being a separate entity, just provide the name of company being registered with. 
	Example: Mr. Gowrav Vishwakarma
	> Mobile No.   : 
	It ask you for the Registered Contact Information about the company. It starts with Country Prefix, followed by Conatct no.
	Example: (+91)(9876543210)
	> Email.		   :
	It ask you for the registered mail-address of the conmpany.
	Example: info@xavoc.company
					
Company Contact Information:
This section ask for geo-location of the company, i.e. its Local Address, City, State, Country, and Pincode.
	
SEO(Search Engine Optimization) Information:
It asks for the search keyword you would like search engines to list your website in the search results , when searched with the given words.

	> Keywords:
	This field ask you for the providing keywords for Search Engines to add your website to the their search results. If you have already provided the keywords in webpage's header section, they will not be over-ruled by the contents of this field. But, if in case, you have forgot, or not mentioned the search keywords in any page of your website, these will acts as meta-keywords for search engines to list that particular page.
	> Description:
	This field contains the meta-information for use of search engines, to describe your page.
	
	
After completing with the above details click Update button to save your information.

====================================================================================
TAB>     Default Email Settings

NOTE: PLEASE BE CAREFULL WHILE PROVIDING FOLLOWING INFORMATION.

Email Transporter To Use
This drop-down ask you select the service you would like to employee for sending mails from your system. 

NOTE: IF YOU ARE NOT SURE ABOUT THESE SERVICES, KEEP SMTP TRANSPORT SELECTED.
	
Connection Settings
	This section ask for the Encryption Type, Email Host Name, Email Port, Email User Name, Email Password
	
	Encryption Type	:	
	How can you send your mails securely that is being sent between applications across an untrusted network? The Transport Layer Security (TLS) protocol and the Secure Sockets Layer (SSL) protocol, provides answer to this common security question. TLS and SSL, authenticates and secures mail transfers by using certificate-based authentication and symmetric encryption keys.
		
	Email Host Name : 
	It specify the server name which will be used to send mails for your company.
		
	Email Port		:
	It specifies the port no. which will be used to send mails from the system.
		
	Email User Name	:
	It specifies your user name, provided you by your server. Its may something like example@servername.com or simple user_name.
		
	Email Password :
	Its specifies you secret password ;-) .
		
Email Reply To Setting
While the "From:" in the email header field basically serves to inform the recipient where the email is coming from, the "Email Reply-To:" field defines the email address that is automatically inserted into the "To:" email field when a affiliate replies to your email message. Today, almost in all organization, for emails, the "From:" and "Reply-To:" fields are the different, so you can specify the latter here, if exist.
	
	Email Reply To:
	It specify the mail address, you want any queries or responses to arrive at, in return, from affiliates, if it is maintained.
		
	Email Reply To Name:
	It specifies the name you want to provide for your your Reply-To mail address.


Email From : Sender Settings
Sometimes it happens that some other entity is sending emails on behalf of us or may be company. If its the case with you as well, you can specify them here.
	
	From Email:
	The "From" Header is intended to be the entity that the message is from. It is who the recipient's email client should display the message is from.
		
	From Name:
	It specifies the name you want to appear for your "From Address".
		
	Sender Email:
	The "Sender Email" specifies the mailbox of the agent responsible for the actual transmission of the message. Example might be gmail when it is configured for a domain not hosted by Gmail. In this case, the From Email header would contain 'you@yourdomainname.com', but the Sender will be 'someusername@gmail.com'. Many mail clients now render this as 'someuser@gmail.com on behalf of you@yourdomain.com'.
	
	Sender Name:
	It specifies the name you want to appear for your "Sender Email" Address.
		
	After its setup, the recipient would see, in his/her mail :
	from_email_address@hostname.com [mailto:from_email_address@hostname.com] On Behalf Of organization_name
		
		
Email Throttling Settings
Some ISPs limit the amount of email they accept from a particular sender during a specified period of time. If you try to send email above their acceptable threshold, they will reject your email resulting in a high number of bouncebacks. This is email throttling and is also referred to as a “deferral.” This refusal to deliver your mail is usually temporary, but it depends on the situation. I mean sometimes the receiving server doesn’t recognize your IP and is afraid you’re sending spam on such continuous sending or in bulk. This is why warming up is so important, so they know who you are. So, stay tuned with our provided options form this problem.
	
	Smtp Auto Reconnect:
	It disconnects and then reconnects to server after sending specified no. of emails after sometime.
		
	Email Threshold:
	It specifies threshold to send emails with this email configuration per minute.
		

Return Path
Every e-mail message has a hidden field called the "Return-Path" address (sometimes called a "bounce address" or "From Address"). A bounce address is an e-mail address to which bounce messages (undeliverable notifications and mails, etc.) are delivered. There are many variants of the name, including return path, reverse path, envelope from, envelope sender, MAIL FROM, 5321-FROM, return address, From_, Errors-to, etc. If you maintain a separate account for such bounced mails, then specify that here, so that you can keep eye on the active and inactive recipients, which will save your time in context with concept of Email Throttling.
	
	
After completing with the above details click Update button to save your information.


=========================
TAB>	SMS Settings

Gate Way Info
Here you provide the basic info about the service provider for your SMS Service.
	
	GateWay Url:
	It specifies the basic REST API URL, provided by Your Service Provider, for sending SMS to recipients.
		
	Gateway User Name:
	Its your User Name you use to access the service via.
		
	Gateway Password:
	Its your top secret password ;-).
		
		
Query String Info
This section asks you for basic variables information, defined in your API, used to successfully send SMS. For more info, read its manual provided by service provider.
	
	Gateway User Name Query String Variable:
	It ask you for the variable which your API uses for specifying USER_NAME.
		
	Number Query String Variable:
	It ask you for the variable which your API uses for specifying Phone Number.		
	
	Messesge Query String Variable:
	It ask you for the variable which your API uses for specifying message intended for sending to recipient.
		
	
SMS Prefix And Postfix
If you want to add some particular suffix or prefix, as your signature or wishes in the message, everytime you send message, You can specify them here.
	
	Message Prefix:
	As the name suggests, you can specify any pharse, you want appear just before your actual message.
		
	Message Postfix:
	As the name suggests, you can specify pharse, you want appear at end of your actual message.
		
	
After completing with the above details click Update button to save your information.