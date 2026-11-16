# Deciding What to do for Freedom Project and Progress Now
##### 11/14/26

### Where I am at Now
For my APCSA Freedom Project, I am working to create an **AI Support System** that is meant to encourage human creativity instead of replacing it in the career field of **Graphic Design**. I chose this for my freedom project because I like to show off creativity, whether it be through drawing, artwork or even digital design despite not having much experience in any of those areas. Now with AI becoming more integrated into these types of career fields, I've seen how useful AI can be when being placed in the right hands. So in order to preserve the creativity spark and use artificial intelligence to its full extent, I decided to use <a href="https://ai-sdk.dev/">Vercel AI SDK</a> to try and fit both aspects for Graphic Designers. Which is a Typescript SDK for creating AI apps.

### The Setback that Led to My Current Tool
My original idea for this year's freedom project was to use <a href="https://unity.com/">Unity</a> to create a revamped verison of a game called Block City Wars. The reason for this idea was that this was a game that I played since I was a kid that lost it's fame overtime as a result of the game developers lack of security against hackers and toxic players. However, while trying to find the time to tinker with this tool, I caught a light fever that made me miss a few days of school. Due to these missed days, I also had to catch up on other assignments that were past due as a result of my fever. Which shifted my mind away from tinkering with Unity. When I got well enough to tinker with Unity, I had also ran into an issue that did not allow me to download the software into my IDE. Even when I tried to download Unity on my personal Macbook, the software still gave me similar issues. This wasted a lot of time for me to try and tinker with the tool. When I felt well enough to go to school, I told my teacher all of this and he told me to try my back up plan, which is the AI Assistant. He then showed me a list of possible tools that could help me with creating my freedom project idea, one of them being AI SDK. 

### How I Tinkered with My Tool (with the time I had)
When I first started tinkering with AI SDK, I did not really know what I was going to do with it being that I did not know what it was. Due to this, I looked up a couple of videos online on how to use it. Which led me to a <a href="https://www.google.com/goto?url=CAESZwHEIkXXl1PDBHC0BO5swkUe3LLku66StvmsHXZRtPRfWDE4x8h2QGGtwR3txfzCqz3haBzJfdMybh39HO-9JzFNZHp_NLcODc4KtR7IJjG8FFPpVJ7DbdNG3-fVncbFPSIUqNvMkZg&gsessionid=cmy9UPMbGfvf1LmW9NZIMjut8AkmUutcwlzhzBdjAGrkY8sylCPlXw">video from CodewithStav</a> that was basically a crash course for AI SDK. I started by using the basic layout that the AI SDK website already provided me and then go through what I can with the video.
###### Website Layout
```js
import { generateText } from 'ai';
const { text } = await generateText({
  model: 'spacexai/grok-4.7',
  prompt: 'Explain the concept of quantum entanglement.',
});

console.log(text);
```

I then noticed that both the layout and video was using a ``.ts`` file, which I did not know was different from ``.html`` until I tried to print the result and it ended up downloading a file with the website layout code into my files. Confused I had to look at the video multiple times to see what I was doing wrong. I had a rewatch a few parts of it multiple times, espcially when it came to text generation. I then noticed that the video was using the IDE terminal to output results. It would do so by calling ``npx tsx`` and then the parent file and the actual file name of where the code was at. When I used this method and it worked, I decided to try what the video was doing and store that code inside of a function to try and run multiple functions. One with the quantum entanglement question and a question of my own. I then noticed that there were control variables that you can add to the variable ``generateText``, which I did not get to yet but from what I saw was that it basically adds to the ``prompt:`` of what should the AI mention. 



### EDP
I am currently in Step 2 of the Engineering Design Process, which is to Research the Problem. I say this step because in order for me to do my project, I first have to understand what tool I will have to use. As well as how to use that tool for the end goal that I want to create. Being that this shift of tools was so sudden and that I had a later start to tinkering with Vercel AI SDK, I had a major project delay when it comes to knowing what tool that I was going to use originally.

### Skills and Takeaways
**Time Management** - I say this because even with the light fever that I caught, I should of placed a time for me to personally tinker with Vercel while at home rather than just leaving time for me just do be by myself. Now I'm working towards adjusting my schoolwork with my time to learn Vercel.


**Asking for Help When Needed** - This was something that I thought I couldn't do being that this was a tool that was not shown in the tool list for the APCSA Freedom Project, but this did not give me an excuse to try and ask Mr.Mueller for help whenever I could. With this setback in time, I realized that I needed all the help that I could get when tinkering with a software that not everybody is using. 


When starting this freedom project, it was very stressful considering everything that was going on at that time. But so far, I am interested to see what other kinds of compoenents that AI SDK as yet to offer!


[Next](entry02.md)

[Home](../README.md)
