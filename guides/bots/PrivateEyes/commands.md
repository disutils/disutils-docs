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

___

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
            <li><a href="#2-sfw-commands">2. SFW</a><br />
                <ul>
                    <li><a href="#21-tags">2.1 Tags</a><br/></li>
                    <li><a href="#22-image">2.2 Image</a><br/></li>
                    <li><a href="#23-favourites">2.3 Favourites</a><br/></li>
                </ul>
            <li><a href="#3-nsfw-commands">3. NSFW</a><br />
                <ul>
                    <li><a href="#31-tags">3.1 Tags</a><br/></li>
                    <li><a href="#32-image">3.2 Image</a><br/></li>
                    <li><a href="#33-favourites">3.3 Favourites</a><br/></li>
                </ul>
            <li><a href="#4-premium-commands">4. Premium</a><br />
                <ul>
                    <li><a href="#41-sfw-tags">4.1 SFW Tags</a><br/></li>
                    <li><a href="#42-nsfw-tags">4.2 NSFW Tags</a><br/></li>
                    <li><a href="#43-irl-tags">4.3 IRL Tags</a><br/></li>
                    <li><a href="#44-sfw-image">4.4 SFW Image</a><br/></li>
                    <li><a href="#45-nsfw-image">4.5 NSFW Image</a><br/></li>
                    <li><a href="#46-irl-image">4.6 IRL Image</a><br/></li>
                </ul>
            <li><a href="#5-info">5. Info</a><br />
            <li><a href="#6-misc">6. Misc</a><br />
        </ul>
    </ul>
</blockquote>

___

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
>/irl favourites

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

___

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
>/sfw image `tag: tag_from_sfw_tags`<br/>
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
>/sfw favourites

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

___

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
>/nsfw image `tag: tag_from_nsfw_tags`<br/>
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

___

## 4. Premium Commands

!!!warning For Premium Users only
These commands are only available to premium users. In order to use these commands you need to buy our premium subscription of **Anime Vault**. Which can be bought from Discord [here.](https://discord.com/application-directory/1295512320801374279/store/1322762632972861583)

Go and get your premium subscription now to use these commands.
!!!

These commands are may look the same as the one above but trust me they have better results and of course more tags. So once again remember to lock the door but this time double check it.

### 4.1 SFW Tags

Shows a list of available tags to be used in ``premium sfw image`` command.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/premium sfw tags

&emsp;**Response:**<br>
&emsp;&emsp;Returns a list of available tags.

<div class="grid-container">
    <div>
        <img src="https://images.disutils.com/disutils_docs/private_eyes/prem_sfw_tags.png" alt="NSFW Tags" />
    </div>
</div>
<figcaption>▲ Premium SFW Tags(Hover to reveal image)</figcaption>

### 4.2 NSFW Tags

Shows a list of available tags to be used in ``premium nsfw image`` command.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/premium nsfw tags

&emsp;**Response:**<br>
&emsp;&emsp;Returns a list of available tags.

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/prem_nsfw_tags.png" alt="NSFW Tags" />
    </div>
</div>
<figcaption>▲ Premium NSFW Tags(Hover to reveal image)</figcaption>

### 4.3 IRL Tags

Shows a list of available tags to be used in ``premium irl image`` command.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/premium irl tags

&emsp;**Response:**<br>
&emsp;&emsp;Returns a list of available tags.

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/prem_irl_tags.png" alt="NSFW Tags" />
    </div>
</div>
<figcaption>▲ Premium IRL Tags(Hover to reveal image)</figcaption>

### 4.4 SFW Image

Fetches a random image based on the provided tags but this time you can tag a user in there.<br/>
&emsp;**Required Argument:** `<tag>` `<member>`
!!!info Note
The tag must be one of the tags provided in the `premium nsfw tags` command.
!!!

&emsp;**Usage:**<br/>
>/premium sfw image `tag: tag_from_prem_sfw_tags` `member: @user`<br/>
>/premium sfw image `tag: slap` `member: @RejectModderss`

&emsp;**Response:**<br>
&emsp;&emsp;Returns a random image based on the provided tag and tags the user in a message sent along the image.<br>

<div class="grid-container">
    <div>
        <img src="https://images.disutils.com/disutils_docs/private_eyes/prem_sfw_image.png" alt="SFW Image" />
    </div>
</div>
<figcaption>▲ Premium SFW Image</figcaption>

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
</button> - Adds the image to your favourites (Can be found in ``sfw favourites``).<br/>

!!!

### 4.5 NSFW Image

Fetches a random image based on the provided tags.<br/>
&emsp;**Required Argument:** `<tag>` `<member>`
!!!info Note
The tag must be one of the tags provided in the `premium nsfw tags` command.
!!!

&emsp;**Usage:**<br/>
>/premium nsfw image `tag: tag_from_prem_nsfw_tags`<br/>
>/premium nsfw image `tag: maid`

&emsp;**Response:**<br>
&emsp;&emsp;Returns a random image based on the provided tag.<br>

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/prem_nsfw_image.png" alt="NSFW Image" />
    </div>
</div>
<figcaption>▲ Premium NSFW Image(Hover to reveal image)</figcaption>

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
</button> - Adds the image to your favourites (Can be found in ``nsfw favourites``).<br/>

!!!

### 4.6 IRL Image

Fetches a random image based on the provided tags.<br/>
&emsp;**Required Argument:** `<tag>`
!!!info Note
The tag must be one of the tags provided in the `premium irl tags` command.
!!!

&emsp;**Usage:**<br/>
>/premium irl image `tag: tag_from_prem_irl_tags`<br/>
>/premium irl image `tag: cosplay`

&emsp;**Response:**<br>
&emsp;&emsp;Returns a random image based on the provided tag.<br>

<div class="grid-container">
    <div class="blur-image">
        <img src="https://images.disutils.com/disutils_docs/private_eyes/prem_irl_image.png" alt="IRL Image" />
    </div>
</div>
<figcaption>▲ Premium IRL Image(Hover to reveal image)</figcaption>

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
</button> - Adds the image to your favourites (Can be found in ``irl favourites``). <br/>

!!!

___

## 5. Info

A set of commands to know various info regarding the bot or a user.

!!!Important
This group is common to all our bots a details regarding this group can be found [here](/guides/common-commands.md#info-cog).
!!!

---

## 6. Misc

A set miscellenous commands that can be used for bug reporting and some other purposes that have nothing to do with the main functionality of bot.
!!!Important
This group is common to all our bots a details regarding this group can be found [here](/guides/common-commands.md#misc-cog).
!!!

---
