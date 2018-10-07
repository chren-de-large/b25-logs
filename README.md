# b25-logs

# Decentralised systems
*Simply being decentralized isn't enough.*
- you wanna call someone if it breaks
Comment by Wired on adoption:

"IPFS gets around this largely by letting people decide which of the content they've visited they actually want to share. But this means that less popular content, even if it's perfectly legal and ethical, might end up disappearing if too few people share it. Benet and company are working on a system called Filecoin that, not unlike Storj, would compensate people for providing access.

Even overcoming these trade-offs inherent in decentralization, people may still not want to use these apps. Storj may be able to win over businesses by being cheaper, but even if it is more reliable, the idea of storing data on random machines scattered across the internet instead of in a traditional data center sounds risky compared to, say, the massively robust AWS, backed by Amazon's technical know-how and billions of dollars. Convincing people to use decentralized alternatives to Facebook and Twitter has proven to be a notoriously difficult problem. Getting people to use what amounts to a whole new version of the web could be even harder."


## Research
[Wired pop article: Pied Piper's New Internet Isn't Just Possible—It's Almost Here](https://www.wired.com/2017/06/pied-pipers-new-internet-isnt-just-possible-almost/)

## Example technologies
### [STORJ](https://storj.io/)
#### What
- Client-side encryption so data owners can trust that only they can access their files. Files cut up to small pieces.
- Cofounder John Quinn says that in order to lose a file, 21 out of 40 of the computers hosting it would have to go offline.

#### When
- Launching in early 2019.

#### How
- Storj network relies primarily on servers, laptops, and desktop computers.

#### Problems
- Storj is a decentralised storage service, not a *whole new internet*.
- Tools like Storj and the venerable peer-to-peer sharing system Freenet make it impossible to know just what content you're storing for other people, which means you could be playing host to, say, child pornography.

### [IPFS](https://ipfs.io/)
#### What
- Eventually, the IPFS team and a gaggle of other groups hope to make it possible to build interactive apps along the lines of Facebook that don't require any centralized servers to run.
- "You need to build a new internet that people will actually want to use."

#### Problems
- IPFS creator Juan Benet told us last year that the project is trying to work out ways to let publishers "recall" pages that are being shared. But that idea is also fraught. What's to stop a government censor from using the recall feature? What happens if someone creates a version that ignores recalls?
- IPFS gets around this largely by letting people decide which of the content they've visited they actually want to share. But this means that less popular content, even if it's perfectly legal and ethical, might end up disappearing if too few people share it.

### [FREENET](https://freenetproject.org/)
Article 08/03/2000: https://www.wired.com/2000/03/alternative-net-protects-pirates/

- Scheirer pointed out that the Web is trustworthy because of the content on certain domains, and he likes the convenience of tracking devices such as cookies that remember log-in names and passwords. "Many of the advantages of Freenet are disadvantages to me," he said.

- "Because it's decentralized no one can be held responsible for it," Clarke said. "Once it's released there's no point coming after me because there's nothing I, nor anyone else, can do to shut it down."

- Napster's central servers, it would be almost impossible to disable a Freenet network running on machines all over the world.

- [Freenet video introduction 1:51:00 duration](https://youtu.be/zu9gM3_gIfM)

### [Indie Web](https://freenetproject.org/)
Article 14/08/2013: https://www.wired.com/2013/08/indie-web/

the web we lost: https://youtu.be/9KKMnoTTHJk

- IndieWebCamp began in 2011, but the movement harkens back to the spirit of the early [social web](http://anildash.com/2012/12/13/the_web_we_lost/).

- "Mass adoption has never been our focus," he says. "It's more about enabling people who are already interested." He'd rather the Indie Webbers lead by example than hype projects that aren't ready yet.

- USER FEEDBACK: "I used to maintain my own blog using an open source blogging framework," she says. "But ultimately, I'm blogging to write and to share what I've written. Maintaining my own implementation, trying to keep the design current on my own, dealing with things when they broke, and hosting it myself was a distraction from that goal." Kane ditched her open source blog and moved to Medium, an online publishing service created by Twitter co-founders Evan Williams and Biz Stone. "While I have the privilege of having had some programming and design training, most of the people in the world don't have access to those skills," she says. "One of the most compelling aspects of mainstream publishing platforms like Twitter is that they lower the bar to publishing online."

- VISION: But people like Çelik envision a world where open source software lowers the bar just as easily. They see a pocket-sized web server pre-loaded with all the Indie Web applications you could possibly need.

- Augustin Bralley, and Harlan Wood took a first step in that direction in building a 1 terabyte file server that can fit in the palm of your hand. They cobbled it together using a Raspberry Pi, a portable hard drive, and the Camlistore software built by Fitzpatrick and Slatkin.

- This is a fundamental tenet of the Indie Web movement: You should always have the option of running a web service on machines that belong to you.

- On any given day, you'll find about 30 or 40 of them on an IRC chat channel, and each summer, they come together in the flesh for this two-day mini-conference, known as [IndieWebCamp](indiewebcamp.com).
- "The Indie Web is a community of folks interested in owning their own content – and identity – online," says Tantek Çelik, another developer at the heart of the movement.
#### Projects
##### [Peerkeep](https://perkeep.org/)
- Alternative to Google Drive

Things Perkeep believes:

    - Your data is entirely under your control
    -  Open Source
    - Paranoid about privacy, everything private by default
    - No SPOF: don't rely on any single party (including yourself)
    - Your data should be alive in 80 years, especially if you are

- "That may seem like an odd undertaking for two people employed by Google. But this is how many Googlers think, harboring the unshakably idealistic view that the needs of the web as a whole are more important even than those of the web company they work for."

##### OpenID
- "I wanted a system that no company controlled," he says. That's another tenet of the Indie Web movement. The result was [OpenID](https://openid.net/), software that could provide a single sign-on for any site willing to use it. It was adopted not only by LiveJournal, but by Google, Yahoo, and others and arguably marked the beginning of of the modern Indie Web.

##### [StatusNet](https://status.net/)
- There was Control Yourself, an open source Twitter alternative now known as StatusNet

##### [DiSo](https://github.com/diso/diso)
- No longer active
- DiSo (dee • zoh) is an umbrella project for a group of open source implementations of these distributed social networking concepts. or as Chris puts it: "to build a social network with its skin inside out".


##### [Diaspora](https://diasporafoundation.org/)
- Raised 200k on kickstarter
- And projects like Diaspora couldn't attract the numbers they needed to compete with the Twitters and Facebooks.
- Sadly, Diaspora co-founder Ilya Zhitomirskiy killed himself in November 2011.


### MESH
"Even if IPFS, Storj, or one of the countless other decentralized platforms out there do win people over, they're still technically riding atop the existing internet infrastructure controlled by a shrinking number of telcos. Silicon Valley hasn't addressed this problem yet. But what if you could chain the smart phones and laptops of the world together using WiFi and Bluetooth to create a wireless network that was free and open to everyone, with no need for Big Telecom?"

#### Projects
#### Serval
Australian computer scientist [Paul Gardner-Stephen](https://www.flinders.edu.au/people/paul.gardner-stephen) tried to do something like that after the Haiti earthquake in 2010. "Mobile phones have the capability to run autonomous networks, it's just that no one had implemented it," he says. He co-created [Serval](http://www.servalproject.org/). Mesh-based messaging app.

- Created also mesh extenders.
##### Privacy/security
- "Voice calls and text messages are always end-to-end encrypted using strong 256-bit ECC cryptography. "
##### Updates
- Currently testing, latest article 4 April 2018

##### Problems
Trying to turn people's mobile phones into servers drains their batteries too quickly to be practical. Today, the Serval team relies on solar powered base stations to relay messages.

### [Wlan Slovenija](https://wlan-si.net/)
- Now covers all of Slovenia and is spreading to neighboring countries.

### [FIRECHAT](https://en.wikipedia.org/wiki/FireChat)
-- Looks DEAD

#### License
Proprietary

### [GUIFI.net](https://guifi.net)
- 39k nodes
- 64.642,4 km of links
- 74 last week new nodes
- 32 working nodes last week

TODO: Article: https://www.wired.com/2016/07/forget-comcast-heres-the-diy-approach-to-internet-access/
- Spanish engineer Ramon Roca got tired of waiting for telecom companies to wire his town — so he did it himself.
