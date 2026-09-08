---
title: "The 3-2-1 Backup Rule and How to Test It"
description: "Three copies, two media, one off-site. What the rule means in practice, and how to confirm your backup actually restores rather than merely exists."
focus_keyword: "3-2-1 backup rule"
slug: "backup-3-2-1-rule"
date: 2026-08-12T10:00:00+03:00
draft: false
categories: ["data-protection"]
featured_image: "cover.webp"
featured_image_alt: "An external storage drive beside a computer in an office setting"
---

Most people set up a real backup only after nearly losing something that mattered.
The rule that condenses long experience in this field is simple: three copies of
the data, on at least two different kinds of media, with one of them off-site.

## Why three copies, not two

An original and a single copy feel like enough, right up until one fails while you
are restoring from the other. The third copy is not indulgence; it covers the case
where two problems land close together, which is more common than it sounds because
disks bought together tend to age together.

## What "two different media" actually means

Two identical drives bought on the same day are not two media in any useful sense.
Different media means different failure modes: a hard drive and a solid-state drive,
or local storage and cloud storage. The goal is that no single cause can take out
every copy at once.

## The off-site copy is the one that survives

Fire, theft, a power surge and ransomware are all events that hit the place, not
just the disk. The copy that lives somewhere else — or is not connected at all — is
the one still standing afterwards. With ransomware specifically, a backup reachable
from the same administrator account that was compromised gets encrypted along with
everything else.

## An untested backup is not a backup

This is the step most often skipped. A backup file existing does not mean it
restores. Test it periodically: bring a real file back to a different location, open
it, and confirm it is intact. The day you lose your data is the wrong time to find
out the backup was corrupt.
