Show Notes - #008 HA and DR All the Things  - 06/19/2014
===========================

Introduction
------------
*Chris* Welcome to Ops All The Things, your podcast for all things DevOps, SysAdmin and Operations.

*Chris* I'm Chris Webber

*Steve* and I'm Steve Murawski and this show is being recorded on June 19th, 2014.

*Chris* And this podcast is sponsored by Chef.

News
----

* *Chris* [Joyent Outage](http://www.joyent.com/blog/postmortem-for-outage-of-us-east-1-may-27-2014)
* *Chris* [Supermarket Launch](https://supermarket.getchef.com)
* *Steve* [DSC Resource Kit Wave 4 is Live](http://blogs.msdn.com/b/powershell/archive/2014/06/06/dsc-resource-kit-wave-4-is-live.aspx)


Main Topic
----------

HA and DR All The Things

* Discuss what DR, HA and the kind of in between states are
  * Includes continuous availability
  * Hot spare / warm spare / cold spare
* Why are you doing backups?
  * and no, RAID is not a backup
* What even is a cluster?
* Acronym Soup
  * SLA
  * MTBF (Mean time between failure) (Etsy's talk)
  * MTTR (Mean time to repair/recovery)
  * MTTD (mean time to discovery)
  * RPO (recovery point objective)
  * RTO (recovery time objective)
* Disaster Recovery
  * Planning
  * Exercises
  * Purpose and goals
    * Get into what does the business actually need (ie working email vs restore of all email)
  * Security to boot
* HA
  * Almost always adds complexity
* Discuss state and how it messes with things
* Use the cloud to illustrate levels of redundancy
* Discuss SPOFs and why they may or may not be bad

NOTES:
--------
[Web Operations book](http://www.amazon.com/Web-Operations-Keeping-Data-Time/dp/1449377440)

Closing
-------
Thanks for joining us for Ops All The Things.  If you have questions, comments, or other feedback, you can find us at <http://www.opsallthethings.com> or on twitter as @opsallthethings.
