# sortlikes
Sort Facebook Likes into categories<br/>
<br/>
## Usage
1. Go to <a href="https://www.facebook.com/me/likes" target=_blank>https://www.facebook.com/me/likes</a><br/>
2. Scroll down, select all, copy. <br/>
3. Go to <a href="https://peterburk.github.io/sortlikes.html" target=_blank>https://peterburk.github.io/sortlikes.html</a><br/>
4. Paste, click the Sort button. <br/>
5. See the results in the text area and on the graph. <br/>
<br/>
### How it works
Underneath each of your Likes is a Category. <br/>
Facebook uses 825 categories. I sorted them into 30 more meaningful groups. <br/>
When you click "sort", my program does a "Find" on the text you typed. <br/>
<br/>
### Is this safe?
Yes. My code doesn't even read your Likes! It just searches for the category names. <br/>
I don't upload your Likes to a server. Everything happens in Javascript in your browser. No cookies. <br/>
If you still don't trust my code, you can save the HTML, disconnect your Internet access, and run it locally. <br/>
<br/>
#### Why did you make it?
I'm trying to teach myself Chinese. I wrote another program, <a href="https://pingtype.github.io" target=_blank>Pingtype</a>, to let me type and read. <br/>
Pingtype helps me read the Bible and sing in church, but I want to find new data sources. <br/>
On 9gag, I saw a comic from <a href="http://blog.mixflavor.com" target=_blank>Mixflavor</a> translated by <a href="https://www.facebook.com/Howardinterprets/" target=_blank>HowardInterprets</a>. <br/>
It has example conversations! That will help me learn how to talk to people! So I decided to look for other comics in Chinese. <br/>
First, I got the list of all my 1576 Facebook friends in Taiwan. <br/>
Next, I wrote a script to go to all my Facebook friends' profiles, and save their 223,783 Likes. <br/>
Then I sorted those Likes into 825 Facebook categories. <br/>
Then I grouped those Facebook categories into my own groupings (this is the code you see here). <br/>
Now I know the most popular Art, Music, Games, etc in Taiwan. <br/>
Then the Cambridge Analytica fiasco happened. Everyone is paranoid about being profiled. I realised my data could be used for this. <br/>
Please calm down! <br/>
I listen to emo music, so I must be depressed, right? <br/>
I've been to the Korean DMZ, so obviously I'm involved in the military, right?<br/>
Facebook and Cambridge Analytica know that these stereotypes don't work very well. <br/>
According to Kogan, the "correlation between predicted and actual scores ... was around [30 percent] for all the personality dimensions."<br/>
<a href="https://arstechnica.com/tech-policy/2018/04/how-cambridge-analyticas-facebook-targeting-model-really-worked" target=_blank>https://arstechnica.com/tech-policy/2018/04/how-cambridge-analyticas-facebook-targeting-model-really-worked</a><br/>
Unlike Cambridge Analytica's machine-generated model of "low openness to experience and high neuroticism", I chose categories that are meaningful. <br/>
I want people to judge me based on the things I chose to Like. <br/>
That's right - please judge me!<br/>
If someone wants to persecute Christians, I'm ready to suffer for my religious views. I'm ready to be rejected due to my taste in music. <br/>
Don't judge me based on the colour of my skin, or where I was born. I can't change those. <br/>
Judge me on the things I chose. <br/>
<br/>
##### What about the Taiwan data?
Download the Excel spreadsheet here:<br/>
<a href="https://github.com/peterburk/sortlikes/blob/master/TaiwanLikes.xlsx" target=_blank>https://github.com/peterburk/sortlikes/blob/master/TaiwanLikes.xlsx</a><br/>
My data is not statistically representative, because it's biased by my friends. <br/>
I'm a fan of 滅火器 Fire EX. so they appear to be much more popular because I met many friends at their concerts. <br/>
Subcategories are more interesting. Knowing I like Rock is more useful than knowing I like Music. <br/>
I sorted the Music category into Genres using the iTunes EPF data. <br/>
<a href="https://github.com/peterburk/sortlikes/blob/master/TaiwanMusicGenres.xlsx" target=_blank>https://github.com/peterburk/sortlikes/blob/master/TaiwanMusicGenres.xlsx</a><br/>
<br/>
##### What else can this model be used for?
- I'm more interested in subcategories (e.g. Music > Rock, Art > Comics). 
- Study how the categories interact with each other (e.g. the flow of money from Construction to Politics to Military). 
- Draw a picture of your interests. These are mine:

![Interests](https://raw.githubusercontent.com/peterburk/sortlikes/master/Interests.jpg "Interests")
<br/>
