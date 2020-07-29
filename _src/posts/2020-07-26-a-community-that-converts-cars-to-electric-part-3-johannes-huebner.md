    Title: An OSS community that converts cars to electric. Part 3: Johannes Huebner
    Date: 2020-07-26T10:29:15
    Tags: electric cars, community, car conversions, Damien Maguire, Johannes Hüebner, Open Inverter, wosniac, CAN bus
    Authors: Andrea Magnorsky

Johannes Huebner on how he wants to democratise car conversions.

<img src="/img/2020-johannes/father-son.jpg" class="rounded" width="400" alter="first kit">

<!-- more -->

This is three two of a series of interviews:

1. [Kevin Sharpe from New Electric Ireland. Running courses to convert cars to electric.](http://coders4climatestrike.com/2020/05/a-community-that-converts-cars-to-electric.html)
2. [Damien Maguire. An Electric Engineer that converts cars to electric](http://coders4climatestrike.com/2020/06/a-community-that-converts-cars-to-electric-part-2-damien-maguire-interview.html)
3. Part 3: Johannes Huebner on how he wants to democratise electric car conversions.


## Johannes, can you tell us a little how you got started with electric vehicles?

It started in 2008. I graduated from University with a degree in Computer Science and electrical engineering. I always had a knack for this stuff, soldering, the hardware part and also some software.
The initial motivation was that I was probably going to have to commute and just thinking that I would turn on my diesel car every day...It smells terrible in the morning when it is a cold start, it pollutes the city... it felt so wrong. This is what got me into electric traction.

I thought about a go-kart, but that didn’t seem like a good idea. Taking the bike was a lot more practical in the end, but it sparked the idea of EV conversions.
The second motivation was purely technical, **I found it intriguing that you can control these large powerful motors with a few lines of code and control very precisely what it can do**... That’s fascinating.

I started with the controller code that was about forty lines of code. It was enough to spin the motor, of course, code started to grow as it got better. At the start I blew up some components, but amazingly little, thankfully after that not too much.
From there on, I spent time after work and persisted on it over years. The first conversion rolled out in 2012/13, roughly 5 years after I started.

<img src="/img/2020-johannes/Proud-of-my-first-transaxle.jpg" width="400" alter="first transaxle">


## Why open and free software and hardware?

I set up an electric car forum where I published the results of my experiments. At some point I was confident that what I built could be used by other people.

At the time. I was a Linux person and I liked the idea of open source, as opposed to Intellectual property. **Hiding or being secretive, I never liked that. So, I decided to start something similar, but for automotive motor control**.

At the time, AC motor control was considered something very complicated that only specialist companies would be able to manage. I wanted to show people that it is not that hard and I wanted people to be able to use these superior AC motors. The code was a great way to achieve that.


<figure class="figure">
  <img src="/img/2020-johannes/the-very-first-prototype.jpg" width="400" alter="first prototype">
  <figcaption class="figure-caption">First prototype.</figcaption>
</figure>


## Why are AC Motors superior?

DC motors have large mechanical components. Many properties of the dynamics of the DC motor control are managed mechanically. They cannot be controlled by software precisely. It's hard to transfer energy back into the battery with DC motors. They wear out because of the moving parts. But, AC motors don't have these problems and they can be precisely controlled. And I mean, there's no production costs.

## So you got the project off the ground, what happened then?

I decided to go open source with both hardware and software. Around that time I came across an open source charger project. I learned a lot from that project, there were many things that I thought didn’t need to be there. It made me focus on how to improve my own designs. It also made me think that perhaps I needed to create a kit.

Soon after, I noticed what [Damien](http://coders4climatestrike.com/2020/06/a-community-that-converts-cars-to-electric-part-2-damien-maguire-interview.html) was doing. I was fascinated by the way he had been doing things and by his enthusiasm. I have to admit, I was very proud when he contacted me to get one of the my kits. He was one of the first people to inquire about it.
He set it up online on his YouTube channel. I was very happy to be in contact with Damien.
This is a relationship that's been growing ever since. The designs are open source, so he took the design and adjusted it to use the Tesla motors. **The rest is history. It's a lot of back and forth between us. I took his ideas and put them back into my design and it’s just very much open source is supposed to work.**


<figure class="figure">
  <img src="/img/2020-johannes/the-first-kit.jpg" width="400" alter="first kit">
  <figcaption class="figure-caption">First kit.</figcaption>
</figure>



## I guess that is how Open Inverter came about then, or is it a collection of things?

It has become a collection. Initially, Open Inverter was just one inverter.

One of the main problems to bridge at the time was how to make your car road legal. If you pick some random motor and build your own inverter you can end up spending a lot of time and money testing to get the car approved and road legal.

The next development was that big car manufacturers like: Nissan, VolksWagen and Tesla started making electric cars, and those electric costs were crashing.
**With this, we have available high quality parts. Those parts are road legal qualified motors. This means that one of the main blockers for car conversions has been lifted! A massive win!**
With all the legal issues gone this is a big push for recycling and making conversions easier.



## These OEM parts are from hybrid, electric only, or both?

It can be from any of them. We started with a few electric components. The first was an OEM drive chain of a Tesla. 
Nowadays we are looking into hybrids more because it's so much cheaper. If you go out and buy a Tesla part, it will set you back by about 5000 euros. If you go out and buy a somewhat equivalent hybrid drive, you can get it for about 200, 300 euros. Another large barrier to EV conversions removed.               

## I get the sense that you're really into democratising this. Is that so?

Most definetly! I was inspired by the Steve Jobs biography and some articles where they describe how [Steve Wosniak](https://en.wikipedia.org/wiki/Steve_Wozniak) worked. For example when he got a $100 per part, he didn't use all the budget on it. He shrunk the design to the very essence of what was necessary.

What I aim for is: **not much there that doesn’t need to be there**. I do not use expensive components because of fancy data sheets. Do not use many components that are supposedly superior. What’s the point in measuring the current with 0.1% accuracy If all you need is like 5% .

## So that gets us to the last few years, what has been happening?

In 2016 I registered the domain for [Open Inverter](openinverter.org). The idea was to create a platform for this ecosystem. 
Not much happened for two years, but then a guy called Demare Deokman from Canada suggested we make a forum. We also added a Wiki and a shop. Before that people had to email me to request the different parts.

Then I started the [patreon page](https://www.patreon.com/openinverter), so that people could support my “artisanal engineering” work. 
I hope it might become self-sustaining soon. If that happens I can spend all my time on this improving on the hardware and software.


## What happens when people order a part from Open Inverter?

The process starts with getting the correct parts ordered, then I put it together, load the software to it, do some test procedures.I try to be as complete as possible, so people don't have to go out and shop for something else when they get the kits.
Follow the link for more info on the features of the [Inverter Kit](http://johanneshuebner.com/quickcms/index.html%3Fen_features,8.html)

## What is the blocker for more car conversions to electric?

<img src="/img/2020-johannes/Touran--electric-transaxle.jpg" width="400" alter="Touran conversion electric transaxle">



The main blocker is education. If you start off knowing nothing it's hard to collect information. We're trying to solve that, but it’s a long road. It would be ideal to know, given a car you want to convert: What parts would be suitable? What work needs to be done,  What mechanical adaptations?

Deleting misinformation would be good too. There are a lot of rumors out there that might keep people from even thinking about doing a car conversion.
Some examples are around lithium batteries and how their usage erases the environmental benefits of an EV. 
Another one is more practical, on how to make sure your car conversions are road legal without huge costs.  

<img src="/img/2020-johannes/Touran--fossil-removal.jpg" width="400" alter="Touran conversion">

## Since you are enabling car conversions, do you have it in your plans to create a car conversion company?

**I wouldn't. I see my work more like an ISO layer. It would be great if my work could enable others to run such a business.**
I think car conversions will eventually become  more mainstream than they  currently are. There are a lot of conversion shops in Germany but they have to charge ridiculous money to get the job done, it's such custom work.

Every car is a new project. Standardising the conversions would make sense because it has certain advantages over buying a new electric car: the environmental impact is lower, parts already exist, also, you can customise certain aspects of the car to suit your needs better. 
**There are some very good chassis out there, that just have the wrong engine**

<img src="/img/2020-johannes/Touran--body-work-with-Arber.jpg" width="400" alter="Touran conversion body work with Arber">

## Speaking of debunking myths, is it expected that I would lose the back seats if I convert a car?

Maybe that would have been true with my first conversion many years ago, the [92 Polo](http://johanneshuebner.com/quickcms/index.html%3Fen_electric-car-conversion,6.html), the battery weighted 250 kilograms. However, with nowadays technology I could probably fit most of the batteries in front and wouldn’t lose them.





<figure class="figure">
  <img src="/img/2020-johannes/Polo-conversion.jpg" width="400" class="rounded" alter="VW Polo conversion">
  <figcaption class="figure-caption">VW Polo conversion.</figcaption>
</figure>

<figure class="figure">
  <img src="/img/2020-johannes/the-polo-inverter.jpg" width="400" class="rounded" alter="VW Polo inverter">
  <figcaption class="figure-caption">VW Polo Inverter.</figcaption>
</figure>

## Are there any interesting integration plans for Open Inverter? 

It is in the plans to have some sort of standard so that other systems, like Open Vehicles can use the information Open Inverter provides such as motor temperature, motor speed, etc. This is a significant amount of work but I think it would be very useful


<figure class="figure">
  <img src="/img/2020-johannes/Conversion-complete-with-branding.jpg" width="400" alter="Conversion with Open inverter branding">
  <figcaption class="figure-caption">Conversion with Open inverter branding.</figcaption>
</figure>

## Important links

* [Johannes github](https://github.com/jsphuebner)
* [Open inverter website](https://openinverter.org/)

Thanks to Johannes for his time doing this interview. All photos in this article are his.





