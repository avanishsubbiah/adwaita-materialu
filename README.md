# Adwaita Preset Generator using Material U Color Generation
Material U Color generation is done using the material-color-utilities available here: https://github.com/material-foundation/material-color-utilities

## Requirements
 - **AdwCustomizer** | Needed for applying preset | https://github.com/ArtyIF/AdwCustomizer
 - **NodeJS** | Required to run script

## Installation
```
git clone https://github.com/avanishsubbiah/adwaita-materialu.git
cd adwaita-materialu
npm install
npm install -g .
```

## Usage
Run the command below and the preset generated will be written to the folder where the image is located.
```
gen-materialu-theme -i <Path to image file> -t <Theme type (dark|light)>
```
Then move the generated preset.json file to the preset folder for AdwCustomizer.
 - Default Location: `$HOME/.var/app/com.github.ArtyIF.AdwCustomizer/config/presets`
