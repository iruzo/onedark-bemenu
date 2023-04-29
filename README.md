<h3 align="center">
    One Dark theme for <a href="https://github.com/Cloudef/bemenu">bemenu</a>
</h3>

![onedark](https://raw.githubusercontent.com/iruzo/onedark-bemenu/main/assets/color.webp)

<p align="center">
	<img src="https://raw.githubusercontent.com/iruzo/onedark-bemenu/main/assets/preview.webp"/>
</p>

## Usage

- Launch from your wm, script or command bemenu adding the desired theme as params:
```sh
# dark
bemenu-run -i -l 20 --fb "#282C34" --ff "#abb2bf" --nb "#282C34" --nf "#abb2bf" --tb "#282C34" --hb "#282C34" --tf "#e06c75" --hf "#e5c07b" --nf "#abb2bf" --af "#abb2bf" --ab "#282C34"
```

- Example for i3/sway config:
```sh
set $menu bemenu-run -i -l 20 --fb "#282C34" --ff "#abb2bf" --nb "#282C34" --nf "#abb2bf" --tb "#282C34" --hb "#282C34" --tf "#e06c75" --hf "#e5c07b" --nf "#abb2bf" --af "#abb2bf" --ab "#282C34"
bindsym $mod+d exec $menu
```

- You can also use an environment variale to set the theme.
```sh
export BEMENU_OPTS='-i -l 20 --fb "#282C34" --ff "#abb2bf" --nb "#282C34" --nf "#abb2bf" --tb "#282C34" --hb "#282C34" --tf "#e06c75" --hf "#e5c07b" --nf "#abb2bf" --af "#abb2bf" --ab "#282C34"
```

