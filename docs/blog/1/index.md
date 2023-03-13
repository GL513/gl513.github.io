---
title: "Finding and Recovering Deleted Images from Discord"
---

By Gavin, Febuary 12th, 2023, 10:32AM
<!--- arbitrary time because I said so. I'll try to have other posts use real timestamps--->
# Finding and Recovering Deleted Images from Discord

!!! warning "Disclaimer!"

    This guide does not guarantee image recovery. I am not a professional at browser development, I'm just a nerdy kid.
## Introduction

<big>[Just skip to the good stuff.](/blog/1/#demonstration)</big>

At some point or another, we have all probably wanted to recover some images, because of family photos, or to prove your point for something. This is especially handy for Discord moderation, and other social platforms.
<br><br>
When deleting images, they are nearly unrecoverable without additional tools. However, when browsing the internet, your browser, such as Firefox or Chrome, will save these images until your session ends.
<br><br>
When an image appears in your browser, it almost always gets cached, in some form or another. The only time when an image is not cached, is when it's just too big to be cached. In this case, it will create a thumbnail. A thumbnail is a smaller, leaner version of the original image, with the cost of quality. Most thumbnails are no larger than 300 pixels tall. In fact, most are a lot smaller.
<br><br>
This means that if you send a rather large image, it likely won't be saved how it was originally. Although, if an image smaller than 300 pixels is *too* small, there is still hope.
<br><br>
The way that Firefox's and Chrome's cache works is nothing new, really. It saves whatever it wants, and if it needs to do something with those files, it can. This includes web links.
<br><br>
Web links are handy because they give you the origin of whatever you are looking for. This could include javascript, videos, images, and other objects. This guide can not only be applied to images, but any publicly accessible file, such as an image uploaded to Discord.
<br>
<br>


## Demonstration

To demonstrate, I am using Discord, a popular channel-based internet chat.
<br>

!!! note "Unfortunately..."

    To use this image recovery process with Discord, you have to keep a window open in the specific channel or chat you want to recover things from all the time. But, that doesn't mean it won't be handy on the fly.

Here is my process:

### Upload an image
I uploaded an image to test with.


![1](https://i.ibb.co/TTjSmYg/Screenshot-20230211-025600.png)

![2](https://i.ibb.co/LPnF1yK/Screenshot-20230211-025648.png)

and on my own account...

![3](https://i.ibb.co/16W9j23/Screenshot-20230211-025902.png)

### Delete the image
Then... deleted it, of course.

![6](https://i.ibb.co/zNpzSYC/Screenshot-20230211-030959.png)

### Restoring from  Firefox
1. In Firefox, go to the page `about:cache?storage=disk`. This page will show you the internals of links cached potentially for later use.
<br>
2. Now, press `ctrl`+`f` to use the "find" function. This is standard on a lot of applications too, not just browsers.
<br>
3. A small windows with a text box should appear that says "Find in page." Type in something like "discord.com" or ".png" and press enter.
<br>
4. You might have multiple search results appear. For this, you can try to use your judgement and look at the web links. Now you should see your image link. You can click on the link, where Firefox then opens another page called "Cache entry information." From here, you can just click the link at the top of the page after the "key:" section.

![5](https://i.ibb.co/PtXtC7h/Screenshot-20230211-034201.png)

5. To save the image, right click on the image and click "Save Image As"



### Restoring from Chrome
1. In Chrome, press `ctrl`+`shift`+`I` to open the developer window, also known as the Inspect Element. Navigate to the "sources" tab.
<br>
2. Go to the "media.discordapp.net" dropdown.
<br>
3. Now, you can navigate through all of the lower level dropdowns, and find the file you are looking for. Click on it and it will show you a preview.

![6](https://i.ibb.co/nPfnjmZ/Deleted-Objects-Inspect-Chrome.png)

<br>
4. To save the image, right click on the preview and press "Save image as..." Chrome will save it to your Downloads folder, or if you have the setting turned on, it will prompt you where to save it to.

## Conclusion

Although social applications and clients do try to make it seem as if things are inaccesible after deletion, it is inevitable that there will be a loophole.

Someone will always find a loophole around things. That's why developers need to be attentive and test their product thoroughly to keep bad things from happening.

Be careful with your newfound power. It can be used to help someone for a legitimate reason, but bad guys could also use the same tactic to blackmail someone, too.

Stay safe out there!
