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
    border-radius: 50%; 
    object-fit: cover; 
    overflow: hidden; 
    }
</style>

# <img class="custom_image" src="https://images.disutils.com/bot_assets/profile_pictures_jpg/Harmodify.jpg" width=50 lenght=50> Harmodify's Commands

___

Harmodify consists of a total of **23 commands**, that have been organized into **3 groups** for the ease of our users.

Here is a list of available groups and the commands included:

<blockquote style="width: 50%; font-size: 16px; padding: 10px; border-left: 4px solid #5865F2;">
📋Table of Contents
    <ul>
        <li><a href="#harmodifys-commands">Harmodify's Commands</a><br /></li>
        <ul>
            <li><a href="#1-music">1. Music</a><br /></li>
            <ul>
                <li><a href="#11-play">1.1 Play</a><br/></li>
                <li><a href="#12-skip">1.2 Skip</a><br/></li>
                <li><a href="#13-shuffle">1.3 Shuffle</a><br/></li>
                <li><a href="#14-nightcore">1.4 Nightcore</a><br/></li>
                <li><a href="#15-bass">1.5 Bass</a><br /></li>
                <li><a href="#16-toggle">1.6 Toggle</a><br /></li>
                <li><a href="#17-volume">1.7 Volume</a><br /></li>
                <li><a href="#18-disconnect">1.8 Disconnect</a><br /></li>
                <li><a href="#19-queue">1.9 Queue</a><br /></li>
                <li><a href="#110-clear-queue">1.10 Clear Queue</a><br /></li>
                <li><a href="#111-lyrics">1.11 Lyrics</a><br /></li>
            </ul>
                <li><a href="#2-info">2. Info</a><br />
                    <ul>
                        <li><a href="#21-spotify">2.1 Spotify</a><br /></li>
                    </ul>
                <li><a href="#3-misc">3. Misc</a><br />
        </ul>
    </ul>
</blockquote>

---

## 1. Music

This group features a set of commands related to the Music functionality of the bot.
!!!warning
The commands in this group require you to be in a voice channel for functionality except Lyrics commands.
!!!

### 1.1 Play

Plays a song with a qiven query.<br/>
&emsp;**Required Argument:** `<query>`
> `<query>` can be one of the following.
>
>- Name of song
>- Url:
>   - Can either be pointing to a song or playlist.
>   - **Supported Sources:** Youtube, Youtube Music, Spotify, Soundcloud and Apple Music.<br/>

&emsp;**Usage:**
> /music play `query: Sunroof`<br>
> /music play `query: https://www.youtube.com/watch?v=8xg3vE8Ie_E`<br>
> /music play `query: https://open.spotify.com/track/7hDoxkN20lLb06zifzYnD2`<br>

![](https://images.disutils.com/disutils_docs/harmodify/music_play_usage.png)
&emsp;**Response:**<br>
&emsp;&emsp;Plays the searched song if found otherwise gives a not found error.
![](https://images.disutils.com/disutils_docs/harmodify/music_play_response.png)
The details about the fucntioning of the buttons can be found [here](/guides/bots/Harmodify/play_button_info.md).

### 1.2 Skip

Skips the currently playing song.<br/>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/music skip

&emsp;**Response:**<br>
&emsp;&emsp;Sends a confirmation embed and skips the currently playing song.

### 1.3 Shuffle

Shuffles the current playing queue.<br>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/music shuffle

&emsp;**Response:**<br>
&emsp;&emsp;Shuffles the current playing queue if there is one otherwise does nothing.

### 1.4 Nightcore

Toggles on/off the Nightcore style.<br>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/music nightcore

&emsp;**Response:**<br>
&emsp;&emsp;Increases Pitch and Speed of the songs currently being played and in queue.

!!!Note
What is Nightcore? Have a look
<a class="external" href="https://en.wikipedia.org/wiki/Nightcore" target="_blank" >
    here
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
         class="bi bi-box-arrow-up-right" viewBox="0 0 16 16" style="margin-left: 4px;">
        <path fill-rule="evenodd" d="M8.636 3.5a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5"/>
        <path fill-rule="evenodd" d="M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0z"/>
    </svg>
</a>.<br>
Even I don't know what Nightcore is. :skull:
!!!

### 1.5 Bass

Sets the bass level.<br>
&emsp;**Required Argument:** `<level>`
> `<level>` the bass boost level to set.
>
> - **Max Value:** 100
> - **Min Value:** 1

&emsp;**Response:**<br>
&emsp;&emsp;Sets the bass level to the given level.

### 1.6 Toggle

Pauses or Resumes the player depending on it's current state.<br>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/music toggle

&emsp;**Response:**<br>
&emsp;&emsp;Changes the current state of player if it's paused, it resumes the audio playback, otherwise pauses the playback.

### 1.7 Volume

Sets the Volume of the player.<br>
&emsp;**Required Argument:** `<value>`
> `<value>` The amount you want the volume to be set at.<br>
>
> - **Max Value:** 100
> - **Min Value:** 0 (which is equal to muting the audio.)

&emsp;**Response:**<br>
&emsp;&emsp;Changes the volume to the amount you set it to be if it's a valid value.

### 1.8 Disconnect

Stops the Music Player.<br>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/music disconnect

&emsp;**Response:**<br>
&emsp;&emsp;Stops the currently playing song and clears up the queue, exits the voice channel.

### 1.9 Queue

Shows the queue.<br>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/music queue

&emsp;**Response:**<br>
&emsp;&emsp;Sends an embed showing the current playing queue.

### 1.10 Clear Queue

Clears the queue.<br>
&emsp;**Required Argument:** `None`

&emsp;**Usage:**<br/>
>/music clearqueue

&emsp;**Response:**<br>
&emsp;&emsp;Clears the current playing queue.

### 1.11 Lyrics

Fetches the lyrics of the searched Song.<br>
&emsp;**Required Argument:** `<title>` `[author]`
>
> - `<title>` the name of the song.<br>
> - `[author]` (Optional) the singer of the song.

&emsp;**Usage:**<br/>
>/music lyrics `title: Imagine Dragon Bones`<br>
>/music lyrics `title: Love Story` `author: Taylor Swift`

&emsp;**Response:**<br>
&emsp;&emsp; Sends an Embed with the lyrics of the searched title otherwise sends an error if no lyrics found

---

## 2. Info

A set of commands to know various info regarding the bot or a user.

!!!Important
This group is common to all our bots a details regarding this group can be found [here](/guides/common-commands.md#info-cog).
!!!

### 2.1 Spotify

!!!Info
This is an exclusive command to **Harmodify Only.**
!!!
Shows the currently playing song in a user's activity.<br>
&emsp;**Required Arguments:** `[user]`
> `[user]` (Optional) The user whom activity you want to know.

&emsp;**Usage:**
>/info spotify<br>
>/info spotify `user: @Jiggly-Ball`

&emsp;**Response**<br>
&emsp;&emsp;Sends an embed containg info regarding the song, if the user tagged is listening to a song on Spotify. If no user is tagged then it will check your Spotify activity.<br>
!!!warning Note
This command will only work if it is the orignal spotify client provided by <a class="external" href="https://open.spotify.com/" target="_blank" >
    Spotify
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
         class="bi bi-box-arrow-up-right" viewBox="0 0 16 16" style="margin-left: 4px;">
        <path fill-rule="evenodd" d="M8.636 3.5a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5"/>
        <path fill-rule="evenodd" d="M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0z"/>
    </svg>
</a>. Alternatives like Spotipy, Ncspot, Spot, etc might or might not work with this command.
!!!

---

## 3. Misc

A set miscellenous commands that can be used for bug reporting and some other purposes that have nothing to do with the main functionality of bot.
!!!Important
This group is common to all our bots a details regarding this group can be found [here](/guides/common-commands.md#misc-cog).
!!!
---
