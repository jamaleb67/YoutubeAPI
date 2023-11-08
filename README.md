##### [Youtube/GDP](Top)

<img src=https://i.imgur.com/ACFFpv2.png width=1500 class="center">
<h1 align="center">Top Youtubers effecting GDP between 2019 - 2022??</h1>
    
    In today's world, the internet has become an integral part of our lives. With the rise of online platforms such as YouTube, it has become easier than ever for people to access information and entertainment from all over the world. At the same time, Gross Domestic Product (GDP) remains one of the most widely used indicators of economic performance. In this project, we aim to explore the relationship between these two seemingly unrelated topics: GDP and YouTube. By analyzing data on GDP and YouTube usage patterns, we hope to gain insights into how these two factors are connected and what implications this may have on our understanding of the modern world.

The objective of this project is to analyze the relationship between GDP and YouTube usage patterns. We will use data on GDP and YouTube usage patterns to gain insights into how these two factors are connected and what implications this may have on our understanding of the modern world.

Our goal is to answer the following questions:

- What are the the top Youtubers in countries around the globe?
- What is the Top GDP countries, and what is there growth during COVID?
- Is there a correlation between Top Youtubers and selected GDP Nations?
- What is statistical corelations can be made?

To answer these questions, we will use Python and its data analysis libraries, such as Pandas and Matplotlib. We will start by importing the dataset and cleaning the data, followed by exploratory data analysis and visualization.

I will be using the following datasets:

- [Top Youtubers](https://www.kaggle.com/mdhrumil/top-5000-youtube-channels-data-from-socialblade)
- [GDP](https://www.kaggle.com/fernandol/countries-of-the-world)

APIs:

- [YouTube API](https://developers.google.com/youtube/v3/docs/channels/list)
- [Google API](https://console.cloud.google.com/apis/library/youtube.googleapis.com)

# Table of contents <a class='anchor' id='top'>

- [Introduction](#Introduction)
- [Import libraries](#import)
- [Load data](#load_data)
- [GDP Analysis](#gdpproject)
- [Bar chart](#bar_chart)
- [GDP Conclusion](#geo)
- [YouTube Analysis](#Analysis)
- [Youtube API](#YouTube)
- [Conclusion](#Conclusion)

<p align="center">
  <b><u><span style="font-size: 24px">
  GDP Analysis from 2019 - 2020<a class='anchor' id='gdpproject'></span></u></b><br>
</p>

### ?WBGAPI World Bank Top 20 Countries by GDP?

import wbgapi as wb
help(wb)
wb.source.info()
##wb.economy.info(db=2)

### Load data <a class='anchor' id='load_data'>

---

## WORKING CODE

class Coder(dict):
'''Class returned by coder if passed a list of terms
'''

    def __repr__(self):
        rows = self._coder_report()
        columns = rows.pop(0)
        return tabulate(rows, tablefmt='simple', headers=columns)

def coder_report(economies):

    global _coder_names

    rows = [('ORIGINAL NAME', 'WBG NAME', 'ISO_CODE')]
    for k,v in economies.items():
        if v:
            wb_name = _coder_names.get(v, '')
        else:
            wb_name = ''

        rows.append((k, wb_name, v))

    output = []
    for row in rows:
        output.append([row[0], row[1], row[2]])

    return output

``

# Youtube Exploratory Data Analysis <a class='anchor' id='Analysis'>

### U.S. Top Channels

1. Mr. Beasts view-source:https://www.youtube.com/@MrBeast/about

- UCX6OQ3DkcsbYNE6H8uQQuVA

2. Cocomelon - Nursery Rhymes view-source:https://www.youtube.com/channel/UCbCmjCuTUZos6Inko4u57UQ

- UCbCmjCuTUZos6Inko4u57UQ

3. Dude Perfect view-source:https://www.youtube.com/channel/UCRijo3ddMTht_IHyNSNXpNQ

- UCRijo3ddMTht_IHyNSNXpNQ

4. ✿ Kids Diana Show view-source:https://www.youtube.com/channel/UCk8GzjMOrta8yxDcKfylJYw

- UCk8GzjMOrta8yxDcKfylJYw

* For India, the top two YouTubers are **Bhuvaneshwar Bam** and **Amit Bhadana**. Bhuvaneshwar Bam is the creator of **BB ki Vines**, a comedy channel that features him playing multiple characters. He has more than 20 million subscribers and over 3 billion views. Amit Bhadana is another comedy channel that features slice of life content, relationships, and comedic skits. He has more than 22 million subscribers and over 1.8 billion views. You can visit their YouTube pages here: [BB ki Vines](^1^) and [Amit Bhadana](^2^).

* For Japan, the top two YouTubers are **HikakinTV** and **Yuka Kinoshita**. HikakinTV is a channel that features various content such as music, games, challenges, and collaborations with other celebrities. He has more than 8.8 million subscribers and over 6.7 billion views. Yuka Kinoshita is a channel that features her eating large amounts of food in a short time. She has more than 5.6 million subscribers and over 2.4 billion views. You can visit their YouTube pages here: [HikakinTV](^3^) and [Yuka Kinoshita].

* For Mexico, the top two YouTubers are **Luisito Comunica** and **Badabun**. Luisito Comunica is a channel that features his travels around the world, exploring different cultures, cuisines, and attractions. He has more than 36 million subscribers and over 4.9 billion views. Badabun is a channel that features various content such as entertainment, news, pranks, and social experiments. He has more than 43 million subscribers and over 14 billion views. You can visit their YouTube pages here: [Luisito Comunica] and [Badabun].

* For South Korea, the top two YouTubers are **Boram Tube Vlog** and **Saebyuk Jang**. Boram Tube Vlog is a channel that features a six-year-old girl named Boram and her family doing various activities such as playing with toys, cooking, traveling, and reviewing products. She has more than 26 million subscribers and over 10 billion views. Saebyuk Jang is a channel that features a young boy named Saebyuk and his parents doing various content such as games, challenges, vlogs, and animations. He has more than 23 million subscribers and over 8 billion views. You can visit their YouTube pages here: [Boram Tube Vlog] and [Saebyuk Jang].

* For the United States, the top two YouTubers are Mr. Beast and Cocomelon. Mr. Beast, is renowned for his philanthropic and grand-scale stunts on YouTube. He's known for giving away substantial sums of money, organizing challenging competitions, and contributing to various charitable causes. Mr. Beast's channel has attracted over 50 million subscribers. Cocomelon is a children's animation channel that offers entertaining and educational content for young viewers. With over 150 million subscribers, it's one of the most-watched channels on YouTube, catering to children's early learning and entertainment needs. You can visit their YouTube pages here:

1. YouTube. https://www.youtube.com/index.
2. Top 50 Popular YouTubers in India (2023) - Moneymint. https://moneymint.com/top-youtubers-in-india/.
3. List of most-subscribed YouTube channels - Wikipedia. https://en.wikipedia.org/wiki/List_of_most-subscribed_YouTube_channels.

#### India Top Channels

1.  view-source: html to website

-

2.  view-source:

-

#### Japan Top Channels

1.  view-source:

-

2.  view-source:

-

#### Mexico Top Channels

1.  view-source:

-

2.  view-source:

-

#### South Korea Top Channels

1.  view-source:

-

2.  view-source:

-

#### United Kingdom Top Channels

1.  view-source:

-

2.  view-source:

-

#### Germany Top Channels

1.

-

2.

-

## YouTube API <a class='anchor' id='YouTube'></center>

# 1. Data creation with Youtube API

# 2. Function to pull data from Youtube API and create a dataframe

# New method to pull data from Youtube API and create a dataframe

               'UC-lHJZR3Gqxm24_Vd_AJ5Yw', # PewDiePie SE
               'UCYWOjHweP2V-8kGKmmAmQJQ', # Badabun MX
               'UCECJDeK0MNapZbpaOzxrUPA', # Luisito Comunica MX
               'UCOmHUn--16B90oW2L6FRR3A', # BLACKPINK

def main(): # List of channel IDs to process
channel_ids = ['UCX6OQ3DkcsbYNE6H8uQQuVA', # Mr. Beast US
'UCbCmjCuTUZos6Inko4u57UQ', # Cocomelon US
'UCqwUrj10mAEsqezcItqvwEw', # Bhuvaneshwar Bam IN
'UC_vcKmg67vjMP7ciLnSxSHQ', # Amit Bhadana IN
'UCjp_3PEaOau_nT_3vnqKIvg', # HikakinTV JP
] # Replace with actual channel IDs

    # Get channel statistics
    channel_data = get_channel_stats(youtube, channel_ids)

    video_df = pd.DataFrame()
    comments_df = pd.DataFrame()

    for channel in channel_data['channelName'].unique():
        logging.info(f"Processing channel: {channel}")
        playlist_id = channel_data.loc[channel_data['channelName'] == channel, 'playlistId'].iloc[0]
        try:
            video_ids = get_top_video_ids_by_view_count(youtube, playlist_id)
            video_data = get_video_details(youtube, video_ids)
            comments_data = get_comments_in_videos(youtube, video_ids)

            video_df = pd.concat([video_df, video_data]).drop_duplicates(subset=['video_id'])
            comments_df = pd.concat([comments_df, comments_data]).drop_duplicates(subset=['video_id'])
        except Exception as e:
            logging.error(f"Error processing channel {channel}: {e}")
            continue

    # Save the data to CSV files
    video_df.to_csv('video_data.csv', index=False)
    comments_df.to_csv('comments_data.csv', index=False)

if **name** == "**main**":
main()

    def get_top_video_ids(youtube, playlist_id):
    """
    Get the top 10 video IDs from the given playlist sorted by view count.

    Params:
    youtube (googleapiclient.discovery.Resource): The YouTube API resource object.
    playlist_id (str): Playlist ID.

    Returns:
    List of the top 10 video IDs in the playlist sorted by view count.
    """
    request = youtube.playlistItems().list(
        part='contentDetails',
        playlistId=playlist_id,
        maxResults=50
    )
    response = request.execute()

    # Extract video IDs and view counts into a list of dictionaries
    videos_data = [{'video_id': item['contentDetails']['videoId']} for item in response.get('items', [])]

    # If there are more pages, continue fetching
    next_page_token = response.get('nextPageToken')
    while next_page_token and len(videos_data) < 10:
        request = youtube.playlistItems().list(
            part='contentDetails',
            playlistId=playlist_id,
            maxResults=50,
            pageToken=next_page_token
        )
        response = request.execute()
        videos_data.extend([{'video_id': item['contentDetails']['videoId']} for item in response.get('items', [])])
        next_page_token = response.get('nextPageToken')

    # Sort the videos by view count in descending order and return the top 10
    top_video_ids = [video['video_id'] for video in videos_data]
    return top_video_ids[:10]



def get_video_details(youtube, video_ids):
"""
Get video statistics of all videos with given IDs
Params:

    youtube: the build object from googleapiclient.discovery
    video_ids: list of video IDs

    Returns:
    Dataframe with statistics of videos, i.e.:
        'channelTitle', 'title', 'description', 'tags', 'publishedAt'
        'viewCount', 'likeCount', 'favoriteCount', 'commentCount'
        'duration', 'definition', 'caption'
    """

    all_video_info = []

    for i in range(0, len(video_ids), 50):
        request = youtube.videos().list(
            part="snippet,contentDetails,statistics",
            id=','.join(video_ids[i:i+50])
        )
        response = request.execute()

        for video in response['items']:
            stats_to_keep = {'snippet': ['channelTitle', 'title', 'description', 'tags', 'publishedAt'],
                             'statistics': ['viewCount', 'likeCount', 'favouriteCount', 'commentCount'],
                             'contentDetails': ['duration', 'definition', 'caption']
                            }
            video_info = {}
            video_info['video_id'] = video['id']

            for k in stats_to_keep.keys():
                for v in stats_to_keep[k]:
                    try:
                        video_info[v] = video[k][v]
                    except:
                        video_info[v] = None

            all_video_info.append(video_info)

    return pd.DataFrame(all_video_info)

def get_comments_in_videos(youtube, video_ids):
"""
Get top level comments as text from all videos with given IDs (only the first 10 comments due to quote limit of Youtube API)
Params:

    youtube: the build object from googleapiclient.discovery
    video_ids: list of video IDs

    Returns:
    Dataframe with video IDs and associated top level comment in text.

    """
    all_comments = []

    for video_id in video_ids:
        try:
            request = youtube.commentThreads().list(
                part="snippet,replies",
                videoId=video_id
            )
            response = request.execute()

            comments_in_video = [comment['snippet']['topLevelComment']['snippet']['textOriginal'] for comment in response['items'][0:10]]
            comments_in_video_info = {'video_id': video_id, 'comments': comments_in_video}

            all_comments.append(comments_in_video_info)

        except:
            # When error occurs - most likely because comments are disabled on a video
            print('Could not get comments for video ' + video_id)

    return pd.DataFrame(all_comments)
