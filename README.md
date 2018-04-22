# sortlikes
Sort Facebook Likes into categories

##Usage
1. Go to <a href="https://www.facebook.com/me/likes" target=_blank>https://www.facebook.com/me/likes</a>
2. Scroll down, select all, copy. 
3. Go to <a href="https://peterburk.github.io/sortlikes/index.html" target=_blank>https://peterburk.github.io/sortlikes/index.html</a>
4. Paste, click the Sort button. 
5. See the results in the text area and on the graph. 

##How it works
Underneath each of your Likes is a Category. 
Facebook uses 825 categories. I sorted them into 30 more meaningful groups. 
When you click "sort", my program does a "Find" on the text you typed. 

##Is this safe?
Yes. My code doesn't even read your Likes! It just searches for the category names. 
I don't upload your Likes to a server. Everything happens in Javascript in your browser. No cookies. 
If you still don't trust my code, you can save the HTML, disconnect your Internet access, and run it locally. 

##Why did you make it?
I'm trying to teach myself Chinese. I wrote another program, <a href="https://pingtype.github.io" target=_blank>Pingtype</a>, to let me type and read. 
Pingtype helps me read the Bible and sing in church, but I want to find new data sources. 
On 9gag, I saw a comic from <a href="http://blog.mixflavor.com" target=_blank>Mixflavor</a> translated by <a href="https://www.facebook.com/Howardinterprets/" target=_blank>HowardInterprets</a>. 
It has example conversations! That will help me learn how to talk to people! So I decided to look for other comics in Chinese. 
First, I got the list of all my 1576 Facebook friends in Taiwan. 
Next, I wrote a script to go to all my Facebook friends' profiles, and save their 223,783 Likes. 
Then I sorted those Likes into 825 Facebook categories. 
Then I grouped those Facebook categories into my own groupings (this is the code you see here). 
Now I know the most popular Art, Music, Games, etc in Taiwan. 
Then the Cambridge Analytica fiasco happened. Everyone is paranoid about being profiled. I realised my data could be used for this. 
Please calm down! 
I listen to emo music, so I must be depressed, right? 
I've been to the Korean DMZ, so obviously I'm involved in the military, right?
Facebook and Cambridge Analytica know that these stereotypes don't work very well. 
According to Kogan, the "correlation between predicted and actual scores ... was around [30 percent] for all the personality dimensions."
<a href="https://arstechnica.com/tech-policy/2018/04/how-cambridge-analyticas-facebook-targeting-model-really-worked" target=_blank>https://arstechnica.com/tech-policy/2018/04/how-cambridge-analyticas-facebook-targeting-model-really-worked</a>
Unlike Cambridge Analytica's machine-generated model of "low openness to experience and high neuroticism", I chose categories that are meaningful. 
I want people to judge me based on the things I chose to Like. 
That's right - please judge me!
If someone wants to persecute Christians, I'm ready to suffer for my religious views. I'm ready to be rejected due to my taste in music. 
Don't judge me based on the colour of my skin, or where I was born. I can't change those. 
Judge me on the things I chose. 

##What about the Taiwan data?
Download the Excel spreadsheet here:
<a href="https://peterburk.github.io/sortlikes/TaiwanLikes.xlsx" target=_blank>https://peterburk.github.io/sortlikes/TaiwanLikes.xlsx</a>
My data is not statistically representative, because it's biased by my friends. 
I'm a fan of 滅火器 Fire EX. so they appear to be much more popular because I met many friends at their concerts. 
Subcategories are more interesting. Knowing I like Rock is more useful than knowing I like Music. 
I sorted the Music category into Genres using the iTunes EPF data. 
<a href="https://peterburk.github.io/sortlikes/TaiwanMusicGenres.xlsx" target=_blank>https://peterburk.github.io/sortlikes/TaiwanMusicGenres.xlsx</a>

##What else can this model be used for?
- Draw a picture of your interests. These are mine:
<img src="https://peterburk.github.io/sortlikes/Interests.jpg">
- I'm more interested in subcategories (e.g. Music > Rock, Art > Comics). 
- Study how the categories interact with each other (e.g. the flow of money from Construction to Politics to Military). 

