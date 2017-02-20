# yellowpages

Reads from two YAML files to import a list of characters. base-contacts.yaml belongs in the data folder and yourname-contacts.yaml belongs in the profiles folder. Any information in yourname-contacts.yaml will take precedence over the base file.
These scripts must be trusted in order to read the contents of these files.

display-guild.lic uses the same code as textsubs to append a prefix in front of all known players. For example, syntyche the warmage will be displayed as W:Syntyche in all text. Bards will be prefixed with D: and thieves will be prefixed with X: to avoid letter conflicts.

yellowpages.lic requires a single name as an argument. It will then query the two yaml for that character and print out any information recorded about them.
