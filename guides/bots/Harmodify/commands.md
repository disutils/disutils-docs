---
icon: gear
order: 900
---

# Harmodify's Commands

___

Harmodify cosists of a total of **33 commands**, that have been organized into **54 groups** for the ease of our users.

Here is a list of available groups and the commands included:
<!-- 
> - [Harmodify's Commands](#harmodifys-commands)
>   - [1. Music](#1-music)
>     - [1.1. Play](#11-play)
>     - [1.2. Skip](#12-skip)
>     - [1.3. Shuffle](#13-shuffle)
>     - [1.4. Nightcore](#14-nightcore)
>     - [1.5. Bass](#15-bass)
>     - [1.6. Toggle](#16-toggle)
>     - [1.7. Volume](#17-volume)
>     - [1.8. Disconnect](#18-disconnect)
>     - [1.9. Queue](#19-queue)
>     - [1.10. Clear Queue](#110-clear-queue)
>     - [1.11. Lyrics](#111-lyrics)
>   - [2. Info](#2-info)
>     - [2.1 Spotify](#21-spotify)
>   - [3. Misc](#3-misc)
>   - [4. Owner](#4-owner) -->

<blockquote style="width: 50%; font-size: 16px; padding: 10px; border-left: 4px solid #5865F2;">
📋Table of Contents
    <ul>
        <li><a href="#harmodifys-commands">Harmodify's Commands</a><br /></li>
        <ul>
            <li><a href="#1-music">1. Music</a><br /></li>
            <ul>
                <li><a href="#11-play">1.1. Play</a><br/></li>
                <li><a href="#12-skip">1.2. Skip</a><br/></li>
                <li><a href="#13-shuffle">1.3. Shuffle</a><br/></li>
                <li><a href="#14-nightcore">1.4. Nightcore</a><br/></li>
                <li><a href="#15-bass">1.5. Bass</a><br /></li>
                <li><a href="#16-toggle">1.6. Toggle</a><br /></li>
                <li><a href="#17-volume">1.7. Volume</a><br /></li>
                <li><a href="#18-disconnect">1.8. Disconnect</a><br /></li>
                <li><a href="#19-queue">1.9. Queue</a><br /></li>
                <li><a href="#110-clear-queue">1.10. Clear Queue</a><br /></li>
                <li><a href="#111-lyrics">1.11. Lyrics</a><br /></li>
            </ul>
                <li><a href="#2-info">2. Info</a><br />
                    <ul>
                        <li><a href="#21-spotify">2.1 Spotify</a><br /></li>
                    </ul>
                <li><a href="#3-misc">3. Misc</a><br />
        </ul>
    </ul>
</blockquote>

## 1. Music
This group features a set of commands related to the Music functionality of the bot.
!!!warning
The commands in this group require you to be in a voice channel for functionality except Lyrics commands.
!!!
### 1.1. Play

Plays a song with a qiven query.<br/>
&emsp;**Requred Argument:** `<query>`
> `<query>` can be one of the following.
>- Name of song
>- Url:
>   - Can either be pointing to a song or playlist.
>   - **Supported Sources:** Youtube, Youtube Music, Spotify, Soundcloud and Apple Music.<br/>

&emsp;**Usage:**
> /music play `query: Sunroof`<br>
> /music play `query: https://www.youtube.com/watch?v=8xg3vE8Ie_E`<br>
> /music play `query: https://open.spotify.com/track/7hDoxkN20lLb06zifzYnD2`<br>

![](/assets/harmodify/music_play_usage.png)
&emsp;**Response:**<br>
&emsp;&emsp;Plays the searched song if found otherwise gives a not found error.
![](/assets/harmodify/music_play_response.png)
The details about the fucntioning of the buttons can be found [here](/guides/bots/Harmodify/play_button_info.md).

### 1.2. Skip

Skips the currently playing song.<br/>
&emsp;**Requred Argument:** `None`

&emsp;**Usage:**<br/>
>/music skip

&emsp;**Response:**<br>
&emsp;&emsp;Sends a confirmation embed and skips the currently playing song.

### 1.3. Shuffle
Shuffles the current user queue.<br>
&emsp;**Requred Argument:** `None`

&emsp;**Usage:**<br/>
>/music shuffle

&emsp;**Response:**<br>
&emsp;&emsp;Shuffles the current queue if there is one otherwise does nothing.


### 1.4. Nightcore
Toggles on/off the Nightcore style. What is Nightcore? Have a look 
<a class="external" href="https://en.wikipedia.org/wiki/Nightcore" target="_blank" style="display: inline-flex; align-items: center; text-decoration: none;">
    here
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-box-arrow-up-right" viewBox="0 0 16 16" style="margin-left: 4px;">
        <path fill-rule="evenodd" d="M8.636 3.5a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5"/>
        <path fill-rule="evenodd" d="M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0z"/>
    </svg>
.</a>

### 1.5. Bass

### 1.6. Toggle

### 1.7. Volume

### 1.8. Disconnect

### 1.9. Queue

### 1.10. Clear Queue

### 1.11. Lyrics

## 2. Info

### 2.1 Spotify

## 3. Misc