# Privilege Escalation on Systems

**Privilehe Escalation** is the activity of exploiting vulnerabilities or misconfigurations in systems to elevate priveleges from one user to another, typically to a use with adminstrative or root privileges. 

#### Description of permissions and privileges in a system.

To start off, we have to be aware of something called the **__protection ring__**, the whole idea behind it is that in every system there is a layered or hierarchical protection and segregation mechanism used to provide different levels of access to functionality and resources on a system.

	Ring 3 === Least Priv === Applications
	
	Ring 2 ===	👇️    === Device Drivers
	
	Ring 1 ===	👇️    === Device Drivers
	
	Ring 0 === Most Priv   === Kernel

The protection ring is what detects how user privileges and permissions are assigned. It aids in specifying and enforcing the functionality of users on a system and their corresponding access to resources. 

Thus we are brought to the adoption of two main roles:

	- Privileged access
	- Unprivileged access
	
With all the above in mind, then our attention is brought to the types of privilege escalation. This essentially comes from the notion that in any given system there is always a privileged access user which tends to be 1 and multiple unprivileged access users.

The types of privilege escalation include:

	- Horizontal privilege escalation
	- Vertical privilege escalation
	
The duo are highly self-explanatory.

#### Understanding the differences between privilege escalation on Windows and Linux

![Diff between Window and Linux](/images/screenshot1.png)
