# Imgur To Guya Reddit Bot

This bot was created to automatically turn imgur albums posted in `/r/manga`
into guya links. This is needed because imgur is oftentimes a very poor place
for any actual albums because it is difficult to easily move back and forth
throughout images and they're oftentimes bloated in size anyways

This bot somewhat solves that by using the Reddit API to listen into submissions
on `/r/manga` and determine whether they're posting an imgur album, if they are,
post a link to a guya proxy in the comments

Posting the proxy is as easy as pasting the id of the imgur image into a
`guya.moe/proxy/imgur/{id}` link

## Example

<!--- Original Imgur Album: https://imgur.com/a/0ilxA85 --->
<p align="center">
  <b>Oversized Imgur Image</b>
  <img src="https://i.imgur.com/Z8IhLJE.png" alt="Imgur Example Image">
  <b>Easily Readable Guya Album</b>
  <img src="https://i.imgur.com/kd5vO5I.png" alt="Guya Example Image">
</p>
