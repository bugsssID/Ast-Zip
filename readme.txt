


Asterisk Logger v1.02
Copyright (c) 2003 - 2005 Nir Sofer
Web Site: http://www.nirsoft.net



Description
===========

Many applications, like CuteFTP, VNC, IncrediMail, Outlook Express, and
others, allows you to type a password for using it in the application.
The typed password is not displayed on the screen, and instead of the
real password, you see a sequence of asterisk ('****') characters. This
utility can reveal the passwords stored behind the asterisks in standard
password text-boxes.
Asterisk Logger is a successor of AsterWin utility. It reveals the
asterisk passwords in the same way as AsterWin utility, but it has some
advantages over the previous utility:
* You don't have to press a button in order to reveal the asterisk
  passwords. Whenever a new window containing a password box is opened,
  Asterisk Logger automatically reveals the password inside the
  password-box, and add a record to passwords list in the main window of
  Asterisk Logger.
* Asterisk Logger displays additional information about the revealed
  password: The date/time that the password was revealed, the name of the
  application that contains the revealed password box, and the executable
  file of the application.
* Asterisk Logger allows you the save the passwords to HTML file and to
  3 types of text files.



Versions History
================


* Version 1.02:
  o 'Copy Selected Items' now copies the items as tab-delimited line.
  o New option: Copy the password to the clipboard.
  o Added support for Windows XP style.

* Version 1.01 - Add support for translation to other languages.
* Versions 1.00 - First Release.



System Requirements
===================

This utility works properly under Windows 9x, Windows ME, Windows 2000,
and Windows XP. If you work on Windows NT, you should download the
'psapi.dll' and place it in your system32 directory. If you don't
download this file under Windows NT, the Asterisk Logger utility will
properly reveal the asterisk passwords, but it won't display the
information about the application that contains the passwords.
(Application and Executable File fields)

Known Limitations
=================

This utility works fine with most password text-boxes, but there are some
applications that don't store the password behind the asterisks, in order
to increase their security. In such cases, Asterisk Logger will not be
able to reveal the password.
The following applications and OS components don't store the password
behind the asterisks:
* Netscape 6.x (Passwords in the Web page)
* Dialup and network passwords in Windows 2000
* Windows NT/2000/XP user management tools.
Asterisk Logger also cannot reveal the passwords in Internet Explorer Web
pages, Because they are stored in different way than in other
applications. if you want to reveal the passwords behind the asterisks in
Internet Explorer, you can download the AsterWin IE utility.



License
=======

This utility is released as freeware for personal and non-commercial use.
You are allowed to freely distribute this utility via floppy disk,
CD-ROM, Internet, or in any other way, as long as you don't charge
anything for this. If you distribute this utility, you must include all
files in the distribution package, without any modification !



Disclaimer
==========

The software is provided "AS IS" without any warranty, either expressed
or implied, including, but not limited to, the implied warranties of
merchantability and fitness for a particular purpose. The author will not
be liable for any special, incidental, consequential or indirect damages
due to loss of data or any other reason.



Using Asterisk Logger
=====================

except for Windows NT, this utility doesn't require any installation
process or additional DLLs. Just copy to executable to any folder you
want, and run it.
Under Windows NT, you can still use this utility without any additional
DLLs, but the information about the application that contains the
asterisk password won't be displayed. In order to display the application
information under Windows NT, you have to download psapi.dll and put it
in your system32 directory. If this file is already exist on your system,
you don't need to overwrite it.

In order to reveal the passwords inside asterisk text-boxes, follow the
instructions below:
1. Run the Asterisk Logger utility. The main window will appear, with
   no items in it.
2. Open the windows that contains the asterisk text-box you want to
   reveal. The password will be instantly revealed inside the password
   box, and in addition, a record containing the password and other
   information will be added to the main window of Asterisk Logger
   utility.
3. After you reveal all the passwords you need, you can select the
   desired passwords in the main window of Asterisk Logger, and save them
   into text or HTML file.

The Asterisk Logger utility also provides 2 additional options for using
in special cases:
* Log Changes In Password Box: If this option is checked, Asterisk
  Logger automatically traces all changes in the revealed password boxes,
  and whenever it find a change in the password, it instantly add a new
  record to the passwords list, which contains the new modified password.
  This option can be useful for some applications, like CuteFTP. When you
  open to site manager of CuteFTP, the password of the current selected
  FTP item is revealed. In order to easily reveal the passwords of other
  items, check this option, and then move through all items that you want
  to get their password. Each time you move into a new item, the password
  will be added to the list in the main window of Asterisk Logger.
* Log Duplicate Passwords: This option is available only if the
  previous option is checked. If this options is checked, a modified
  password will be added even if it's identical to one of the previous
  passwords of the same password-box.



Translating Asterisk Logger to the languages
============================================

In order to translate Asterisk Logger to other language, follow the
instructions below:
1. Run Asterisk Logger with /savelangfile parameter:
   astlog.exe /savelangfile
   A file named astlog_lng.ini will be created in the folder of Asterisk
   Logger utility.
2. Open the created language file in Notepad or in any other text
   editor.
3. Translate all string entries to the desired language. Optionally,
   you can also add your name and/or a link to your Web site.
   (TranslatorName and TranslatorURL values) If you add this information,
   it'll be used in the 'About' window.
4. After you finish the translation, Run Asterisk Logger, and all
   translated strings will be loaded from the language file.
   If you want to run Asterisk Logger without the translation, simply
   rename the language file, or move it to another folder.



Feedback
========

If you have any problem, suggestion, comment, or you found a bug in my
utility, you can send a message to nirsofer@yahoo.com


