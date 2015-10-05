# pio.io the decentralized social web

Pio is code, conventions, and standards for a social web platform built on top of IPFS. 

Blogging and the platforms which were built upon it were decentralized. Publish your website and start posting. Readers would collect RSS or Atom feeds and keep track of what to read through feed readers. You needed to get a server to host the blog, either installing software like movabletype & wordpress or you could use blogger to publish via ftp. Eventually hosting services like wordpress.com launched and after a while blogging and related activities  moved to being fully hosted at places like tumblr (low brow), livejournal (hipster), and medium (high brow). These services still exist and are the dominate way of writing long form online. 

There are millions of blogs which generate huge traffic and that ecosystem isn't going to disapear. But it's also lost it's edge. It's been defeated by the  app world. People's primary interaction with the social web is through apps. 

But these app's are very centralized and that has all sorts of bad implications for what people can do with them. The moment it's centrally controlled then that central authority needs to create all sorts of restrictions. Some are due to the market, controlling the platform to make it safe for advertising, and some are due to the state. In western 'open' democracies we mostly censor to protect copyright and intellectual property and elsewhere it's done to restrict the free flow of ideas. Even if the creator's of this technology want it to be open and free they can't. The legal and technical constraints force them in to controlling their platforms.

So we see conflicts, the queer community fighting for the right to user their own self defined names. Mother's wanting to be able to publish pictures of themselves breastfeeding. Or even the restriction on the karma sutra, with our without pictures, being included in Apple's app store. 

So we need something better. We need a communications medium which is really a medium based on standards and isn't a walled garden controlled by one or a group of organizations. Federation, the idea behind diaspora, was a valient attempt. The idea was to make social media more like email, controlled by the people running email (or diaspora) servers with the ability to follow and communicate with people on other servers. Twitter itself flirted with this federated model before it decided it'd rather own the space. 

Even though the main thurst of social media has been driven by this massive centralization, there's been a small rebel alliance who've kept the faith. The indie web crew. They've kept on building software for a self hosted, open standards based model for how we communicate online. Their work and software hasn't taken off, but that doesn't mean that they haven't been spending years digging in to solving the hard problems of what a less centralized, less controlled network would look like. There are standards for this stuff, if not widely adopted. 

Just because we have ideological or practical reasons why we want a decentralized social media platform doesn't make it happen. For years i've dismissed attempts at building a peer to peer web being sisyphean task. The tech stack for centralized or federated technologies were so good and the decentralized tech was so bad. But that's changed. In filesharing we've got years of refinement in bittorrent. In distributed processing and balancing work we've got the blockchain which drives bitcoin. And thirdly we've got a distributed way for handling files and changes in them through git. 

Those technologies have been combined to create IPFS, a project to re-decentralize the web, make it so data isn't hosted only by the creators but also anybody who's consuming or viewing it. The original publisher can go away, offline, and the content is live because others want to view it. 

The idea for Pio is to build a decentralized social media platform based on open technologies like IFPS and web standards. Pio will be an app, or many apps, which publish based on convention and light weight standards. It will cover publishing content, sharing content, and consuming. 

# How It Works (Or might work?)

Pio is used as an application. Users install a native application on their desktop or mobile device. That application has two parts. A front end which provides an interface for viewing and publishing content and the ipfs backend storage engine. 

Publishing. Each user will publish an ipns hash indiciating their current blog location. This hash is a long living pointer to where their current content is published. The content is structured pretty simply, a series of files in a directory with an updated RSS / json file linking to new content. The plan is to encourage storing the files in various formats, including at least html and json. Attachments are just uploaded and linked to via it's ipfs:// url from the primary content. 

Reading. You could read a single user's feed or sub-feeds of content through something which feels a lot like tumblr. A consumption interface which let's you comment, share, and publish your own content. Who you follow is similar to blogs, twitter, and tumblr instead of the two way default on facebook.

Updating. There needs to be a system to figure out who's updated what. I still need to figure this part out but it'll probably adapt something like LOAF. Basically it needs to be fast, close to real time, and where the burdon of checking for updates is on the reader. Better to support somebody having millions of followers than following millions of people. 

An open platform. So while Pio will have a compiled application which can be used, the content is published via hash's on the open IPFS network. This has two major implications, it's not setup for pivate communications. This is about public social media, creating a networked public sphere. This open nature means anybody could follow the conventions and build their own app in the pio ecosystem. Twitter's most powerful element was it's app ecosystem and that was abandoned when twitter faced an attempt to hijack the ecosystem through other companies buying up the twitter clients. In Pio the ecosystem is protected because third part apps have direct access to the underlying data in IPFS and there is no centralized place where they could be locked out. 

Pio is a work in progress and subject open to change. 

# Who are you?

I'm @rabble. I've been doing this internet stuff for a long time, i'm not a kid, although i was one when i started at my frist startup in 1995. I've had my own blog since 2000, anarchogeek.com. I helped create a media activist network for self publishing news at indymedia.org. In 2004 i joined a podcasting startup Odeo as it's lead developer. While at Odeo i worked on txtmob and got everybody excited about building something with sms and telephony. That work lead to Odeo's creation of Twitter. Since then i build, a now killed, privacy protecting location sharing platform for Yahoo, FireEagle. Most recently I was CTO of Digitial Garage's Neo, a lean product development company, and as a senior consultant to avaaz.org. 

# What does Pio mean?

The word pio pio is roughtly the word twitter in spanish. It's the sounds birds make when they're communicating. 
