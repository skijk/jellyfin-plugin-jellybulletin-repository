# JellyBulletin Plugin Repository

<p align="center">
  <img src="logo-v2.png" alt="JellyBulletin" width="220">
</p>

Public distribution repository for JellyBulletin releases.

Add the following URL under **Dashboard → Plugins → Repositories** in Jellyfin:

```text
https://raw.githubusercontent.com/skijk/jellyfin-plugin-jellybulletin-repository/main/catalog-v2.json
```

## Dependencies and integrations

| Component | Status | Used for |
| --- | --- | --- |
| Jellyfin 10.11.11 | Required | Supported server and web client |
| File Transformation | Required | Loads the bulletin panel in Jellyfin Web |
| JellySpotlight | Optional | Coordinates home-screen placement when both plugins are enabled |

JellyBulletin does not require Jelana, Playback Reporting, Radarr Watch,
Jellyfin Enhanced or JS Injector. Add the File Transformation repository and
install it before JellyBulletin:

```text
https://www.iamparadox.dev/jellyfin/plugins/manifest.json
```

Source code, documentation and issue tracking:

https://github.com/skijk/jellyfin-plugin-jellybulletin
