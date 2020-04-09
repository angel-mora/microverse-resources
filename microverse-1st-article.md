# THE ULTIMATE GUIDE TO HACK YOUR MOTIVATION FOR LEARNING TO CODE!

*This is a very motivating article for you. If you follow it until the end, you'll find yourself having your first webpage is just a few minutes. It doesn't matter if you have never done this before.*

I'm pressuming a very simple yet validated hypothesis:

> Attention is our most valuable form of capital nowadays.

This means that corporations, marketing and some other industries are developing technologies to catch our attention 24/7. There are a lot, A LOT of distractions nowadays. And each of them last no more than 30 seconds and most of them become addictive. Adult entretainment or addiction to certain social networks can easily catch you up. Specially if you area a Millennial. Millennials struggle a lot to figure out what to do. We want to solve all kind of trouble out there but we can't keep focused in one only thing for more than that half a minute.

And there's a reason for that. There are companies who invest literally millions of dollars trying to catch your attention. It's so hard to keep focus nowadays that probably the last thing we want to use our attention to is doing something hard, frustrating and unconfortable.

On the other side, there's a veil of wisdom surrounding programmers. It's not like that. It's just people who commited a lot in getting a goal and finding the motivation to keep going. Yet Web Development and Data Science, a couple of frustrating code-related things to learn, are some of the best well payed career in the US. And guess what, remote work is a very popular practice among programmers. If remote work was already a thing before COVID-19, now that most computer-related jobs have become remote worldwide, chances to get a remote job in a global tech brand increases and probably got in to stay.

So the best thing one could do if want to have a good job and live more than 50 years is finding a way to get into the new digital economy. Programming is not only about hacking and binary numbers. For me it's about most simpler things such as Logic and counting. As resources get scarced, counting and optimizing becomes even more neccesary. And though this violent economic flows will leave a lot of people without any job, knowing how to deal complexity through algoritmic thinking can get you capable of imagine how a post-work can be. One were we all can work 4-hours shifts and enjoy the benefits of automation in a democratic way.

[Check 80,000 hours](https://80000hours.org/) to make an effective change through your professional career and get motivated in the process.

Yet again, how can you start to do something so challenging and keep motivation during the though journey. 

But doing so is, I won't lie to you, actually hard. As our attention span decreases, our motivation to do things that get us out of our confort zone is decreasing too. I recently joined Microverse Web Development Bootcamp and I'll tell you some of the things that worked for me. I'll be honest with you. Before I started preparing for Microverse bootcamp, I didn't have enough motivation to trust myself I could achieve the goal of master web development.

You can get a good review of Motivation hacker [here](https://www.evernote.com/shard/s4/client/snv?noteGuid=ed74279f-29ba-470b-99c1-31387f5ea5fa&noteKey=6189febf5d13ded1d38706e54fd05daa&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs4%2Fsh%2Fed74279f-29ba-470b-99c1-31387f5ea5fa%2F6189febf5d13ded1d38706e54fd05daa&title=The%2BMotivation%2BHacker).

Now that everything has stopped, time is the best investment you can do and probably you are giving it to Facebook, Netflix, Youtube, Amazon Prime or some adult entretainment company. That time you are waisting can be useful to make you a valuable asset to rebuild our economies and get you in a better employment situation and probably will give you some agency over the current status of the world.

In my personal experience... Microverse is a great help and I'll explain you why with this recommendations to learn to code.

I'll start with a micro-tutorial to set a live website in less than 30 minutes,based on Ubuntu:

## PART 1: The Tutorial

### STEP 1: Install Visual Studio Code

First, update the packages index and install the dependencies by typing:

```
$ sudo apt update
$ sudo apt install software-properties-common apt-transport-https wget
```

Next, import the Microsoft GPG key using the following wget command:

```
$ wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
```

And enable the Visual Studio Code repository by typing:

```
$ sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
```

Once the apt repository is enabled, install the latest version of Visual Studio Code with:

```
$ sudo apt update
$ sudo apt install code
```

That’s it. Visual Studio Code has been installed on your Ubuntu desktop and you can start using it

### STEP 2: Create a GitHub repository

Get to the GitHub website and create an account.

Start a new repository with the license you want but including README file.

Go to the top-right corner and you will find a green button that says "Clone or Download". Get the URL. It should look like https://github.com/user/project-name.git

Now go back to the terminal and follow the next commands:

```
$ git clone https://github.com/user/project-name.git
```

Then go to the recently created folder:

```
$ cd project-name
```

Once you are there, check git status.

```
$ git status
```

Open the same folder in VSCode and create a new HTML file either through Terminal or the GUI. I'll call it index.html

```
$ touch index.html
```

### STEP 3: Launch your first website using Bootstrap

Now just go to [Bootstrap website](https://getbootstrap.com/docs/4.4/getting-started/introduction/), copy the Starter template and paste it in your index.html file. It already says the classic *Hello World*. Now save the changes.

```{html}
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  </body>
</html>
```

### STEP 4: Upload your website using Github Pages

Git is a bit complicated but for now you'll be good if you follow the instructions. The proper workflow to save and upload info on your website is with the next commands:

```
$ git status
```

To check the status of your repo. It will say your current branch and if there are things to commit to stage (don't worry if you don't get it yet, just follow the instructions).
Now you will add your current changes and write a meaninful message for your commit (which is the version you are saving and adding to stage now):

```
$ git add .
$ git commit -m "add index.html file and basic Bootstrap starter template"
```

Now the last step is to push your changes to the online repo. Just code this commands and write down your GitHub credentials:

```
$ git push origin master
```

### STEP 5: Set your website live

Go back to your repository in GitHub.

Go top-right corner and click on Settings.

In that same window, go down until you reach GitHub Pages section.

In Source, select *master branch*.

The brower's window will update and take you back to the beginning. Go down to find GitHub pages again. Now you'll have your site published in something like: https://user.github.io/project-name
and *voilá*, you have your first site up and running.

## PART 2: Follow this 10 habits if you want to succed

As you can see, deliver a website is amazingly easy. And the way we focused in one single project, gave us enough fullfilment to keep reading. Now I will recall Steve Yegge advice on how to learn to math for programmers. He says:

> The right way to learn math is breadth-first, not depth-first. You need to survey the space, learn the names of things, figure out what's what.

I think the same applies to most of knowledge. Understanding an specific object or topic won't make anything unless you work in a broad general view of what you are doing as a whole. That's why we launched a whole website, so you can see all the process. Of course, this is usually more complex than the way we did it but now you kind of get the role of everything you interacted with.

As time flows, you'll find yourself more into the way Git works or Bootstrap, or you might want to style it with some CSS. But for now there's a delivered product that iterates a very superficial yet crucial layer or level of knowledge inside your mind. So Mastery is less about knowing all concepts and codes by heart and more about being able to deliver a quality product for some given specifications with our current capabilities. There's something about that I learned through Microverse and I love it.

You start by cloning websites and suddenly you find yourself catching up some of the most important concepts of Web Design, such as CSS Flexbox or Grid. For CSS, one of my favorites was [this one](https://designshack.net/articles/css/5-steps-to-drastically-improve-your-css-knowledge-in-24-hours/). You don't have to be an expert to be successful. Just master things.

Let's start the list now:

### Breathe first, deep later

So remember our adapted mantra:

> The right way to learn CODE is breath-first, not depth-first. You need to survey the space, learn the names of things, figure out what's what.

### Documentation is everything

There's an old saying when starting to code: *RTFM*. It stands for *Read the f\* manual*. And that's because most of us don't read manuals. How do you want to understand something if not by reading its instructions?

However, remembering our breathe first strategy, you can also start by watching a YouTube tutorial just to get familiar with the general features of what you want to learn. I also read articles a lot. But the most important is to classify the content you liked the most to create a good links collection. For those purposes, I highly recommend you [pinboard.in](https://pinboard.in/u:angelmoma).

Try to review you collection and start writing articles to give them a narrative flow. If you ever stuck by not knowing how to write some processes down, trust this sources:

- Use [Hemingway](http://www.hemingwayapp.com/) to make yourself readable.
- Translate every word with [Deepl](url).
- Check your grammar with [Grammarly](url).
- Read faster with [Spreeder](url).

In the long term, this notes will help you to easily remember things you want to review.
Don't forget that Google will become your best ally. Also Stackoverflow.

### Play around

With this I literally mean play games. There are too many interactive games out there to help you get the most out of your learning experience. I highly recommend [mastery.games](https://mastery.games/) to learn Flexbox and Grid.

### Get involved

Programming has to do with solving problems. Find a problem that make you feel curious and dive into it. Is it about making web animations? Do you want to make an interactive dashboard to optimize your spendings? You just to start an e-commerce? Feel free to find things that you'd like to solve.

### Clone and copy-paste

If you are learning Web Design, some of the most useful things you can do in the beginning is trying to clone websites. Trust copy paste but just to learn and play around on how properties work.
Use Firefox Developer Edition. It will be also valuable when trying to understand javascript.

BUT when you are writing actual code, NEVER COPY AND PASTE. It's better if you click on concepts by yourself and make an script work rather than copying and not actually learning. Also, rest at least 10 minutes every 50 of work and try to take a 30 minutes break after 4 rounds of 50 minutes to keep you mind clear and not overwhelm.

### Learn by chunks

For me, the most fundamental project to start web development is to deliver a GitHub pages site either with plain HTML or through Jekyll if you are planning to make a whole static web project. It takes no more than 2 hours and the fact you are achiving results pumps adrenaline and joy up.

Try to stick to small delivered projects. You can rely on Clockify or Trello to keep track of your times. Motivation is the most important skill to have after a couple of months that progress speed starts to slow down.

Don't get stuck. If after chunking you are feeling like unable to solve the problem you are currently facing, just visualize another problem you know will be easier to solve for you and once you get your endorphins reward, come back to the harder one knowing you achieved something cool just before. 

### Exercise both mind and body

Everything starts with what you eat and how you move. I have to confess I've struggled with some compulsive behaviour and issues dealing frustration. Most of us milleannials are like that, the span of attention a digital consumer has is really short. So it gets harder and harder to deal with anxiety, FOMO and depression. I think medidation and exercise are the best options. It's important to realize that code is all about patience and analysis.

Remember our brain is also a reward-oriented system. There are plenty of tools to help you achieve your goals like delayed gratification through workmode extensions for browsers.

### Find a Coding Partner

I want you to repeat this with me:

YOU

ARE

NOT

ALONE

Nowadays, specially due to Coronavirus terrible pandemic, a lot of people is getting more and more in videoconference. Are you worried about how to make it after the economic crisis? Learn something useful like Data Science basics or even code, create communities of self-learners. Ask a good friend to share screen with you as you work learning something new. It would be amazing if, instead of play one of those MMOGs for just half a year, by spending your time learning with a partner for the next months you could accelerate your code learning process. In Microverse, that's what they call *pair programming*. And it can get you in a **60,000 USD** per year job.

#### Get some good headphones

Like those for gamers, good sound and good mic.

### Show your work

- Make tutorials. Every time you are explaining something to someone else you learn a bit more how it actually works. That's why recording yourself showing off (always with humbleness) your projects or what you know is a good way to get some eyes on your work and might even help you reach some customers.
- Also review your work. Always look for best practices and linters to highlight and show in terminal your errors.
- Set a portfolio. There are many templates you can use, most of them are responsive. If you want to include your CV on it, I highly recommend [Flow CV](https://flowcv.io/login).

### Take your time (but not too long to get bored)

It's easy to get stuck at some reading listening voices around saying you've been too long working on it. Don't worry. Try as many times as you need. Speak loud if that helps. Write notes. Practice playing around with the concept in your text editor. If you've spend more than 2 or 3 weeks without moving, ask for help and work in something related until you figure it out. Do not stop learning.

Microverse has brought me into a nice combination of education methodologies. Apart from *Mastery Learning*, they encourage us to work through *Deep Learning* as well. This basically stands for high quality learning. Avoid distractions, get good lights on you, a confortable chair and try to deep focus in one only task for at least 25 minutes. 

## Conclusion

Let's recall the advices:

- Breath first
- Take notes
- Trust games
- Find a problem you care about
- Clone and understand
- Learn by chunks
- Exercise!
- Work in pair
- Show your work
- Take your time

As Codecademy says, learning to code will help you in every aspect of your life. It will have effects not only in the way you work and the chances to get some extra income but it will also make you feel like what you considered problems before are actually opportunities to deliver creative solutions. If you liked these habits I am sharing, you should seriously consider joining Microverse bootcamp.

Follow me on Twitter or LinkedIn to get a special referal: @angelmoma_

## Some extra references

You feeling stuck with adult content on the internet? Trust [noFap]().
Can't you focus for more than 30 seconds? Read [Attention Revolution]().
Feeling overwhelmed? Try [Hacking motivation]().
Get inspired by this [hacker manifesto]() or Kevin Mitnick's [work]().