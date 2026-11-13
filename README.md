# Home Cinema — Privacy Policy

Last updated: 13 November 2026

Home Cinema is a media browser and player available as a desktop app, an Android app and a Chrome extension. This policy describes what the Chrome extension stores and sends.

## What stays on your device

- Your settings, viewer profiles ("tickets"), favourites, watch progress and badges are stored in the browser's storage for the extension. Removing the extension removes them.
- Nothing about your browsing in other tabs is read, recorded or sent. The extension has no content scripts and does not run inside other websites.
- The extension's own requests are sent without cookies. The one exception is a catalogue site (hdss.art) that sets a session cookie of its own before it lists a film's players: your browser keeps that site's cookie and sends it back to that site only. The extension does not read it.

## Optional online profile

If you create or open an online profile, the following is stored on our database (hosted by Supabase, in the European Union) so that it follows you from one device to another and can be shared with the friends you add:

- the profile name and portrait you choose (no real name or email address is requested or stored);
- a friend code, your list of friends and the invitations between you;
- what you watch: titles, progress, favourites, completed films, badges and rank, and your current status ("watching …") while a film plays;
- a random identifier for each device that opens the profile, and the IP address it was last seen from (see below);
- if you set a password or a recovery ticket: only an irreversible hash of it;
- if you use "Sign in with Google": only an irreversible code derived from your Google account identifier. Your Google email address, name and picture are not read or stored.

Your friends see your status and history according to the visibility settings in Settings › Profile (everyone, friends only, or nobody for who you watched with). The IP address a profile and each of its devices was last seen from is kept with the profile. It is used to list the profiles recently seen from the same connection ("Is this you?"), to tell you whether a screen asking for your profile is on your connection, and to limit password guessing. It is never shown to other users.

You can sign out of a device at any time. To have an online profile and all its data deleted, use the contact below and give its friend code.

## Third-party services the extension contacts

- The Movie Database (TMDB) for film and series information and artwork.
- The catalogue and video hosts that a film or channel is played from (Kweflix, FrenchStream, FrameXTV, TopFlix, HDSS, Cuevana, Wiflix, Rezka, MovieFFM, the Internet Archive and their stream hosts), which receive your IP address as any website does when you load a page or a video from it. Each catalogue can be switched off in Settings.
- Our own server function (hosted by Supabase) and GitHub, when a TV channel plays the commercials between films: the function hands your browser a short-lived link to the video file, which is hosted on GitHub. Both receive your IP address; nothing about you or your profile is sent with the request. The commercials can be switched off in Settings › TV.
- YouTube (youtube-nocookie.com) when you play a trailer.
- Google, only if you choose "Sign in with Google".

Each of these services has its own privacy policy.

## What we do not do

- We do not sell or rent your data.
- We do not use it for advertising, profiling or any purpose other than running the features described above. The commercials shown on the TV channels are part of the retro television look: nobody pays for them and they are not chosen according to who is watching.
- We do not transfer it to third parties, except the hosting provider that stores it on our behalf.

## Contact

Open an issue on this repository: https://github.com/BrunoAraujo99/home-cinema-privacy/issues
