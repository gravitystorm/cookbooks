Opscode Public Cookbooks for Chef
=================================

This repository is the primary project source of Opscode's published, public cookbooks for Chef. This repository is considered "in development." Published cookbooks are shared by Opscode on the Chef Community Site.

* http://community.opscode.com/users/opscode

Cookbooks in this repository are only ones maintained and supported by Opscode.

Contributing
============

While this repository is hosted on GitHub, we do not use pull requests as the primary mechanism or workflow for contributions.

For information on how to contribute, see the CONTRIBUTING file in this repository.

Opscode cookbooks are distributed under the Apache 2 Software License. See LICENSE.

Using this Repository
=====================

Opscode does not recommend that you use this repository directly, either as a submodule or as a "canonical" repository. Chef Cookbooks are "packages" for managing resources in your infrastructure, and there are as many ways to manage the various pieces of software provided here as there are different infrastructures. These cookbooks reflect our opinions about the best ways to manage these infrastructure components with Chef.

We recommend you install our cookbooks into your Chef repository from the Chef Community site, and uploaded to your Chef Server with the command-line tool "knife".

    knife cookbook site install COOKBOOK
    knife cookbook upload COOKBOOK

Use of this repository is recommended for developers who wish to contribute fixes to Opscode's cookbooks.

Bugs
====

Like any software, there may be bugs in our cookbooks. You can open a ticket in the COOK project at:

* http://tickets.opscode.com

If you know the fix for the bug, you can contribute it. See the CONTRIBUTING file in this repository.

Do note that if you downloaded a cookbook from the community site that is not maintained by Opscode, you'll need to contact the maintainer of that cookbook for contributing fixes.

Links
=====

Chef Community Site:

* http://community.opscode.com

Cookbooks Project Source:

* http://github.com/opscode/cookbooks

Chef Repository Skeleton:

* http://github.com/opscode/chef-repo

Tickets/Issues (COOK project):

* http://tickets.opscode.com/

Chef Documentation:

* http://wiki.opscode.com/display/chef/Home/
* http://help.opscode.com
