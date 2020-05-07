# Anirath's Dotfiles #

**Homepage -- [anirath.github.io/dotfiles][1]**

**GitHub   -- [anirath/dotfiles][8]**

## WARNING ##
*This project of mine is just beginning, so expect this **Readme** as well as the rest of the project to be*
*incomplete. So, I don't recommend following any of this documentation, or even attempting to use any of*
*these files at all, while I am still developing this project. When things are in a generally functional*
*state this **Readme** will be updated to remove this warning as well as contain valid and helpful info.*

## README ##
[This collection][1] of [dotfiles][2] is used in my own config, but is available to the public so anyone who
wants to may use them both *privately* or *commercially*. I don't mind at all! All of the actual files can be
found in the various subdirectories under `./src/`. A potential user can either manually pick and choose then
install the files of their choice, or one could simply run the included [install script](install.sh) to
automatically install their chosen files.

## Install ##
Installing these [dotfiles][2] is fairly simple, and there are essentially two different methods for this.
But, before anything your first step will be to download the project.

### Download ###
*There are three methods for downloading the files:*
- **Method 1** *(Invalid for Now)* -- Download one of the [releases][9], and extract the *downloaded archive*.
- **Method 2** -- Clone the repository: `git clone https://github.com/anirath/dotfiles.git anirath_dotfiles`.
- **Method 3** *(Recommended)* -- Fork the repository and clone your new fork.

### Install ###
*There are two methods for installing the files:*
- **Automated Install** -- After downloading the files you can run the included [install script](install.sh).
The script will prompt the user through installing the files of their choice, and allows for a limited bit of
custom configuration.
- **Manual Install** -- If you would like to only use certain files, and you don't want to run the automated
script, you can also browse through the various files contained in `./src/` to find which files you want.
Then, you just have to copy or move the selected files into their particular locations.
*(You can find the default expected location for a file in the first couple lines of the code.)*

### Project Resources ###
**Online Links**
1. [Anirath @ GitHub][7] -- [GitHub][6] page, and general *homepage*, for the developer **Anirath**.
2. [Git Repository][8] -- The main repository for this project hosted on [GitHub][6].
3. [Project Homepage][1] -- The *homepage* for this project.

**File Links**
1. [Readme](docs/readme.md) -- The main **Readme** document *(i.e. this file)*.
2. [License](docs/license.md) -- The *license* used by this project.
3. [Docs](docs/) -- Project's documentation directory.
4. [Source](src/) -- The *source* files for the project.
5. [Install Script](install.sh) -- Automated install via executing this script.

### External Resources ###
1. [Intro to Dotfiles][3] -- An article hosted on [thoughtbot.com][4] introducing [dotfiles][2].
2. [GitHub Dotfiles][5] -- The unofficial guide to dotfiles on [GitHub][6].

[1]: https://anirath.github.io/dotfiles/
[2]: https://en.wikipedia.org/wiki/Hidden_file_and_hidden_directory
[3]: https://thoughtbot.com/upcase/videos/intro-to-dotfiles
[4]: https://thoughtbot.com/
[5]: https://dotfiles.github.io/
[6]: https://www.github.com/
[7]: https://anirath.github.io/
[8]: https://github.com/anirath/dotfiles
[9]: https://github.com/anirath/dotfiles/releases
