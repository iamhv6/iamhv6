### Welcome to my profile

![image](https://github.com/user-attachments/assets/c2d6a33c-3333-4f65-85ea-d4fa9eb34344)

### Gist Profile


![cropped_image](https://github.com/user-attachments/assets/ac3c10a9-0560-4d23-99d6-3cfb668d289d)


 [YTvideo](https://gist.github.com/iamhv6/ce9d99b6aebc958fcda9ee56628bd544) 
 
 <img align="right" src="https://github.com/user-attachments/assets/d8fac992-5b29-438e-9598-c312430ee837" width="30" height="30" />
 
```js
function getYTVideoDetails() {
    try {
        const title = document.querySelector("title").textContent.replace(" - YouTube", "");
        const description = document.querySelector('ytd-text-inline-expander span.yt-core-attributed-string').textContent.trim();
        const views = document.querySelector("ytd-watch-info-text #info-container #info").textContent.split('views')[0].trim();
        const uploadDate = uploadDateString.split('views')[1].trim().split('#')[0].trim();
        const channelName = document.querySelector("#owner #channel-name #container #text-container #text").title;

        return {
            title,
            description,
            views,
            uploadDate,
            channelName

```
[<img src="https://github.com/user-attachments/assets/495ba126-6c41-4778-a86c-4986434ba618" width="80"/>](https://gist.github.com/iamhv6/ce9d99b6aebc958fcda9ee56628bd544)

<!--
**iamhv6/iamhv6** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
