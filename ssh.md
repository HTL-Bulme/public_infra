# SSH - Sandbox Server

HTL Bulme provides a designated Linux server that can be reached from
outside the Bulme network. This allows students and teachers to perform
programming tasks from home without installing any software on their
computers.

## Login
To log in to `sandbox`, type

```shell
ssh firstname.lastname@sandbox.bulme.at  # students
ssh shortcode@sandbox.bulme.at  # teachers
```

The password to log in to the service is the LDAP password (same as
webmail or ekb).

## Provided Tools

### Programming Languages
Currently, the available programming languages (compilers) and core tools are

| language   | compiler or interpreter                              |
|------------|------------------------------------------------------|
| C          | `gcc` (11.3.0), `clang` (14.0.0)                     |
| C++        | `g++` (11.3.0), `clang++` (14.0.0)                   |
| Go         | `go` (1.18.1)                                        |
| Python     | `python` (3.10.6), `ipython` (8.6.0), `pip` (22.3.1) |
| JavaScript | `node` (12.22.9), `yarnpkg` (1.22.10)                |

It is also possible to host (static) websites. To do so, place your files in
your `~/public_html/` (`mkdir ~/public_html/` if the directory doesn't exist).
Content can be copied to and from sandbox via the `sftp` and `fish`
protocols.

### Programming Editors
All common command-line editors are available on `sandbox`. These include
`emacs`, `jed`, `micro`, `nano`, `vi`, `vim`.

For new users, `micro` is clearly the recommended choice.


### Additional Tools and Libraries
If additional tools, programming languages and libraries are required,
contact `sg@bulme.at`. Tools that have approved open source licenses, do not
require x11 and are part of the official package manager can usually be
added.

## Restrictions
For now, we do not provide backups of the user's home directories of
`sandbox`. Please make sure to backup critical data yourself.

For now, there is no access to data stored on other Bulme servers.
