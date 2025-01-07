---
icon: gear
order: 900
---

<style>
    a.external{
        display: inline-flex;
        align-items: center;
        text-decoration: none;
    }
    a.external:hover {
        text-decoration: underline;
    }
    .custom_image {
            border-radius:50%;
    }

    .grid-container {
        display: grid; /* Enable Grid layout */
        place-items: center; /* Center content horizontally and vertically */
        height: ; /* Full viewport height */

    }

    .blur-image {
        overflow: hidden; /* Hide any overflowing content */
        filter: blur(15px);
        transition: filter 0.5s ease; /* Smooth transition */
    }

    .blur-image img {
        width: 100%; /* Stretch image to fill div width */
        height: 100%; /* Stretch image to fill div height */
        object-fit: cover; /* Ensure the image fills the div without distortion */
    }

    .blur-image:hover {
        filter: none;
    }

    figcaption {
        font-size: 0.8em;
        color: #999;
        margin-top: 2em;
        text-align: center;
    }
</style>

# <img class="custom_image" src="https://images.disutils.com/bot_assets/profile_pictures_jpg/PrivateEyes.jpg" width=50 length=50> Private Eyes's Commands

!!! Disclaimer
I'm a boob guy so all the pics I'm going to use are related to boobs. If you're not comfortable with that, then I don't care because I like it that way. If you're still reading this, then you're a pervert like me.
!!!

Private Eyes consists a total of **37 commands**, which are divided into **6 categories**.

Here's a list of the commands with their respective categories:

<blockquote style="width: 50%; font-size: 16px; padding: 10px; border-left: 4px solid #5865F2;">
📋Table of Contents
    <ul>
        <li><a href="#private-eyess-commands">Private Eyes's Commands</a><br /></li>
        <ul>
            <li><a href="#1-irl-commands">1. IRL</a><br /></li>
                <ul>
                    <li><a href="#11-tags">1.1 Tags</a><br/></li>
                    <li><a href="#12-image">1.2 Image</a><br/></li>
                    <li><a href="#13-favourites">1.3 Favourites</a><br/></li>
                </ul>
            <li><a href="#3-misc">2. SFW</a><br />
                <ul>
                    <li><a href="#11-play">2.1 Tags</a><br/></li>
                    <li><a href="#12-skip">2.2 Image</a><br/></li>
                    <li><a href="#13-shuffle">2.3 Favourites</a><br/></li>
                </ul>
            <li><a href="#3-misc">3. NSFW</a><br />
                <ul>
                    <li><a href="#11-play">3.1 Tags</a><br/></li>
                    <li><a href="#12-skip">3.2 Image</a><br/></li>
                    <li><a href="#13-shuffle">3.3 Favourites</a><br/></li>
                </ul>
            <li><a href="#3-misc">4. Premium</a><br />
                <ul>
                    <li><a href="#11-play">4.1 IRL Tags</a><br/></li>
                    <li><a href="#12-skip">4.2 IRL Image</a><br/></li>
                    <li><a href="#11-play">4.3 NSFW Tags</a><br/></li>
                    <li><a href="#12-skip">4.4 NSFW Image</a><br/></li>
                    <li><a href="#11-play">4.5 SFW Tags</a><br/></li>
                    <li><a href="#12-skip">4.6 SFW Image</a><br/></li>
                </ul>
            <li><a href="#2-info">5. Info</a><br />
            <li><a href="#3-misc">6. Misc</a><br />
        </ul>
    </ul>
</blockquote>

## 1. IRL Commands

!!!danger Warning
These commands feature Nudity.
!!!
This group features a set of commands that relate to real-life images (IRL = In Real Life) before using these make sure you are alone and your door is locked if you don't want to get caught in an awkward situation. The commmands in this group are:

### 1.1 Tags

Shows a list of available tags to be used in ``irl image`` command.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/irl tags

&emsp;**Response:**<br>
&emsp;&emsp;Returns a list of available tags.

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/irl_tags.png" alt="IRL Tags" />
    </div>
</div>

<figcaption>▲ IRL Tags (Hover to reveal image)</figcaption>

### 1.2 Image

Fetches a random image based on the provided tags.<br/>
&emsp;**Required Argument:** `<tag>`
!!!info Note
The tag must be one of the tags provided in the `irl tags` command.
!!!

&emsp;**Usage:**<br/>
>/irl image `tag: tag_from_irl_tags`

&emsp;**Response:**<br>
&emsp;&emsp;Returns a random image based on the provided tag.<br>
<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/irl_image.png" alt="IRL Image" />
    </div>
</div>
<figcaption>▲ IRL Image (Hover to reveal image)</figcaption>

!!! Additional Info on Buttons
<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(67, 93, 189);
">
    ⟳
</button> - Fetches a new image based on the same tag

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color: #F32013;
">
    ♡
</button> - Adds the image to your favourites<br/>

!!!

### 1.3 Favourites

Show the images in your favourites list that were added via the <button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(67, 93, 189);
">
    ♡
</button> in ``irl image`` command.

&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/irl tags

&emsp;**Response:**<br>
&emsp;&emsp;Shows an embed paginator with to cycle your favourite list.

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/irl_fav.png" alt="IRL Favourites" />
    </div>
</div>
<figcaption>▲ IRL Favourites (Hover to reveal image)</figcaption>

!!! Additional Info on Buttons
<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
   ⏪
</button> - Show first image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
   ⬅️
</button> - Show previous image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:#F32013;
">
    🗑️
</button> - Delete the embed.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ➡️
</button> - Show next image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ⏩
</button> - Show last image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:#F32013;
">
    <img src="https://images.disutils.com/disutils_docs/private_eyes/unlike.png" width=27 length=20>
</button> - Unfavourite the currently displayed image.<br/>
!!!

## 2. SFW Commands

!!!warning Warning
These commands feature Ecchi content that's not safe for kids.
!!!
This group features a set of commands that relate to SFW images. They might or might not contain Nudity but that does not mean kids can use them.

### 2.1 Tags

Shows a list of available tags to be used in ``sfw image`` command.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/sfw tags

&emsp;**Response:**<br>
&emsp;&emsp;Returns a list of available tags.

<div class="grid-container">
    <div>
        <img src="https://images.disutils.com/disutils_docs/private_eyes/sfw_tags.png" alt="SFW Tags" />
    </div>
</div>
<figcaption>▲ SFW Tags</figcaption>

### 2.2 Image

Shows a random image based on the provided tags.<br/>
&emsp;**Required Argument:** `<tag>`
!!!info Note
The tag must be one of the tags provided in the `sfw tags` command.
!!!

&emsp;**Usage:**<br/>
>/sfw image `tag: tag_from_sfw_tags`
>/sfw image `tag: oppai`

&emsp;**Response:**<br>
&emsp;&emsp;Returns a random image based on the provided tag.<br>

<div class="grid-container">
    <div>
        <img src="https://images.disutils.com/disutils_docs/private_eyes/sfw_image.png" alt="SFW Image" />
    </div>
</div>
<figcaption>▲ SFW Image</figcaption>

!!! Additional Info on Buttons
<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(67, 93, 189);
">
    ⟳
</button> - Fetches a new image based on the same tag

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color: #F32013;
">
    ♡
</button> - Adds the image to your favourites<br/>

!!!

### 2.3 Favourites

Show the images in your favourites list that were added via the <button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(67, 93, 189);
">
    ♡
</button> in ``sfw image`` command.

&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/sfw tags

&emsp;**Response:**<br>
&emsp;&emsp;Shows an embed paginator with to cycle your favourite list.

<div class="grid-container">
    <div>
        <img src="https://images.disutils.com/disutils_docs/private_eyes/sfw_fav.png" alt="SFW Favourites" />
    </div>
</div>
<figcaption>▲ SFW Favourites</figcaption>

!!! Additional Info on Buttons
<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
   ⏪
</button> - Show first image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
   ⬅️
</button> - Show previous image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:#F32013;
">
    🗑️
</button> - Delete the embed.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ➡️
</button> - Show next image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ⏩
</button> - Show last image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:#F32013;
">
    <img src="/assets/private_eyes/unlike.png" width=27 length=20>
</button> - Unfavourite the currently displayed image.<br/>
!!!

## 3. NSFW Commands

!!!danger Warning
These commands feature Nudity.
!!!
This group features a set of commands that relate to NSFW images that are completely not for kids to see so make sure to chase away any kids around you. The commmands in this group are:

### 3.1 Tags

Shows a list of available tags to be used in ``nsfw image`` command.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/nsfw tags

&emsp;**Response:**<br>
&emsp;&emsp;Returns a list of available tags.

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes//nsfw_tags.png" alt="NSFW Tags" />
    </div>
</div>
<figcaption>▲ NSFW Tags(Hover to reveal image)</figcaption>

### 3.2 Image

Fetches a random image based on the provided tags.<br/>
&emsp;**Required Argument:** `<tag>`
!!!info Note
The tag must be one of the tags provided in the `nsfw tags` command.
!!!

&emsp;**Usage:**<br/>
>/nsfw image `tag: tag_from_nsfw_tags`
>/nsfw image `tag: oppai`

&emsp;**Response:**<br>
&emsp;&emsp;Returns a random image based on the provided tag.<br>

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/nsfw_image.png" alt="NSFW Image" />
    </div>
</div>
<figcaption>▲ NSFW Image(Hover to reveal image)</figcaption>

!!! Additional Info on Buttons
<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(67, 93, 189);
">
    ⟳
</button> - Fetches a new image based on the same tag

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color: #F32013;
">
    ♡
</button> - Adds the image to your favourites<br/>
!!!

### 3.3 Favourites

Show the images in your favourites list that were added via the <button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(67, 93, 189);
">
    ♡
</button> in ``nsfw image`` command.

&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/nsfw Favourites

&emsp;**Response:**<br>
&emsp;&emsp;Shows an embed paginator with to cycle your favourite list.

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/nsfw_fav.png" alt="NSFW Favourites" />
    </div>
</div>
<figcaption>▲ NSFW Favourites(Hover to reveal image)</figcaption>

!!! Additional Info on Buttons
<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ⏪
</button> - Show first image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ⬅️
</button> - Show previous image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:#F32013;
">
    🗑️
</button> - Delete the embed.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ➡️
</button> - Show next image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:rgb(70, 69, 69);
">
    ⏩
</button> - Show last image.<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color:#F32013;
">
    <img src="https://images.disutils.com/disutils_docs/private_eyes/unlike.png" width=27 length=20>
</button> - Unfavourite the currently displayed image.<br/>
!!!

## 4. Premium Commands

!!!info Note
These commands are only available to premium users.
