# Request Falcon FPP Plugin

The FPP (Falcon Player) plugin for [Request Falcon](https://requestfalcon.com) — a SaaS for letting viewers control your Christmas light show from their phone.

This is a fork of [Remote Falcon's plugin](https://github.com/Remote-Falcon/remote-falcon-plugin) (GPL-3.0). The only meaningful change is that the default API URL points at Request Falcon instead of Remote Falcon.

## Install

In FPP: **Content Setup → Plugin Manager → Install Plugin From URL** and paste:

```
https://raw.githubusercontent.com/Seanieg87/request-falcon-plugin/master/pluginInfo.json
```

After installing, **reboot your Pi**. Then go to **Content Setup → Request Falcon** and paste your plugin token from your Request Falcon dashboard.

If you're migrating from the original Remote Falcon plugin, you can run both side-by-side — they install to different directories (`/opt/fpp/media/plugins/request-falcon/` vs `/opt/fpp/media/plugins/remote-falcon/`).

## License

GPL-3.0, inherited from the upstream Remote Falcon plugin. See `LICENSE`.

## Original credits

The original Remote Falcon plugin was created by [James Vance](https://github.com/whitesoup12) and contributors. This fork exists because Remote Falcon announced a sunset of its hosted service in May 2026; Request Falcon is a successor service for the same use case.
