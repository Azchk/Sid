# This is an Norwegian SIDs setup for EuroSscope plugin VFPC.
# Forked from https://github.com/beregor/Sid to make improvements and fix bugs:
- Major overhaul of all SIDs:
- Sorted airports alphabetically
- Sorted SIDs with omnidirectional, non-RNAV departures and Heli departures first, then directions clockwise from north.
- Added some airports and missing SIDs
- Updated all mandatory routes and restrictions according to Eurocontrol RAD. Keep in mind they are not all mandatory on Vatsim.
- ENBR restrcitions fixed with mandatory DCT ZOL after TUXIL unless going to ENCN with DCT PEVEB after TUXIL
# Main plugin can be downloaded from https://github.com/hpeter2/VFPC
# Installation:
# Download the file and replace the sid.json file inside you plugins folder within EuroScope.
# If you using latest ES, it should be in: "C:\Users\ (username) \AppData\Roaming\EuroScope\ENOR\Plugins"
# If using older versions it is: "Documents\EuroScope\ENOR\Plugins"
# After installing use command .vfpc reload
