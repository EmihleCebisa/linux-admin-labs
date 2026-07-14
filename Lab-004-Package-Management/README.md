# Lab 004 - File Ownership

## Objective

Learn how Linux file ownership works and how to change file owners and groups using ownership management commands.

## Difficulty

Beginner

## Estimated Time

20–30 minutes

## Commands Practiced

* ls -l
* chown
* chgrp
* id

## Steps Performed

1. Created a test file.
2. Viewed file ownership using `ls -l`.
3. Verified user information using `id`.
4. Changed file ownership using `chown`.
5. Changed file group ownership using `chgrp`.
6. Verified ownership changes using `ls -l`.

## Ownership Concepts

Every file and directory in Linux has:

* An owner (user)
* An associated group

Example:

```text id="lh8h0e"
-rw-r--r-- 1 analyst cybersecurity 0 Jul 14 testfile.txt
```

Where:

* `analyst` is the file owner.
* `cybersecurity` is the file group.

## Commands Used

View ownership:

```bash id="y6i2u5"
ls -l
```

Change owner:

```bash id="v5gk4m"
sudo chown analyst testfile.txt
```

Change group:

```bash id="qovv1v"
sudo chgrp cybersecurity testfile.txt
```

Verify changes:

```bash id="w25h9l"
ls -l
```

## Screenshots

Add screenshots demonstrating:

* Initial file ownership
* User information with `id`
* Changing ownership with `chown`
* Changing group ownership with `chgrp`
* Verifying ownership changes

## Key Takeaways

* Every file has an owner and a group.
* Ownership controls who can manage files.
* `chown` changes ownership.
* `chgrp` changes group ownership.
* Ownership works together with permissions to control access.

## Skills Learned

* File ownership management
* User and group administration
* Linux access control fundamentals
* Command-line administration

