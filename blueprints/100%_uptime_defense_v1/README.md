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

// Incorrect blueprint, need to replace quantum fading with simple evasion
`MTAwJSB1cHRpbWUgZGVmZW5zZTtpbmZpbml0eS5hdHRhY2suc3BlZWQ7YXR0YWNrLnNwZWVkO2F0dGFjay5tdWx0aXNob3Q7YXR0YWNrLmJvdW5jZTthdHRhY2sucmFwaWRmaXJlO2luZmluaXR5LnNwbGFzaDtzYWNyaWZpY2UuZGFyaztpbmZpbml0eS5pbXBldHVzO2F0dGFjay5iYXNoO2F0dGFjay5zcGFyaztzaGFyZHMuaWNlO3NwbGFzaC5haXI7c3BsYXNoLmZyb3N0O3NwZWxsLm11bHRpc2hvdDtjcml0LmluZmluaXR5O2F0dGFjay5pY2VicmVhdGg7ZGVmZW5zZS5zdHJpa2ViYWNrO2RlZmVuc2Uub3ZlcmNoYXJnZTtlYXJ0aC5ncmF2ZWw7YXVyYS5mcm9zdDtzaGllbGQuZnJvc3Q7ZGVmZW5zZS5kYWlnb3BhcnJ5O2F1cmEuZGVhdGg7ZmFkaW5nLnF1YW50dW07cmVzaXN0YW5jZS5hYnMuZmlyZTtyZXNpc3RhbmNlLmFicy5kYXJrbmVzcztzaGllbGQuYWR2YW5jZWQ7c3BlbGwuZGlzcGVsO3NwZWxsLmZyb3N0bm92YTtzcGVsbC50aWRlc2hpZnQ7YmFycmllci50ZW1wb3JhbDtkZWZlbnNlLnNoZWx0ZXI7ZW5lcmd5LnJlZ2VuZXJhdGlvbjtib251cy5jb25kZW5zZTtlbmVyZ3kubW9vbjtlbmVyZ3kuYmFzaWM7ZW5lcmd5LnJlY3ljbGluZzt4cC5ib251czttdWx0aXNob3QuZm9jdXNlZDtpbmZpbml0eS5yYW5nZTthbXBsaWZpZXIubmV1dHJhbDttaXNzaWxlLnNlcmlvdXM7ZGVmZW5zZS5zdG9uZXNraW47c3BlbGwuc25hcE9mRGVzdGlueTtzaGllbGQuaW1tb3J0YWxpdHk7YWlyLmh1cnJpY2FuZTt0b3dlci5zdXBlci4zO3Rvd2VyLnN1cGVyLjI7dG93ZXIuc3VwZXIuMTtzaGllbGQudW5pdmVyc2FsO2ZvdW5kYXRpb24uaW5maW5pdHk=`

Modules:

- Attack speed/multi target : Attack speed, Quantum speed, Rapidfire, Strike back, Overcharge, Multishot, Basic Bouncing, Super Multishot, Hurricane, Super Tower 1, Super Tower 2, Infinity Range
- Damage : Infinity Splash, Infinity Impetus, Infinity Crit, Super Tower 3, Snap of Destiny, Neutral Amplifier, Serious Missile, Death Aura
- Defense : Advanced Shield + Temporal Barrier, Frost Nova + Tideshift, Immortality Shield, Darkness Armor, Fire Armor, Universal Shield, Daigoparry, Frost Aura, Shield of Frost, Simple Evasion, Shelter, Stoneskin, Gravel, Air Slice, Bash, Spark, Ice Shards, Frost Splash, Ice Breath
- Energy : Energy, Energy Regeneration, Energy Recycling, Moon Energy,
- Utility : XP Bonus, Condense, Dispel, Dark Sacrifice
