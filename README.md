# 🌟 OBS Plugin Freeze Filter

![Version](https://img.shields.io/badge/PluginVersion-0.3.3-brightgreen)
![Version](https://img.shields.io/badge/FlatpakVersion-1.0-blue)
![License](https://img.shields.io/github/license/Blackstareye/obs-plugin-freeze-filter-flatpak
)
![GitHub
issues](https://img.shields.io/github/issues/Blackstareye/obs-plugin-freeze-filter-flatpak)
![GitHub last
commit](https://img.shields.io/github/last-commit/Blackstareye/obs-plugin-freeze-filter-flatpak)
![Maintenance](https://img.shields.io/maintenance/yes/2025)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H096MU7)

## Description

> [!Important] 
> This is not the official flatpak build by the author, just for clarification

### What does it do ?

see [OBS Forum](https://obsproject.com/forum/resources/freeze-filter.950/) for that info.

> [!NOTE] 
> Plugin for OBS Studio to freeze a source using a filter

### Why does it need a flatpak build ?

According to the discussion in OBS official discord channel, plugin can't be installed via copy files into its flatpak container since 30.2.

So this plugin can't be used in flatpak builds anymore.

But this is not of that plugin.

Hence I wanted to continue using that plugin I build a flatpak version of it.

Atm, the author doesnt have a flatpak. I hope that it will be available soon.

## 🎯 Installation

### Flatpak build

```
git clone https://github.com/Blackstareye/obs-plugin-freeze-filter-flatpak obs_plugin
cd obs_plugin
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install builddir com.obsproject.Studio.Plugin.ObsFreezeFilter.yml
```

## 📄 LICENSE

this project is under the GPL 2.0 License, see [LICENSE](LICENSE)

## 🙏 Credits

plugin is developed by [exeldro](https://github.com/exeldro/obs-freeze-filter) (check him also out 💚):

## 📬 Contact

- **GitHub**: [@blackstareye](https://github.com/Blackstareye)

- **Website** for Freelancing:
    [Oldschoolmanier](https://oldschoolmanier.de)

## General Support of my Projects 💚

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H096MU7)

If you enjoy the work I do and would like to support me, I would be
truly grateful for any donations. Your contribution doesn't just help
keep this project going --- it enables me to pursue new ideas, work on
exciting future projects, and continue creating content that I'm
passionate about. Every donation, no matter how big or small, makes a
real difference and helps me dedicate more time and energy to what I
love doing. Your support enables me doing exactly that, thank you 💚.
