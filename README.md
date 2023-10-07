# minihass

![MiniHass-Banner-01](https://github.com/fredrikpersson92/minihass/assets/105781178/5b3fd949-3a2f-406e-904b-17997335c291)

**Hi and welcome to MiniHass MKII, my second version of this minimalistic, rounded, and colorful dashboard UI for Home Assistant.**

***How do I install it?***

This UI does use some custom components that will need to be downloaded from HACS, but other than that, it completely relies on your ability to add lines of YAML code to either your GUI Lovelace dashboard or through the backend, using tools such as Visual Studio Code. The latter is much easier and gives you more control. However, if you already have a dashboard in the GUI editor, then you can add any of the cards there by using the manual card and pasting the code. Please note that some cards rely on templates though, which would need to be added in the Raw Config Editor. You can read more on that [here](https://github.com/custom-cards/button-card#configuration-templates).

***Theme and fonts***

This dashboard is dependent on the correct theme to utilize its full potential, including light and dark modes. I also opted for the font Montserrat from Google Fonts. You can install custom fonts from Google by adding this to your configuration.yaml, or as a *resource* to your GUI dashboard.

```
  lovelace:
    mode: yaml
    resources:
    - url: /www/community/button-card/button-card.js
      type: module
    - url: https://fonts.googleapis.com/css2?family=Montserrat:wght@300;700&display=swap"
      type: css
  ```

***Included cards***

I will keep adding new cards gradually. For now, these are the available card templates you can copy and use:

*Navigate Card
*Light Card
*Garbage Collection Card
*Security Card

