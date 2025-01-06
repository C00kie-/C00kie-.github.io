---
title: "MISP quick start (VM)"
categories: [MISP, cheat sheets]
tags: [MISP, quick-start, CTI]
---
Here are a few steps to get started with MISP using a VM. 

Download a MISP VM: [https://vm.misp-project.org](https://vm.misp-project.org)

To access your instance in the browser, follow the ip adress and ports provided at boot (in the VM). MISP runs on port 443 or 8443.

To log into the MISP instance, use the installation default credentials.

*Username: admin@admin.test*

*Password: admin*

Before doing anything change the password immediatly.

Make a coffee.

```

      )  (
     (   ) )
      ) ( (
 mrf_______)_
 .-'---------|  
( C|/\/\/\/\/|
 '-./\/\/\/\/|
   '_________'
    '-------'

````

Then, follow these steps: 

- Go to: *Administration, Server settings and maintenance*, tab *Misp Settings*.

- Create a new organisation like MY ORGANISATION for this instance.

- You need then to indicate this organisation as the default one. For this, replace ‘MISP.host_org_id’. 

- To change the default message the users will see when connecting to an instance, set ‘MISP.footermidleft’ and ‘MISP.footermidright’ to display the message you want.

Users:

- Create a new user as admin role for MY ORGANISATION.

- Log out.

… Have a sip of coffee.

- Log in with the new user. Now you can remove the default user ‘admin@admin.test’.


Additionally:

It’s recommended that you select the taxonomies for you sharing community, as also the external feeds. You can select caching only if you don’t want the full events.

Also select and enable the warning list. You don’t want to block known ip for example. If you don’t know what that is, just select and enable all, it’s fine.

// add remote instances ... 

For more see : https://github.com/MISP/misp-book