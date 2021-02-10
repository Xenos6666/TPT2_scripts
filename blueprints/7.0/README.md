# Blueprint

New and improved blueprint for TPT2 7.0, with its customized set of scripts.

*Doesn't work on regions that have elec, uni, dark and earth at the same time*

## Blueprint import code

`Ny4wIGluZmluaXR5IHB1c2g7aW5maW5pdHkuYXR0YWNrLnNwZWVkO2F0dGFjay5zcGVlZDthdHRhY2subXVsdGlzaG90O2F0dGFjay5ib3VuY2U7YXR0YWNrLnJhcGlkZmlyZTtpbmZpbml0eS5zcGxhc2g7c2FjcmlmaWNlLmRhcms7YXR0YWNrLmJhc2g7YXR0YWNrLnNwYXJrO3NoYXJkcy5pY2U7c3BsYXNoLmFpcjtzcGxhc2guZnJvc3Q7c3BlbGwubXVsdGlzaG90O2F0dGFjay5pY2VicmVhdGg7Y3JpdC5pbmZpbml0eTtjcml0LmVtZXJnZW5jeTtzdHJpa2Uuc29sYXI7YXR0YWNrLmRlYXRod2lzaDtkZWZlbnNlLnN0cmlrZWJhY2s7ZGVmZW5zZS5vdmVyY2hhcmdlO2F1cmEuZnJvc3Q7c3BlbGwuZGlzcGVsO2JhcnJpZXIudGVtcG9yYWw7ZGVmZW5zZS5zaGVsdGVyO2V2YXNpb24uYmFzaWM7ZGVmZW5zZS5kZWZpYW5jZTtkZWZlbnNlLmRhaWdvcGFycnk7YmxvY2suZGFya25lc3M7cmVnZW5lcmF0aW9uLnJlbGF0aXZlO3NoaWVsZC5iYXNpYztzaGllbGQudHJhbnNmb3JtYXRvcjthdXJhLmRlYXRoO2VuZXJneS5yZWdlbmVyYXRpb247Ym9udXMuY29uZGVuc2U7ZW5lcmd5Lm1vb247ZW5lcmd5LmJhc2ljO2VuZXJneS5yZWN5Y2xpbmc7eHAuYm9udXM7bXVsdGlzaG90LmZvY3VzZWQ7aW5maW5pdHkucmFuZ2U7ZGVmZW5zZS5zdG9uZXNraW47c2hpZWxkLmltbW9ydGFsaXR5O2Fpci5odXJyaWNhbmU7dG93ZXIuc3VwZXIuMjt0b3dlci5zdXBlci4xO3NoaWVsZC51bml2ZXJzYWw7ZGVmZW5zZS5idWx3YXJrO2FtcGxpZmllci5uZXV0cmFsO3Rvd2VyLnN1cGVyLjM7bWlzc2lsZS5zZXJpb3VzO2ZvdW5kYXRpb24uaW5maW5pdHk=`

## Scripts

### Requirements

- [Round modules](/modules/round)

### Scripts import codes

#### Load abilities settings

`F2xvYWQgYWJpbGl0aWVzIHNldHRpbmdzAAAAAAAAAAAJAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BA9zdXBlcl9tdWx0aXNob3QIY29uc3RhbnQCAQAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQOZGFua19zYWNyaWZpY2UIY29uc3RhbnQCAgAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQQdGVtcG9yYWxfYmFycmllcghjb25zdGFudAIDAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BAZkaXNwZWwIY29uc3RhbnQCBAAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQNc3VwZXJfdG93ZXJfMwhjb25zdGFudAIFAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BAtzdXBlcl90b3dlcghjb25zdGFudAIGAAAADmdsb2JhbC5pbnQuc2V0CGNvbnN0YW50BAlodXJyaWNhbmUIY29uc3RhbnQCBwAAAA5nbG9iYWwuaW50LnNldAhjb25zdGFudAQSaW1tb3J0YWxpdHlfc2hpZWxkCGNvbnN0YW50AggAAAAOZ2xvYmFsLmludC5zZXQIY29uc3RhbnQEDXN1cGVyX3Rvd2VyXzIIY29uc3RhbnQCCQAAAA==`


#### Abilities compute

`EWFiaWxpdGllcyBjb21wdXRlAAAAAAAAAAANAAAAEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBFkYW5rX3NhY3JpZmljZV9jZApkb3VibGUubWF4EWFyaXRobWV0aWMuZG91YmxlA2kyZA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQLcm91bmRfZ29pbmcIY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEEWRhbmtfc2FjcmlmaWNlX2NkCGNvbnN0YW50BAEtEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAtyb3VuZF9kZWx0YQhjb25zdGFudAMAAAAAAAAAABFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQJZGlzcGVsX2NkCmRvdWJsZS5tYXgRYXJpdGhtZXRpYy5kb3VibGUDaTJkDmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAtyb3VuZF9nb2luZwhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQJZGlzcGVsX2NkCGNvbnN0YW50BAEtEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAtyb3VuZF9kZWx0YQhjb25zdGFudAMAAAAAAAAAABFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQSc3VwZXJfbXVsdGlzaG90X2NkCmRvdWJsZS5tYXgRYXJpdGhtZXRpYy5kb3VibGUDaTJkDmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAtyb3VuZF9nb2luZwhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQSc3VwZXJfbXVsdGlzaG90X2NkCGNvbnN0YW50BAEtEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAtyb3VuZF9kZWx0YQhjb25zdGFudAMAAAAAAAAAABFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQVaW1tb3J0YWxpdHlfc2hpZWxkX2NkCmRvdWJsZS5tYXgRYXJpdGhtZXRpYy5kb3VibGUDaTJkDmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAtyb3VuZF9nb2luZwhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQVaW1tb3J0YWxpdHlfc2hpZWxkX2NkCGNvbnN0YW50BAEtEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAtyb3VuZF9kZWx0YQhjb25zdGFudAMAAAAAAAAAABFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQbaW1tb3J0YWxpdHlfc2hpZWxkX2R1cmF0aW9uCmRvdWJsZS5tYXgRYXJpdGhtZXRpYy5kb3VibGUDaTJkDmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAtyb3VuZF9nb2luZwhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQbaW1tb3J0YWxpdHlfc2hpZWxkX2R1cmF0aW9uCGNvbnN0YW50BAEtEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAtyb3VuZF9kZWx0YQhjb25zdGFudAMAAAAAAAAAABFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQTdGVtcG9yYWxfYmFycmllcl9jZApkb3VibGUubWF4EWFyaXRobWV0aWMuZG91YmxlA2kyZA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQLcm91bmRfZ29pbmcIY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEE3RlbXBvcmFsX2JhcnJpZXJfY2QIY29uc3RhbnQEAS0RZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEC3JvdW5kX2RlbHRhCGNvbnN0YW50AwAAAAAAAAAAEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBl0ZW1wb3JhbF9iYXJyaWVyX2R1cmF0aW9uCmRvdWJsZS5tYXgRYXJpdGhtZXRpYy5kb3VibGUDaTJkDmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BAtyb3VuZF9nb2luZwhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQZdGVtcG9yYWxfYmFycmllcl9kdXJhdGlvbghjb25zdGFudAQBLRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQLcm91bmRfZGVsdGEIY29uc3RhbnQDAAAAAAAAAAARZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEDGh1cnJpY2FuZV9jZApkb3VibGUubWF4EWFyaXRobWV0aWMuZG91YmxlA2kyZA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQLcm91bmRfZ29pbmcIY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEDGh1cnJpY2FuZV9jZAhjb25zdGFudAQBLRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQLcm91bmRfZGVsdGEIY29uc3RhbnQDAAAAAAAAAAARZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEEHN1cGVyX3Rvd2VyXzJfY2QKZG91YmxlLm1heBFhcml0aG1ldGljLmRvdWJsZQNpMmQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEC3JvdW5kX2dvaW5nCGNvbnN0YW50BAEqEWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBBzdXBlcl90b3dlcl8yX2NkCGNvbnN0YW50BAEtEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAtyb3VuZF9kZWx0YQhjb25zdGFudAMAAAAAAAAAABFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQWc3VwZXJfdG93ZXJfMl9kdXJhdGlvbgpkb3VibGUubWF4EWFyaXRobWV0aWMuZG91YmxlA2kyZA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQLcm91bmRfZ29pbmcIY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFnN1cGVyX3Rvd2VyXzJfZHVyYXRpb24IY29uc3RhbnQEAS0RZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEC3JvdW5kX2RlbHRhCGNvbnN0YW50AwAAAAAAAAAAEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBJzdXBlcl90b3dlcl8xXzNfY2QKZG91YmxlLm1heBFhcml0aG1ldGljLmRvdWJsZQNpMmQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEC3JvdW5kX2dvaW5nCGNvbnN0YW50BAEqEWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBJzdXBlcl90b3dlcl8xXzNfY2QIY29uc3RhbnQEAS0RZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEC3JvdW5kX2RlbHRhCGNvbnN0YW50AwAAAAAAAAAAEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24KZG91YmxlLm1heBFhcml0aG1ldGljLmRvdWJsZQNpMmQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEC3JvdW5kX2dvaW5nCGNvbnN0YW50BAEqEWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24IY29uc3RhbnQEAS0RZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEC3JvdW5kX2RlbHRhCGNvbnN0YW50AwAAAAAAAAAADGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAAAAAA==`


#### Abilities

`CWFiaWxpdGllcwAAAAAAAAAABwAAABNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BBJzdXJ2aXZhbCBhYmlsaXRpZXMMZ2VuZXJpYy5zdG9wCGNvbnN0YW50BBFzdXZpdmFsIGFiaWxpdGllcxNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BBBhdHRhY2sgYWJpbGl0aWVzDGdlbmVyaWMuc3RvcAhjb25zdGFudAQQYXR0YWNrIGFiaWxpdGllcxNnZW5lcmljLmV4ZWN1dGVzeW5jCGNvbnN0YW50BA5zcGFtIGFiaWxpdGllcwxnZW5lcmljLnN0b3AIY29uc3RhbnQEDnNwYW0gYWJpbGl0aWVzDGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAAAAAA==`


#### Survival abilities

`EnN1cnZpdmFsIGFiaWxpdGllcwAAAAAAAAAAEwAAAA5nZW5lcmljLmdvdG9pZghjb25zdGFudAIFAAAAEWNvbXBhcmlzb24uZG91YmxlEWFyaXRobWV0aWMuZG91YmxlCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFWltbW9ydGFsaXR5X3NoaWVsZF9jZBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQZdGVtcG9yYWxfYmFycmllcl9kdXJhdGlvbghjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASoIY29uc3RhbnQDZmZmZmZm5j8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAABAf0AIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8IY29uc3RhbnQEAS0MdG93ZXIuZW5lcmd5CGNvbnN0YW50AQAIY29uc3RhbnQEASsRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFXRvd2VyX3Jlc2VydmVkX2VuZXJneQhjb25zdGFudAQBPghjb25zdGFudAMAAAAAAAAAABd0b3dlci5tb2R1bGUudXNlaW5zdGFudA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQSaW1tb3J0YWxpdHlfc2hpZWxkEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBVpbW1vcnRhbGl0eV9zaGllbGRfY2QRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDx0s3iUEAMkAIY29uc3RhbnQEASsRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEE3RlbXBvcmFsX2JhcnJpZXJfY2QRZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEG2ltbW9ydGFsaXR5X3NoaWVsZF9kdXJhdGlvbghjb25zdGFudAMAAAAAAAAYQBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAR0aW1lEWFyaXRobWV0aWMuZG91YmxlCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFWltbW9ydGFsaXR5X3NoaWVsZF9jZBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQZdGVtcG9yYWxfYmFycmllcl9kdXJhdGlvbghjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAADwPwhjb25zdGFudAQBKxFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAAAIQAhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZQpkb3VibGUubWluEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBZzdXBlcl90b3dlcl8yX2R1cmF0aW9uCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFWltbW9ydGFsaXR5X3NoaWVsZF9jZBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQZdGVtcG9yYWxfYmFycmllcl9kdXJhdGlvbghjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFWltbW9ydGFsaXR5X3NoaWVsZF9jZBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQZdGVtcG9yYWxfYmFycmllcl9kdXJhdGlvbghjb25zdGFudAQBLQpkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBBzdXBlcl90b3dlcl8yX2NkEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24IY29uc3RhbnQEAS8KZG91YmxlLm1heApkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBVpbW1vcnRhbGl0eV9zaGllbGRfY2QRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEGXRlbXBvcmFsX2JhcnJpZXJfZHVyYXRpb24IY29uc3RhbnQDlWR54X/9pT0QbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQLbW9vbl9jdXRvZmYKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAAApkb3VibGUubWluEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEBHRpbWURYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAAFEAIY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAAAEAIY29uc3RhbnQEAS0KZG91YmxlLm1heAhjb25zdGFudAPNzMzMzMzsPxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAAAAQAhjb25zdGFudAQBKgx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAQhjb25zdGFudAQDbG9nEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAFlEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEDmVuZXJneV9mb3JtdWxhEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAFlCGNvbnN0YW50BANwb3cRYXJpdGhtZXRpYy5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQLbW9vbl9jdXRvZmYIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyb8IY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGUMdG93ZXIuZW5lcmd5CGNvbnN0YW50AQAIY29uc3RhbnQEASsRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEAWUIY29uc3RhbnQEA3BvdxFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAttb29uX2N1dG9mZghjb25zdGFudAQBKghjb25zdGFudAOamZmZmZnJPwhjb25zdGFudAQBLQhjb25zdGFudAMAAAAAAADwPwhjb25zdGFudAQBKhB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAErEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEAS8IY29uc3RhbnQDAAAAAAAAJEAIY29uc3RhbnQEASoKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAR0aW1lCGNvbnN0YW50BAEtEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEC21vb25fY3V0b2ZmEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBV0b3dlcl9yZXNlcnZlZF9lbmVyZ3kRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFXRvd2VyX3Jlc2VydmVkX2VuZXJneQhjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASoIY29uc3RhbnQDZmZmZmZm5j8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAABAf0AIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8IY29uc3RhbnQEAS0KZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BA5lbmVyZ3lfZm9ybXVsYQhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBLRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQUdG93ZXJfcGxhbm5lZF9lbmVyZ3kRZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEFHRvd2VyX3BsYW5uZWRfZW5lcmd5EWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBR0b3dlcl9wbGFubmVkX2VuZXJneQhjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAACmRvdWJsZS5taW4RYXJpdGhtZXRpYy5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQOZW5lcmd5X2Zvcm11bGEIY29uc3RhbnQEAS0MdG93ZXIuZW5lcmd5CGNvbnN0YW50AQARYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUMdG93ZXIuZW5lcmd5CGNvbnN0YW50AQAIY29uc3RhbnQEASoIY29uc3RhbnQDZmZmZmZm5j8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAABAf0AIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8IY29uc3RhbnQEAS0KZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BA5lbmVyZ3lfZm9ybXVsYQhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBLRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAEqCGNvbnN0YW50A2ZmZmZmZuY/CGNvbnN0YW50BAErCGNvbnN0YW50AwAAAAAAQH9ACGNvbnN0YW50BAEqCGNvbnN0YW50AzMzMzMzM+M/DmdlbmVyaWMuZ290b2lmCGNvbnN0YW50Ag4AAAARY29tcGFyaXNvbi5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUKZG91YmxlLm1heBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQbaW1tb3J0YWxpdHlfc2hpZWxkX2R1cmF0aW9uEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBN0ZW1wb3JhbF9iYXJyaWVyX2NkCGNvbnN0YW50BAErCmRvdWJsZS5tYXgIY29uc3RhbnQDAAAAAAAAAAARYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBKghjb25zdGFudAN7FK5H4XqEPwhjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAIizQAhjb25zdGFudAQBKghjb25zdGFudAMzMzMzMzPjPwhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBKxFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQVdG93ZXJfcmVzZXJ2ZWRfZW5lcmd5CGNvbnN0YW50BAE+CGNvbnN0YW50AwAAAAAAAAAAF3Rvd2VyLm1vZHVsZS51c2VpbnN0YW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BBB0ZW1wb3JhbF9iYXJyaWVyEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBN0ZW1wb3JhbF9iYXJyaWVyX2NkCGNvbnN0YW50AwAAAAD0OSNBEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBl0ZW1wb3JhbF9iYXJyaWVyX2R1cmF0aW9uCGNvbnN0YW50AwAAAAAAAD5AEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEBHRpbWURYXJpdGhtZXRpYy5kb3VibGUKZG91YmxlLm1heBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQbaW1tb3J0YWxpdHlfc2hpZWxkX2R1cmF0aW9uEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBN0ZW1wb3JhbF9iYXJyaWVyX2NkCGNvbnN0YW50BAEqEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50AwAAAAAAAPA/CGNvbnN0YW50BAErEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50AwAAAAAAAAhACGNvbnN0YW50BAEqEWFyaXRobWV0aWMuZG91YmxlCmRvdWJsZS5taW4RZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFnN1cGVyX3Rvd2VyXzJfZHVyYXRpb24KZG91YmxlLm1heBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQbaW1tb3J0YWxpdHlfc2hpZWxkX2R1cmF0aW9uEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBN0ZW1wb3JhbF9iYXJyaWVyX2NkCGNvbnN0YW50BAErCmRvdWJsZS5tYXgIY29uc3RhbnQDAAAAAAAAAAARYXJpdGhtZXRpYy5kb3VibGUKZG91YmxlLm1heBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQbaW1tb3J0YWxpdHlfc2hpZWxkX2R1cmF0aW9uEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBN0ZW1wb3JhbF9iYXJyaWVyX2NkCGNvbnN0YW50BAEtCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEEHN1cGVyX3Rvd2VyXzJfY2QRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEGHN1cGVyX3Rvd2VyXzFfM19kdXJhdGlvbghjb25zdGFudAQBLwpkb3VibGUubWF4CmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEG2ltbW9ydGFsaXR5X3NoaWVsZF9kdXJhdGlvbhFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQTdGVtcG9yYWxfYmFycmllcl9jZAhjb25zdGFudAOVZHnhf/2lPRBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAttb29uX2N1dG9mZgpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAACmRvdWJsZS5taW4QbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQEdGltZRFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAAAUQAhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAAAAQAhjb25zdGFudAQBLQpkb3VibGUubWF4CGNvbnN0YW50A83MzMzMzOw/EWFyaXRobWV0aWMuZG91YmxlCGNvbnN0YW50AwAAAAAAAABACGNvbnN0YW50BAEqDHRvd2VyLmVuZXJneQhjb25zdGFudAEBCGNvbnN0YW50BANsb2cRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEAWUQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQOZW5lcmd5X2Zvcm11bGERYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEAWUIY29uc3RhbnQEA3BvdxFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAttb29uX2N1dG9mZghjb25zdGFudAQBKghjb25zdGFudAOamZmZmZnJvwhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBKxFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQBZQhjb25zdGFudAQDcG93EWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEC21vb25fY3V0b2ZmCGNvbnN0YW50BAEqCGNvbnN0YW50A5qZmZmZmck/CGNvbnN0YW50BAEtCGNvbnN0YW50AwAAAAAAAPA/CGNvbnN0YW50BAEqEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASsRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBLwhjb25zdGFudAMAAAAAAAAkQAhjb25zdGFudAQBKgpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEBHRpbWUIY29uc3RhbnQEAS0QbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQLbW9vbl9jdXRvZmYRZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEFXRvd2VyX3Jlc2VydmVkX2VuZXJneRFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQVdG93ZXJfcmVzZXJ2ZWRfZW5lcmd5CGNvbnN0YW50BAErCmRvdWJsZS5tYXgIY29uc3RhbnQDAAAAAAAAAAARYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBKghjb25zdGFudAN7FK5H4XqEPwhjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAIizQAhjb25zdGFudAQBKghjb25zdGFudAMzMzMzMzPjPwhjb25zdGFudAQBLQpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEDmVuZXJneV9mb3JtdWxhCGNvbnN0YW50BAEtDHRvd2VyLmVuZXJneQhjb25zdGFudAEACGNvbnN0YW50BAEtEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBR0b3dlcl9wbGFubmVkX2VuZXJneRFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQUdG93ZXJfcGxhbm5lZF9lbmVyZ3kRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFHRvd2VyX3BsYW5uZWRfZW5lcmd5CGNvbnN0YW50BAErCmRvdWJsZS5tYXgIY29uc3RhbnQDAAAAAAAAAAAKZG91YmxlLm1pbhFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BA5lbmVyZ3lfZm9ybXVsYQhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBABFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAEqCGNvbnN0YW50A3sUrkfheoQ/CGNvbnN0YW50BAErCGNvbnN0YW50AwAAAAAAiLNACGNvbnN0YW50BAEqCGNvbnN0YW50AzMzMzMzM+M/CGNvbnN0YW50BAEtCmRvdWJsZS5tYXgIY29uc3RhbnQDAAAAAAAAAAARYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQOZW5lcmd5X2Zvcm11bGEIY29uc3RhbnQEAS0MdG93ZXIuZW5lcmd5CGNvbnN0YW50AQAIY29uc3RhbnQEAS0RYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBKghjb25zdGFudAN7FK5H4XqEPwhjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAIizQAhjb25zdGFudAQBKghjb25zdGFudAMzMzMzMzPjPwxnZW5lcmljLndhaXQIY29uc3RhbnQDAAAAAAAAAAA=`


#### Attack abilities

`EGF0dGFjayBhYmlsaXRpZXMAAAAAAAAAABQAAAAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCBgAAABFjb21wYXJpc29uLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZQpkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBJzdXBlcl90b3dlcl8xXzNfY2QRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFnN1cGVyX3Rvd2VyXzJfZHVyYXRpb24IY29uc3RhbnQEASsKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAEqCGNvbnN0YW50A5qZmZmZmck/CGNvbnN0YW50BAErCGNvbnN0YW50AwAAAAAAQJ9ACGNvbnN0YW50BAEqCGNvbnN0YW50AzMzMzMzM+M/CGNvbnN0YW50BAEtDHRvd2VyLmVuZXJneQhjb25zdGFudAEACGNvbnN0YW50BAErEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBV0b3dlcl9yZXNlcnZlZF9lbmVyZ3kIY29uc3RhbnQEAT4IY29uc3RhbnQDAAAAAAAAAAAXdG93ZXIubW9kdWxlLnVzZWluc3RhbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEC3N1cGVyX3Rvd2VyF3Rvd2VyLm1vZHVsZS51c2VpbnN0YW50Dmdsb2JhbC5pbnQuZ2V0CGNvbnN0YW50BA1zdXBlcl90b3dlcl8zEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBJzdXBlcl90b3dlcl8xXzNfY2QIY29uc3RhbnQDeekmMQhAZEARZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEGHN1cGVyX3Rvd2VyXzFfM19kdXJhdGlvbghjb25zdGFudAMAAAAAAABUQBBsb2NhbC5kb3VibGUuc2V0CGNvbnN0YW50BAR0aW1lEWFyaXRobWV0aWMuZG91YmxlCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEEnN1cGVyX3Rvd2VyXzFfM19jZBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQWc3VwZXJfdG93ZXJfMl9kdXJhdGlvbghjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAADwPwhjb25zdGFudAQBKxFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAAAIQAhjb25zdGFudAQBKhFhcml0aG1ldGljLmRvdWJsZQpkb3VibGUubWluEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBZzdXBlcl90b3dlcl8yX2R1cmF0aW9uCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEEnN1cGVyX3Rvd2VyXzFfM19jZBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQWc3VwZXJfdG93ZXJfMl9kdXJhdGlvbghjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlCmRvdWJsZS5tYXgRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEEnN1cGVyX3Rvd2VyXzFfM19jZBFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQWc3VwZXJfdG93ZXJfMl9kdXJhdGlvbghjb25zdGFudAQBLQpkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBBzdXBlcl90b3dlcl8yX2NkEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24IY29uc3RhbnQEAS8KZG91YmxlLm1heApkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBJzdXBlcl90b3dlcl8xXzNfY2QRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFnN1cGVyX3Rvd2VyXzJfZHVyYXRpb24IY29uc3RhbnQDlWR54X/9pT0QbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQLbW9vbl9jdXRvZmYKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAAApkb3VibGUubWluEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEBHRpbWURYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAAFEAIY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAAAEAIY29uc3RhbnQEAS0KZG91YmxlLm1heAhjb25zdGFudAPNzMzMzMzsPxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAAAAQAhjb25zdGFudAQBKgx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAQhjb25zdGFudAQDbG9nEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAFlEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEDmVuZXJneV9mb3JtdWxhEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAFlCGNvbnN0YW50BANwb3cRYXJpdGhtZXRpYy5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQLbW9vbl9jdXRvZmYIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyb8IY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGUMdG93ZXIuZW5lcmd5CGNvbnN0YW50AQAIY29uc3RhbnQEASsRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEAWUIY29uc3RhbnQEA3BvdxFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAttb29uX2N1dG9mZghjb25zdGFudAQBKghjb25zdGFudAOamZmZmZnJPwhjb25zdGFudAQBLQhjb25zdGFudAMAAAAAAADwPwhjb25zdGFudAQBKhB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAErEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEAS8IY29uc3RhbnQDAAAAAAAAJEAIY29uc3RhbnQEASoKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAR0aW1lCGNvbnN0YW50BAEtEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEC21vb25fY3V0b2ZmEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBV0b3dlcl9yZXNlcnZlZF9lbmVyZ3kRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFXRvd2VyX3Jlc2VydmVkX2VuZXJneQhjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyT8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAABAn0AIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8IY29uc3RhbnQEAS0KZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BA5lbmVyZ3lfZm9ybXVsYQhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBLRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQUdG93ZXJfcGxhbm5lZF9lbmVyZ3kRZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEFHRvd2VyX3BsYW5uZWRfZW5lcmd5EWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBR0b3dlcl9wbGFubmVkX2VuZXJneQhjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAACmRvdWJsZS5taW4RYXJpdGhtZXRpYy5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQOZW5lcmd5X2Zvcm11bGEIY29uc3RhbnQEAS0MdG93ZXIuZW5lcmd5CGNvbnN0YW50AQARYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBKghjb25zdGFudAOamZmZmZnJPwhjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAECfQAhjb25zdGFudAQBKghjb25zdGFudAMzMzMzMzPjPwhjb25zdGFudAQBLQpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEDmVuZXJneV9mb3JtdWxhCGNvbnN0YW50BAEtDHRvd2VyLmVuZXJneQhjb25zdGFudAEACGNvbnN0YW50BAEtEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyT8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAABAn0AIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8OZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCDwAAABFjb21wYXJpc29uLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZQpkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBBzdXBlcl90b3dlcl8yX2NkEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24IY29uc3RhbnQEASsKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAEqCGNvbnN0YW50A5qZmZmZmck/CGNvbnN0YW50BAErCGNvbnN0YW50AwAAAAAAQI9ACGNvbnN0YW50BAEqCGNvbnN0YW50AzMzMzMzM+M/CGNvbnN0YW50BAEtDHRvd2VyLmVuZXJneQhjb25zdGFudAEACGNvbnN0YW50BAErEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBV0b3dlcl9yZXNlcnZlZF9lbmVyZ3kIY29uc3RhbnQEAT4IY29uc3RhbnQDAAAAAAAAAAAXdG93ZXIubW9kdWxlLnVzZWluc3RhbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEDXN1cGVyX3Rvd2VyXzIRZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEEHN1cGVyX3Rvd2VyXzJfY2QIY29uc3RhbnQDeekmMQhAZEARZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEFnN1cGVyX3Rvd2VyXzJfZHVyYXRpb24IY29uc3RhbnQDAAAAAAAAVEAQbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQEdGltZRFhcml0aG1ldGljLmRvdWJsZQpkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBBzdXBlcl90b3dlcl8yX2NkEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24IY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAA8D8IY29uc3RhbnQEASsRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAACEAIY29uc3RhbnQEASoKZG91YmxlLm1pbhFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQWc3VwZXJfdG93ZXJfMl9kdXJhdGlvbgpkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBBzdXBlcl90b3dlcl8yX2NkEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24IY29uc3RhbnQEAS8KZG91YmxlLm1heApkb3VibGUubWF4EWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBBzdXBlcl90b3dlcl8yX2NkEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBhzdXBlcl90b3dlcl8xXzNfZHVyYXRpb24IY29uc3RhbnQDlWR54X/9pT0QbG9jYWwuZG91YmxlLnNldAhjb25zdGFudAQLbW9vbl9jdXRvZmYKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAAApkb3VibGUubWluEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEBHRpbWURYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAAFEAIY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDAAAAAAAAAEAIY29uc3RhbnQEAS0KZG91YmxlLm1heAhjb25zdGFudAPNzMzMzMzsPxFhcml0aG1ldGljLmRvdWJsZQhjb25zdGFudAMAAAAAAAAAQAhjb25zdGFudAQBKgx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAQhjb25zdGFudAQDbG9nEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAFlEGxvY2FsLmRvdWJsZS5zZXQIY29uc3RhbnQEDmVuZXJneV9mb3JtdWxhEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAFlCGNvbnN0YW50BANwb3cRYXJpdGhtZXRpYy5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQLbW9vbl9jdXRvZmYIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyb8IY29uc3RhbnQEASoRYXJpdGhtZXRpYy5kb3VibGUMdG93ZXIuZW5lcmd5CGNvbnN0YW50AQAIY29uc3RhbnQEASsRYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEAWUIY29uc3RhbnQEA3BvdxFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAttb29uX2N1dG9mZghjb25zdGFudAQBKghjb25zdGFudAOamZmZmZnJPwhjb25zdGFudAQBLQhjb25zdGFudAMAAAAAAADwPwhjb25zdGFudAQBKhB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAErEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEAS8IY29uc3RhbnQDAAAAAAAAJEAIY29uc3RhbnQEASoKZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAR0aW1lCGNvbnN0YW50BAEtEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEC21vb25fY3V0b2ZmEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBV0b3dlcl9yZXNlcnZlZF9lbmVyZ3kRYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFXRvd2VyX3Jlc2VydmVkX2VuZXJneQhjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyT8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAABAj0AIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8IY29uc3RhbnQEAS0KZG91YmxlLm1heAhjb25zdGFudAMAAAAAAAAAABFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRBsb2NhbC5kb3VibGUuZ2V0CGNvbnN0YW50BA5lbmVyZ3lfZm9ybXVsYQhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBLRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQUdG93ZXJfcGxhbm5lZF9lbmVyZ3kRZ2xvYmFsLmRvdWJsZS5zZXQIY29uc3RhbnQEFHRvd2VyX3BsYW5uZWRfZW5lcmd5EWFyaXRobWV0aWMuZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBR0b3dlcl9wbGFubmVkX2VuZXJneQhjb25zdGFudAQBKwpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAACmRvdWJsZS5taW4RYXJpdGhtZXRpYy5kb3VibGUQbG9jYWwuZG91YmxlLmdldAhjb25zdGFudAQOZW5lcmd5X2Zvcm11bGEIY29uc3RhbnQEAS0MdG93ZXIuZW5lcmd5CGNvbnN0YW50AQARYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBKghjb25zdGFudAOamZmZmZnJPwhjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAECPQAhjb25zdGFudAQBKghjb25zdGFudAMzMzMzMzPjPwhjb25zdGFudAQBLQpkb3VibGUubWF4CGNvbnN0YW50AwAAAAAAAAAAEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEGxvY2FsLmRvdWJsZS5nZXQIY29uc3RhbnQEDmVuZXJneV9mb3JtdWxhCGNvbnN0YW50BAEtDHRvd2VyLmVuZXJneQhjb25zdGFudAEACGNvbnN0YW50BAEtEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyT8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAABAj0AIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8MZ2VuZXJpYy53YWl0CGNvbnN0YW50AwAAAAAAAAAA`


#### Spam abilities

`DnNwYW0gYWJpbGl0aWVzAAAAAAAAAAAUAAAADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AmMAAAARY29tcGFyaXNvbi5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBKghjb25zdGFudAN7FK5H4Xq0Pwhjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAAA0QAhjb25zdGFudAQBKghjb25zdGFudAMzMzMzMzPjPwhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBKxFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQVdG93ZXJfcmVzZXJ2ZWRfZW5lcmd5CGNvbnN0YW50BAE+CGNvbnN0YW50AwAAAAAAAAAADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AgYAAAARY29tcGFyaXNvbi5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEEWRhbmtfc2FjcmlmaWNlX2NkCGNvbnN0YW50BAErCmRvdWJsZS5tYXgIY29uc3RhbnQDAAAAAAAAAAARYXJpdGhtZXRpYy5kb3VibGUIY29uc3RhbnQDMzMzMzMz4z8IY29uc3RhbnQEAS0MdG93ZXIuaGVhbHRoCGNvbnN0YW50AQEIY29uc3RhbnQEAT4IY29uc3RhbnQDAAAAAAAAAAAXdG93ZXIubW9kdWxlLnVzZWluc3RhbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEDmRhbmtfc2FjcmlmaWNlEWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBFkYW5rX3NhY3JpZmljZV9jZAhjb25zdGFudAMCK4cW2c4MQAxnZW5lcmljLmdvdG8IY29uc3RhbnQCYwAAAA5nZW5lcmljLmdvdG9pZghjb25zdGFudAJjAAAAEWNvbXBhcmlzb24uZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEWFyaXRobWV0aWMuZG91YmxlEHRvd2VyLmVuZXJneS5tYXgIY29uc3RhbnQEASoIY29uc3RhbnQDmpmZmZmZyT8IY29uc3RhbnQEASsIY29uc3RhbnQDAAAAAAAAaUAIY29uc3RhbnQEASoIY29uc3RhbnQDMzMzMzMz4z8IY29uc3RhbnQEAS0MdG93ZXIuZW5lcmd5CGNvbnN0YW50AQAIY29uc3RhbnQEASsRZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEFXRvd2VyX3Jlc2VydmVkX2VuZXJneQhjb25zdGFudAQBPghjb25zdGFudAMAAAAAAAAAAA5nZW5lcmljLmdvdG9pZghjb25zdGFudAILAAAAEWNvbXBhcmlzb24uZG91YmxlEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BAxodXJyaWNhbmVfY2QIY29uc3RhbnQEAT4IY29uc3RhbnQDAAAAAAAAAAAXdG93ZXIubW9kdWxlLnVzZWluc3RhbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQECWh1cnJpY2FuZRFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQMaHVycmljYW5lX2NkCGNvbnN0YW50A+Olm8QgAEtADGdlbmVyaWMuZ290bwhjb25zdGFudAJjAAAADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AmMAAAARY29tcGFyaXNvbi5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGURYXJpdGhtZXRpYy5kb3VibGUQdG93ZXIuZW5lcmd5Lm1heAhjb25zdGFudAQBKghjb25zdGFudAMfhetRuB7VPwhjb25zdGFudAQBKwhjb25zdGFudAMAAAAAAHCXQAhjb25zdGFudAQBKghjb25zdGFudAMzMzMzMzPjPwhjb25zdGFudAQBLQx0b3dlci5lbmVyZ3kIY29uc3RhbnQBAAhjb25zdGFudAQBKxFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQVdG93ZXJfcmVzZXJ2ZWRfZW5lcmd5CGNvbnN0YW50BAE+CGNvbnN0YW50AwAAAAAAAAAADmdlbmVyaWMuZ290b2lmCGNvbnN0YW50AhAAAAARY29tcGFyaXNvbi5kb3VibGURZ2xvYmFsLmRvdWJsZS5nZXQIY29uc3RhbnQEEnN1cGVyX211bHRpc2hvdF9jZAhjb25zdGFudAQBPghjb25zdGFudAMAAAAAAAAAABd0b3dlci5tb2R1bGUudXNlaW5zdGFudA5nbG9iYWwuaW50LmdldAhjb25zdGFudAQPc3VwZXJfbXVsdGlzaG90EWdsb2JhbC5kb3VibGUuc2V0CGNvbnN0YW50BBJzdXBlcl9tdWx0aXNob3RfY2QIY29uc3RhbnQDN4lBYOXQ/D8MZ2VuZXJpYy5nb3RvCGNvbnN0YW50AmMAAAAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCYwAAABFjb21wYXJpc29uLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRB0b3dlci5lbmVyZ3kubWF4CGNvbnN0YW50BAEqCGNvbnN0YW50A5qZmZmZmck/CGNvbnN0YW50BAErCGNvbnN0YW50AwAAAAAAABRACGNvbnN0YW50BAEqCGNvbnN0YW50AzMzMzMzM+M/CGNvbnN0YW50BAEtDHRvd2VyLmVuZXJneQhjb25zdGFudAEACGNvbnN0YW50BAErEWdsb2JhbC5kb3VibGUuZ2V0CGNvbnN0YW50BBV0b3dlcl9yZXNlcnZlZF9lbmVyZ3kIY29uc3RhbnQEAT4IY29uc3RhbnQDAAAAAAAAAAAOZ2VuZXJpYy5nb3RvaWYIY29uc3RhbnQCYwAAABFjb21wYXJpc29uLmRvdWJsZRFhcml0aG1ldGljLmRvdWJsZRFnbG9iYWwuZG91YmxlLmdldAhjb25zdGFudAQJZGlzcGVsX2NkCGNvbnN0YW50BAErCmRvdWJsZS5tYXgIY29uc3RhbnQDAAAAAAAAAAADaTJkDmFyaXRobWV0aWMuaW50CGNvbnN0YW50AgEAAAAIY29uc3RhbnQEAS0UdG93ZXIuYnVmZnMubmVnYXRpdmUIY29uc3RhbnQEAT4IY29uc3RhbnQDAAAAAAAAAAAXdG93ZXIubW9kdWxlLnVzZWluc3RhbnQOZ2xvYmFsLmludC5nZXQIY29uc3RhbnQEBmRpc3BlbBFnbG9iYWwuZG91YmxlLnNldAhjb25zdGFudAQJZGlzcGVsX2NkCGNvbnN0YW50A6JFtvP91Ow/DGdlbmVyaWMud2FpdAhjb25zdGFudAMAAAAAAAAAAA==`