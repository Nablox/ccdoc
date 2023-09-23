# $imageTextFill

write a filled text on an image

## Usage

```bash
$imageTextFill[Text;position x;position y;color;opacity]
```

### Example:
<discord-messages>
          <discord-message :bot="false" role-color="#ffcc9a" author="Member">
        !!exec $imageCreate[300;300]<br>$imageTextSize[30]<br>$$imageTextAlign[center]<br>$imageTextFill[CC is Awesome;150;150;#4461b3]<br>$image[$imageOutput]<br><br>
          </discord-message>
          <discord-message :bot="true" role-color="#0099ff" author="Custom Command" avatar="https://media.discordapp.net/avatars/725721249652670555/781224f90c3b841ba5b40678e032f74a.webp">
            <discord-embed slot="embeds" image="https://i.imgur.com/PwNg0VA.png">
            </discord-embed>
        </discord-message>
</discord-messages>