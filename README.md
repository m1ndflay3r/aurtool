# Aurtool
***Simple bash based aur management utility.***




this project depends on package-query, which aurtool will install automatically on first run






<h4>Setup instructions</h4>

---------------------------------------------------------------------------------------------------------------------


<h5>step 1</h5>

- clone this repository:

- ``` git clone https://github.com/m1ndflay3r/aurtool ```

- ``` cd aurtool ```


<h5>step 2</h5>

- launch aurtool!

- ``` ./aurtool --help ```


<h4>Usage:</h4>


- ***-S*** : install package(s) from AUR by-name. Supports multiple operands.

- ``` aurtool -S packagename ```


- ***-SS*** : install a package, trying pacman first, and AUR if pacman fails.

- ``` aurtool -SS packagename ```


- ***-Ss*** : search the AUR for a package by name.

- ``` aurtool -Ss packagename ```


- ***-Sss*** : search both repositories and AUR for package by name

- ``` aurtool -Sss packagename ```


- ***-R*** : remove a package

- ``` aurtool -R packagename ```


- ***-Sy*** : check for updates to installed AUR packages.

- ``` aurtool -Sy ```


- ***-Syu*** : check for updates to AUR packages and install any that are available

- ``` aurtool -Syu ```


- ***-Syyu*** : check for updates to both AUR + repository packages and install any that are available

- ``` aurtool -Syyu ```


- ***--help*** : show help information

- ``` aurtool --help ```


- ***--version*** : show versioninfo

- ``` aurtool --version ```
