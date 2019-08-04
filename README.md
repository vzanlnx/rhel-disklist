# rhel-disklist

A simple bash script which shows disk information.

 Usage:
 
	-l - Show all uniq devices attached to host with wwid and size in GB
	
	-t - Show volumetry sum in GB
	

 For environments with multipathing, it's useful because it doesn't show
 the duplicated wwid ones.

 ToDo:
 
	- Implement a way to identify what is the multipathing software being
	  used and show the device mapper name in the list
	- Modify check_linux_version to compare kernel versions instead OS nickname
	- Include sys_rhel8
	- Refactor the entire code, because this is an amateur piece of my learning path in
	  programming. blah!
	- Add suport for other linux servers distros.

Works in RHEL5, RHEL6 and RHEL7 environments. for Physical and Virtual servers.
