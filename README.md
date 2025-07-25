# bitnames-whitepaper

Sidechain For BitNames/Logins/DNS, Taking on ICANN
05 Feb 2021
MOTIVATION
Hundreds of essays every year were attempted;
the computer automatically rejected any that
were not written by the real Demosthenes
-Speaker for the Dead, Orson Scott Card, Ch 5
TABLE OF CONTENTS
We will start with a few sections emphasizing “the point” of BitNames:
Part 1 -- "One Login" (same username across all platforms)
Part 2 -- Blockchain Social Media, The "Fallback" Strategy
Part 3 -- The Problem of Spam, "Bit-Introductions"
Next, I will backtrack and give explicit details on how exactly a “Namecoin sidechain” achieves this functionality.
Part 4 -- Updates/Clarifications re: the previous BitNames Post
Fifth, I will give a strategy for defeating ICANN. Any BitName system inevitably doubles as a DNS system, which means it inevitably
encroaches on ICANN’s turf. Thus, ICANN are natural enemies of the project. It’s kill-or-be-killed; so let’s kill!
Part 5 -- How to take on ICANN and win!
Finally, I include a half-baked suggestion that DNMs might be decentraliz-able if we had a BitName sidechain.
Part 6 -- Decentralized DarkNet Markets?
1. “One Login”
A. UNIVERSAL LOGINS
With a BitName system, it is possible for me to register the BitName “psztorc”, and then use “psztorc” as my login at any participating web
service.
So, instagram, for example, would let me type in “psztorc” as my username. It would then look up “psztorc” in the BitNames system, and
look up the public key there. Then instagram would ask me to sign a message with that keypair. That is how I would log on to instagram.
I could therefore lay permanent claim to the “psztorc” account, at all services that support BitNames. I would own “psztorc” everywhere,
even on new social media platforms that haven’t been invented yet (and even on platforms that I never use). The digital identity would
really “be” me.
B. “QUBES-OS FOR IDENTITY”
It is certainly advisable for each user to have a few different identities, if only to prevent a hacker from suddenly compromising their entire
internet life in one fell swoop.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 1 of 19
In many ways, a BitName acts as a “password manager”. But imagine if the hacker stole your Password Manager login? That would be
devastating.
But if you had multiple accounts, such as “psztorc-default”, “psztorc-important”, and “throwaway-58930”, then (hopefully) an attacker
would only be able to steal “psztorc-default”. Your “important” account would still be safe, as would your “throwaway” account (that you use
for online trolling, or internet romance or whatever).
Thus, you would have your 4 or 5 blockchain identities. If you talk to someone on Twitter and want to catch up with them on Facebook,
Telegram, or whatever, then you already can! All of the identities would be in one spot. And you’d have your separate “shame/stigma
identity”, for when you go on PornHub or FetLife (or whatever). If you meet someone you like, you already have all their contact info. Like a
big phone book.
C. BLOCKING
Blocking people actually becomes easier in a world where all logins are bound to one digital identity – you can “superblock” someone across
all platforms – even platforms that haven’t been invented yet. (Although I would hope that you would still let usuers “PayMail” you
[perhaps at a higher penalty-rate], in case they have something important to say.)
And two people can superblock each other (after interacting badly on Grindr, or whatever), and yet still communicate normally via their
other identities. Since the identities are separate, you might not even know that you blocked a coworker on Grindr (or whatever); nor would
they.
See also (https://twitter.com/csuwildcat/status/1234932069911810048).
2. Blockchain Social Media
A. PAY-TO-SEND EMAIL
It can already be used for pay-to-send e-mail. The send dialog is
resizeable and you can enter as long of a message as you like.
It's sent directly when it connects. The recipient doubleclicks
on the transaction to see the full message. If someone famous is
getting more e-mail than they can read, but would still like to
have a way for fans to contact them, they could set up Bitcoin
and give out the IP address on their website. "Send X bitcoins to
my priority hotline at this IP and I'll read the message personally."
-Satoshi
Source (https://www.metzdowd.com/pipermail/cryptography/2009-January/015014.html).
B. “X ON THE BLOCKCHAIN”
The strategy that Satoshi outlines above, is a version of a class of strategies that I will call “X on the blockchain”. Specifically, in the case
above, x=email and the strategy is “email on the blockchain.”
All “X on the blockchain” strategies consume a frightening amount of blockspace at scale. For all of them require one Bitcoin txn (at least),
per message sent by a user.
Most people send emails/sms/facebook-posts/tweets at a faster rate than they spend money via card/cash transactions. So, the “x on the
blockchain” scalability problem is even bigger than the regular old bitcoin scalability problem!
C. THE “FALLBACK” STRATEGY
Fortunately, we can turn the half-baked dreams of “putting X on the blockchain” into fully-baked ideas that we can all get excited about.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 2 of 19
My view will combine the naive optimism of the “everything on the blockchain” group, with the Maximalist obsession with “Layers”.
First, we must acknowledge the tremendous power of the blockchain. If there truly were social media “on the blockchain”, then I could
make an account, and post whatever message I want to all of my followers. I would know that they got the message, as intended.
Facebook/Twitter/Govts around the world would not be able to alter the presentation of my message, for any reason. There would be no
“shadow banning”, no “account suspended”, no “demonetization” (see here (https://en.wikipedia.org/wiki/Shadow_banning), here
(https://www.polygon.com/2018/5/10/17268102/youtube-demonetization-pewdiepie-logan-paul-casey-neistat-philip-defranco ), here
(https://twitter.com/BretWeinstein/status/1319355932388675584?s=19) if unfamiliar).
Second, we must acknowledge the absurd technical overhead implied by such an idea. The storage and bandwidth alone would be immense.
Would the messages only arrive once every 10 minutes (as they do in Bitcoin)? Hard to see how it could possibly work.
Nonetheless, via a “Fallback” strategy, I think we can get the best of both worlds. We will indeed have a “Layer 1” Twitter-like 1
messaging
system “on the blockchain” (on the BitNames blockchain). But its use in practice will be rare, limited only to cases where a user is “de-
platformed” from every conventional site (Twitter/YouTube/DNS/Facebook/Gmail) at once.
This change may seem simple, but in practice it would turn the table on the entire internet.
D. DIGRESSION: META-MEDIA
This sub-section is philosophical and can be skipped.
The ‘traditional players’ (Google/Twitter/Facebook/Reddit) are trying to occupy the privileged position of the “meta-media” – the media
through which you learn about all other media (such as new TV shows, books, movies, websites, etc). This position was once held by
newspapers (1800s), and then by radio (early 1900s), and then by TV (1960-2000), and today it is held by something like
Google/Twitter/Facebook/Reddit. (Movie theaters carved themselves a self-sustaining niche loop, via the clever “previews” concept.)
Whoever holds the ‘meta-media’ wields tremendous power, since they can control what is known, what is knowable, and what knowledge
is ‘common’ [publicly acknowledged by everyone]. On top of that: people prefer to be “in the loop”, and so users naturally cluster on a single
meta-media – the meta-media is a natural monopoly. Since anyone who wants to say anything must first come to the meta-media, the
meta-media also happens to learn everything worth knowing very quickly – much faster than everyone else. Tremendous power, the best
knowledge, and a near-unassailable monopoly advantage – what’s not to like?
Against the “meta-media”, everything else must compete. By “everything” I mean all rival medias (radio, TV, and even each individual user)
– we are “commoditized” (https://www.gwern.net/Complement) and have no monopoly power. If we are locked out of our account, we lose
everything. Only a few superstars (PewDiePie, Joe Rogan) have themselves enough monopoly power to fight back. The rest are powerless.
This creates the so-called “chilling effect”
(https://en.wikipedia.org/wiki/Chilling_effect#:~:text=A%20chilling%20effect%20is%20an,reporting%20concerns%20of%20any%20kind.),
and eventual death spiral (loss of rational discourse).
Furthermore, every individual is subject to the meta-media’s prejudices. Neil Postman once lamented (in the 80s): “if I write a new book, I
have to promote it on television!”, since at the time the public got all of their news via TV. Once on TV, he would have to look and act and
dress and speak a certain way – all of which, he thought, was irrelevant to the merit of his new book (which consisted solely of text).
E. BITNAMES AS META-MEDIA?
BitNames is VERY unlikely to triumph over social media.
However, nonetheless, the BitNames-Message-System (BMS) might still have the effect of commoditizing the big sites (Twitter/Facebook,
even the DNS) and robbing them of their monopoly powers. After all, if Twitter disables my account, I can use the BMS to tell my followers
exactly what happened – and where to contact me next. I can shop around, to see if I will be more welcome on Facebook, YouTube, or a
Twitter competitor like Mastodon, Twetch, etc. Culturally, Internet-users would know that, if they want to find someone whose account is
now missing, they can always find them at the BMS.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 3 of 19
Reach whoever, whenever.
-Slogan of Facebook, Inc.
Furthermore, users can easily “download” and “upload” all of their Tweets/Posts/Photos whatever. It would require some engineering, but
in principle it is an extraordinarily simple matter of simply reading the user’s data and saving it locally as some XML file (or whatever). The
file can contain all their tweets, and all the information about timing, replies etc. It can be accompanied by a folder containing their photos
and video.
To facilitate this, there can be scripts and browser plugins which download this information from the traditional sites – eg a plugin that
scans your actual Twitter.com (http://Twitter.com) tweets to make sure that your XML file is up to date (or which makes it from scratch).
Since BitNames are unique, and associated with the user’s social media screenname history, the destination social media site can migrate
entire conversations from one social media platform to another, even if the people involved migrate at completely different times or have
erratic usernames. It is just a simple database join operation.
Thus the commoditization would become intense, and power flow away from the platforms, and back to the users (where it belongs).
As usual, the mere fact that a cheap option to leave exists, would itself enforce much more discipline on the existing social media sites. They
would have less bullying power.
boy looking at stars
* * *
** * *** * *
* * * * *
__[]_____________
Above: Some Art, by me. The [] is a young child, and constellations represent the friends that the child can contact via computer at any time,
thanks to BitName.
3. Spam
Let’s say years ago you started a company and put your cell phone number
on some of the initial paperwork. Then years later the company is bigger
than you expected and you get 5-10 calls a day from sales people, VCs,
and spam.
Is there any solution besides just getting a new #?
Above: Twitter question (https://twitter.com/nathanbarry/status/1223279622755799040)
A. SPAM RUINS EMAIL
The root problem with email is spam. Spam is the reason you need help from Gmail/Yahoo. Spam is the reason that Gmail/Yahoo can’t give
away abundant free accounts (such that we can all have unlimited burners). Spam is the reason why you have to selectively give out your
email address at all (instead of people just being able to look it up). Spam is what makes your email difficult to use.
You can always try to set up your own email server. But then you have to deal with spam yourself. See also (https://lwn.net/Articles/769917/).
B. FALLBACK STRATEGY FOR THE “CORE SERVICES” (EMAIL/SMS)
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 4 of 19
We certainly can’t expect the blockchain to “replace Email” (nor to replace WhatsApp/Telegram/SMS). But via the “fallback” strategy we just
discussed, we might still be able to use it to break up the email/SMS monopolists.
These monopolists provide services on which we rely. Without email/SMS, digital live is almost unbearable – for a start, we can’t even join
Telegram/WhatsApp/Instagram/Twitter without email/SMS. Furthermore, if someone steals our email/SMS, then they can control those
accounts completely: for they are where the “forgot your password?” link leads!
C. “BIT-INTRODUCTIONS”
As before, the key is to only rely on the Blockchain Messaging System (BMS) as little as possible.
In particular, it will only be used for introductions. The first interaction (between two BitNames via email/SMS/Telegram/Snapchat/etc)
requires an on-the-blockchain payment. But thereafter the emails/texts are free.
This would be enforced primarily by the email client, which would just filter out any new messages that hadn’t paid. (After all, it is only the
human attention which is scarce.)
Optionally, the “free” emails/SMS can come with some kind of “downvote button”. If the score reaches -3 (or whatever), then the message
counterparty might have to pay the introduction fee again! The email clients can each track each other’s score (and ask for and report for it),
and so one party can be warned if they are about to lose the attention of their conversation partner.
Thus, the senders of emails, need to make sure that the recipient actually enjoys them – if the recipient hates them, then the relationship is
burnt. Spammers can NOT get around this by sending from many different email addresses, because, remember, they all must be
whitelisted.
D. SMALL RANT ON EXISTING EMAIL
Today’s email systems are not self-sovereign.
Firstly, the big email providers all now require you to hand over your SMS number.
I recently tried to get a ProtonMail address over TOR, but it demanded that I give out an SMS number.
Secondly, the big email providers will sometimes not allow you to access your own email, without an SMS number. Recently, I had all the
correct info (correct username, password, recovery email), but I was traveling and using a fresh computer. Google locked me out for days!
Perhaps this is good for security (and perhaps not), but what is certain is that it is likely to lead to a further loss of privacy. Just imagine –
the internet without anonymous email! And only being allowed to access your email if your physical devices and physical location are
tracked at all times!
4. Updates/Clarifications
My previous post (https://www.truthcoin.info/blog/codex-identity-sidechain/ ) outlined a design for a BitNames sidechain.
However, upon re-reading it, I’ve noticed that the writing is poor and the explanation is bad. I will use this section to try to improve things.
(Probably, it is best to read this section before reading the Codex post. That way you will be forewarned of the awkward/bad sections.)
A. REGRET: SOCIAL KEY RECOVERY
In the post, I regret shilling the “Friend” Reset-Your-Password concept (or recovery-hackathon/) as it is called in the literature).
“social key recovery” (https://adorsys.com/de/blog/social-key-
It is optional. If you don’t want it, don’t use it. Or, you can grant 100% of your “password reset powers” to just a second key that you control
(it would then function as a Revocation Key).
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 5 of 19
Above: Revocation key screenshot, from StackExchange (https://superuser.com/questions/625015/how-do-i-create-a-pgp-key-revocation-
certificate-in-kleopatra ).
The “Friend Reset” idea has three big attractions:
1. Laypeople need a “forgot your password?” in the UX, and the friend-reset is a very very clever, fully decentralized “blockchain way” to
2. 3. accomplish that.
The pairwise relationships require a signature from each party (ie, like a modern day ‘friend request’), and so these relationships
would automatically transform into a Web-of-Trust that doesn’t suck.
Merely by existing, it would passively deter “impostor” profiles and Sybil attacks.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 6 of 19
Above: An impostor twitter profile. The photo is the same as the real Elon Musk, and the name and screen-name (“EloП MЦsk”,
“elionsumusks”) are written to deceive the careless observer. Notice also the ‘social proof’ (https://en.wikipedia.org/wiki/Social_proof)
below – fake accounts created and controlled by computers. See also (https://www.mailguard.com.au/blog/crypto-scams-twitter).
Companies or fly-by-night entrepreneurs will also use your name and face
to sell everything from web services and e-books to shady info products
and penis pills (sadly, all real examples). This is something that my law-
yers deal with on a weekly basis. It's non-stop. For both reputational and
liability reasons, it's important to track and guard against much of this.
-Tim Ferris
Source (https://tim.blog/2020/02/02/reasons-to-not-become-famous/ ).
Furthermore, declaring friend-relationships might be a fun way to onboard casual users (exploiting the ‘social proof’ angle, for good instead
of evil).
But, I regret emphasizing it. Why? Because it is still very half-baked.
B. REGRET: LONG NAMES, AND SHARED NAMES
Why did I allow 100 bytes for names? Now that seems like way, way too many. Even this guy
(https://en.wikipedia.org/wiki/Hubert_Blaine_Wolfeschlegelsteinhausenbergerdorff_Sr.) could be referred to with a 53-length string (using
only 53 bytes of ASCII).
Furthermore, the WoT element passively sorts out all the “John Smith”s (as they would have different core group of friends). Humans just
can’t remember that many bytes, anyway. Which largely defeats the point. Maybe 60 would be better than 100.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 7 of 19
Furthermore, I think it is fine for people to deal with name-collisions in their own way. They can append a “2” to their name, or birthday. I
regret messing with the “X the Fifth” concept.
C. UNDER-EMPHASIZED: NAMESERVER ANALOGY
In the CODEX post, “super-full” nodes play the part of “nameservers”.
You can pay them (even via LN)! On top of that, they can resist DoS by forcing users to do basic hashcash. This is “nameserver
remuneration”.
D. UNDER-EMPHASIZED: NAMESERVER REMUNERATION
“Nameserver remuneration” has a game-theoretic effect, which acts to prevent name-censorship.
Above: The name “libertyreserve.com (http://libertyreserve.com)” has been Censored from ICANN. See also
(http://copyleftsystem.blogspot.com/2013/05/finally-liberty-reserve-website-has.html ).
How so?
Before explaining further, we must review two pieces of background information. First, if you are trying to look up Google’s ip4 address (for
example) in BitName, then anyone with the correct address (the one corresponding to the radix tree leaf hash), can not only give it to you, but
also sell it to you. (This includes Google itself – but of course you’d first need one of their ip4 addresses, so that your computer could find
theirs.) Second, the exact same hash-locked-name-lookup-sale process, can be used to sell you the leaf hash itself. For this you need only
the sidechain headers (a paltry 8 or so megabytes of data, per year).
So: if you want a name, you can buy it. You don’t need a resource-intensive node, or a strong internet connection. You just need some SPV
software, and enough internet access to at least find one nameserver (ie, any “superfull node” on the network). And enough coins to
purchase the lookup, of course.
So, name-lookups are very easy to purchase. And they can be purchased confidentially, from anyone anywhere around the world. A good
start.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 8 of 19
But it gets better. The sellers (the super-full nodes) are likely to be very heterogeneous. Some will be corporations, universities,
hobbyists/enthusiasts, and activist groups, and they will be located all around the world.
Furthermore, the sellers are very competitive – because of blockchain, each seller must render the exact same undifferentiated “lookup
service”. So they compete only on cost. So, (first of all) the equilibrium cost will be very low – near-zero.
But secondly, if a country enforced mandatory “name-censorship”, then customers would respond by ‘purchasing’ from a different country.
“Name-censorship” can only succeed, if it is uniformly enforced across the globe. But it probably cannot – some of the nameserver
superfull-nodes will be in places like Switzerland, Cayman Islands, Somalia, international waters, etc. And some will be run by activists
secretly.
Obviously, any living superfull-nodes can earn money by providing the name-lookup service. But more importantly: the effect of enforcing
“name-censorship”, is merely to deny the home country access to a revenue stream. The state censorship does not actually result in the
name being censored. And therefore, countries are unlikely to attempt to enforce “name-censorship” in the first place.
E. UNDER-EMPHASIZED: JSON
BitNames (in the “Codex” post) do not resolve to mere IP addresses. Instead they resolve to a hash of some arbitrary data. Since you (as the
owner) can modify the data, it acts as a kind of bare-bones super-secure website.
Thus, it solves “cross-platform usernames”…
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 9 of 19
Above: The state of the art (in 2020) of digital identity management. (From here (https://jacob.hoffman-andrews.com/README/the-safe-
way-to-put-a-pgp-key-in-your-twitter-bio/ ), and here (https://www.youtube.com/watch?v=zW0ZBxo3HZs)).
…and it solves “username squatting” as well. Once you have a BitName, you can link it to any new service:screenname pairs you like. (Even
for websites that haven’t been invented yet, or for sites where an impostor is squatting on ‘your’ name.) Remember, the logins are now
Universal – they work everywhere!
F. UNDEREMPHASIZED: NESTED JSON
Nested JSON is both possible and desirable. This gives a BitName even more of the flexibility of a website.
The ‘layer 1’ nameserver can resolve to {the ip4 address, ip6 address, SSL key, and a new ‘interior’ hash}. When you actually contact the
private server (at the ip4 address you were just given), the server can give you more JSON (corresponding to the interior hash). The new
JSON might contain a hash, ad infinitum.
This allows users to gradually share more and more information with each other. Which is rational, and mirrors real-world relationships (in
which you start by giving people your name; then Social Media accounts / business email; then finally your cell number; and last of all your
address, SSN, medical records, etc).
G. HTTPS
http-https/).
Setting up Https is cumbersome and expensive – and, these days, more or less required (https://www.elevated.com/guide-converting-site-
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 10 of 19
In particular, you need to purchase an SSL certificate, from one of the trusted centralized gatekeepers of SSL
(https://en.wikipedia.org/wiki/Certificate_authority#Providers) (with the notable exception of “Let’s Encrypt”, which aspires to be free). In
fact, since you have to re-buy it every year, you really need to rent the certificate on an ongoing basis, forever.
Then you need to install the SSL certificate, which is sometimes quite a chore (https://www.simplemachines.org/community/index.php?
topic=555034.0) involving all kinds of server/OS/site-specific instructions, generous use of FTP/SSH, editing of configuration files, and so
forth.
But with BitNames, HTTPS comes along automatically. Each name already is linked to a known keypair (that is how the “coin” of the name
is managed), already publicly available on the blockchain. And, even if no key were pre-linked (or if the user wished to use a different key),
the user could trivially add one to their layer-1 JSON (and unilaterally update it whenever they like). Thus, BitNames-HTTPS is free,
permanent, user-friendly, permission-less, and decentralized.
It is probably also more secure (https://en.wikipedia.org/wiki/Certificate_authority#CA_compromise). See also
(https://krebsonsecurity.com/2020/11/godaddy-employees-used-in-attacks-on-multiple-cryptocurrency-services/ ).
H. ENCODING
We will have to keep the existing ASCII-backbone (https://www.icann.org/icann-acronyms-and-terms/en/G0339 ) / punycode method.
Otherwise, it would be a chore to translate back and forth and specify what encoding is being used for what.
Still, it bothers me that a whole byte (256 values) encodes a symbol in base-38 (26 lower-case letters, 10 numeric digits, and 2 symbols
[hyphen and period]).
If we chose, we could utilize a custom base-64 encoding, which only makes use of the first six bits of a bit-octet. Every three bytes, it could
split the fourth byte into three chunks, and insert those chunks into the first two bites of each of the three preceding bit-octets.
Certainly, that is a bit of a nutty and counterintuitive way of encoding text as bytes. But it would compress the name-sizes (both storage and
on disk) by up to 25%. And it would have no drawbacks (other than peculiarity).
I. FRONT RUNNING
Name-Registration cannot work properly if front-running is possible. Once a user sets out to register a new Name, they must be able to
obtain it without interference (provided that they are willing and able to pay).
Front running can be solved via the classic hash-reveal strategy. First the “registration” is entered into the blockchain, as a “name inside an
envelope”. Second the “envelope” is unsealed on blockchain.
In other words, you first register a hash(name, salt) and later you reveal the salt. A total of two txns are required.
However, if reasonable guardrails are not imposed on the timeline, people can game the system.
So we need to add some rules:
1. 2. If two ‘Reveals’ claim the same name, then the earlier hash-tx wins. Not the earlier salt-revelation. Rationale: the timing of the hash-
txn is what the attacker is least able to control; the innocent users will always have the earlier hash-txn.
Salt must be revealed within 72 hours (144 blocks). Rationale: hash-txns must expire, otherwise the name-set will not have finality (ie,
any young name might suddenly be uprooted by a an ultra-old hash-txn).
Notes:
If you like a name, and want to use it immediately, and don’t think it will be front-run, then you can just reveal the salt very quickly (in
the very next block, or even the same block). Then you can start using it immediately!
If someone still tries to front-run your name, you have some recourse.
J. BROWSER PLUGIN
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 11 of 19
Should be pretty easy to build a browser plugin that does all of this, especially if that browser plug in has some kind of bitcoin wallet
technology attached to it.
In particular, the browser could tell you exactly what to do, if you visted a non-ICANN domain (see below).
K. TOR SITES
I mentioned you can associate a name with a .onion address. But why not cut out the middleman completely, and just associate the full
onion service descriptor (Step two) (https://2019.www.torproject.org/docs/onion-services)? Instead of using a DHT, you can just use
BitNames itself (ie “BHT”, a “Blockchain Hash Table”).
Further improvements may be possible (https://blog.torproject.org/introducing-bastet-our-new-directory-authority )…
L. PERFORMANCE
Our blockchain will eventually have one name per human (at least!) but a few extra for people who have burner IDs, or business IDs.
That’s a big Merkle Tree.
Or is it?
A 15-billion height Merkle Tree only contains a total of 30-billion items, and has a height of just 34 (since log_2( 15B ) = 33.804). Each node
will be 32 bytes in size, so the total size of the tree would be 960 GB.
See here (https://people.eecs.berkeley.edu/~kubitron/courses/cs262a-F18/projects/reports/project1_report_ver3.pdf) and here
(https://medium.com/ontologynetwork/everything-you-need-to-know-about-merkle-trees-82b47da0634a ).
M. “NEAR” NAMES / TYPOSQUATTING
"You just created a student named Bernard-blank, B-E-R-N-A-R-D-space,
so the computer didn't kick it out as a repeat of another student."
...
"I found something else. I can't do it with your name."
"Oh?"
"Anything with Ender in it gets kicked out."
-"Ender's Game" (1985), Chapter 7, Orson Scott Card
One annoying form of “identity theft” is “typosquatting” (https://en.wikipedia.org/wiki/Typosquatting)
How can we sort the “real” names from the “imitators”? One rule of thumb is that the real names must come first, and the imitators must
(by definition) follow after.
Therefore, next to names, we could always indicate the name’s log-scale age. Level 1 - one month; Level 2 - three months, Level 3 - a year;
Level 4 - two years; Level 5 - five years; ten years; twenty years; forty years; eighty years. These could be color coded so that “El0n Musk” (a
new, impostor name) will be a totally different color from “Elon Musk” (the older, legitimate name).
Secondly, we could Hash160 each name (the hash160 of “El0n Musk” will be totally different from the hash160 of “Elon Musk”), and try to
represent as much of the result as possible.
For instance, we could use a 2 million-strong icon pack. (2*1000*1000)^4 happens to be larger than (2^80), which is half of a Hash160. So
four icons could potentially represent, for example, the first half of a hash 160. Thus we could give every name an “avatars” that are just a
sequence of 4 icons from the pack. They would be calculated deterministically by just taking the Hash160 of the name, taking the left half of
the bytes, and casting it as a 4 digit base-2million number. So, thus, “El0n Musk” would have totally different symbols “Elon Musk”.
This has a number of downsides, especially for any vulgar or unwanted icons. But it would significantly cut down on typosquatting.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 12 of 19
Part 5: How to Take on ICANN and Win
The success of a hypothetical identity sidechain (here, “BitName”), rests more on its popularity/adoption, than it does on any flashy new
technical features.
A. COMMUNITY-FOCUSED
I'd humbly suggest .web as the TLD to use,
but anything will work as long as it is
short and not currently in use.
-dtvan
excellent points ... +1
-satoshi
Source (https://bitcointalk.org/index.php?topic=1790.260).
For adoption, the core design challenge of BitNames is to simultaneously respect two different sets of property rights:
1. 2. The existing domain owners (and/or, those people who wont be aware of the BitName project until a while after it launches).
New domain owners (the people who are fully informed, and want reliable, censorship-resistant self-sovereign names/domains).
I think the best trade-off is to “hard fork” the existing DNS, without “replay protection”.
B. “HARD FORKING” THE ICANN “UTXO SET”
In other words, if you bought “google.com (http://google.com)” from ICANN back in 1995, then when this project launches (in 2025?) you
should already own “google.com (http://google.com)” in it.
At first glance, the most straightforward way of doing this would be to shapshot the existing DNS database and use it as a starting point for
our new blockchain.
However:
1. 2. 3. BitNames (the “new database”) requires each domain to associate with a public key (or equivalent). However, this information is not in
the existing ICANN DNS database anywhere. (Most domain owners have never even heard of asymmetric key cryptography.)
A snapshot of the database (at a single point in time), will not include changes made afterward (even immediately afterward). This is a
problem because BitDNS users deserve the opportunity to test/research BitDNS before adopting it seriously. While they test, they will
rely on their existing ICANN domains (for their serious projects/companies/etc), some of which they will need to resister/buy/sell.
The database is large and constantly changing. In fact, (afaik) there really is no single “one” database for us to copy – there are several
that work together to become consistent as rapidly as possible.
So, it would be better to snapshot in some ongoing way, as users onboard to BitNames. New BitName-user can provide their fresh ECDSA
public key when they onboard.
C. A SUPERKEY
The most straightforward way of accomplishing this, would be to give a “Super User” some special powers.
Specifically, they will be able to re-assign some Names – the “ICANN-style BitNames”:
I will define “ICANN-style BitNames” (ISBs) are those ending in dot-TLD (https://tld-list.com/tlds-from-a-z ). In other words, ISBs are
names which end first with a dot “.”, and second with a text string that was considered a ‘top level domain’ (on the date when BitName first
launched).
All other names are Non-ICANN-style BitNames.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 13 of 19
ICANN-style BitName Non-ICANN-style BitName
“google.com (http://google.com)” “google.anarchy”
“bitcoin.org” “bitcoin.fuckingrules”
“healthcare.gov” “ƒ†‰.Š‡”*
“vgmusic.com (http://vgmusic.com)” ”—hello,_mom!—”
“jackbox.tv” ”..Silk Road..”
“healthcare.gov.is.a.failure.lol”** “healthcare.gov.is.a.failure.lol!!”
* BitNames need to be ASCII, and they cannot contain slashes “/” (as otherwise we could not have a filesystem – eg
“www.google.com/folder/subfolder/page.html” (http://www.google.com/folder/subfolder/page.html”)). But other than that they can
contain any characters.
** Technically, “failure.lol” is a valid ICANN name, since “*.lol” is currently a valid TLD. The previous words (“a”,”is”,”gov”,”healthcare”) are,
in ICANN-world, not party of the domain. Personally, I would expect you to get arrested if you tried to pull this stunt (ie, using a domain of
the form “popular.domain”.”other.distracting.words.obscureTLD”). In any event, “lol!!” (with the exclamation points) is not an ICANN-valid
TLD (not yet, anyway) so this domain could never have been registered with ICAN, and therefore “healthcare.gov.is.a.failure.lol!!” (entire
phrase) would not be considered an “ICANN-style” BitName.
Users can choose if they want to register a new, self-sovereign name, or if they want to inherit an ICANN-controlled name they already
control. Either way, the user always gets what they prefer.
Terminology:
register (verb) – Create a completely new BitName, controlled by you.
claim (verb) – Ask the SuperKey to seize control of an ICANN-style BitName, and give it to you.
D. CLAIMING A BITNAME
The SuperKey allows the owner of an ICANN domain, to claim the equivalently-spelled BitName-Name.
Here are the steps (all off-blockchain, except step 4):
1. 2. 3. 4. First, we adopt the strategy used by “robots.txt” (https://moz.com/learn/seo/robotstxt): the domain-owner puts a file, “bitname.txt”,
into their site’s root directory. “bitname.txt” contains the owner’s 160-bit
(https://en.bitcoin.it/wiki/Technical_background_of_version_1_Bitcoin_addresses) public address (or a P2SH multisig script address, or
whatever).
Owner contacts SuperKey and pays a review fee (for example, $2). Owner provides the {Name} they think they should own, in
BitNames. No subdomain mischief allowed – the “{Name}” request can only contain one period.
After being paid, the federation looks up “{Name}/bitname.txt” on the internet, and reads the address there. It makes a special
message assigning the BitName to the address specified in “bitname.txt”, and keeps all these unsigned messages in a pile somewhere.
Once per period (for example, 1 month), the SuperKey signs the entire pile of messages and broadcasts them. The protocol obeys the
SuperKey, and (re)assigns the BitNames to the specified owners.
Notes:
Google Corporation can use this process to ensure that “google.com (http://google.com)” is always assigned to themselves. But they
can NOT use this process to obtain, for example, “google.anarchy” or “google.lolfuckgoogle!!”. Those names do not end in a string “on
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 14 of 19
the list” – the predetermined, fixed list of ICANN TLDs at the time BitName was created.
A BitName can be “claimed” more than once, at any time. So, if you buy “www.google.com” (http://www.google.com”) from ICANN,
you will always be able to get “www.google.com” (http://www.google.com”) from BitNames. No matter when you buy it. Therefore,
you should never register an ICANN-style BitName unless you also own that ICANN-name (and plan to own it forever).
The $2 fee deters people from spamming the review process. The federation only earns revenue as long as it does its job, and its job is
very simple and auditable. Any profits it makes can be used to promote the BitName network.
Non-ISBs will never make it past Step 3 – the SuperKey federation will try to look up “google.lol!!!/bitname.txt”, and won’t be able to
find it. So it will give up.
Subdomain mischief is defeated in Step 2. The SuperKey federation will just ignore a request, if it contains two or more periods.
Therefore, “sucks.lol/bitname.txt” (http://sucks.lol/bitname.txt”) (on ICANN) cannot be used to claim the “heathcare.gov.sucks.lol”
BitName.
Beneficial Results:
Existing domain-owners keep all their domains. New domains (registered with ICANN after the launch of BitName sidechain) will still
entitle their owner to the corresponding BitName.
Conversely, anyone can register a new domain that is completely self-sovereign and which can never be affected by the SuperKey or
anyone else.
ICANN cannot subvert this scheme by releasing new TLDs (the SuperKey will only affect TLDs in existence on the date that the
BitName software was released).
Users are unlikely to ever actually need to pay $5 to reclaim their ICANN-style names – because (fearing the SuperKey) no one will
bother squatting those Names in the first place. For example, only the ICANN-owner of “google.com (http://google.com)” would even
try to register the “google.com (http://google.com)” BitName – since, if anyone did try, the real Google Corporation could take it from
them for $5. As a result, you should be able to reclaim your ICANN-style domains, ultra-quickly and ultra-cheaply.
E. COMMENTS ON LAND-GRABBING
In any new namesystem, users may attempt to quickly register many promising-sounding names (“Land-Grabbing”) and then sit on these,
hoping to sell them later for a profit (“squatting”).
In this scheme specifically, I’m not sure what land-grabbers would do:
Grab everything that has no dot? eg “Google”
Grab everything that begins/ends with a dot? eg “.google” or “google.”
Such squatter-strategies assume that laypeople are ready to switch away from “.com”-style domain names. But, to what? The original appeal
of “.com” domains was that they were the only capitalist domains available (unlike .org and .gov, which were non-profit). From there it
became a self-fulfilling prophecy. But here there is too much creativity.
Instead, I think people would get a kick out of making up their own creative new domains. For example, “google.anarchy”,
“plural_OfMongoose”, “___000___000_” are all legal domains on day 1. A period “.” is not required and is just as arbitrary as any other symbol
– so people can make up their own TLDs or make up something new entirely. With punycode (https://www.punycoder.com/), we can even
2
have domains like “點.看” or “♥♦♣♠.realwebsite!” . Such nigh-unpronounceable names would probably be uncompetitive…from our point of
view in the year 2020. But future generations will find a creative use for them, eventually.
So there is almost too much land to grab, in my opinion. And anyway, 99.9% of the total land-value will belong to already-existing ICANN-
style names. Those BitNames belong to their old owners and cannot be ‘grabbed’.
F. GOVERNING THE SUPERKEY
Make it multisig:
One public figure – the face of the website etc
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 15 of 19
Two other keys, with identities secret, who only exist to veto the public figure’s decision, if they think the public figure is under duress.
These measures help discourage duress.
Also, sunset it passively:
Expires if not used for 1 year.
Therefore, by just doing nothing for a year, the SuperKey owner can be freed from his toxic ability to re-assign domain names.
Users can also USAF out all SuperKey messages, thus de facto sunsetting it early.
G. USER EXPERIENCE
Since the property rights are so different, the user-experience must explicitly be different, for ICANN-style and punycode names.
Throw an error message if someone tries to register a domain:
ending in .[known TLD]” (ICANN-style, these can be stolen for $5)
starting with “xn–”.” (punycode, will probably become other characters)
And of course, the web browser is where the certification/connection information is all displayed.
6. Decentralized DarkNet Markets (?!)
This is kind of half-baked but I thought I would include it at the end.
Skip it if you think this is too crazy.
A. READABLE TOR DOMAINS
First of all, obviously, BitNames can help tremendously with TOR. Each user-friendly BitName can map to a scary, bizarre ‘.onion’ address. In
fact, each name can map to many onion-addresses, which is useful because onion-site-operators often maintain many different onion-
addresses (presumably, to prevent/deter/respond-to DDoS attacks).
That is certainly very helpful, but I have a slightly crazier idea in mind than that.
B. CAN ‘ID-LISTS’ MOSTLY REPLACE DNMS?
TOR’s “hidden services” concept is unique, in that it allows the physical location of the physical web server (ie, the box with the hard drive
that has the files on it) to remain hidden.
Obviously, someone’s ISP must know the physical location of every computer – and so TCP/IP/ICMP know it as well. That’s how the internet
works (see here (https://www.youtube.com/watch?v=G05y9UKT69s)/here (https://www.youtube.com/watch?v=AGUrTwIX7b8)). TOR works
by just routing an encrypted message though a big tangle of many computers – somewhere along the way, the TOR hidden service read the
message and authored a reply, before passing it on through the tangle.
So TOR needs a lot of computers to volunteer, to take in, read, and transmit a lot of information that isn’t theirs.
The crazy thing is – that is already what the blockchain is doing! Everyone’s computers download the whole blockchain, even stuff that isn’t
relevant to them.
C. DNMS ARE FOR MAKING INTRODUCTIONS?
Why do users visit Darknet markets? To find reliable vendors.
All of the value-add of the DNM is front-loaded. It is about making introductions, and specifically brokering the first deal. Hence: showing the
photos of products, and product/vendor reviews.
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 16 of 19
But once the buyer and seller have interacted a little, they are likely to trust each other. Henceforth they can just email each other. They
don’t need the DNM.
D. ROBUST INTRODUCTION-INFRASTRUCTURE
DarkNetMarket-sites often close unexpectedly – disrupting commerce. It would be better to have a hierarchy of introductions – with top sites
being vaguer, and lower sites being more specific.
Near the top of the tree, could be sites like “dark.fail” which give the user a “list of active DarkNet sites”. One of those sites
(“commerce.onion”, below) could itself be a “list of DNMs”, pointing further down the tree. Then the “DNMs” sites could be nothing more
than “list(s) of X-merchants” – for example, they might have a “list of reputable Bible-sellers”. Then the user can contact the merchant
directly.
dark.fail
/ \
... commerce.onion
/ \
... SilkRoad.onion
/ / \
... Drugs.SR Literature.SR
/ / \ / \
... ... ... ... Bible-Merchants
| Merchant A
Merchant B Merchant B
Merchant Q Merchant C
... Merchant D
...
A merchant might pay the owner of the “Bible-Merchants” list a “rent”, in exchange for being listed there. In turn, “Bible-Merchants” would
pay rent to “Literature.SR”, in exchange for being listed there. And so on. – Literature would rent from “SilkRoad”; “SilkRoad” would rent
from “commerce.onion”; “commerce.onion” would rent from “dark.fail”. On top of $, landlord could require “tenants” to meet other
requirements (quality control, dispute-resolution, escrow accounts, fraud, etc).
This would be a lot more hassle – but it would be robust to failure. A given Bible-Merchant might be listed in many places at once (see
“Merchant B”, above). In fact, probably many people would have multiple redundant copies of the entire list, making it somewhat pointless
for an attacker to disable any part of the structure. Furthermore, since different countries have different laws (specifically, free speech laws
and contraband/drug legalization laws), it should be easy for as much of the list to be legally compliant as possible.
This would significantly alter DNM-economics (see here (https://www.gwern.net/Complement#fnref9)).
7. Conclusion: What?!
There are a lot of ideas in this post. I suggest that, in the future, people might run a SPV-mode BitNames sidechain on their computer, which
would act as an email client, password manager, nameserver, bare-bones social media feed, and DarkNet browser.
Will any of that happen? I don’t know. But it would help solve many of today’s problems. Bitcoin would actually be doing something (other
than banking). So we probably wouldn’t hear as much of:
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 17 of 19
it inherently has no intrinsic value...it's
anti-social, stupid, immoral ... it's not
having any desirable social purpose.
-Charlie Munger, on Bitcoin
From here (https://www.youtube.com/watch?v=AIYPu4MFLl4) (~17m).
FOOTNOTES
1. 2. By this, I mean that it will support “tweets” (ie, public messages to everyone) as well as private “direct messages”. It does not
necessarily need to have a character limit. It might philosophically resemble the contact-feature of WHOIS.
Aka, “xn–md7a.xn–c1y” and “xn–b6hffe.realwebsite!”, respectively.
ALSO ON TRUTHCOIN
The MAHF And Replay
"Protection"
Sidechains for Privacy --
zSide and Melt/Cast
8 years ago 1 comment
Comments for this thread are now closed
4 years ago 1 comment
Security Budget II, Low
Fees, and Merged
Mining
4 years ago 1 comment
BitAssets - A Digital
Assets Sidechain
7 years ago 2 comments
Map-Territory
Epistemology (Part 1)
6 years ago 1 comment
×
0 Comments 1 Login

Share Best Newest Oldest
The MAHF And Replay
"Protection"
Sidechains for Privacy --
zSide and Melt/Cast
Security Budget II, Low
Fees, and Merged
Mining
This discussion has been closed.
BitAssets - A Digital
Assets Sidechain
Map-Territory
Epistemology (Part 1)
Subscribe Privacy Do Not Sell My Data
OLDER · VIEW ARCHIVE (68) (HTTP://WWW.TRUTHCOIN.INFO/ARCHIVE)
Sidechains for Scaling -- Thunder Network (http://www.truthcoin.info/blog/thunder/)
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 18 of 19
pretext - prē′tĕkst″ (n.) A reason or excuse given
to hide the real reason for something.
--Thunder Genesis Block(?)
NEWER
Security Budget II, Low Fees, and Merged Mining (http://www.truthcoin.info/blog/security-
budget-ii-mm/)
BTC transaction fees are low today. They will probably stay low, forever. By themselves, they will not be
enough to fund hashrate security (as Satoshi intended). Fortunately, merged mining (another Satoshi
invention) will ride to the rescue.
LINKS
 Home (http://www.truthcoin.info)
Bitcoin Hivemind (http://www.bitcoinhivemind.com/)
Drivechain.Info (http://www.drivechain.info)
 Github (https://github.com/psztorc/truthcoin)
 Forum (http://forum.truthcoin.info)
 Twitter (https://twitter.com/truthcoin)
Paul's Reviews (/reviews)
Blog Archive (/archive)
Misc Files (/files)
Paul Sztorc Media Appearances (/rss)
AUTHOR
Paul Sztorc
 Email (mailto:truthcoin@gmail.com)
 Twitter (https://twitter.com/truthcoin)
 Reddit (https://www.reddit.com/user/psztorc)
Disqus (https://disqus.com/by/psztorc/)
©2025 Truthcoin
https://www.truthcoin.info/blog/bitnames/ 6/17/25, 5:00 AM
Page 19 of 19
