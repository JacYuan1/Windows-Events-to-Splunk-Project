# Windows Event to Splunk Project

## Table of Contents

- [Introduction](#Introduction)
- [Tools Used](#Tools-Used)
- [Approach to Problem](#Approach-to-Problem)
- [Learning Outcomes](#Learning-Outcomes)
- [Final Grade Received](#Final-Grade-Received)
- [References](#References)

<h2 id="#Introduction">Introduction</h2>

The premise of this project is to create a custom windows event in which it will be forwarded to Splunk for further analysis. The final report will be linked in the [References Section](#References)

<h2 id="#Tools-Used">Tools Used</h2>

The tools used here are the following:

1. [Splunk](https://www.splunk.com/)
2. [Splunk Universal Forwarder](https://www.splunk.com/en_us/download/universal-forwarder.html)
3. [Oracle VM VirtualBox](https://www.virtualbox.org/)
4. Windows 10 ISO

<h2 id="#Approach-to-Problem">Approach to Problem</h2>

1. Create a Windows event using PowerShell by using the EventLog functions.
2. Forward to Splunk using the Splunk Universal Forwarder.
3. Search the windows event in Splunk by using the EventID that was created in step #1. 

<h2 id="#Learning-Outcomes">Learning Outcomes</h2>

1. Understood how Splunk Universal Forwarder works.
2. Understood different types of searching mechanisms in Splunk such as using regular expression, strings, boolean conditions, by events, by patterns, etc.
3. Understood how to manipulate fields such as adding and deleting selected fields and interesting fields.

<h2 id="#Final-Grade-Received">Final Grade Received</h2>

100%

## References

[Written report linked here](https://github.com/JacYuan1/Windows-Event-to-Splunk-Project/blob/main/Written%20Report.pdf)
