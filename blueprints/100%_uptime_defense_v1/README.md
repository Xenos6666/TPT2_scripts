# 100 % uptime defense

This blueprint combines immortality shield, tideshift and temporal barrier to get 100% uptime of defensive mesures.

This blueprint is paired with a set of scripts that allows very precise tracking of energy and timing of skill autocasts.


## Requirements

This blueprint assumes that you've unlocked the Necronomicon artifact.


## How to use the scripts

To use these scripts, first check that the values in `load abilities settings` line up with the positions of your skills in a round, if not, modify them accordingly,; inside the same script, set you max available energy.

Start a new round, pause it make sure your energy is maxed, all your skills are available to be cast, and the 2x time disabled.
You can then enable the AI, then press "0" to enable the scripts, once you've done that, you shouldn't press the "pause" or "x2" buttons manually or close the AI until the end of the run (I recommend remapping these buttons to buttons you wouldn't frequently use to prevent muscle memory from killing your run).
To pause/unpause you should use the "9" key, and to switch between x1 and x2 you should use the "8" key. From there everything should work as expected.


## The blueprint

|| Incorrect blueprint, need to replace quantum fading with simple evasion
`MTAwJSB1cHRpbWUgZGVmZW5zZTtpbmZpbml0eS5hdHRhY2suc3BlZWQ7YXR0YWNrLnNwZWVkO2F0dGFjay5tdWx0aXNob3Q7YXR0YWNrLmJvdW5jZTthdHRhY2sucmFwaWRmaXJlO2luZmluaXR5LnNwbGFzaDtzYWNyaWZpY2UuZGFyaztpbmZpbml0eS5pbXBldHVzO2F0dGFjay5iYXNoO2F0dGFjay5zcGFyaztzaGFyZHMuaWNlO3NwbGFzaC5haXI7c3BsYXNoLmZyb3N0O3NwZWxsLm11bHRpc2hvdDtjcml0LmluZmluaXR5O2F0dGFjay5pY2VicmVhdGg7ZGVmZW5zZS5zdHJpa2ViYWNrO2RlZmVuc2Uub3ZlcmNoYXJnZTtlYXJ0aC5ncmF2ZWw7YXVyYS5mcm9zdDtzaGllbGQuZnJvc3Q7ZGVmZW5zZS5kYWlnb3BhcnJ5O2F1cmEuZGVhdGg7cmVzaXN0YW5jZS5hYnMuZmlyZTtzaGllbGQuYWR2YW5jZWQ7c3BlbGwuZGlzcGVsO3NwZWxsLmZyb3N0bm92YTtzcGVsbC50aWRlc2hpZnQ7YmFycmllci50ZW1wb3JhbDtkZWZlbnNlLnNoZWx0ZXI7cmVzaXN0YW5jZS5hYnMuZGFya25lc3M7ZXZhc2lvbi5iYXNpYztlbmVyZ3kucmVnZW5lcmF0aW9uO2JvbnVzLmNvbmRlbnNlO2VuZXJneS5tb29uO2VuZXJneS5iYXNpYztlbmVyZ3kucmVjeWNsaW5nO3hwLmJvbnVzO211bHRpc2hvdC5mb2N1c2VkO2luZmluaXR5LnJhbmdlO2FtcGxpZmllci5uZXV0cmFsO21pc3NpbGUuc2VyaW91cztkZWZlbnNlLnN0b25lc2tpbjtzcGVsbC5zbmFwT2ZEZXN0aW55O3NoaWVsZC5pbW1vcnRhbGl0eTthaXIuaHVycmljYW5lO3Rvd2VyLnN1cGVyLjM7dG93ZXIuc3VwZXIuMjt0b3dlci5zdXBlci4xO3NoaWVsZC51bml2ZXJzYWw7Zm91bmRhdGlvbi5pbmZpbml0eQ==`

Modules:

- Attack speed/multi target : Attack speed, Quantum speed, Rapidfire, Strike back, Overcharge, Multishot, Basic Bouncing, Super Multishot, Hurricane, Super Tower 1, Super Tower 2, Infinity Range
- Damage : Infinity Splash, Infinity Impetus, Infinity Crit, Super Tower 3, Snap of Destiny, Neutral Amplifier, Serious Missile, Death Aura
- Defense : Advanced Shield + Temporal Barrier, Frost Nova + Tideshift, Immortality Shield, Darkness Armor, Fire Armor, Universal Shield, Daigoparry, Frost Aura, Shield of Frost, Simple Evasion, Shelter, Stoneskin, Gravel, Air Slice, Bash, Spark, Ice Shards, Frost Splash, Ice Breath
- Energy : Energy, Energy Regeneration, Energy Recycling, Moon Energy,
- Utility : XP Bonus, Condense, Dispel, Dark Sacrifice
