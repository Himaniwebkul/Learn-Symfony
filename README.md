#Learn-Symfony
[![Build Status](https://travis-ci.org/vaishaliwebkul/Learn-Symfony.svg?branch=master)](https://travis-ci.org/vaishaliwebkul/Learn-Symfony)
[![Open Source Helpers](https://www.codetriage.com/vaishaliwebkul/learn-symfony/badges/users.svg)](https://www.codetriage.com/vaishaliwebkul/learn-symfony)
![GitHub contributors](https://img.shields.io/github/contributors/cdnjs/cdnjs.svg)
<p align="center"><a href="https://www.uvdesk.com/en/" target="_blank">
    <img src="https://s3-ap-southeast-1.amazonaws.com/cdn.uvdesk.com/uvdesk/bundles/webkuldefault/images/uvdesk-wide.svg">
</a></p>

A fully-functional [UVDesk Community Edition][1] project skeleton packaged along with the bare essential utilities that you can use to develop your own custom helpdesk solutions.

<b> <h3>  Introduction? </h3> </b>

 <a href="https://www.uvdesk.com/en/opensource"> UVdesk Opensource </a> is an Enterprise Helpdesk system built on top of <a href="https://symfony.com/"> Symfony/PHP framework </a>. It assemble all your customer request at one place.

<b> <h3> Why we had done this? </h3> </b>

Our main aim is to provide a full fledge helpdesk ticket system for those who have unpredicted customization and would like to seamlessly offer excellent customer service using the Symfony/PHP framework along with complete customized code and technical documentation. 

UVdesk Open Source is an endeavor to bring the best suited dynamic customer support solution for all businesses of every size.

UVdesk Opensource is a great approach to reduce agent workload and get live reporting along with automated rules, saved replies, analytics, ticket types, unlimited support agents in order to provide high-grade customer support, whether your business is small or large, 

<b> For Developers - </b> This is a guide for all dev guys, to get you started down with Symfony and PHP Framework, which is known for its robustness, scalability, High performance, security, and a Component-based system. 

<p> Now, the whole class of PHP/Symfony developers, can also contribute to this project and create your own helpdesk by using any code and make it better for your customers. Expect bugs and sharp edges. Please help us by trying it out, <a href="https://github.com/uvdesk/community-skeleton/issues"> reporting bugs</a>, and letting us know what you
think!</p>

<h3> <b> Features  </h3>
<ul>
<li>Email Piping + unlimited mailbox</li>
<li>Unlimited support assistants.</li>
<li>Knowledgebase - self-service portal.</li>
<li>Saved Replies - pre-formatted reply templates.</li> 
<li>Tags.</li>
<li> Ticket Types. </li>
<li>Prepared responses - manual workflow.</li>
<li>Brilliant - workflow.</li>
<li>Live - Reportings.</li>
<li>Standard Email Templates.</li>
<li>Branding to promote business.</li>
<li>Easy integration with apps.</li>
</b> </ul>


<h3> <b> What's Included? </b> </h3>


The standard distribution comes pre-configured with the following bundles:

  * [**UVDeskCoreBundle**][3] - The core framework bundle for bulding helpdesk solutions

  * [**UVDeskAutomationBundle**][4] - Adds support for workflows and prepared responses to automate any specific operations within your helpdesk system

  * [**UVDeskSupportCenterBundle**][5] - Integrates the easily customizable support center portal to enable users to easily interact with the support staff through your helpdesk system

<span style="color:blue"><b> Prerequisite </b> </span>

<p> Before creating your UVDesk Community project, make sure that you're using PHP 7 or higher and have <a href="http://php.net/manual/en/book.imap.php" rel="nofollow">Composer</a> installed. You also need to ensure that you have the following PHP extensions installed: </p>
<ul>
<li><a href="http://php.net/manual/en/book.mailparse.php" rel="nofollow">PHP IMAP</a></li>
<li><a href="https://getcomposer.org/" rel="nofollow">PHP Mailparse</a></li>
</ul>

<h3> <b> Installation </b> </h3>
To create your project, run the following command:

```bash
$ composer create-project uvdesk/community-skeleton helpdesk-project --stability dev
```

After creating your project, you can setup the project in the following ways:

**Via Terminal**

```bash
$ php bin/console uvdesk:configure-helpdesk
```

**Via Web Installer**

After opening your project in the web browser, navigate to /setup/, where you will be greeted by the web installer to guide you in setting up your project.

<h3> <b> License </b> </h3>

All libraries and bundles included in the UVDesk Community Edition are released under the <a href="https://opensource.org/licenses/MIT">MIT</a> or <a href="https://opensource.org/licenses/BSD-3-Clause">BSD license </a>.


[1]: https://www.uvdesk.com/
[3]: https://github.com/uvdesk/core-framework
[4]: https://github.com/uvdesk/automation-bundle
[5]: https://github.com/uvdesk/support-center-bundle



