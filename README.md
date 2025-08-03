# Zenit Home Assistant Theme

A beautiful and modern theme for Home Assistant.

## Features

- Dark and light mode variants
- Consistent color scheme
- Optimized for mobile and desktop
- Easy to customize

## Installation

This theme can be installed via HACS (Home Assistant Community Store).

### Via HACS (Recommended)

1. Make sure you have [HACS](https://hacs.xyz/) installed
2. Go to HACS → Frontend
3. Click the "+" button
4. Search for "Custom Home Assistant Theme"
5. Install the theme
6. Restart Home Assistant

### Manual Installation

1. Download the `custom_theme.yaml` file
2. Copy it to your `config/themes/` directory
3. Add the following to your `configuration.yaml`:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
4. Restart Home Assistant

## Usage

1. Go to your Home Assistant profile
2. Select "Custom Theme" from the theme dropdown
3. Enjoy your new theme!

## Customization

You can customize the theme by editing the `custom_theme.yaml` file and modifying the CSS variables.

## Screenshots

<!-- Add screenshots of your theme here -->

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
