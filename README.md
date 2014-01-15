  
Perl Executing Browser, v.0.1  
  
Perl Executing Browser (PEB) is a Qt4/5 WebKit browser capable of  
executing Perl scripts locally with or without a webserver,  
providing them even when executed locally with a nice HTML4/5 interface  
for both input and output and using CGI protocol GET and POST methods  
for communication with the scripts.  
  
Perl Executing Browser has the following design objectives:  
* 1. Easy to set up and adapt HTML/CSS/JavaScript GUI for  
    Perl (possibly PHP, Python and other) scripts;
* 2. Zero installation when needed:  
    pack your Perl modules and even your version of Perl with  
    a copy of PEB and its Qt libraries and  
    run your application from every folder, even from USB sticks;  
* 3. Cross-platform availability:  
    use it on every platform and device (desktop, tablet, smartphone),  
    where Perl and Qt4 or Qt5 could be compiled;  
* 4. Maximal flexibility of the network access:  
    a) if no network connectivity is wanted or needed,  
    no services are started, no ports are opened, no firewall notifications are triggered,  
    no need for administrative privileges and everything remains in the userspace, but  
    b) if network connection is essential, PEB can be configured as  
    a client or both as a client and a server for a network-based database  
    in a variety of combinations and topologies.  
    Webserver functionality is provided by a minimally modified version of  
    Mongoose web server.  
  
PEB also exposes some desktop functionalities,  
which are accessible from special URLs and currently are:  
open file, open folder and close browser.  
File to open and folder to open are accessible for every script as  
environment variables FILE_TO_OPEN and FOLDER_TO_OPEN.  
Printing current page by clicking a special URL is also supported.  
  
PEB is also capable of executing long-running scripts -  
i.e. scripts running for arbitrary long time, far beyond any  
server timeouts for CGI or FastCGI scripts.
  
PEB was started as a simple GUI for personal databases.  
This small project is still in its very beginning and  
current version should be considered alpha pre-release.  
Do not use it for production purposes!  
No feature or implementation should be considered final at this point.  
Proper documentation and examples are still missing.  
  
Compiled and tested successfully using:  
1. Qt Creator 2.5.0 and Qt 4.8.2 on 32 bit Debian Linux,  
2. Qt Creator 2.8.1 and Qt 5.1.1 on 32 bit Debian Linux,  
3. Qt Creator 3.0.0 and Qt 5.2.0 on 32-bit Debian Linux,  
4. Qt Creator 3.0.0 and Qt 5.2.0 on 32-bit Windows XP,  
  
This software is licensed under the terms of GNU GPL v.3 and  
is provided without warranties of any kind!  
Dimitar D. Mitov, 2013 - 2014, ddmitov (at) yahoo (dot) com  
  