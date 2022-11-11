---
description: A brief introduction to research skills for pentesting.
---

# Introductory Researching

> As I am learning i am making the notes so please don't blame me for any unnecessary answers or content.

### Task 01 (Introduction)

The ability to research effectively is _the_ most important quality for a hacker to have. By its very nature, hacking requires a _vast_ knowledge base -- because how are you supposed to break into something if you don't know how it works? The thing is: no one knows everything.&#x20;

Learn Whats going on, understand it the Software, Hardware, Mechanism, Flow of the work and find out its weak points/ parts ware we can use it for vernabilities.

We will be Learning the following topics:&#x20;

* An example of a research question .
* Vulnerability Searching tools .
* Linux Manual Pages.

### Task 02 (Explain Research Questions)

We'll begin by looking at a typical research question: the kind that you're likely to find when working through a CTF on TryHackMe, HackTheBox or any other Platform which are available.

{% code title="In the Burp Suite Program that ships with Kali Linux, what mode would you use to manually send a request (often repeating a captured request numerous times)?" %}
```bash
Repeater
```
{% endcode %}

{% code title="What hash format are modern Windows login passwords stored in?" %}
```bash
NTLM
```
{% endcode %}

{% code title="What are automated tasks called in Linux?" %}
```bash
Cron Jobs
```
{% endcode %}

{% code title="What number base could you use as a shorthand for base 2 (binary)?" %}
```bash
BASE 16
```
{% endcode %}

{% code title="If a password hash starts with $6$, what format is it (Unix variant)?" %}
```bash
sha512crypt
```
{% endcode %}

### Task 03 (Vulnerability Searching)

Exploitation, Vulnerabilities, Exposures and anything else....

CVE (Common Vulnerabilities and Exposures):  it is exploit available for public a list of records — each containing an identification number, a description, and at least one public reference — for publicly known cybersecurity ... (format for CVE is **CVE-YEAR-IDNUMBER**)

{% code title="What is the CVE for the 2020 Cross-Site Scripting (XSS) vulnerability found in WPForms?" %}
```bash
CVE-2020-10385
```
{% endcode %}

[https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-10385](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-10385)

{% code title="There was a Local Privilege Escalation vulnerability found in the Debian version of Apache Tomcat, back in 2016. What's the CVE for this vulnerability?" %}
```bash
CVE-2016-1240
```
{% endcode %}

[https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-1240](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-1240)

{% code title="What is the very first CVE found in the VLC media player?" %}
```bash
CVE-2007-0017
```
{% endcode %}

[https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-0017](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2007-0017)

{% code title="If you wanted to exploit a 2020 buffer overflow in the sudo program, which CVE would you use?  " %}
```bash
CVE-2019-18634
```
{% endcode %}

[https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-18634](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-18634)

### Task 04 (Manual Pages)

Guide is requried to learn how the product works similarly Manual is a type of guide. In Luinux we use **MAN** command  for manual of a tool&#x20;

```markup
Syntax: Man Tool_Name
```

{% code title="SCP is a tool used to copy files from one computer to another." %}
```markup
What switch would you use to copy an entire directory?
-r
```
{% endcode %}

{% code title=" fdisk is a command used to view and alter the partitioning scheme used on your hard drive." %}
```markup
What switch would you use to list the current partitions?
-t
```
{% endcode %}

{% code title="nano is an easy-to-use text editor for Linux. There are arguably better editors (Vim, being the obvious choice); however, nano is a great one to start with." %}
```markup
What switch would you use to make a backup when opening a file with nano?
-B
```
{% endcode %}

{% code title="Netcat is a basic tool used to manually send and receive network requests. " %}
```markup
What command would you use to start netcat in listen mode, using port 12345?
nc -l -p 12345
```
{% endcode %}

### Conclusion

In this Room i leant how to use Manual, CVE, and research how the Vulnerabilities works.
