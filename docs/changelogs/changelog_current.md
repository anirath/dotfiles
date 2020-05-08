# Anirath's Dotfiles #
**Changelog -- v0.1**
*Modified: 2020.05.08*

## Added ##
### 2020.05.07 ###
- Created a subdirectory in `docs/` for containing any document templates. (`docs/templates/`)
- Another `docs/` subdirectory, but for all **changelogs**. (`docs/changelogs/`)
- Created a template for **changelogs**. (`docs/templates/changelog.md`)
- Created a working document for the current **changelog**. (`/docs/changelogs/changelog_current.md`)
#### 04:15 ####
- A new directory, `docs/readme/`, to the existing `docs/` directory to contain the *readmes* and *licenses*.
#### 04:49 ####
- An alternative **Readme** file, formatted differently, and saved as a `.txt` file. (`docs/readme/readme.txt`)
- Added a symlink to the new `docs/readme/readme.txt` file in the root directory. (`README`)
#### 05:07 ####
- Created a symlink in the project's root for the latest changelog. (`changelog.md`)
#### 18:00 ####
- Added associated files for configuring PyPi Python Packaging, SendGrid API & Python Libraries, and other
Python related files. (`setup.py`, `python_pkg/`, `tests/`, `.travis.yml`, and `sendgrid.env`)
- Created a **gitignore** file which will be developed as things go. (`.gitignore`)
- Created a **SendGrid API Key** for this project's new release notifier. (`sendgrid.env`)
- Created a **PyPi Token** for the entire account of **Anirath**. (`setup.py`)

## Removed ##
### 2020.05.07 ###
- The `license.md` file. It's essentially just pointless excess, so deprecated it.
### 2020.05.08 ###
- Changed mind about *Python Packaging*, **PyPi**, **SendGrid**, etc. So, I removed all relevant **Python**
related files. (`setup.py`, `python-pkg/`, `.travic.yml`, `sendgrid.env`, etc.)
#### 02:12 ####
- Removed the **Jekyll** config file used by **GH-Pages**. (`docs/_config.yml`)

## Changes ##
### 2020.05.07 ###
- Moved the existing `readme.md`, `license.md`, and `license.txt` files into the new `docs/readme/` directory.
#### 04:34 ####
- Updated the **Readme** and **License** symlinks in the root directory.
#### 04:47 ####
- Updated the new **changelog template**. (`docs/templates/changelog.md`)
#### 05:03 ####
- Fixed up the **changelog template** and updated the **current changelog** to match. (`../../changelog.md`)
#### 18:00 ####
- Configured and modified the files that were created for handling Python related data.
- Configured **SendGrid** functionality using this project's new API key. (`sendgrid.env`)
- Configured *Python Packaging* via **PyPi** using the newly generated account-wide token for **Anirath**.
### 2020.05.08 ###
- Reorganized the file structure after removing all of the **Python** related files.
#### 02:12 ####
- Reconfiguring it so that the **GH-Pages** publishing source will be in a new branch titles `gh-pages`. This
is also so the `docs/` directory can be used for building project documentation with **Sphinx**.

## Notes ##
### 2020.05.07 ###
Now that I've managed to pretty much finish the **bash** portion of **dotfiles** based on my existing ones
being used by **anirath** on [rishon@maarekhet][1] I would like to start work on the **install script**.
Obviously, won't be *anywhere* near finishing it soon, but it would be nice to get started on it at least for
the now existing **configs**.

[1]: https://rishon.ddns.net/
