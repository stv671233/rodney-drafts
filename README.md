# rodney-drafts
Repository for socials

## schedule.json (Hub → Social → 🗓️ Post schedule)
Every post to load into Metricool. Each item: id (unique, never reuse), date (YYYY-MM-DD), time (HH:MM UK), kind (Image/Reel/Video/Pin), networks, title, file, folder, thumb (thumbs/*.jpg),
and captions: instagram / facebook / tiktok, or pinterest {title, description, link, board}. Add new posts to the list and push; the Hub picks them up on next load. "Scheduled" ticks live in the browser, keyed by id.
YouTube cards: networks ["YouTube"], kind "YouTube video" or "YouTube Short", youtube {title, description, tags, playlist, thumbnail (file name, episodes only)}.
File naming: RTV_###_YYYY-MM-DD_Title.mp4, _thumb.jpg, _Short1..3.mp4 (### = Hub script-calendar day, date = episode publish day; Shorts keep the episode date).
