# KSHairsBaldHelmetsFixer

When using KS Hairs with many vanilla helmets, the character's head may appear completely bald underneath. This is because many of the helmets use the biped slot 41 - LongHair, which blocks out the hairline from showing. This patcher removes the biped slot from all the helmet records, allowing the hairline to show again. Obviously it's not as good as a proper hair model, but it's better than nothing.

EditorIDs for items you do not wish to modify can be added to the blacklist in the settings. The blacklist is a comma separated string of EditorIDs. The items on the list are partially matched, case-insensitive. E.g., if you want to blacklist all KS SMP wigs, you can add "kswig" (without quotes) to the blacklist.

May introduce minor clipping with vanilla hairs on some armors, depending on the meshes used.
