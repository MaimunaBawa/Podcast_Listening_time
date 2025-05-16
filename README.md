# Podcast_Listening_time



### About features of Dataset

Podcast_Name (Type: string)
Description: Names of popular podcasts.
Example Values: "Tech Talk", "Health Hour", "Comedy Central"

Episode_Title (Type: string)
Description: Titles of the podcast episodes.
Example Values: "The Future of AI", "Meditation Tips", "Stand-Up Special"

Episode_Length (Type: float, minutes)
Description: Length of the episode in minutes.
Example Values: 5.0, 10.0, 30.0, 45.0, 60.0, 90.0

Genre (Type: string)
Description: Genre of the podcast episode.
Possible Values: "Technology", "Education", "Comedy", "Health", "True Crime", "Business", "Sports", "Lifestyle", "News", "Music"

Host_Popularity (Type: float, scale 0-100)
Description: A score indicating the popularity of the host.
Example Values: 50.0, 75.0, 90.0

Publication_Day (Type: string)
Description: Day of the week the episode was published.
Possible Values: "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"

Publication_Time (Type: string)
Description: Time of the day the episode was published.
Possible Values: "Morning", "Afternoon", "Evening", "Night"

Guest_Popularity (Type: float, scale 0-100)
Description: A score indicating the popularity of the guest (if any).
Example Values: 20.0, 50.0, 85.0

Number_of_Ads (Type: int)
Description: Number of advertisements within the episode.
Example Values: 0, 1, 2, 3

Episode_Sentiment (Type: string)
Description: Sentiment of the episode's content.
Possible Values: "Positive", "Neutral", "Negative"

Listening_Time (Type: float, minutes)
Description: The actual average listening duration (target variable).
Example Values: 4.5, 8.0, 30.0, 60.0



### Tools and Libaries used 
**Python**
**Pandas**
**Numpy**
**Sklearn**
**Matplotlib**
**seaborn**


### Challenges
**Ensuring categorical variables were properly encoded without duplicating columns.**
**Avoiding re-encoding after the train-test split to prevent mismatched features.**
**Long runtimes for some models made iteration slower.**
**Managing data versions between transformation and modeling steps.**
