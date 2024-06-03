# 🌿 Labyrinth

Discover Labyrinth, a serene color scheme inspired by hidden pathways and mossy landscapes. Let its gentle tones guide your creativity with calm elegance.

Labyrinth provides four distinct variants with varying levels of contrast and color vibrancy to suit your preferences:

 - Dusk: The most contrasty variant, perfect for those who prefer sharp distinctions and vibrant colors.
 - Shade: A balanced variant, offering a comfortable middle ground with moderate contrast and vibrancy.
 - Gloom: A softer variant with reduced contrast, ideal for a more subdued and relaxed visual experience.
 - Mist: The least contrasty variant, featuring the most gentle and subtle tones for a calm and unobtrusive interface.

Whether you're coding, designing, or simply exploring new aesthetics, Labyrinth adapts to your needs with its harmonious palette.

## Getting started

1. Locate (or create) Alacritty's config file (refer to [the *Configuration* section of Alacritty's readme](https://github.com/alacritty/alacritty/tree/master#configuration))
2. Clone this repository
3. Copy the contents of the `dist/` directory to a location of your choosing
4. Import **one** of the TOML files you just copied into Alacritty's config

### Example

The following example will assume that your Alacritty's config path is `~/.config/alacritty/alacritty.toml`.

```sh
# Clone this repository
git clone https://github.com/dgabka/labyrinth-alacritty.git

# Copy the contents of the `dist` directory to Alacritty's config directory
cp ./labyrinth-alacritty/dist/* ~/.config/alacritty

# Delete the cloned repository (optional)
rm -r ./labyrinth-alacritty
```

Import one of theme variants into your Alacritty's config:

```toml
import = ["~/.config/alacritty/labyrinth-dusk.toml"]
```

## Gallery

Fetch featured below is [NerdFetch](https://github.com/thatonecalculator/nerdfetch)

**Labyrinth Gloom**

![Alacritty with Labyrinth Gloom](assets/gloom.png)

**Labyrinth Dusk**

![Alacritty with Labyrinth Dusk](assets/dusk.png)

**Labyrinth Shade**

![Alacritty with Labyrinth Shade](assets/shade.png)

**Labyrinth Mist**

![Alacritty with Labyrinth Mist](assets/mist.png)

### Credits

Thanks to the [Rosé Pine](https://github.com/rose-pine) creators!
A special thanks to [Rosé Pine for Alacritty](https://github.com/rose-pine/alacritty) which this theme is based on.
