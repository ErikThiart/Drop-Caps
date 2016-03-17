# Drop-Caps
Target the first character of the first paragraph using pseudo class selectors. No extra markup needed, but no IE &lt; 9 support.


![Image of Drop Cap Example](https://github.com/ErikThiart/Drop-Caps/blob/master/2016-03-17_14-06-16.jpg)

##HTML

```
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tristique lobortis orci ac lacinia. Fusce eu purus eget diam vehicula auctor nec eu elit. Morbi consequat facilisis orci vel malesuada. Donec ultrices molestie sollicitudin. Aliquam pharetra libero enim. Donec et suscipit massa. Donec dui odio, dignissim non sodales et, tincidunt a sapien. Phasellus elit nibh, adipiscing sed blandit vel, interdum et arcu.
</p>
```

##CSS3

```
p:first-child:first-letter { float: left; color: #903; font-size: 75px; line-height: 60px; padding-top: 4px; padding-right: 8px; padding-left: 3px; font-family: Georgia; }
```

##HOW TO USE:

Easy - Copy and Paste the CSS3 code the rest will take care of itself.
