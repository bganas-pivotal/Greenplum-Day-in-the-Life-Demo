Greenplum-Day-in-the-Life-Demo
==============================

Artifacts for spinning up this demo

------------------------------------
-- INTRODUCTION
------------------------------------
--  This is the "Day-in-the-Life" demo used by Central FE for prospects new to Greenplum/MPP database. 
--  Its most effective when executed on a 1/4 rack DCA.  This is designed to be easily portable/re-creatable so demos can be spun-up quickly


--  1. The premise is to showcase how GPDB can address day-to-day tasks performed in typical DW/BI environments.  
--  2. This demo is most effective when put on a live DCA.  The data volumes should be big enough to make an SMP database struggle but small enough to have queries complete quickly.
--  3. Target audience includes DBA, BI team, Analysts,  heavy influencers.  
--  4. Designed for a 2.5 hour meeting.
--  5. This is an evolving script.
--  6. The accompanying .ppt is used to introduce each section.  The .ppt includes animated slides for those new to MPP

-- For ease, make a directory called /home/gpadmin/ditl and move all the demo files into it.


-- BIG Thanks to those who inspired this:  Matt Neglay, Austin Rutherford, and others!!
