# Godot Ascii Post Processing Shader
The **Godot Ascii Post Processing Shader** shader graph based post processing shader for godot 4 that converts the screen space into ascii.

# Features
## Customizable Character Sets

![ascii-sample-texture](https://user-images.githubusercontent.com/10996715/234729761-e1c6fb63-7c6b-4f5a-a7dc-4340afda7ab9.png)

Any monospaced one directional image can be used as a character set regardless of character count.
Higher count character sets allow for greater brightness sampling.

## Variable Pixel Density
![variable pixel density example](https://user-images.githubusercontent.com/10996715/234730823-149d3840-9a24-41ea-b0b9-f41693be6669.png)
 **Godot Ascii Post Processing Shader** allows you to change the pixelation settings, so you can fine tune exactly how large the displayed characters are and the effective resolution the image renders at.

## Curve based brightness control
![curve based brightness example](https://user-images.githubusercontent.com/10996715/234731590-e39a0614-742f-49a6-823c-8ad8990bcc82.png)
Allows you to manage your brightness via curve to achieve the proper lighting for a given game.

##Black and White/Color Support
A toggle allowing you to select whether the scene should be rendered with color, or purely brightness information
