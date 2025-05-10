# Update for game updates

Run, then press enter to use base game
```bash
python create_compatible_files.py
```
Done

# Update for mod updates
Run, then copy and paste the path to the local mod folder
```bash
python create_compatible_files.py
```
Move contents of created folder such as `2216659254` to a separate compatibility mod folder.
Some common ones are:

- CFP 
```
F:\SteamLibrary\steamapps\workshop\content\1158310\2220098919
```
- POD
```
F:\SteamLibrary\steamapps\workshop\content\1158310\2216659254
```
- LoTR, Realms in Exile
```
F:\SteamLibrary\steamapps\workshop\content\1158310\2291024373
```
- AGOT
```
F:\SteamLibrary\steamapps\workshop\content\1158310\2962333032
```

# Update for armature changes
Sometimes game updates changes the armature for the characters and will require converting existing meshes over.
Typically someone will create a script on the CK3 Mod Co-op discord channel to do this, and it will involve
moving blend scenes under a gendered folder tree and running a script there to convert all mesh recursively.