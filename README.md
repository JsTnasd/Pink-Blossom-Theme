<div align="center">

# 🌸 Pink Blossom

A pink and violet BetterDiscord theme with five wallpapers, adjustable background shading, and soft pastel details.

![Temporary Pink Blossom preview](https://res.cloudinary.com/bfyniy76/image/upload/v1790360681/image.png)

*Preview*

</div>

## ✨ Features

- 🖼️ Switch between five wallpapers by changing one number.
- 💜 Adjust the violet overlay opacity to balance the wallpaper and text readability.
- 🎀 Pink reactions, controls, and channel icons.
- 🌙 Darker settings pages for easier reading.
- 🪟 Profile cards show the selected wallpaper on an opaque background, so chat messages do not show through.
- 💬 Slash command suggestions use a solid violet panel for clear text.
- 🎮 Profile Board tabs have larger, easier-to-use buttons.

## 🖼️ Wallpapers

| Choice | Preview | Image |
| :---: | :--- | :--- |
| **Wallpaper 1** | <img src="https://wallpaperaccess.com/full/626893.jpg" width="240" alt="Wallpaper 1"> | [Open image](https://wallpaperaccess.com/full/626893.jpg) |
| **Wallpaper 2** | <img src="https://i.redd.it/ykflm71667s21.png" width="240" alt="Wallpaper 2"> | [Open image](https://i.redd.it/ykflm71667s21.png) |
| **Wallpaper 3** | <img src="https://res.cloudinary.com/bfyniy76/image/upload/v1790361353/wp15382549.png" width="240" alt="Wallpaper 3"> | [Open image](https://res.cloudinary.com/bfyniy76/image/upload/v1790361353/wp15382549.png) |
| **Wallpaper 4** | <img src="https://preview.redd.it/1920x1080-pink-v0-pt1iqfk90lh71.jpg?auto=webp&amp;s=c6f0cc6440a027a896f94029a799a0610ac92969" width="240" alt="Wallpaper 4"> | [Open image](https://preview.redd.it/1920x1080-pink-v0-pt1iqfk90lh71.jpg?auto=webp&s=c6f0cc6440a027a896f94029a799a0610ac92969) |
| **Wallpaper 5** | <img src="https://www.zastavki.com/pictures/1920x1080/2020Anime_Anime_girl_with_pink_hair_in_a_white_dress_144914_23.jpg" width="240" alt="Wallpaper 5"> | [Open image](https://www.zastavki.com/pictures/1920x1080/2020Anime_Anime_girl_with_pink_hair_in_a_white_dress_144914_23.jpg) |

## 📥 Installation

1. Download `Pink-Blossom.theme.css` from this repository.
2. Place it in `%AppData%\BetterDiscord\themes`.
3. Open **Discord Settings → Themes**, disable the previous version, and enable **Pink Blossom**.

## 🎨 Choose a wallpaper

Open `Pink-Blossom.theme.css` and change the number near the top of the file:

```css
--hk-wallpaper: var(--hk-wallpaper-1);
```

Choose any value from `--hk-wallpaper-1` through `--hk-wallpaper-5`. You can also use your own image URL:

```css
--hk-wallpaper: url("https://example.com/my-wallpaper.jpg");
```

## 💜 Adjust the violet overlay

The opacity setting is directly below the wallpaper selection:

```css
--hk-overlay-opacity: .70;
```

`0` shows the wallpaper without the violet overlay, `.50` shows more of the image, `.70` is the default, and `1` fully covers it. Profile cards have their own dark layer to keep text readable.

## 📂 Files

- `Pink-Blossom.theme.css` is the complete theme file to install in BetterDiscord.
- `main.css` contains the same CSS for editing or hosting in this repository; you do not need to install both files.

Wallpapers load from their original image URLs, so an internet connection is needed to display them.
