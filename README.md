# cursedgotchi
A̵̢̳̹̳̾͜ ̷̧͎͚͙̐̍̉̄͝c̵̦̩͓̼̗̀̉ù̴̖̞̯̚ś̷̭̗̼̞̰̅̕t̶̢̰̟͕̂͒͆o̶̭̥̠̩͌m̸̤̜̄ ̴̧̻͚͂͝c̶̺̩̭̈̕ủ̴̡͔̼͙̈́̀r̸̔̒̊̌͘ͅs̸̢͋̎͑͐̄è̵̱̞̗͗́̈́͋ḑ̸͓͔̗̫͆̈ ̸͕̦͕̩̯̽̊̇͑̆ẗ̸͔̤̌h̵͇͓̦̖̻͋ȅ̵͓̝̬̝̃m̶̧͉̹̖͇͘e̵͉̱̟̔̅͜

requirements
>First
>Follow [this tutorial](https://github.com/roodriiigooo/PWNAGOTCHI-CUSTOM-FACES-MOD/tree/main#pwnagotchi-v155---custom-faces-mod-_)
Next step
> Connect pwnagotchi to computer in MANU mode, with SSH connection.
> Copy the images from cursedgotchi into custom faces folder
>
>Stop pwnagotchi service
>
>Open the pwnagotchi config.toml
>vi /etc/pwnagothi/config.toml
>
+i
###
ui.faces.look_r = "/custom-faces/LOOK-R.png"
ui.faces.look_l = "/custom-faces/LOOK-L.png"
ui.faces.look_r_happy = "/custom-faces/LOOK-R-HAPPY.png"
ui.faces.look_l_happy = "/custom-faces/LOOK-L-HAPPY.png"
ui.faces.sleep = "/custom-faces/SLEEP.png"
ui.faces.sleep2 = "/custom-faces/SLEEP2.png"
ui.faces.awake = "/custom-faces/AWAKE.png"
ui.faces.bored = "/custom-faces/BORED.png"
ui.faces.intense = "/custom-faces/INTENSE.png"
ui.faces.cool = "/custom-faces/COOL.png"
ui.faces.happy = "/custom-faces/HAPPY.png"
ui.faces.excited = "/custom-faces/EXCITED.png"
ui.faces.grateful = "/custom-faces/GRATEFUL.png"
ui.faces.motivated = "/custom-faces/MOTIVATED.png"
ui.faces.demotivated = "/custom-faces/DEMOTIVATED.png"
ui.faces.smart = "/custom-faces/SMART.png"
ui.faces.lonely = "/custom-faces/LONELY.png"
ui.faces.sad = "/custom-faces/SAD.png"
ui.faces.angry = "/custom-faces/ANGRY.png"
ui.faces.friend = "/custom-faces/FRIEND.png"
ui.faces.broken = "/custom-faces/BROKEN.png"
ui.faces.debug = "/custom-faces/DEBUG.png"
ui.faces.upload = "/custom-faces/UPLOAD.png"
ui.faces.upload1 = "/custom-faces/UPLOAD1.png"
ui.faces.upload2 = "/custom-faces/UPLOAD2.png"
ui.faces.png = true
###
ESC, :wq

Then reboot pwnagotchi service
systemctl restart pwnagotchi
