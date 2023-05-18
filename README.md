---
title: 'Microchallenge III'
disqus: hackmd
---

Group 1 - Teacher Dashboard  - Facilitating Perception Board Sessions
===
Group Members: Jimena, Ariel and Wen

## Table of Contents

[TOC]

## Initial idea
*Initial idea / Concept of the Project (aligned to research areas).*

Our initial idea is to visualize the futures imagined by children in our first intervention creating collages wth them to create a digital gallery that can act as an exhibit that we share back with teachers and parents to raise funds as NFTs.

Our aim was to develop a digital interface that allows children to create imagery out of the futures they create during the futures literacy workshop.

## Purpose
*What is supposed to do or not to do.*

Web app that allows teachers to input futures imagined by children in futures literacy sessions and generate images that spark thinking and debate for older generations.

### What
This is a tool that will help us in facilitating the classroom and workshop experience with school children.


### Who
Our goal would be to integrate the tool into a session with teachers wishing to run Perception Board sessions and futures literacy programs to imagine futures.

### Where

Classroom settings (primary and secondary students) in facilitated workshops or spaces of discussion around futures literacy.

### How

This can be done through a workshop or a small game session.

**Workshop 1** 
Primary school children use collage to imagine futures related to schools, parks, zoos and sports taking into consideration climate change, gender equality and mental health. The output is a micro short story.

**Digital interface** 
Children input their stories in our "Futures generator" and save the image they most feel capture their idea.

**Workshop 2** 
Older children (15 and above) visualize children's images and use that as prompts to map their perceptions in regards to topics such as climate change, mental health and gender equality.



|  Imagined futures by children     |                                                         |         |
| --- | ------------------------------------------------------------------------------------- | --- |
| New animals are imagined by humans and they are placed in the zoos                    | Zoos    |
| Poor children go to a school and are fed                                              |  Schools   |
| Police capture bad man that kills animals and puts him in jail                        |   Parks  |
| A future with no zoos and where animals are treated well                              |    Zoos |
| Animals are trained to be strong to compete in sports competitions                    |  Sports   |
| Humans live with wild animals and humans feed them                                    |   Zoos  |
| Animals are treated like our family without killing the environment                   |  Zoos   |
| In sports competitions, humans can play any clothes they want. There are no uniforms. | Sports    |
| One sports arena where all the sports in the world can be played in the same place.   |  Sports   |
| Parks of the future have animals and fruits and cars are forbidden.                   | Parks    |
| A school where you can bring your own pokemon to class                                |  Schools   |
| In the zoos of the future there are giant snakes and horses are tiny.                 |Zoos     |
| Its forbidden to hunt animals and humans are friends with animals.                    |  Parks   |
| Trapped animals in the jungle are rescued by a man                                    | Zoos    |


### Why
We have been working with children to imagine the future in 3 dimensions: mental health, gender equality and climate change. From our first workshop we collected voice records and collages about the vision of 7 - 8 years old children.

Now, we want to develop this futures with the help and vision of 13-14 years old teenagers of the same school. With this on mind, we want to generate AI images of the children's future stories to interpret them and foster intergenerational learning. A provocative exercise to stimulate the creativity of teenagers and include the vision of children in their own future stories.

## Planification
![](https://hackmd.io/_uploads/H1E5-mGrn.png)

During the first day we outlined our plan for this challenge. While our output was not completely clear from the start, we decided to start with the most complex part of our system: the text-to-image generator that would be used to bring to life children's futures.

## Integrated design
*Integrated Design (How you designed it - relation between elements)*

When we are designing, we position ourself and try our best to relate back to our interventions. 

One of the feedback we got from the previous design studio is that we were somewhat too intentional during our design and facilitation of our workshop. Therefore, this time, we plan to use this tool as an invitation for the workshop participants to co-design the experience through collecting their feedbacks.

### Design Process


**AI-powered design process**
We started asking Chat GPT how to visualize the futures imagined by the children and to walk us step by step into how to use Dall-E or midjourney to create these images.

We also used a Figma plug in to outline a first draft for the app using Wire Gen. 

**Figma file**
https://www.figma.com/file/eZKuFNFJQ4wFc4Pbzoma0y/Big-Little-Futures---Teacher-app?type=design&node-id=0-1&t=oBjVotu6YoqOopZ8-0

We were also thinking maybe to have two text box to generate two different possibility futures. Then, the student can choose which one is more likely to happen.

We could use the image generated to be a collage, or decoration in the classroom etc. It can also be a platform that collect ideas that is more collective and be able to foster conversation.


### Problems

We tried using chat GPT to generate a code that integrates Dall-E open API to run an image generator in our local servers but encountered a lot of errors. After this, we tried running code with Dall-E but on Colab. 

We conducted a lot of failed experiments, iterating code with the help of chat GPT using Dall-E and huggingface.

After a few more tries, we found out there were problem connecting to the local server. We figured that maybe there is some problems with the code. Thus, what we did was we tried to modify and combine the existing code.

Finally it worked on the 2nd day. We will be enhacing the UX of the whole webpage.

### Feedbacks

We got a lot of constructive feedback that helps us figure out how to be more intentional.

## Honest design
*Honest Design (use of technology in a meaningful way, in relation to your interventions)*

We are hoping that through this process, it will aid our co-design session with the students. For example, at the end of the intervention, we hope to include this: 

Sample questions that we might want to ask include this quick survey question to collect feedback and opinion from the participants:
1. Do you want to discuss more about the issues raised after this exercise?
2. Did you move your pointers at least 2 times?
3. Do you think you are more open minded after this exercise?
4. At the scale from 1-10, how satisfied are you with your experience with the perception board?
5. Do you feel uncomfortable seeing different opinions of others?


## Exploration

*Explore design boundaries (based on your expertise)*

When we are starting to do this exercise, we felt intimidated as it seems like a new realm for all of us since no one from the team had a heavy coding experience.

However, we are not discouraged and continue to explore tools and resources online, following free tutorials on Youtube. After a few tries and errors, we are able to build a functional page with HTML and even personalize it to our requirements.

## Fabrication process

Our fabrication process was focused mainly on the use of digital tools and synthetic realities since we wanted a text-to-image output using the input from children's imagined futures. We considered using Midjourney or Dall-E and then went with Dall-E since their API was faster to integrate and the token generation was very seamless.

### Day 1

During the first day, we planned the outline for the week and prioritized getting feedback from both the class and the Fab Lab Team. 

**Santi feedback (Day 1):**
- App that takes an input and creates an image or create a web with images generated? 
- Image from text you need an account, etc. Using an API allows everyone to use without an account.
- A gallery of images that showcases the futures.
- Idea: Use Midjourney through Discord and join Midjourney channel to send prompts and generate images.
- Do you want to use this interface as something else than a digital portfolio? Could be printed cards with the imagery. 
- Other ideas: text - image - and the image is input for something. We are missing one extra step.
- Temperature parameter in Chat GPT which is the degree of how strict that the answer given is. Works similarly for images. (0-1, 1 being more creative).
- Questions: Once you have the AI powered image, how can we incorporate that? Can we build suggestions on top of that?
- Design constraint: We can't generate images in real-time. Input: voice to text

**Day 1 Group feedback**
- Generate specific style of image, i.e. children drawing aesthetic
- Reference of: Ticket of dolphin
- Think closely of the why you are doing this - i.e. Generate a feedback loop between teenagers and children
- Be specific with AI prompts
- Prioritize and start with most important question
- Maybe you don't need a digital interface, maybe its a printed poster or a website
- Design the system and the technicalities

### Day 2

Our goal for the day was to finalize the text-to-image generator that could be used by teachers to generate images from the students' stories.

We played around with existing websites that had managed this integration successfully and asking chat GPT4 to help us iterate our code.

![](https://hackmd.io/_uploads/SkC9gXMH2.jpg)

![](https://hackmd.io/_uploads/H1c3gmzS2.jpg)

![](https://hackmd.io/_uploads/BJingQfrh.jpg)

![](https://hackmd.io/_uploads/BkE5QXzS3.jpg)

We also focused on producing assets for the workshop with teenagers in Sant Andreu School in Badalona where we plan to integrate the images generated by AI as inputs.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSatTTImB0ZxQ1Hkg6_JTX6yDSupz8rt0FjpkDVNE3fW-p71X0p3GyZAL97MltnWsWoTea4EGs6HjOl/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

We also focused on creating the printable version of our Perception Board.

**Figma with printables**
https://www.figma.com/file/uOMyI6194EmIxtUgXjSZdM/Little-Big-Futures?type=design&node-id=0-1&t=jYnRESeiPIRRTqoP-0

This is our final design by the end of Day 2:

![](https://hackmd.io/_uploads/HyUafVzS3.png)

We are thinking to create a QR code so that people can scan and use it.

**Day 2 Group Feedback:**
- Incorporate voice for later stages could be interesting
- Use QR inside classrooms
- Host on online server as opposed to Ariel's laptop
- Try to integrate the interface during MDEFest
- Figure out how to add a save image function to make a repository of all the children's futures (We will try to do this tomorrow with Pietro's help)

### Day 3
For Day 3, we spend some time to improve the microcopy and UX for the website.

**Exploration Sketches**

When we started the exploration process, we tried to think things from a UX perpective.

![](https://hackmd.io/_uploads/rymcyEzr3.png)

We then focused more on "build to think" approach and switched to trying to code the text-to-image generator and making the main interface work. 

During the third day, we focused on the system as a whole and also on developing the UI of our interface playing around with the typography and background colors.

![](https://hackmd.io/_uploads/B18cN_Xrn.jpg)
Here we are playing around with incorporating an image headline to make the website more attractive.

We also played around with the instructions text and with the headers to make it as self explanatory as possible.


### End Product Photos

![](https://hackmd.io/_uploads/HJ9cNFmBn.png)

![](https://hackmd.io/_uploads/HkJi4FXrn.png)

**Final code (HTML)**

https://drive.google.com/file/d/1_lT5Kwxd2q2L125VvRh4LR_9sBwKKhCh/view?usp=share_link

|  Imagined futures by children     |                                                         |         |
| --- | ------------------------------------------------------------------------------------- | --- |
| New animals are imagined by humans and they are placed in the zoos                    |  ![](https://hackmd.io/_uploads/BykhQt7B3.png) |
| Poor children go to a school and are fed                                              |  ![](https://hackmd.io/_uploads/HJ1Ymt7rh.png) |
| Police captures bad man that kills animals and puts him in jail                        |   ![](https://hackmd.io/_uploads/H1DMmtXH3.png) |
| A future with no zoos and where animals are treated well                              |   ![](https://hackmd.io/_uploads/BJN0fFXSn.png)
 |
| Animals are trained to be strong to compete in sports competitions                    |  ![](https://hackmd.io/_uploads/rkYqetXS3.png)  |
| Humans live with wild animals and humans feed them                                    |   ![](https://hackmd.io/_uploads/BkYBZFmSn.png) |
| Animals are treated like our family without killing the environment                   |  ![](https://hackmd.io/_uploads/Sk8QGFQrn.png) |
| In sports competitions, humans can play any clothes they want. There are no uniforms. | ![](https://hackmd.io/_uploads/Hyvjpu7Hh.jpg)  |
| One sports arena where all the sports in the world can be played in the same place.   | ![](https://hackmd.io/_uploads/BkB8auXr2.jpg)|
| Parks of the future have animals and fruits and cars are forbidden.                   | ![](https://hackmd.io/_uploads/B1Jin_XSn.jpg)|
| A school where you can bring your own pokemon to class                                |  ![](https://hackmd.io/_uploads/rJn0iu7Hh.png)  |
| In the zoos of the future there are giant snakes and horses are tiny.                 |![](https://hackmd.io/_uploads/SkWDiu7r3.png)|
| Its forbidden to hunt animals and humans are friends with animals.                    |  ![](https://hackmd.io/_uploads/r1SG6OmH3.jpg)|
| Trapped animals in the jungle are rescued by a man                                    |  ![](https://hackmd.io/_uploads/B1kitu7Bh.png)|


### Physical Material Resources
N/A

We plan to print out the AI generated images from our platform and bring them physically to our workshop with 15 year old students in Badalona.

## System Diagram
*Illustration explaining function, parts and relations*
![](https://hackmd.io/_uploads/SJaFnmMB2.png)

## Resources

We found this helpful video from YouTube that helps us a lot on how to build the final product.

<iframe width="560" height="315" src="https://www.youtube.com/embed/sibEVMI1gWY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

We used the video in combination with chat GPT to solve any potential bugs and relink to a new HTML page.

## Related Links

- [Ariel](https://argallardo.github.io/Ariel-MDEF/)
- [Jimena](https://jimenasalinasgroppo.github.io/MDEF/term3/03-Prototyping%20For%20Design/)
- [Wen](https://wenqianchua.github.io/MDEF/term03/02-prototypingfordesign/)
- [HackMD](https://hackmd.io/@Kg_pc2JTTZe5jnIcsbUSKQ/ry22rpgrn)
- [Course Miro](https://miro.com/app/board/uXjVMI9o11k=/)
