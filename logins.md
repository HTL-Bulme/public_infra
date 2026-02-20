# Uses Logins

At HTL Bulme, we currently have two parallel directory services, LDAP and AD.
Users may have two distinct passwords - one for each system. The following
table provides an overview of which password to use for which service.

|                 | **LDAP**                | **AD**             |
| --------------- | ----------------------- | ------------------ |
| Username        | firstname.lastname      | firstname.lastname |
| Email Address   | ??@bulme.at             | ??@ms.bulme.at     |
| Student Webmail | [mymail.bulme.at][1]    | office.com         |
| Teacher Webmail | [webmail.bulme.at][2]   | office.com         |
| Computer logins | Linux Clients           | Windows Clients    |
|                 | Linux Servers, eg.      |                    |
|                 | [sandbox.bulme.at][7]   |                    |
|                 | [schueler.bulme.at][8]  |                    |
| Other services  | [ekb.bulme.at][3]       | Wifi               |
|                 | [gwp.bulme.at][4]       |                    |
|                 | [moodle.bulme.at][5]    | eduvidual.at       |
|                 | [nextcloud.bulme.at][6] |                    |

Please note that the username for office.com (et al.) as well as eduvidual is
<kbd>firstname.lastname@ms.bulme.at</kbd> instead.

## Changing the LDAP Password

There are multiple ways of changing the LDAP password. In our Linux computer
labs or when working on a Linux server, the password can be changed after
logging using the

```shell
passwd
```

command in a terminal.

To change the password via a web-based GUI, please log in to our webmail
system and change the password there. The direct link for changing passwords
is

|          | Link for Changing the Password |
| -------- | ------------------------------ |
| Students | [https://mymail.bulme.at/?_task=settings&_action=plugin.password][9] |
| Teachers | [https://webmail.bulme.at/?_task=settings&_action=plugin.password][10] |


[1]: https://mymail.bulme.at
[2]: https://webmail.bulme.at
[3]: https://ekb.bulme.at
[4]: https://gwp.bulme.at
[5]: https://moodle.bulme.at
[6]: https://nextcloud.bulme.at
[7]: https://sandbox.bulme.at
[8]: https://schueler.bulme.at
[9]: https://mymail.bulme.at/?_task=settings&_action=plugin.password
[10]: https://webmail.bulme.at/?_task=settings&_action=plugin.password
