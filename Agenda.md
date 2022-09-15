
**09:00** - **NICOS wish list from each facility (70 minutes)**

- Each facility should compile some slides before the meeting on what development in NICOS they are interested in both short term (e.g. auto-formatting) and long term (e.g. SciCat integration).
- Discussions regarding these topics. We discuss these in an order based on priority and level of interest, that we decide on before the meeting.

**10:10** - **Coffee break (20 minutes)**
- Break for coffee and snacks.

**10:30** - **Continued discussions on NICOS wish lists**
Some suggested topics for discussion (some might also end up in the NICOS road map above).

`ESS`:
- SciCat integration.
- GUI developments (switch to PyQt6 and/or flow UI).
- Dry run in NICOS.
- Auto-formatting of NICOS code.
- Imaging daq scripts.
- Web UI.
- Road map.

`MLZ`:
- new cache backend (substitution of file based)
- file service
- new daemon protocol (http/websockets)
- easy switch between "real" and "virtual" instrument
- 'parameters' in GUI panels

`PSI`:
- GOD objects issue
- EPICS libraries (replacement of pyepics with caproto).
- Kafka library (confluent-kafka instead of kafka-python).
- GUI for imaging (starting with slider to limit range of intensity)
- Python versions officially supported
- Consolidation of the GUI
- Detach GUI form daemon
- User authentication/file permissions (LDAP, Posix)
- Workflow in Gerrit (please make specific example and suggest solutions, _e.g._ specify "if this commit will not be reviewed before ... will be automatically merged")
- Something that makes communications to the hardware easier (_e.g._ async server)


**12:00** - **Lunch**

