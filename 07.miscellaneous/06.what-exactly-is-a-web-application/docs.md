---
title: 'What Exactly is a Web Application'
taxonomy:
    category:
        - docs
---

![photo1](https://farm2.staticflickr.com/1625/24524099635_49f6e708f8_z.jpg)

In the most general terms, a Web application is a piece of software that runs on a Web server. A Web server is a just a computer that has been dedicated and specially configured to host Web pages.

Most Web applications are comprised of two components: files and a database. When you install a Web application, you will need to make sure all of the files are copied over into the appropriate location AND that a database (and database user) has been set up to connect to those files. Often, you will have to do some configuration to make sure the application knows how to access the database.

The system we use for [Reclaim Hosting](https://reclaimhosting.com) uses a special script installer called **Installatron** that allows you to automatically install over 100 open source applications. When you use Installatron, you don't need to worry about moving files, creating databases, or doing the initial configuration. It's all taken care of for you.

In order to run on the Reclaim Hosting server, Web applications must be able to run on a LAMP server (an acronym which stands for Linux, Apache, MySQL, PHP), which is the particular kind of Web server that we use. Occasionally, a Web application may require additional components or modules that need to be installed on the server. If you want to install an application that is not part of the Installatron suite and it has requirements that you're not sure the server can meet, submit a ticket and we'd be happy to look into it for you.
