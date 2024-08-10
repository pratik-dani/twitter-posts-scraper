# Twitter Posts Scraper

Interested in using this scraper? Get it here: [Twitter Posts Scraper](https://apify.com/pratikdani/linkedin-people-profile-scraper). Scrape Twitter posts and extract detailed information in bulk.

## Pricing
For better pricing you can signup here: https://datamagnet.co or reachout to us directly at pratik@clientlist.co

## Features

**Comprehensive Data Extraction:** Extract detailed data from Twitter posts including text content, user information, engagement metrics, and media attachments. This allows for a complete analysis of the posts' reach and user interaction.

**Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. You can select the fields you want, allowing for seamless integration with other tools and platforms for further analysis and utilization.

**Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the scraper has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

**Ability to Resume Last Failed Runs:** In case of unexpected errors, you can simply go to the scraper's last run page and click on the 'Resurrect' button to resume the last scraping progress.

## Integrations

You can use [Make](https://www.make.com/en/register) to integrate the Twitter Posts Scraper with any other SaaS platform by designing your own automation flows.

## Sample Output

Here is a sample output of this scraper:

```json
{
  "biography": "Here we go! © fabrizio.romano93@gmail.com 📩",
  "bookmarks": 756,
  "date_posted": "2023-07-24T19:26:23.000Z",
  "description": "Here we go? Al Hilal you can take me. I look like Kylian Mbappe",
  "external_url": null,
  "followers": 21754744,
  "following": 2583,
  "hashtags": null,
  "id": "1683559267524136962",
  "input": {
    "url": "https://x.com/FabrizioRomano/status/1683559267524136962/"
  },
  "is_verified": false,
  "likes": 259030,
  "name": "Fabrizio Romano",
  "photos": null,
  "posts_count": 46594,
  "profile_image_link": "https://pbs.twimg.com/profile_images/1741753635158024192/j0m8Ucvv_normal.jpg",
  "quoted_post": {
    "date_posted": null,
    "description": "Al Hilal you can take me. I look like Kylian Mbappe 😂😂👀 https://t.co/VH0syez3VX",
    "photos": [
      "https://pbs.twimg.com/media/F10rS33WwAAJOQo.jpg"
    ],
    "post_id": "1683549442287255552",
    "profile_id": "Giannis_An34",
    "profile_name": "Giannis Antetokounmpo",
    "url": "https://x.com/Giannis_An34/status/1683549442287255552",
    "videos": null
  },
  "quotes": 607,
  "replies": 2752,
  "reposts": 14319,
  "tagged_users": null,
  "url": "https://x.com/FabrizioRomano/status/1683559267524136962",
  "user_posted": "FabrizioRomano",
  "videos": null,
  "views": 19844857
}
```

## Output Data Documentation

Here is the JSON fields documentation without including the sample values:

- **biography** (string): The biography or description associated with the user's profile.
- **bookmarks** (integer): The number of times the post has been bookmarked by users.
- **date_posted** (string): The date and time when the post was created, in ISO 8601 format.
- **description** (string): The text content of the post.
- **external_url** (string or null): A URL related to the post or user's profile. This can be an external link shared in the profile or post.
- **followers** (integer): The number of followers the user has.
- **following** (integer): The number of accounts the user is following.
- **hashtags** (array or null): An array of hashtags used in the post.
- **id** (string): A unique identifier for the post.
- **input** (object): Contains details about the input parameters used to retrieve the post.
  - **url** (string): The URL of the post.
- **is_verified** (boolean): Indicates whether the user's account is verified on the platform.
- **likes** (integer): The number of likes the post has received.
- **name** (string): The name associated with the user's profile.
- **photos** (array or null): An array of URLs pointing to photos included in the post.
- **posts_count** (integer): The total number of posts the user has made on the platform.
- **profile_image_link** (string): The URL to the user's profile image.
- **quoted_post** (object or null): Details of the post that is being quoted or replied to, if applicable.
  - **date_posted** (string or null): The date and time when the quoted post was created, in ISO 8601 format.
  - **description** (string): The text content of the quoted post.
  - **photos** (array or null): An array of URLs pointing to photos included in the quoted post.
  - **post_id** (string): The unique identifier of the quoted post.
  - **profile_id** (string): The unique identifier of the user who created the quoted post.
  - **profile_name** (string): The name associated with the profile of the quoted post's creator.
  - **url** (string): The URL of the quoted post.
  - **videos** (array or null): An array of URLs pointing to videos included in the quoted post.
- **quotes** (integer): The number of times the post has been quoted.
- **replies** (integer): The number of replies to the post.
- **reposts** (integer): The number of times the post has been reposted.
- **tagged_users** (array or null): An array of users tagged in the post.
- **url** (string): The URL of the post.
- **user_posted** (string): The username of the person who posted the content.
- **videos** (array or null): An array of URLs pointing to videos included in the post.
- **views** (integer): The number of views the post has received.
