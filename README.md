# Aurtool
Simple bash based aur management utility. 




***IMPORTANT: This project depends on package-query, which is attainable via the AUR.***




<h4>Setup instructions</h4>

---------------------------------------------------------------------------------------------------------------------


<h5>step 1</h5>

- clone this repository:

- ``` git clone https://github.com/m1ndflay3r/aurtool ```


<h5>step 2</h5>

- cp aurtool to any location in your PATH, and mark it as executable

- ``` cp aurtool /bin/ ```

- ``` chmod 755 /bin/aurtool ```


<h5>step 3</h5>

- install package-query to enable all functions of aurtool and prevent strange issues

- ``` aurtool -S package-query ```


<h4>Usage:</h4>


- ***-S*** : install package(s) from AUR by-name. Supports multiple operands.

- ``` aurtool -S packagename ```


- ***-Ss*** : search the AUR for a package by name.

- ``` aurtool -Ss packagename ```


- ***-Sy*** : check for updates to installed AUR packages.

- ``` aurtool -Sy ```


- ***-Syu*** : check for updates to AUR packages and install any that are available

- ``` aurtool -Syu ```


- ***-Syyu*** : check for updates to both AUR + repository packages and install any that are available

- ``` aurtool -Syyu ```



