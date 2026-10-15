# Awesome-Video-Players-Media-SDKS

## Top Video Players & Media SDKs Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on HTML5 Players, ABR Playback (HLS/DASH), Embeddable SDKs & Adaptive Streaming Clients*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Video Players & Media SDKs**. These libraries play progressive and adaptive streams in the browser and apps—HLS, DASH, DRM hooks, and consistent UI across devices.



**Examples** include Video.js, hls.js, Shaka Player, dash.js, Bitmovin Player, JW Player, THEOplayer, Clappr, Plyr, MediaElement.js, and **Plyr** (`sampotts/plyr`)—a simple, customizable HTML5, YouTube and Vimeo media player.



**Open-source emphasis**: Web playback is led by open source. **Video.js**, **hls.js**, **Shaka Player**, **dash.js**, **Plyr**, and **Clappr** power a huge share of online video. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Bitmovin Player, THEOplayer, JW Player](https://bitmovin.com/)**  

  Commercial player SDKs—analytics, DRM integrations, support SLAs, and multi-platform SDKs for enterprise streaming.



- **[Brightcove, Vimeo, other OVP-bundled players](https://www.brightcove.com/)**  

  Online video platforms that ship hosted players with CMS, ads, and CDN integration.



- **[Mux Player and developer-oriented player services](https://www.mux.com/)**  

  API-first video platforms with opinionated players and quality analytics.



- **[Other commercial media player SDKs](https://www.jwplayer.com/)**  

  Additional licensed players for broadcast, OTT, and advertising workflows.



## Open-Source GitHub Projects



### Full Players & UI



- **[Video.js](https://github.com/videojs/video.js)**  

  Leading open HTML5 video player framework—plugin ecosystem, skins, and wide adaptive-streaming integrations.



- **[Plyr](https://github.com/sampotts/plyr)**  

  Simple, accessible open media player—HTML5, YouTube, and Vimeo with a clean, customizable UI.



- **[Clappr](https://github.com/clappr/clappr)**  

  Open extensible media player—plugin architecture and strong community usage for web embeds.



- **[MediaElement.js](https://github.com/mediaelement/mediaelement)**  

  Open HTML5 audio/video player with Flash fallbacks historically—consistent API across sources.



- **[Vime / Vidstack](https://github.com/vidstack/player)**  

  Modern open web component media players oriented toward accessibility and framework integration.



### ABR Engines (HLS / DASH)



- **[hls.js](https://github.com/video-dev/hls.js)**  

  Open HLS client for browsers without native HLS—MSE-based playback used across the industry.



- **[Shaka Player](https://github.com/shaka-project/shaka-player)**  

  Open DASH/HLS player from Google—robust adaptive streaming, offline, and DRM-oriented features.



- **[dash.js](https://github.com/Dash-Industry-Forum/dash.js)**  

  Official open reference player for MPEG-DASH maintained by the DASH Industry Forum.



- **[hasplayer.js / community DASH-HLS bridges](https://github.com/search?q=hls.js+OR+dash.js)**  

  Additional open adaptive clients and integration layers.



### Native & Cross-Platform SDKs



- **[ExoPlayer / Media3 (Android)](https://github.com/androidx/media)**  

  Open Android media player library—production standard for adaptive playback on Android.



- **[AVPlayer ecosystem / open wrappers (Apple)](https://developer.apple.com/documentation/avfoundation)**  

  Platform player with open companion tools and community wrappers (core is platform-provided).



- **[libmpv / mpv](https://github.com/mpv-player/mpv)**  

  Open versatile media player and library—embeddable playback engine for desktop and custom UIs.



- **[VLC / libVLC](https://github.com/videolan/vlc)**  

  Open cross-platform player and SDK—plays almost every format; embeddable via libVLC.



### Additional Strong Open-Source Options



- **General web player**: Video.js or Plyr.

- **HLS in Chrome/Firefox**: hls.js.

- **DASH + advanced ABR**: Shaka Player or dash.js.

- **Android**: Media3 / ExoPlayer.

- **Desktop embed**: mpv or libVLC.

- **Composable stacks**: hls.js/Shaka → Video.js/Plyr UI → optional analytics beacons.

- Commercial players still lead for integrated ads, DRM support packages, and vendor SLAs.



**Frameworks for building custom systems**:  

**Video.js** or **Plyr** for UI; **hls.js** / **Shaka** / **dash.js** for ABR; **Media3** on Android; **libVLC**/**mpv** for heavy-format desktop.  

Fully open player stacks are production-standard for web and many mobile apps.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Players handle user media and sometimes DRM-protected content—follow content licenses, accessibility requirements (captions, keyboard), and privacy rules for analytics. Test across browsers and devices.

- Open-source players offer full control and no per-play license from the player vendor. Commercial SDKs shift support and ad/DRM integrations to the vendor. Neither replaces CDN design and encoding quality.



---



**Made for frontend engineers, OTT teams, and anyone embedding video on the web.**  

Let's expand open media players while recognizing the enterprise packaging that commercial player SDKs deliver.
