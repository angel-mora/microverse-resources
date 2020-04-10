 # THE ULTIMATE GUIDE TO HACK YOUR MOTIVATION FOR LEARNING TO CODE!

*This is a very motivating article for you. If you follow it until the end, you'll find yourself having your first webpage is a few minutes. It doesn't matter if you have never done this before.*

I'm presuming a very simple yet validated hypothesis:

> Attention is our most valuable form of capital nowadays.

Corporations, marketing, and some other industries know it and are developing technologies to catch our attention 24/7. There are a lot, A LOT of distractions nowadays. Each of them lasts no more than 30 seconds and most of them become addictive. Adult entertainment or addiction to certain social networks can easily catch you up. Especially if you are a Millennial. Millennials struggle a lot to figure out what to do. We want to solve all kinds of trouble out there but we can't keep focused on one only thing for more than that half a minute.

And there's a reason for that. Some companies invest millions of dollars trying to catch your attention. It's so hard to keep focus nowadays and probably the last thing we want is to use our attention to do something hard, frustrating and uncomfortable.

On the other side, there's a veil of wisdom surrounding programmers. It's not like that. It's just people who committed a lot in getting a goal and finding the motivation to keep going. Yet Web Development and Data Science, a couple of frustrating code-related things to learn, are some of the best well-payed careers in the US. And guess what, remote work is a very popular practice among programmers. Now, most computer-related jobs have become remote worldwide and chances to get a remote job in a global tech brand have increased.

So the best thing one could do if want to have a good job and live a good life is to get into the new digital economy. Programming is not only about hacking and binary numbers. For me, it's about simpler things such as Logic and counting. As resources scarce and COVID-19 stops the world economy, programming becomes even more necessary. These violent economic fluctuations will leave a lot of people without a job. They will bring a lot of social struggle. But if you are able to deal with complexity through algorithmic thinking you will be capable of imagining how a post-work world can be. One where we all can work 4-hours shifts and democratically enjoy the benefits of automation. If this sounded to you, you can also check [80,000 hours](https://80000hours.org/) to make an effective change through your professional career.

But doing so is, I won't lie to you, actually hard. As our attention span decreases, our motivation to do things that get us out of our comfort zone is decreasing too. I recently joined Microverse Web Development Bootcamp and I'll tell you some of the things that worked for me. I'll be honest with you. Before I started Microverse Bootcamp, I didn't have enough motivation to believe I could master web development. So I researched how people can start to do something so challenging and keep motivated during the tough journey.

That's when I read Motivation hacker (you can get a good review of it [here](https://www.evernote.com/shard/s4/client/snv?noteGuid=ed74279f-29ba-470b-99c1-31387f5ea5fa&noteKey=6189febf5d13ded1d38706e54fd05daa&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs4%2Fsh%2Fed74279f-29ba-470b-99c1-31387f5ea5fa%2F6189febf5d13ded1d38706e54fd05daa&title=The%2BMotivation%2BHacker)). It stands for understanding ourselves like reward-oriented learners so we can hack ourselves. That way we can achieve our goals.

Now that everything has stopped, time is your most valuable asset. And you are giving it to Facebook, Netflix, Youtube, Amazon Prime or some adult entertainment company. That time could make you a valuable asset to rebuild our societies or get you in a more fulfilling employment situation.

In my personal experience... Microverse is a great help and I'll explain to you why with these recommendations to learn to code.

I'll start with a Ubuntu-based quick tutorial to set a live website in less than 30 minutes.

## PART 1: The Tutorial

### STEP 1: Install Visual Studio Code

https://linuxize.com/post/how-to-install-visual-studio-code-on-ubuntu-18-04/

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

Start a new repository with the license you want but including the README file.

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

Now go to [Bootstrap website](https://getbootstrap.com/docs/4.4/getting-started/introduction/), copy the Starter template and paste it in your index.html file. It already says the classic *Hello World*. Now save the changes.

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

Git is a bit complicated but for now, you'll be good if you follow the instructions. The proper workflow to save and upload info on your website is with the next commands:

```

$ git status

```

To check the status of your repo. It will say your current branch and if there are things to commit to the staging area (don't worry if you don't get it yet, just follow the instructions). 

Now you will add your current changes and write a meaningful message for your commit (which is the version you are saving and adding to stage now):

```

$ git add .

$ git commit -m "add index.html file and basic Bootstrap starter template"

```

The last step is to push your changes to the online repo. Code this commands and write down your GitHub credentials:

```

$ git push origin master

```

### STEP 5: Set your website live

Go back to your repository in GitHub.

Go top-right corner and click on Settings.

In that same window, go down until you reach GitHub Pages section.

In Source, select *master branch*.

The browser's window will update and take you back to the beginning. Go down to find GitHub pages again. Now you'll have your site published in something like https://user.github.io/project-name

and *voilá*, you have your first site up and running.

## PART 2: Follow these 10 habits if you want to succeed

As you can see, deliver a website is very easy. And the way we focused on one single project, gave us enough fulfillment to keep reading. Now I will recall Steve Yegge's [advice]() on how to learn to math for programmers. He says:

> The right way to learn math is breadth-first, not depth-first. You need to survey the space, learn the names of things, figure out what's what.

The same applies to most knowledge. Understanding a specific object or topic won't help unless you work in a broad general view of what you are doing as a whole. That's why we launched a whole website, so you can see all the process. Of course, this is usually more complex than the way we did it but now you kind of get the role of everything you interacted with.

As time flows, you'll find yourself more into the way Git works or Bootstrap, or you might want to style it with some CSS. But for now, there's a delivered product that iterates a very superficial yet crucial layer or level of knowledge inside your mind. So Mastery is less about knowing all by heart and more about being able to deliver a quality product with our current capabilities. There's something about that I learned through Microverse and I love it.

You start by cloning websites and after a couple of weeks you are catching up some of the most important concepts of Web Design, such as CSS Flexbox or Grid. For CSS, one of my favorites was [this one](https://designshack.net/articles/css/5-steps-to-drastically-improve-your-css-knowledge-in-24-hours/). You don't have to be an expert to be successful. Just master things.

Let's start the list now:

### Breathe first, deep later

So remember our adapted mantra:

> The right way to learn CODE is breath-first, not depth-first. You need to survey the space, learn the names of things, figure out what's what.

### Documentation is everything

There's an old saying when starting to code: *RTFM*. It stands for *Read the f\* manual*. And that's because most of us don't read manuals. How do you want to understand something if not by reading its instructions?

But don't forget to remember our breathe-first strategy. You can also start by watching a YouTube tutorial to get familiar with the general features of what you want to learn. I also read articles a lot. But the most important is to classify the content you liked the most to create a good link collection. For those purposes, I recommend you [pinboard.in](https://pinboard.in/u:angelmoma).

Try to review your collection and start writing articles to give them a narrative flow. If you ever stuck by not knowing how to write some processes down, trust these sources:

- Use [Hemingway](http://www.hemingwayapp.com/) to make yourself readable.

- Translate every word with [Deepl](url).

- Check your grammar with [Grammarly](url).

- Read faster with [Spreeder](url).

In the long term, these notes will help you to easily remember things you want to review.

Don't forget that Google will become your best ally. Also Stackoverflow.

### Play around

With this, I mean to play games. There are too many interactive games out there to help you get the most out of your learning experience. I recommend [mastery.games](https://mastery.games/) to learn Flexbox and Grid.

### Get involved

Programming has to do with solving problems. Find a problem that makes you feel curious and dive into it. Is it about making web animations? Do you want to make an interactive dashboard to optimize your spendings? Do you just want to start e-commerce? Feel free to find things that you'd like to solve.

### Clone and copy-paste

If you are learning Web Design, some of the most useful things you can do in the beginning is trying to clone websites. Trust copy paste but only to learn and play around on how properties work.

Use Firefox Developer Edition. It will be also valuable when trying to understand javascript.

BUT when you are writing actual code, NEVER COPY AND PASTE. It's better if you click on concepts by yourself and make a script work rather than copying and not learning at all. Also, rest at least 10 minutes every 50 of work and try to take 30 minutes to rest after 4 rounds of 50 minutes, to keep your mind clear and not overwhelmed.

### Learn by chunks

For me, the most fundamental project to start web development is to deliver a GitHub pages site either with plain HTML. You can also try Jekyll if you are planning to make a whole static web project. It takes no more than 2 hours to learn and the fact you are achieving results pumps adrenaline and joy up.

Try to stick to small delivered projects. You can rely on Clockify or Trello to keep track of your times. Motivation is the most important skill to have after a couple of months that progress speed starts to slow down.

Don't get stuck. If after chunking you are feeling unable to solve the current problem, visualize another problem you know will be easier to solve for you. Then solve it. Once you get your endorphins reward, come back to the harder one knowing you achieved something cool before. 

### Exercise both mind and body

Everything starts with what you eat and how you move. I have to confess I've struggled with some compulsive behavior and issues dealing with frustration. Most of us millennials are like that, the span of attention a digital consumer has is really short. So it gets harder and harder to deal with anxiety, FOMO and depression. Meditation and exercise are the best options. It's important to realize that code is all about patience and analysis.

Remember our brain is also a reward-oriented system. There are plenty of tools to help you achieve your goals. Like delayed gratification through work-mode extensions for browsers.

### Find a Coding Partner

I want you to repeat this with me:

YOU

ARE

NOT

ALONE

Nowadays, especially due to the Coronavirus pandemic, a lot of people are getting more and more in videoconferences. Are you worried about how to make it after the economic crisis? Learn something useful like Data Science basics or even code, create communities of self-learners. Ask a good friend to share the screen with you in a video call as you work learning something new. It would be amazing if instead of play one of those MMOGs, by spending half a year learning with a partner, you could become a web developer. In Microverse, that's what they call *pair programming*. And it can get you in a **60,000 USD** per year job.

#### Get some good headphones

Like those for gamers, good sound, and a good mic.

### Show your work

- Make tutorials. Every time you are explaining something to someone else you learn a bit more how it works. That's why recording yourself showing your projects or what you know is a good way to get eyes on your work. It might even help you reach some customers.

- Also, review your work. Always look for best practices and linters to highlight and show in terminal your errors.

- Set a portfolio. There are many templates you can use, most of them are responsive. If you want to include your CV on it, I highly recommend [Flow CV](https://flowcv.io/login).

### Take your time (but not too long to get bored)

It's easy to get stuck at some reading listening voices around saying you've been too long working on it. Don't worry. Try as many times as you need. Speak loud if that helps. Write notes. Practice playing around with the concept in your text editor. If you've spent more than 2 or 3 weeks without moving, ask for help and work in something related until you figure it out. Do not stop learning.

Microverse has brought me into a nice combination of education methodologies. Apart from *Mastery Learning*, they encourage us to work through *Deep Learning* as well. This stands for high-quality learning. Avoid distractions, get good lights on you, a comfortable chair and try to deep-focus on a single task for at least 25 minutes. 

## Conclusion

Let's recall the advice:

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

As Codecademy says, learning to code will help you in every aspect of your life. It will have effects not only in your income but it will also make you see problems as opportunities to deliver creative solutions. If you liked these habits I am sharing, you should seriously consider joining Microverse Bootcamp.

Follow me on Twitter or LinkedIn to get a special referral: @angelmoma_

## Some extra references

- Are you feeling stuck with adult content on the internet? Trust [noFap]().

- Can't you focus for more than 30 seconds? Read [Attention Revolution]().

- Feeling overwhelmed? Try [Hacking motivation]().

- Get inspired by this [hacker manifesto]() or Kevin Mitnick's [work]().