# Hydrogen future, the website, the communication for contributors

> There are so many questions regarding the whole Hydrogen project raising over the last months (or even years?), I don't even know where to start.

~But, maybe let me start from here (me) to get the whole picture:~ *This personal info is placed [here now](AUTHOR.md) to get out of the way.*

The potential of Hydrogen is much higher than many would probably think of. I am pretty sure. For many it's just another drum thingy with a kind of outdated interface. While some developers may know that it's not. 

Since I know how often drum and rhythm section programming gets misunderstood and many instrument concepts get in the mix I can surely say: It's all about communication, about making clear what Hydrogen can accomplish what others can't. _It_ actually _HAD THE POTENTIAL_ to be __the__ intuitive and fast drum machine on the qualified fingertips, others are not!

But it makes me sad to see how things go wrong IMHO with Hydrogen, the road map, the development time line and the aging process, which makes it even worse. And it feels like never leaving a certain beta kind of status. And this is where my decision came from to write this letter to you. In the hope to motivate, to refresh, but not to offend anybody or to simply complain.

I know how hart it is to keep up with a started project or to contribute to an open source project without financial support and with only limited time in life. I have much respect for your outstanding work on this project and I only would love to see it growing, more bug free and more respected in your interest.

> But many possible chances to optimize a situation can fade when options and nodes to make decisions are missed in time frequently.

So please, let me show you a list of questions raising over the last 2 years, and if I wasn't too offending hopefully some of the contributors or developers can chime in to give their 2 cents to my concerns. It maybe makes things clearer to me and shows off my misunderstanding of the whole or it maybe can help you to get a distant look at your project from somebody who was much involved in professional drumbeat and rhythm section programming. 

Please notice that my motivation is coupled with the will to support, contribute and help the project, but only if the minds are open. Some questions are simple, others are more generic, others are maybe too far beyond a simple possible answer.

## List of points I wonder about (not finished yet):

  1. If Hydrogen is on Github why the installation from source documentation still recommends svn? Git is the most common installed version control system library on most Linux machines. Does svn even still work for Hydrogen or is the website outdated here? Concentrate on one place for development, bug tracking and more. Github/Gitlab is absolutely fine for an open-source project like Hydrogen. And other services, which are build around Github or Gitlab are easy to add. They are modern, neat, clean, and often helpful to speed up communication and protocoling/reporting.
  2. Why nobody from the closer cycle can't be found on typical developer channels like IRC or runs some more PR in the web, like on twitter about the project? There are social sync services and modules for your CMS available doing the job for you. It feels so outdated to get in contact with Hydrogen guys. And the forum is quite broken, TBH. I would love to see some of you Hydrogen guys in IRC or somewhere else at minimum. There is no chance for active pro audio Linux contributors, who regularly talk on IRC to each other, to catch you for some exchange and to get motivated for contribution. This would live things up.
  3. The website feels kind of broken at some point (and I know what I am talking about).
    + Sometimes it says you are logged in, sometimes not. 
    + Links are dead and docs are far outdated.
    + The forum activity is low because the forum lacks many useful additions.
    + The website and especially the forum is damn slow. Do you need server resources? We maybe can help.
    + The input forms act weird and feel broken. Sended forms often didn't get viewed (forum).
    + Why not making a hard cut here and start a new fresh Drupal 8 installation with a modern Bootstrap or whatever mobile first design
    + Users and forum posts etc can be synchronized or copied via feed import or migration modules
  4. Broken features (testing env: Debian 9 LXDE, Hydrogen 0.9.7 and compiled from source)
    + Import Export library does not work flawless. A simply exported library should simply be able to be imported and work again. It does not (at least on Linux).
    + The \<info\> group of an exported library is broken under Linux, maybe caused by a broken export text file type character coding set.
    + Overall experience users tell me is that Hydrogen acts weird on some points here and there with no clue whats up and there are only few resources to read about it. And it is very sensitive about HOW you do things. But this is not how software should be. Software should only provide functions, which it can really unmistakenly manage or there should be clear and easy to reach sources explaining the HOW to not break it.
    + A manual should have a search or filter function to be able to jump to search words. This is a standart function on pdf viewers and common by users who regularely read manuals.
    + The GUI of Hydrogen should be flexible and stretchable to cover the many different screen sizes nowadays. Fixed size interfaces are quite out of date.
    + ... a.s.o
 
 > Here I was starting to worry if I would ever sent this letter and stopped writing ...
