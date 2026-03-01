# CTF Write Up

## Challenge Info
**Name:** The Herald's Forgotten Broadcast
**Category:** OSINT  
**Event:** ISSessions 2026  
**Completed:** Yes  

## Challenge Description
The Royal Herald was tasked with broadcasting a secret decree across the realm. He scattered fragments of the message across the public notice boards of the land.
Only those who can trace his identity and follow his trail will recover the full decree.
A scrap of parchment was found bearing the herald's alias. Track him down and recover the sealed decree.


## Challenge Files
=== INTERCEPTED PARCHMENT ===

This fragment was recovered from a dead drop near the Guild Hall's eastern gate.
The handwriting matches that of the Royal Herald — a figure known to operate
under the alias:

    FantasyCTF-Herald-2026

The Herald is known to post public notices across the realm's notice boards.
Track down his identity and recover the sealed decree.

— Intelligence Division, Guild Hall

---

## Challenge Hints
Free Hint: The herald's name is also his identity on the world's largest code forge.

## Investigation
Look up FantasyCTF-Herald-2026 in github, there is a user.
put an image here when you stop being lazy

The user's only repository is called Royal Degree and has a simple readme that reads
>The Royal Herald's archive of public proclamations.
>
>"Not all decrees are meant for mortal eyes. Some are sealed, some are burned, and some are hidden in the echoes of time."
>
>No decrees are currently on file. The Herald's quill has gone silent.
>
>"The decree was sealed before it was published. Look to the past."

The message hints that it likely has been removed, the repository has 3 commits on record
put an image here when you stop being lazy

The oldest commit is labelled "Add classified decree" and inside there is a decree including the flag
>=== ROYAL DECREE #7 — FOR THE EYES OF THE KING'S COUNCIL ONLY ===
>
>By order of the Crown, the following intelligence has been verified:
>
>The infiltrator's identity has been confirmed. The Shadow Council's
>agent was discovered operating under the alias "Thornwick" in the
>eastern provinces. All guild masters are to be on high alert.
>
>The sealed phrase, known only to the Council, is:
>
>FantasyCTF{th3_h3r4ld_sp34ks_thr0ugh_t1m3}
>
>Burn this decree after reading.
>
>— The Royal Herald

## Outcome
**Flag:** FantasyCTF{th3_h3r4ld_sp34ks_thr0ugh_t1m3}
