# This is a Norwegian setup for the EuroScope plugin VFPC.
# Features are:
- ALL Airports SIDs added
- Always Checking for ODD/EVEN rule and min/max alt restrictions
- Checking for FRA connecting routes and legal DCT (WIP)
- Checking for engine type on SIDs with multiple suffixes (ENVA, ENAT, ENGM)
- Checking for RNAV1 (WIP)
- OMNI SIDs added with all the same checks to facilitate non-RNAV aircraft and other abnormal departures. (WIP)
# Limitations:
- Always check the flightplan manually, this is meant as a tool to enhance correct flight plan completion. Not all restrictions need be simulated on vatsim.
- Restrictions and reroutes from RAD refrencing military and danger areas are NOT added.
- The applicable SID must be selected for the plugin to apply the correct checks.
- The plugin can not tell you why a route is incorrect.
- For ODD/EVEN to work, change the RFL in the flight plan, not in the list.
- VFR is not supported. Remember that max vfr altitude is FL285
- OTHER sid selection for Visual Departures is not added yet.
- Not yet implemented functionality for non-RVSM airspace above FL400 in ODD/EVEN checks. It will throw an error for FL430, FL470, FL510, Fl550 and so on as they are odd numbered but still correct for flying South and West.
# Installation:
- Download the plugin from https://github.com/hpeter2/VFPC and follow the installation instructions.
- Download and replace the sid.json file inside your plugins folder within EuroScope.
- If you are using the latest ES, it should be in: "C:\Users\ (username) \AppData\Roaming\EuroScope\ENOR\Plugins"
- If using older versions it is: "Documents\EuroScope\ENOR\Plugins"
- After installing use the command .vfpc reload
