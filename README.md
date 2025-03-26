# watchparse
Watch Guard Firewall XML config Parser

# Export Configuration

Download the Configuration File

From Fireware Web UI, you can download your Firebox configuration to a compressed file. 

    Select System > Configuration File.
    The Configuration File page appears.
    Click Download the Configuration File.
    The Select location for download dialog box appears.
    Select a location to save the configuration file.

The configuration file is saved in a compressed (.GZ) file format. Before you can use the python script, you must use a utility such as Winzip or 7-zip to extract the file to a location on your computer. 

# Running the Parser

    Python3 parser.py <path of xml>
