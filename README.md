# lainos_repo
A Pacman repository for the inclusion of Calamares installer during LainOS ISO build and for packages not included in the Arch Core, Extra, Community, and AUR repositories.

To use this repo, append this line to pacman.conf:
[lainos_repo]
SigLevel = Optional TrustAll
Server = https://github.com/The-LainOS-Project/lainos_repo/raw/main/X86_64/
