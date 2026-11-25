# Experiment log (Auto Anatomy)

## 2026-11-22: quality over quantity (user decision)
Trigger: the user saw no virality with 12 reels/day and asked to focus on video quality, changing the whole concept if needed.

Instagram data, 42 reels, 2026-11-17 to 2026-11-21 (account has 79 followers; about 99% of views come from non-followers):
- Median about 1.8k views per reel. Almost every reel stops at the first test audience of about 1.3k-2.7k.
- Breakouts: VTEC 23.7k views (51 shares, 103 saves, 646 likes, skip rate 27%), EGR 6.8k (skip 22%), BMW VANOS 5.7k (15 shares, 23 saves).
  Common: a named, recognisable enthusiast technology or a surprising claim ("eats its own exhaust"), low 3-second skip rate, shares and saves.
- Videos are 48 s; average watch time is about 15 s (about 30%), skip rate within 3 s is 30-45% on most reels. The call to action at the end is seen by few.
- 0 comments on 42 reels (no reason to talk). All reels use the same "Did you know?" hook and the same 8 x 6 s template.
- Posting 12/day gave no extra reach per reel. YouTube showed the same pattern (first upload of the day 1-2k views, later ones 0-55).

Changes made 2026-11-22 (user decisions: 1 reel a day, same 3D look but better):
- All 12 old producer tasks ("Auto Anatomy daily video 1/12" to "12/12") paused (enabled=false), not deleted.
- New producer task "Auto Anatomy quality reel (1 per day)", 05:03 Europe/Belgrade, queues one reel with wave 2 so it posts at 11:07 (the three best reels were posted between 10:49 and 13:11 Belgrade time).
- New format ("30 s concept"): 30 s = 5 scenes x 6 s, money shot and big claim text from frame 0, first spoken line is the claim, aha by about second 15, last scene asks a comment question, caption = hook claim + question + 4 hashtags, closer cutaways and more camera motion, quality gate on the finished mp4 (skip the day rather than ship a weak reel).
- Topic shortlist: named enthusiast tech and counterintuitive claims (VTEC vs VANOS vs VVT-i first), follow-ups of any breakout.
- Publisher waves 1/2/3 unchanged: they post what is queued and upload the capped YouTube backlog (2 + 1 + 1 per day).
Review: after 5-7 days compare the 30 s reels against the old median (1.8k views) on views, skip rate, avg watch time, shares, saves, comments, and log it here.
2026-11-22 #52 VTEC vs VANOS vs VVT-i, hook "Only one swaps the cam lobe", 30 s, 30 s concept (queued wave 2, posts 11:07)

## 2026-11-22 evening: at least 6 reels a day + SKILL call to action (user decisions)
- The user asked for at least 6 reels a day at the 30 s quality bar (not 1). Six producer tasks "Auto Anatomy quality reel 1/6" to "6/6" run 05:03-05:23 Belgrade; slots 1-2 queue wave 1, 3-4 wave 2, 5-6 wave 3. Topic and idea number are deterministic per slot (K-th unused slug of a fixed shortlist, N = highest number before today + K) so parallel slots never collide.
- New ending: every reel ends with "Want to make videos like this? Comment the word SKILL." (big COMMENT SKILL text at the top from 25.8 s). Commenters get a DM with a paid offer for the reel-making skill. Track comments per reel from now on.
- #52 after ~8 h: 2.4k views, skip rate 43%, avg watch 13.2 s, 2 shares, 10 saves (hook "Only one swaps the cam lobe" too abstract). Next hooks: a plain surprising claim.
2026-11-22 #53 Why Mazda rotary engines burn oil on purpose, hook "IT BURNS OIL ON PURPOSE", 30 s, 30 s concept + SKILL CTA (queued wave 2)

## 2026-11-22 19:43 Belgrade: SKILL comment responder, first run
- Instagram comments, last 7 days (Windsor): 5 comments on 3 older reels (posted 18-20 Nov), none contains "skill", so 0 replies were sent. The SKILL call to action only started today with #53, so no SKILL comments were expected yet.
- Windsor returns cached comments; the current plan has no refresh on request, so new SKILL comments can show up a few hours late.
- PayPal list_transactions failed with 401 Unauthorized (twice), so payments were NOT checked. Fix: reconnect the PayPal connector in Claude settings.
- Created notes/skill_replies.txt (empty; replied comment_ids get appended there).
- User notified by push.
2026-11-23 #54 How BMW Valvetronic controls power without a throttle (bmw-valvetronic-no-throttle), hook "NO THROTTLE NEEDED", 30 s, 30 s concept, SKILL CTA, slot 1 (queued wave 1)
2026-11-23 #56 cylinder-deactivation-v8-as-v4, hook "THIS V8 TURNS INTO A V4", 30 s concept, SKILL CTA, slot 3
2026-11-23 #58 koenigsegg-freevalve-no-camshaft, hook "THIS ENGINE HAS NO CAMSHAFT", 30 s concept, SKILL CTA, slot 5
2026-11-23 #57 mazda-skyactiv-x-compression-ignition, hook "PETROL ENGINE IGNITES LIKE A DIESEL", 30 s concept, SKILL CTA, slot 4
2026-11-23 #59 How a twin-scroll turbo fights turbo lag (twin-scroll-turbo-lag), hook "YOUR EXHAUST FIGHTS ITSELF", 30 s concept, SKILL CTA, slot 6 (queued wave 3)
2026-11-24 #60 subaru-boxer-rumble, hook "THE RUMBLE IS UNEVEN PIPES", 30 s concept, SKILL CTA, slot 1 (queued wave 1)
2026-11-24 #62 pushrod-ls-v8-compact, hook "THIS V8 HAS ONE CAMSHAFT", 30 s concept, SKILL CTA, slot 3
2026-11-24 #63 anti-lag-rally-bangs, hook "RALLY CARS BANG ON PURPOSE", 30 s concept, SKILL CTA, slot 4
2026-11-24 #64 mclaren-f1-gold-engine-bay, hook "LINED WITH REAL GOLD", 30 s concept, SKILL CTA, slot 5
2026-11-24 #65 sodium-filled-valves, hook "THIS VALVE HOLDS LIQUID METAL", 30 s concept, SKILL CTA, slot 6 (queued wave 3)
2026-11-25 #66 electric-turbo, hook "THIS TURBO HAS A MOTOR", 30 s concept, SKILL CTA, slot 1 (queued wave 1). Slot 1 took a follow-up topic because #63 anti-lag broke out (10.8k views, about 6x the 30 s median); instead of dual-clutch-gearbox, which stays first in line for the next free slot 1.
