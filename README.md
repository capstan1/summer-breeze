# summer-breeze
heartwarming theme for Home Assistant

## How to apply this theme (for beginners)

1. create a folder named themes in your home assistant directory
2. download summer_breeze.yaml and place it in this new folder
– (place other themes’ files you downloaded before/your preexisting themes.yaml to that very same folder)
3. download the background image and place it in your www folder (create a folder called www if there is none yet)
4. add the following to your configuration.yaml
```
#frontend:
  themes: !include_dir_merge_named themes
```
5. open the lovelace raw editor in the frontend (top right corner of the overview) and add this line:
```background: var(--lovelace-background)```

6. apply the theme by clicking on your Avatar/your letter in the sidebar and choose `summer_breeze` there

7. you’re done!

'' Custom components I used / Credits:
- Compact Custom Header
- Card Modder
  *changes the colors of the markdown cards I used for headers (“Lautsprecher”, “Sensoren”)
  changes the background to transparent for cards used inside vertical stack in card (image 3)*
-Vertical Stack in Card
- Slider Entity Row
  *for the sliders used underneath each light*
- Simple Weather Card
- Mini Graph Card
- Mini Media Player
- Theme Maker *(helped me a lot while tweaking)*
- I started based on Clear Theme 12, thanks a lot for this @naofireblade
