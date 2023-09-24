# InDesign GREP collection

Collection of useful InDesign GREP expressions for Find/Change queries used in my pre-press days.

# Installation
1. Backup your current setup
2. Copy files from GREPs folder to InDesign's Find-Change Queries/GREP folder.

## macOS
Users\[username]\Library\Preferences\Adobe InDesign\[Version]\[Language]\Find-Change Queries\[query type]

## Windows
Users\[username]\AppData\Roaming\Adobe\InDesign\[Version]\[Language]\Find-Change Queries\[query type]

# Usage
[Adobe has a pretty decent explanation](https://helpx.adobe.com/indesign/using/find-replace-grep-queries.html) of how to use GREP with Find/Change query panel. Use it at your own risk!

# Legend
You'll see some of the queries contains letters like [A], [M] or [O], to explain it shortly how I used to use them in my workflow:
- \[A] - find and change query can be completed without any intervention, you can use *Change All* in one go)
- \[M] - you'll want to use *Find Next* and *Change* each query based on your judgement (e.g. sometimes imported WordDocument contained inconsistencies)
- \[O] - totally optional step, e.g. sometimes a Word Document I've been given would contain two spaces/forced returns at the end of the paragraph and I'd usually remove them (more for a file hygiene reason)
- \[RTL] - Right To Left (a simple GREP looking for Latin script letters inside the RTL script)
- \[HB] - used for Hebrew script
- \[FR] - used for French language docs