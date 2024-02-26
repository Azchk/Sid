# This is a Norwegian SIDs setup for EuroSscope plugin VFPC.
# Forked from https://github.com/beregor/Sid to make improvements and fix bugs:
- Major overhaul of all SIDs:
- Sorted airports alphabetically
- Sorted SIDs with omnidirectional and non-RNAV departures first, then directions clockwise from north, heli departures last.
- Added ALL airports with SIDs
- Updated all mandatory routes and restrictions according to Eurocontrol RAD. Keep in mind they are not all mandatory on Vatsim.
- ENBR restrictions fixed with mandatory DCT ZOL after TUXIL unless going to ENCN with DCT PEVEB after TUXIL
# The main plugin can be downloaded from https://github.com/hpeter2/VFPC
# Installation:
- Download and replace the sid.json file inside your plugins folder within EuroScope.
- If you are using the latest ES, it should be in: "C:\Users\ (username) \AppData\Roaming\EuroScope\ENOR\Plugins"
- If using older versions it is: "Documents\EuroScope\ENOR\Plugins"
- After installing use the command .vfpc reload
