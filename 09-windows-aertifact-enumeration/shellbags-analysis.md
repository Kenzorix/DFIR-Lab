# ShellBags Analysis
## Overview
ShellBags are Windows Registry artifacts that can provide evidence of folders and directories accessed through Windows Explorer.
As part of this investigation, the ShellBags artifact was examined to understand filesystem interaction and identify evidence of previously accessed locations.

## Artifact Source
- **Registry Hive:** `NTUSER.DAT`
- **Artifact:** ShellBags
- **Artifact Type:** Windows Registry Artifact
- **Analysis Focus:** Folder and directory access

## Investigation Proces
1. Located the user's `NTUSER.DAT` registry hive.
2. Loaded the hive for forensic examination.
3. Navigated to the Registry locations associated with ShellBags.
4. Examined the available ShellBags entries.
5. Interpreted the entries to understand previously accessed folders and directories.

## Findings
The ShellBags artifact contained records associated with folders and directories that had been accessed through Windows Explorer.
These entries can provide useful context when reconstructing user activity during a Windows forensic investigation.

## Forensic Significance
ShellBags can assist investigators in reconstructing user interaction with the Windows filesystem.
They may provide evidence of previously accessed directories, including locations that may no longer be present on the system.
ShellBags should be interpreted alongside other Windows artifacts to build a more complete timeline of user activity.
