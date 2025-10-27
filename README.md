# HuSSHLog
Pronounced "Hush Log", this is a super small, lightweight, ans basic terminal based ham radio logger built in Python. Designed with SSH in mind!

Tried to capture the vibes of DOS loggers, while still making it platform agnostic. There is six included color pallets 
(Cyan, Amber, Red, Grey, DOS-Amber, and DOS-Green), and documentation for creating your own is soon to come.

Logbooks are stored as CSVs to avoid databases, and included is the ability to export as ab ADIF.

Expect some UI tweaking, and additions such as POTA and Field Day templates.


## Information
Syntax: `HuSSHLog.py <logbook_name>`

> [!NOTE]
> The logbook.csv and ADIF exports will be in the same directory as the program. It is recommended to create a seperate directory for this program.

> [!IMPORTANT]
> If atempting to run on Windows, you will need to build [python-curses-build](https://github.com/cgohlke/python-curses-build) as the official module is not supported on Windows.


## Looking forward
Below are some milestone I hope to achieve

- [X] Create more complete documentation (Ongoing)
- [ ] [Adding POTA template](https://github.com/DomTheDorito/husshlog/issues/2)
- [ ] Add fallback for unsupported curses module in Windows environments
- [ ] Add multi-window support (ASCII map view, etc)
- [ ] Optional networking
- [ ] Ability to upload directly to QRZ

