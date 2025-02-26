---
title: Grainy & Gradient Rainbow Text Animation
description: Browser source for OBS with a bouncing welcome animation adapted for SB from a Coedpen made by Shaw at keyframers
published: true
date: 2023-03-06T14:16:54.094Z
tags: 
editor: markdown
dateCreated: 2023-03-06T14:16:54.094Z
---

# Import Code

```
TlM0RR+LCAAAAAAABADFVUtv1DAQviPxH6KVels3dpxnJYSAQuHSSqVwQRz8GO9GTewlj+2uqv53HGcXkg2vSi3NIQ9/38x4voxnbp8/87zZGqo6N3p24gVzt6BZCfZrdlaxXG+9S3vn5sa7gk0z6xlMNNaitqQv3bfn3fYPC+WyMyUQYogwRYmkBIUSCMpEqBDFEEsWKQiirPfljL610LqQnEEYZZKjLJQpCrniKE0ThYjiMZUJSCn4wA404wV0EZuqhcH6RhSthHeVKd/ndWOqraUoVtQDzl+zdKxFZdrVjrZa5sJ7qxSIph5QWHHDtvVlq6cxKqalKV85taaoMFq0VQW6mWIThUcqO0otQMP5LosrKFemYjbR+Zhk2kr8YI1zPaC2VdFxVF7Aie/7b078T7UtDV+yhi39Cw2nVb4G/xTq68as/IXzhexD5jaFGjVWOV9auf1cS9gcL5uyeNmp/OKotY6ODsLZ7DW4LD+4ksG7C/3itr8OXPS1FsQiwXEkkAxwgsJIEcQUThGTQaIAohQ4PzC8gXyx7FTHx3iMNNtVpxRNx8v7MtBtUYyR35Rgv79Ohy7Kz9W7+f/6nXXDmo6FH0n2lAccZ6lCCuIQhZnMukMrEbaCk4SEMQvje8uOH1J28i+yr1nhWk9k8xy7Kdnm8w48QPpjPTm0A3FUFNJAxRJlrv+xOEMsVhlScRZS20AYjtV9xSEYBw8pT/CUVUkeqSqB4lRFhCIpIjtAKKcoDQKCKCegVMKw4PC0VUkHsu9fvx42/rMuhOv+A0iYomCrGuQA7UHnqGf2s/QPo/meI5YXRlznejGZsfv5efH642y6C2HK0p6S/SbvvgPg6PAJawgAAA==
```

# Installation

In Streamer.bot in select `Import` from the top left.
Copy the `Import Code` and paste it into the `Import String`.

- [<i class="mdi mdi-file-download"></i> **Assets Needed *Click to Download***](/assets/grainy-rainbow-text/grainy-rainbow-text.zip)
{.btn-grid .my-5}

Download the Grainy Rainbow Text zip and extract it to a folder of your choice.

Add a Browser source in OBS. Give it a name and in Properties ***do not tick `Local file`*** but do tick `Shutdown source when not visible` and `Refresh browser source when scene becomes active`.
Click `OK`. *Do not worry that we have not given it a URL*

Using Windows Explorer navigate to the folder you exported the zip to and open the index.html file with your browser.

Click inside the address bar of the browser window and copy the location Should start with `file:///`

In Streamer.bot go to the action you imported called Bouncing Welcome and double-click the OBS Set Browser Source URL to edit it.
![grainy-setup.png](/assets/grainy-rainbow-text/grainy-setup.png)
Choose your Scene, Source and paste the address you copied into the URL box as shown above. Next take this string and paste it to the end of the RUL you just added. `?name=%user%` so that the end of the string looks like this:
`\index.html?name=%user%`

Assign the action to a command, channel point redeem or anything really

# Video Example
<video width="100%" height="100%" aspectRatio="16/9" controls>
<source src="/assets/grainy-rainbow-text/grainy-rainbow-text.mp4" type="video/mp4" />
</video>

# Contributors

[Lyfesaver74](https://www.twitch.tv/Lyfesaver74){.twitch}
[Original Codepen](https://codepen.io/LukyVj/pen/poOjqBve){.codepen}
{.contributors}