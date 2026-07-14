# Lab 005 - Package Management

## Objective

Learn how to install, update, upgrade, search for, and remove software packages using the APT package management system.

## Difficulty

Beginner

## Estimated Time

20–30 minutes

## Commands Practiced

* apt update
* apt upgrade
* apt install
* apt remove
* apt search
* apt list --installed

## Steps Performed

1. Updated the package repository information.
2. Checked for available package updates.
3. Searched for a software package.
4. Installed a package.
5. Verified the installation.
6. Listed installed packages.
7. Removed the package.
8. Verified package removal.

## Package Management Concepts

APT (Advanced Package Tool) is the package management system used by Ubuntu and Debian-based Linux distributions.

Common tasks include:

* Updating package information
* Installing software
* Removing software
* Upgrading the system
* Managing dependencies

## Commands Used

Update package information:

```bash
sudo apt update
```

Upgrade installed packages:

```bash
sudo apt upgrade
```

Search for a package:

```bash
apt search tree
```

Install a package:

```bash
sudo apt install tree
```

Verify installation:

```bash
tree --version
```

List installed packages:

```bash
apt list --installed
```

Remove a package:

```bash
sudo apt remove tree
```

## Screenshots

Add screenshots demonstrating:

* Updating package repositories
* Searching for a package
* Installing a package
* Verifying installation
* Listing installed packages
* Removing a package

## Key Takeaways

* APT simplifies software management.
* Package repositories provide trusted software sources.
* Packages can be installed, updated, and removed from the terminal.
* Keeping systems updated is an important security practice.

## Skills Learned

* Package management
* Software installation
* System maintenance
* Linux administration fundamentals

