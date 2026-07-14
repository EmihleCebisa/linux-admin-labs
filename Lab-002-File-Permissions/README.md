# Lab 002 - File Permissions

## Objective

Learn how Linux file permissions control access to files and directories and how to modify permissions using command-line tools.

## Commands Practiced

* ls -l
* chmod
* chown
* groups
* id

## Steps Performed

1. Viewed file permissions using `ls -l`.
2. Identified user and group information using `id`.
3. Displayed group memberships using `groups`.
4. Modified file permissions using `chmod`.
5. Verified permission changes using `ls -l`.
6. Examined file ownership using `ls -l`.

## Permission Breakdown

Linux permissions are represented as:

```text
-rwxr-xr--
```

Where:

* First character indicates file type.
* First set of three characters represents owner permissions.
* Second set represents group permissions.
* Third set represents permissions for others.

Permission values:

| Permission  | Value |
| ----------- | ----- |
| Read (r)    | 4     |
| Write (w)   | 2     |
| Execute (x) | 1     |

Examples:

| Numeric | Meaning                                    |
| ------- | ------------------------------------------ |
| 777     | Full access for everyone                   |
| 755     | Owner full access, others read and execute |
| 644     | Owner read/write, others read only         |

## Screenshots

Add screenshots demonstrating:

* Viewing permissions with `ls -l`
* Viewing user information with `id`
* Viewing group memberships with `groups`
* Changing permissions using `chmod`
* Verifying updated permissions using `ls -l`

## Skills Learned

* Understanding Linux permission structure
* Managing file access
* Reading permission notation
* Using numeric permission values
* Basic ownership and access control concepts

