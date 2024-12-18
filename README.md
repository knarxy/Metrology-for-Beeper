# Metrology for Beeper

Metrology is a series of app customizations and redesigns aimed at bringing a bold, clear, and consistent user experience to [various apps](https://github.com/Madelena?tab=repositories&q=Metrology). Its design language is based on [Metro](https://en.wikipedia.org/wiki/Metro_(design_language)) and [Fluent](https://www.microsoft.com/design/fluent/) design systems pioneered by Microsoft Design since the 2010s.

This is a theme for [Beeper](https://www.beeper.com/), a brand-new universal chat client!

### This fork only maintains the light theme variant (whilst the dark theme code is still restorable, it's just commented out)
![image](https://user-images.githubusercontent.com/4341881/208801551-3e1e637b-bd79-40f8-850b-26322019f49e.png)
*Light Theme*

## How to Install

To install, simply copy and paste [the CSS code](https://github.com/knarxy/Metrology-for-Beeper/blob/main/Metrology-for-Beeper_minified.css) to the Custom CSS box under Settings > Appearances, and you're all set.

As theming for Beeper is still at an early stage of development, so any new updates may break the theme. As a precaution, the app will reset to the base theme every time the app is restarted. You will need to go back into Settings > Appearance and press the Apply button to reapply the theme each time.

## Theme Customizations

### Change Theme Color

The default color is set to purple (my favorite), and you are not limited to that! Simply change the first line:
```css
--metrology-hue: 275;
```
Enter a number between 0 to 355, and you are all set!
(0 = red, 30 = orange, 60 = yellow, 120 = green, 180 = teal, 210 = blue, 300 = purple)

### Change Favorites size

![image](https://user-images.githubusercontent.com/4341881/209044618-a5e25edb-1c85-41c3-ad81-8e3f5af08902.png)

You can make Favorite avatars on the Rooms List smaller or even larger, by changing the `--metrology-favorites-size` variable.

