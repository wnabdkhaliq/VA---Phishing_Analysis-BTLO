BTLO - Phishing_Analysis

I downloaded the file and open it as text editor, then I searched for recipient,subject,timestamp and Originating IP.

**1. Email Header Analysis**
Recipient: kinnar1975@yahoo.co.uk
Subject: "Undeliverable: Website contact form submission"\
Timestamp: 18 March 2021, 04:14 
Originating IP: 103.9.171.10

<img width="720" height="128" alt="1-Recipient" src="https://github.com/user-attachments/assets/6edb9299-2917-4d5f-b658-9770c0885b16" />

**2. Infrastructure Investigation**
Reverse DNS lookup was performed on the originating IP address.

Resolved Host: **c5s2-1e-syd.hosting-services.net.au**

<img width="556" height="146" alt="2-Originating IP" src="https://github.com/user-attachments/assets/6468c597-16df-4a5b-b493-88947ff27778" />

**3. Attachment and URL Analysis**
The .eml file was opened using Thunderbird to extract embedded information.

Attached File: **Website contact form submission.eml**

<img width="430" height="213" alt="4-Website Contact Form" src="https://github.com/user-attachments/assets/26be7b78-d8e3-4f34-a24a-50a40af6fa5b" />

I found the URL in the text editor: **[https://35000usdperwwekpodf.blogspot.sg](https://35000usdperwwekpodf.blogspot.sg)**

<img width="783" height="112" alt="5-URL" src="https://github.com/user-attachments/assets/61d672f1-b685-416d-a511-e09a6a41ee66" />

Hosting Service: The URL is hosted on the Blogger (Blogspot) platform.

<img width="963" height="140" alt="6-Blogspot" src="https://github.com/user-attachments/assets/a296de2c-da48-4ef9-87f7-5a319268f60a" />

**4. Verification**
The URL was processed using **URL2PNG** to capture the page state.

Result: The page displayed "Blog has been removed," confirming the malicious site had been taken down.

<img width="700" height="446" alt="7-Header (Blog Removed)" src="https://github.com/user-attachments/assets/aacaa0ac-77e5-4523-8f1d-acfadbf6ab52" />

