---
layout: post
categories : [General]
title: "On the road to a new era"
tags : [General]
excerpt : "SolidInvoice is moving into a new era with lots of updates. Version 2 is around the corner with a whole new look and feel and a lots of changes to improve usability and stability."
image : /assets/images/2017-08-18-a-new-era-is-coming/banner.jpg
---

A lot of new changes has been happening in the last few months, and I am very excited about what is laying ahead.

### CSBill is now SolidInvoice

One of the most important changes that has been made, is the re-branding of CSBill into SolidInvoice. This name change is an important milestone, since I have always felt the name CSBill did not give justice to the application.
Changing the name to SolidInvoice will breath new life and meaning into the project, and it fits more in line with what the application is about.

### Version 2.0.0 is on it's way

It's been a while since there was a new release, and that is because I've been hard at work on version 2.0. Version 2.0.0 Alpha 1 has just been released which marks the first big milestone of the version 2 release.
Expect more frequent releases and updates in the coming months. This new version comes with a bunch of improvements and some new features that I'm very excited about.
I have always felt that version 1 was very rushed, and not enough time was spent in setting up a proper architecture to make future updates easier. That's why when I started to think about version 2, I thought it was the best time to re-write the code base as much as possible.
This re-write was necessary in order to make the application more stable and to make it easier to add enhancements in the future. This re-write does not remove any functionality, so everything will still work the same way you are currently used to.

Some of the new changes in that you can expect in version 2 is:

* Minimum required PHP version has been bumped to 7.1
* Symfony upgraded to 3.3
* Support Environment variables for configuration
* Add support for monetary discount values along with percentage values
* Revamped UI (More about this below)
* Re-worked the API and add support for JSON-LD
* Upgrade MarionetteJS to version 3 and add a new process to manage asssets
* Add VAT number to clients
* Many bug fixes

### A new design

Version 2 includes a brand new user interface and this design. While the original design was sufficient, I felt that it was lacking in some areas and in some cases didn't feel professional enough.
The new design is more in line with a professional business application and offers a cleaner look and feel. It also gives some flexibility with customising the UI.
Although the UI looks different, a lot of elements will still feel familiar and you can expect a lot of the functionality to still work the same.

Here is a preview of what Version 2.0 will look like:

{:class="image left"}
[![Dashboard][0]][0]

{:class="image left"}
[![Clients][1]][1]

{:class="image left"}
[![Clients View][2]][2]

{:class="image left"}
[![Invoices][3]][3]

{:class="clear"}

### New website and unified design

I'm also proud to show off the brand new website for SolidInvoice, which has been completely re-designed from the old one. The website is available at [https://solidinvoice.co](https://solidinvoice.co).
Along with the new website, I also felt that it was time to create a unified design for all the sites related to SolidInvoice. Previously the blog and documentation had different styles, but as of today, the blog and documentation share the same, clean design.
Both the blog and the docs has been re-designed from the ground up, and you can expect any future online presence relating to SolidInvoice to share this same look and feel.

### The road forward

There are still a lot of work to be done before version 2 stable will be released, but I'm very excited about the future of SolidInvoice. I'm going to continue working on refactoring and improving the code-base, as well as working on the stability of SolidInvoice and adding some new features.
Expect another coupld of alpha releases in the next few weeks, before the feature freeze and the first Beta is released. Once version 2 hits the feature freeze, I'm just going to focus on stability to ensure version2 is as bug-free as possible when it is released.
If all goes well, I hope to have the stable release for version 2 out before the end of the year.

Along with working on version, there are also a lot of documentation that needs to be added.
If you want to contribute in getting version 2 stable, you can have a look at some of the open issues at [https://github.com/SolidInvoice/SolidInvoice/issues](https://github.com/SolidInvoice/SolidInvoice/issues) and help close some of the issues.
You can also contribute to the documentation (which is in need of much love) which is located at [https://github.com/SolidInvoice/docs](https://github.com/SolidInvoice/docs).

Be sure to keep an eye in this blog for future updates, as well as following SolidInvoice on twitter at [https://twitter.com/SolidInvoice](https://twitter.com/SolidInvoice) to keep up to date with future developments.


[0]: {{ site.url }}/assets/images/2017-08-18-a-new-era-is-coming/screencapture-solidinvoice-dashboard-1503395002905.png
[1]: {{ site.url }}/assets/images/2017-08-18-a-new-era-is-coming/screencapture-solidinvoice-clients-1503395380313.png
[2]: {{ site.url }}/assets/images/2017-08-18-a-new-era-is-coming/screencapture-solidinvoice-clients-view-1-1503395394916.png
[3]: {{ site.url }}/assets/images/2017-08-18-a-new-era-is-coming/screencapture-solidinvoice-invoices-view-1-1503396796414.png