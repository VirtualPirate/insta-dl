# Introduction

Hello, this is a Intagram Video Parser package.

## Installation

```
> npm install insta-dl
```

## Example

```javascript
const instaDL = require("insta-dl");

instaDL
  .getReelInfo("https://www.instagram.com/reel/CrQ9TvAAuRe/")
  .then((data) => console.log(data));
```

## Output

```javascript
{
  author: {
    id: 'ken.rsn',
    image: 'https://scontent.cdninstagram.com/v/t51.2885-19/338819651_236282702295484_2279478049368151471_n.jpg?stp=dst-jpg_s100x100&_nc_cat=102&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=QRMNfycDZmAAX9FGxPf&_nc_ht=scontent.cdninstagram.com&oh=00_AfDfnCyrAjbRBHSGJPirD6KpdqNXVpU5zOeCC59KNyukLQ&oe=64A39CD2',
    name: 'Ken Rosner'
  },
  video: {
    likesCount: 100413,
    commentCount: 183,
    '@type': 'http://schema.org/VideoObject',
    uploadDate: '2023-04-20T09:39:00-07:00',
    description: '100K likes, 183 comments - Ken Rosner (@ken.rsn) on Instagram: "Quote of the day.\n' +
      '\n' +
      '#grind #health #challenge #fitness #mindsetquotes #development #inspiration #f..."',
    name: 'Ken Rosner on Instagram: "Quote of the day.\n' +
      '\n' +
      '#grind #health #challenge #fitness #mindsetquotes #development #inspiration #focus #quoteoftheday #aesthetic #stoicism #dedication"',
    caption: 'Quote of the day.\n' +
      '\n' +
      '#grind #health #challenge #fitness #mindsetquotes #development #inspiration #focus #quoteoftheday #aesthetic #stoicism #dedication',
    height: '1280',
    width: '720',
    contentUrl: 'https://scontent.cdninstagram.com/o1/v/t16/f1/m82/7E4DADE8464B3190C4DE9E38C5E11192_video_dashinit.mp4?efg=eyJ2ZW5jb2RlX3RhZyI6InZ0c192b2RfdXJsZ2VuLjcyMC5jbGlwcyJ9&_nc_ht=scontent.cdninstagram.com&_nc_cat=108&vs=1599966017182295_1270402677&_nc_vs=HBksFQIYT2lnX3hwdl9yZWVsc19wZXJtYW5lbnRfcHJvZC83RTREQURFODQ2NEIzMTkwQzRERTlFMzhDNUUxMTE5Ml92aWRlb19kYXNoaW5pdC5tcDQVAALIAQAVABgkR0x1TWJoUWw2S1F1ZGxJR0FNYTdEcmFUN1o1S2JxX0VBQUFGFQICyAEAKAAYABsBiAd1c2Vfb2lsATEVAAAmoKzi9sPR4z8VAigCQzMsF0A3TMzMzMzNGBJkYXNoX2Jhc2VsaW5lXzFfdjERAHUAAA%3D%3D&ccb=9-4&oh=00_AfDX1E7NnUiPqePoBToLh6-mnt6dNKa3quX3SY4uVvwN3g&oe=647D902F&_nc_sid=c07a80&_nc_rid=3ff8084028',
    thumbnailUrl: 'https://scontent.cdninstagram.com/v/t51.36329-15/342248927_3372903832949729_1979314125548670501_n.jpg?stp=dst-jpg_s640x640&_nc_cat=102&ccb=1-7&_nc_sid=8ae9d6&_nc_ohc=uupVv7UNsMAAX_muvX2&_nc_ht=scontent.cdninstagram.com&oh=00_AfC3nX26bI93Br85p9RTBm8m4iLRc7Qm9SthEBxHF_p5MQ&oe=648112C7',
    genre: [],
    keywords: [],
    interactionStatistic: null
  }
}
```

## Access Direct download url at

```javascript
reelInfo.video.contentUrl;
```
# insta-dl
