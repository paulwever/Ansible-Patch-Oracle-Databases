Patch databases using Ansible

Provided roles will allow you to download patches, unzip them or mount them from a mountpoint,
update opatch, patch and datapatch databases. 

The configuration is done in group_vars/<your_group_name>.yml

please note the location when you don't let these roles unzip your patches:
unzip the patches in stage_dir/p_<<the_patch_number>>
this way the patch will be found by the scripts

