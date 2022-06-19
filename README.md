# SmileWithUs
## Inspiration

We were inspired to create this project based on our own experiences. We attend a very competitive school, where college aspirations are put before everything else. Though mental health is talked about at our school, many students don't feel comfortable talking with others about mental health & they don't know where they could quickly destress. The result? Our school has the highest suicide rate in our district, maybe even the bay area. What we need is a quick, truly anonymous way that students could take care of their mental well-being; the main problem we tried to address. We've all struggled with mental health and we wanted to create something to help both ourselves and each other. 

## What it does

Our project gives people a shoulder to rely on, by allowing them to talk about what happened and how they feel. We present breathing exercises and techniques to calm them down in case of tense situations. We are able to record their verbal responses to several questions while maintaining a conversation-type feel. Then, we use an API to classify the responses in which emotion is portrayed using Convolutional Neural Networks. To run the project on your local system, you will have to obtain both Komprehend AI and YouTube Data V3 API Keys, and appropriately replace the current placeholders for them in the final.html, settings.cfg, and views.py files. Then, run python manage.py runserver in the highest self-care directory and open the link provided in the terminal. 

Depending on which emotion is most prominently portrayed (happy, sad, angry, bored, or fear), we base
the video and song recommendations to counter their negative mood using their desired content preferences. We use an API key from YouTube Data V3 to embed the video recommendations onto the website. 

On the user's very first visit, they put in their favorite television shows, sports teams, artists, and YouTubers which then get saved. For every subsequent visit, the user is recommended videos and songs based on their preferences and current mood/emotion. 


## UI Details and Choices for the Site

**Start Page (2nd page)**
- The background was chosen because it's serene and open to calm the nerves. The still water especially provides a sense of calmness
- Dialogues remain at 20% opacity to allow users to enjoy the background view unblocked
- If the mouse is hovered over the dialogues, then there's a 100% opacity for the words to read
- We had lots of spaces on the UI between dialogues to simulate the kind of therapist-person session
- The recorded questions are also a means to make it feel more realistic like a therapeutic sessions
_- Therapist and person sessions usually are more of the person talking than the therapist, so the website acts perfectly in that sense_
- The questions shown on the page are common therapist questions and are scientifically proven to help better someone's mental health by letting out the users' inner feelings & emotions

**Breathing (3rd page)**
- Used blue color, space, and mountains because it evokes a sense of calmness
_Proven that the color of blue and sea green (as the color of the breathing ball) helps in destressing_
- The inhale & exhale ball also feels very realistic as it is like how a human really breathes (fast at the beginning and then it slows down to a stop)
- Has a 2-minute timer for breathing and then redirects the user to the last page

**Final Page (4th page)**
- 1st picture I used was the earth from a space perspective because, after receiving that feeling of finally being mentally free with the help of the breathing, the earth helps reinforce that same idea (mainly bc its so big and it proves to show that there is so much freedom and opportunities to be achieved)
- 2nd picture as you scroll down is that of a sunny sidewalk path, where we put the videos and the songs
-The picture helps stand with the idea that we're giving the user stuff to help them along the path to wellness

- Last picture, when scrolling down, talks about mental health 
- A general overview:
1. What is mental health
2. Why is mental health important & why not to ignore it
3. What steps need to be taken in order to keep a mental well being
4. How this applies to yourself, as well as, family and friends
5. Who are trusted individuals or adults to talk to
6. National Suicide Prevention Lifeline description
7.  National Suicide Prevention Lifeline button that redirects to the website
 - The picture also says "Saftey first" as a final message that mental health is also prone to risk and one should keep it safe


## How we built it

We built this web application using the Django Framework and we coded it using Python, JavaScript, HTML, and CSS. We used a YouTube Data V3 API to embed the video and song recommendations on the website. We also used an Emotion Analysis API to figure out which emotions were portrayed by the user when they were talking about their day and how they felt. 

## Challenges we ran into

Over the course of these few days, we faced several challenges, which we were able to overcome with persistence and hard work. First, our emotion analysis program was giving completely inaccurate readings and taking over 30 seconds to process. After doing much more research and background learning, we were able to find an API that suited our needs much better. This emotion analysis API gives accurate emotion predictions instantly. For example, another challenge we ran into was learning how to incorporate scrolling with moving backgrounds. We had to play around with CSS a lot to understand how it worked; we had to separate the photos into multiple layers in such a way to make it seem the photo itself is moving. 

## Accomplishments that we're proud of

Implementing a fully functioning web application with a variety of features for a great cause -- betterment of the mental health of all its users. 

## What we learned

We got more experience in building an end-to-end web application using the tools, technologies, languages, etc. We also got more experience attending virtual hackathons -- this was the first for some of our team members :)

## What's next for Smile With Us

In the near future, we hope to improve our web application by including a login page (username/password) to be able to track the user's progress. Essentially, we hope to be able to track growth and how the user's emotions/mood for every session is generally improving. Furthermore, instead of embedding individual songs on the website, we plan to implement a Spotify API and generate a whole playlist for each session the user has on the website. 

## Final Thoughts
"One life. Protect it." Mental health is a real issue and our website is a means to take care of it. The amount of work and effort we put into this just comes to show how seriously we and others take it. So don't feel ashamed to talk about your mental health to other trusted individuals and safeguard your mental well-being.
