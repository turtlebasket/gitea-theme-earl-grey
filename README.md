# `earl-grey` Gitea Theme

From: [Artix Linux Gitea](https://gitea.artixlinux.org/explore/repos)

## Usage

Copy into `$GITEA_CUSTOM/public/css/theme-earl-grey.css`. Then, edit `app.ini`:


```toml
# $GITEA_CUSTOM/conf/app.ini

[ui]
DEFAULT_THEME                     = earl-grey
THEMES                            = gitea,arc-green,...,earl-grey
```

