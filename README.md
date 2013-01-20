profile-backup-scripts
======================

A couple bash scripts I use to backup my user profile using rsync. 

to-HDD sends my profile from the SSD in my computer to the HDD every day. It keeps a bunch of copies (currently 60), and uses hard links instead of making copies of identical files. 

to-desktop sends a backup of my HDD over ssh to another computer and updates the copy there. I run this one manually around weekly. The HDD contains my profile backups, iTunes library, iPhoto library, and other big stuff. I use exclusions to only send the most recent profile backup. 
