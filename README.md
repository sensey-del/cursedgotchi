<br/>
<p align="center">
  <a href="https://github.com/S3NSEY/Cursedgotchi">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Cursedgotchi</h3>

  <p align="center">
    Custom faces for pwnagotchi
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/sensey-del/cursedgotchi/total) ![Stargazers](https://img.shields.io/github/stars/sensey-del/cursedgotchi?style=social) ![Issues](https://img.shields.io/github/issues/sensey-del/cursedgotchi) 

## About The Project

![Screen Shot](images/screenshot.png)

I decided to create interesting icons for pwnagotchi in my opinion

## Getting Started

>First
>Follow [this tutorial](https://github.com/roodriiigooo/PWNAGOTCHI-CUSTOM-FACES-MOD/tree/main#pwnagotchi-v155---custom-faces-mod-_)

### Prerequisites

> Connect pwnagotchi to computer in MANU mode, with SSH connection.
> Copy the images from cursedgotchi into custom faces folder

### Installation


1. Open the pwnagotchi config.toml

```sh 
vi /etc/pwnagothi/config.toml 
```
2. Add path to folder with custom faces
```sh
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
```

Then reboot pwnagotchi service

```sh
systemctl restart pwnagotchi
```


