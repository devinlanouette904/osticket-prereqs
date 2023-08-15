<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install and enable Internet Information Services (IIS) and IIS Management Console 
- Install PHP Manager for IIS
- Install URL Rewrite Module 
- Install PHP 7.3.8
- Install VC Redist
- Install MySQL 5.5.62
- Install osTicket v1.15.8
- Install HeidiSQL

<h2>Installation Steps</h2>
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/46adfacd-dbb2-4c9c-89d5-c283fba5705f">
<p>

</p>
<p>
First, I installed and enabled Internet Information Services, and enabled CGI and Common HTTP Features using the control panel under my virtual machine.
</p>
<br />

<p>
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/4101c3af-cdcd-4d29-a265-020de0db1772">

</p>
<p>
Next, I installed PHP Manager for IIS.
</p>
<br />

<p>
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/eaa21c8a-59f9-4725-a936-1ed2f1eab792">

</p>
<p>
Next, I installed the URL Rewrite Module.
</p>
<br />
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/62ec87fb-e743-4768-b4ae-521e414864cc">

</p>
<p>
Next, I created a new directory under the C Drive (C:\PHP), then installed PHP 7.3.8 and extracted the contents into C:\PHP.
</p>
<br />
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/9b629cb5-389f-4249-87fb-0eb984dc167d">

</p>
<p>
Next, I installed VC Redist. 
</p>
<br />
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/f9e99a47-82de-443e-8900-d941fb7fe26e">

</p>
<p>
Next, I installed MySQL using a typical setup and standard configuration. 
</p>
<br />
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/8f99a3ec-04ce-4aa8-afad-cc7a4acac21f">

</p>
<p>
Next, I registered PHP from within IIS. Using the directory (C:\PHP) I created under the C Drive, I used the path php-cgi.exe.
</p>
<br />
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/795a75ac-3b18-49a7-bd87-aa8013f2a4a2">

</p>
<p>
Next, I installed osTicket v.1.15.8 and enabled the extensions php_imap.dll, php_intl.dll, and php_opcahce.dll within IIS. 
</p>
<br />
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/ea8c83cd-aeef-4924-b249-e19525c0c459">

</p>
<p>
Next, I installed HeidiSQL, created a new session, and created a database called "osTicket" within HeidiSQL.
</p>
<br />
<img width="500" alt="image" src="https://github.com/devinlanouette904/osticket-prereqs/assets/142081954/a0b4578e-de1c-412f-a41c-502bdc43cec6">

</p>
<p>
Finally, I continued setting up osTicket within the browser, and successfully installed and was able to log in with no errors. 
</p>
