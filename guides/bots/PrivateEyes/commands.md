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
            <li><a href="#3-misc">2. Premium</a><br />
                <ul>
                    <li><a href="#11-play">2.1 IRL Tags</a><br/></li>
                    <li><a href="#12-skip">2.2 IRL Image</a><br/></li>
                    <li><a href="#11-play">2.3 NSFW Tags</a><br/></li>
                    <li><a href="#12-skip">2.4 NSFW Image</a><br/></li>
                    <li><a href="#11-play">2.5 SFW Tags</a><br/></li>
                    <li><a href="#12-skip">2.6 SFW Image</a><br/></li>
                </ul>
            <li><a href="#3-misc">3. SFW</a><br />
                <ul>
                    <li><a href="#11-play">3.1 Tags</a><br/></li>
                    <li><a href="#12-skip">3.2 Image</a><br/></li>
                    <li><a href="#13-shuffle">3.3 Favourites</a><br/></li>
                </ul>
            <li><a href="#3-misc">4. NSFW</a><br />
                <ul>
                    <li><a href="#11-play">4.1 Tags</a><br/></li>
                    <li><a href="#12-skip">4.2 Image</a><br/></li>
                    <li><a href="#13-shuffle">4.3 Favourites</a><br/></li>
                </ul>
            <li><a href="#2-info">5. Info</a><br />
            <li><a href="#3-misc">6. Misc</a><br />
        </ul>
    </ul>
</blockquote>

## 1. IRL Commands

!!! Warning
These commands feature Nudity.
!!!
This group features a set of commands that relate to real-life images (IRL = In Real Life). The commmands in this group are:

### 1.1 Tags

Shows a list of available tags to be used in ``irl image`` command.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/irl tags

&emsp;**Response:**<br>
&emsp;&emsp;Returns a list of available tags.

<div class="grid-container">
    <div class="blur-image">
        <img src="/assets/private_eyes/irl_tags.png" alt="IRL Tags" />
    </div>
</div>

<figcaption>▲ IRL Tags (Hover to reveal image)</figcaption>

### 1.2 Image

Fetches a random image based on the provided tags.<br/>
&emsp;**Required Argument:** `tag`
!!!info Note
The tag must be one of the tags provided in the `irl tags` command.
!!!

&emsp;**Usage:**<br/>
>/irl image `tag: tag_from_irl_tags`

&emsp;**Response:**<br>
&emsp;&emsp;Returns a random image based on the provided tag.<br>
<div class="grid-container">
    <div class="blur-image">
        <img src="/assets/private_eyes/irl_image.png" alt="IRL Image" />
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
    ♡
</button> - Adds the image to your favourites<br/>

<button style="
    font-size: 20px;
    padding: 0px 16px;
    border: 0px solid #333;
    border-radius: 8px;
    background-color: #F32013;
">
    ⟳
</button> - Fetches a new image based on the same tag
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
        <img src="/assets/private_eyes/irl_fav.png" alt="IRL Favourites" />
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
    <img src="/assets/private_eyes/unlike.png" width=27 length=20>
</button> - Unfavourite the currently displayed image.<br/>
!!!
