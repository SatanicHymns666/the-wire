# The Feed

This is an automated daily news sweep. It runs every day. It collects. It organizes. It records. The world breaks things and this system writes it down.

Each file in the `feed/` directory is a dated snapshot. The format is consistent: headlines, keywords extracted from each article, the source, and a direct link. Thirteen categories, same order every time — Earth, Water, Sky, Infrastructure, Aviation, Maritime, Violence, Public Spaces, Political, Economic, Health, Space, Unexplained. The categories do not editorialize. They contain data.

The categories are searched across dozens of queries per run. Earthquakes, eruptions, floods, plane crashes, mass shootings, disease outbreaks, geomagnetic storms, mass animal deaths — whatever the day produced. If something happened and a news source indexed it, there's a reasonable chance it's in here. If a category is empty, it says so. That's also data.

This system does not predict, analyze, or explain. It does not rank events by significance or comfort you about their causes. It captures what the news cycle surfaced for a given UTC day and writes it to a file. The file persists. It is never deleted. The archive grows by one entry every day the system runs.

The feed is blunt because the news is blunt. It doesn't soften the list by leaving things out.

## Latest Feed

[2026-10-14] — 15 entries
[feed/2026-10-14.md](feed/2026-10-14.md)

## Archive

Daily feeds are stored in the `feed/` directory, dated by collection day. They are never deleted.
