# Unofficial LineageOS ROM for Blackberry Key2

## ROM Sources:
LineageOS ROM sources for Blackberry Key2 and Key2 LE are kept here (https://github.com/orgs/Lineage-BBKey2/repositories).

The ROM sources were forked from [krab-ubica](https://github.com/tim-ecoder/lineageos_blackberry_athena) and [FumoEnterprises](https://github.com/FumoEnterprises).

Almost all[*] of [krab-ubica's patches](https://github.com/tim-ecoder/lineageos_blackberry_athena/tree/lineage-22.2-athena/patches) have been committed to the corresponding repos. Some patches were applied to forked upstream LineageOS repos.

Further changes done by me (zapaca), sometimes with help from others and attributed as co-authors in the commits.

Help from AI conversational prompting was used in some cases and is noted in the corresponding commits.

## Download/Install:

* Blackberry Key2: https://github.com/Lineage-BBKey2/distribution/releases/latest
* Blackberry Key2 LE: https://github.com/Lineage-BBKey2LE/distribution/releases/latest
* Installation guide/tips: https://daphnis-past-midnight.nekoweb.org/wiki/key2.html (created/maintained by [Luna-Terra-CG](https://github.com/Luna-Terra-CG))

## Notes
[*] The following patches were not applied:
- [03-custom-signing-keys.patch](https://github.com/tim-ecoder/lineageos_blackberry_athena/blob/lineage-22.2-athena/patches/03-custom-signing-keys.patch) - private signing keys/release version IDs
- [05-mediaprovider-selinux-fix.patch](https://github.com/tim-ecoder/lineageos_blackberry_athena/blob/lineage-22.2-athena/patches/05-mediaprovider-selinux-fix.patch) - Based on my testing, no problems with SD card functionality without this patch 
- [Lokker](https://github.com/tim-ecoder/lineageos_blackberry_athena/blob/lineage-22.2-athena/patches/06-lokker-system-app.patch) and [K12KB](https://github.com/tim-ecoder/lineageos_blackberry_athena/blob/lineage-22.2-athena/patches/07-k12kb-app.patch) app patches: Apps are included in device_blackberry_athena repo but for the releases here they are not signed as specified in these patches 
