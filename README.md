# cycle5

These are some bash scripts to facilitate some typical attacker-like activities on a Linux target. Firstly, it grabs some credentials and then goes and acquires and aggregates various files that could be of interest. It seals them up in a tar, obfuscates said tar, and dispatches it to the target over netcat. At the same time, we use netcat to create a backdoor, so that we can go in and do whatever we like on the target. We then clean up some of our tracks.

To use these it is necessary to chmod +x each of the scripts.

Future work
Establish persistence, add additional functionality for quickly gathering material, clean up more of our tracks (some opportunities currently exist); find a better and more secure method to transmit material -- maybe Cryptcat.
