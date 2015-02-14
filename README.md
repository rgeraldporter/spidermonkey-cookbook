spidermonkey-cookbook
=====================

Very basic Chef cookbook for spidermonkey on CentOS or Ubuntu. Forked from <https://github.com/cloudant/cloudant_cookbooks>, which was missing required parameters for the latest version of Chef Solo, and generally very out of date. 

Vagrant Setup 
=============

In your Vagrant role file, add

    "recipe[spidermonkey]"
    
to your `run_list`.

Notes
=====

Untested thus far on Ubuntu, but should work.