# Sesh Privacy Policy

**Last updated: October 8, 2026**

Sesh ("the app") is a practice journal for iPhone, operated by Eugene Lee
("we"). This page explains what the app does with your data. The short
version: your videos, notes, tags, and edits stay on your device. We never
see them.

## What stays on your device

Everything you put into Sesh is stored only on your iPhone:

- Videos and photos you import. Sesh stores a reference to the item in your
  Photos library and never copies or uploads it. (The sample clips that ship
  with the app are stored as local files.)
- Trims, crops, speed settings, tags, notes, and dates.
- Thumbnails Sesh generates for its grid.

We have no servers that hold your content, no accounts, and no backup of
your library. Deleting the app deletes everything in it. If you choose to
share or export a clip, it goes only where you send it.

## Photos access

Sesh asks for access to your Photos library so you can pick clips. It reads
the items you choose and, when you ask it to, can save exported clips back to
Photos or delete originals you've imported (iOS always shows its own
confirmation before anything is deleted). When you share a video into Sesh
from another app, Sesh's share extension looks through your Photos library's
metadata (filenames, dates, durations) on your device to find the matching
original, so it can store a reference instead of a copy. That search never
leaves your phone. If an original lives in iCloud
Photos, your device downloads it through Apple; Sesh does not handle that
transfer.

## Usage analytics

To understand which features are used, Sesh sends anonymous usage events to
PostHog, an analytics service, hosted in the United States. What is sent:

- The name of an action (for example "clip imported", "comparison opened").
- Coarse, bucketed properties (for example "1–5 clips", "under 30 seconds",
  a tag category like "Power", a link domain bucket like "youtube").
- Device model, iOS version, app version, language, time zone, screen size,
  and whether you're on Wi-Fi or cellular.
- A random identifier generated on your device so repeat events from the
  same install can be counted. It is not tied to your name, email, Apple ID,
  or advertising identifier.

What is never sent: your videos, photos, thumbnails, tag names you typed,
note text, filenames, Photos identifiers, your precise location, or your
contacts. Like any internet request, PostHog's servers receive your IP
address to deliver the data; we have IP-based location lookup turned off and
do not store IP addresses.
We do not use session recording, crash reporting, or advertising tracking.
We do not sell analytics data, and we do not share it with anyone other than
PostHog, which stores and processes it on our behalf.

**Retention.** Analytics events are kept for one year and then deleted.

**Your choices.** There is currently no in-app switch to turn analytics off.
Because events are anonymous, we have no way to find or delete the events
from a particular person; if you would rather send nothing, the only option
today is not to use the app. We'll note it here if that changes.

## Link previews

If you add a web link to a note, your iPhone fetches that page's title and
image directly from the website to show a preview. That request goes from
your device to the website, like opening the link in Safari. Sesh does not
see it.

## Notifications

Sesh can show local reminders about your own clips. These are scheduled on
your device. There is no push server and no notification data leaves your
phone.

## Children

Sesh is not directed at children under 13 and does not knowingly collect
information from them.

## Changes

If this policy changes, the new version will be posted here with an updated
date. Material changes to what the app collects will also be reflected in
the App Store privacy details.

## Contact

Questions, requests, or support: **sesh.practice@gmail.com**

## Open source

Sesh includes posthog-ios, © PostHog Inc., and PLCrashReporter, © Microsoft
Corporation and © 2008–2014 Plausible Labs Cooperative, Inc., both used under
the MIT License.
