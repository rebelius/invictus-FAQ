I just dumped a bunch of content from the forum on here, now time to organize




What is ProtoShares?

ProtoShares is a class of crypto-currency that let you capture a position in one or more new DACs before 
they are even implemented. The speculative value of a DACs ProtoShares is a subjective mix of three market 
perception pillars. These pillars are the market’s assessment of:

• The speculative value of a future DAC share.
• The probability that the DAC can and will be successfully fielded.
• Confidence that the ProtoShares map to an equitable share in the implementation.

So owning Protoshares gives you a share in future DACs. for more in depth info, go here https://bitsharestalk.org/index.php?topic=5.0

What is AngelShares? 

AngelShares is a crowd funding operation that works to support the development of DACs. It functions like a mining pool where every day shares are mined and divided among contributors proportional to how much they contributed. Rather than hash-power based proof-of-work like Bitcoin based Digital Currencies, AGS uses money as a reusable PoW making it an efficient resource-light community operation that does not divert hash power used to secure Protoshares.

Like ProtoShares, they represent a way to gain a stake in the new crypto-equity industry. ProtoShares acknowledge a contribution to the launch of the new industry, representing a proof of work done in generating public interest. AngelShares acknowledge an equally important financial contribution to the industry infrastructure.

What is Bitshares

BitShares is the first Decentralized Autonomous Company (DAC) and represents a whole family of such DACs. The companies can vary from unmanned banks and exchanges to online gaming and gambling. It is in development and is intended to be a Decentralized Bank. see here http://invictus-innovations.com/bitshares2

How to get ProtoShares and AngelShares?

To get started Protoshares you need to download the client 

for linux users https://github.com/InvictusInnovations/ProtoShares

or use this script (much easier) Tested on Ubuntu(my personal favourite) 

Code: [Select]
sudo apt-get update && sudo apt-get install git make g++ build-essential libminiupnpc-dev libboost-all-dev libdb++-dev libgmp-dev libssl-dev dos2unix
git clone https://github.com/InvictusInnovations/ProtoShares
cd Protoshares/src
make -f makefile.unix
echo "rpcuser=[youruser]" >> ~/.protoshares/protoshares.conf
echo "rpcpassword=[yourpass]" >> ~/.protoshares/protoshares.conf
./bitcoind -daemon
./bitcoind setgenerate true 3

for windows users http://the-iland.net/static/downloads/ProtoShares-0.4.0.zip will give you the QT version, just run it and you will have your client.

for mac users http://invictus-innovations.com/downloads/

The new clients have hard coded seed nodes and connect to the network almost instantly. The fix was a combined effort between bytemaster, toast Freetrade and myselft to provide users with a more enjoyable hassle free experience.

I would suggest an optimized miner since the difficulty of the network has reached a point where you are unlikely to ever solo-mine a block unless you happen to use the tian-he super computer. 

What is an optimized Miner?

An optimized miner is a standalone miner that has greater performance, meaning it mines faster than the client. 
There are many in existence and you can see them here https://bitsharestalk.org/index.php?board=11.0 most however are locked to a specific pool. 


Why must I withdraw my PTS to a PTS wallet?

There is risk in storing your PTS on an exchange so its best practice not to do this.

In addition you wont get any BitShares (or shares in any other DACs) if you keep your PTS on the exchange. This is because when Invictus launches a DAC it will reward PTS holders with shares in the new DAC by rewarding the addresses which contain the PTS. If your PTS is stored on an exchange, the exchange’s PTS address will receive your BitShares.



PTS wallet management

How do I safely store PTS on a PTS wallet/client?

You can download the client for MAC or Windows or download and compile the code from here www.protoshares.com.

Note: I prefer to use MAC as there are less security issues.

Run the client and allow it to sync with the network.

Before you send any PTS to your wallet, you first need to encrypt the wallet. You can do this by clicking on the ‘settings’ tab and then ‘encrypt wallet’. 

It will ask you to type in a password (encryption key) twice. Use a password of at least 32 characters. It is best to not use any real words or patterns but a random string of letters (in lower case and capitals), numbers and characters such as $@^&*

Important: Do not save your password on your computer or type it into any program. Your password should be written down on good old fashioned paper. You write the password down twice on two different pieces of paper for storage in different locations. DO NOT LOOSE THIS PASSWORD OR YOU WILL LOSE YOUR PTS.



How do I backup my PTS wallet?

You can create a backup of your wallet by clicking on the ‘file’ tab then ‘backup wallet’. 

Just to be 100% sure also backup your wallet by making a copy of your wallet.dat file found in %AppData%/protoshares on Windows and ~/.protoshares on Linux.

The .protoshares folder is a hidden folder. 

To make it visible on mac check out this link: http://www.mikesel.info/show-hidden-files-mac-os-x-10-7-lion/

To make it visible on windows check out this link: http://www.bleepingcomputer.com/tutorials/show-hidden-files-in-windows-7/

Store your backups in multiple off-line, off-computer locations. You can store it on flash drives and cds which can be stored at different locations (such as home and work).

Once you have backed up your wallet. You can delete the wallet.dat file found in the .protoshares folder. This will remove your wallet from your computer making your wallet less vulnerable to hackers. Hackers may be able to get into your hard drive but they will find it allot harder to get into your desk at work.

Note: Store your wallet.dat file and pass-phrase separately. So that if someone gets hold of one they still wont be able to get your PTS without the other.

Importantly: you should refresh this backup of your wallet.dat file at least every 99 transactions.  You need to do this because the wallet starts out with a pool of 100 key pairs that are used for transactions that require new key pairs.  Once you have used up the 100 key pairs your wallet can create new key pairs when syncing with the network. This new wallet with refreshed key pairs should then be saved. IF YOU DO NOT DO THIS YOU CAN LOSE PTS!



How do I restore my PTS wallet from a backup? 

If you need to gain access to your PTS do the following:
•   Install the client 
•   copy your wallet.dat back into the .protoshares folder (replacing the wallet.dat file that will be there)
•   Sync with the network and you should see your transactions and balance.

Note: Only keep your wallet.dat file in your .protoshares folder when you want to have access to your PTS. Otherwise keep it offline for safety.



How will I claim BitShares (BTS) using PTS?

Invictus is developing a user friendly software where you would simply download the BitShares client and then point it at your PTS wallet.dat file to collect your BTS.



After collecting my BTS what do I do with my PTS?

I would advise you keep them! PTS has value because it functions as a social contract. May more DACs may come and honour the social contract, thus you are earning a stake in a new industry of DACs.

Note: Compare this to being able to buy a piece of every future internet based company when the internet just started out.

More answers will be added to this FAQ as information come to light. If you feel something needs to be added, comment and let me know. 

Tips for FAQ writers:
PiNEJGUv4AZVZkLuF6hV4xwbYTRp5etWWJ
PhVq6eidddft6Ut3dcC3RsFWYQskdmK7US









Owning BitShares PTS is a way to acquire future BitShares and speculate on their value today!


What is BitShares PTS?
BitShares PTS is a class of crypto-currency that let you capture a position in one or more cool new DACs before they are ever implemented. The speculative value of PTS is a subjective mix of three market 
perception pillars. These pillars are the market’s assessment of:

• The speculative value of a future DAC share.
• The probability that the DAC can and will be successfully fielded.
• Confidence that the PTS will map to an equitable share in the implementation.

... summed across all DACs that announce there intention to honor PTS holders with shares when launched.

Developers use BitShares PTS to capture early adopter interest in their new idea. 

Investors use PTS to get in on the ground floor of an entire new industry.  Instead of enduring the hassles and costs of mining every new DAC into existence, they focus on acquiring PTS once and for all, and thereby claim a stake in every new DAC that honors BitShares PTS.

Developers and Investors start on a level playing field for obtaining BitShares PTS. They are being slowly mined and easily accessible from public exchanges as one of the top crypto-currencies on the market.

What about that Third Pillar?

The third Public Perception Pillar is confidence that owning a DAC’s PTS will translate into 
actual ownership of an equitable share in the objective DAC. It is up to the DAC developer to convince 
the market that this will happen using whatever social consensus the market will accept. The PTS Social Consensus is simply:

Quote
At our DAC’s pre-published launch time, a DAC’s genesis block shall be initialized
to precisely match the current unspent outputs of the corresponding BitShares PTS blockchain.

For every BitShares PTS proto-share you hold at that launch time, you now have a corresponding 
share in the DAC accessible via the same public address to which you hold a private key. 

That’s it. Simple. Easy to understand. Real hard to renege.

You can read about the latest, more general form here:  http://invictus-innovations.com/social-consensus/

What do you mean “real hard to renege” on your social consensus? 

Who would want to abandon the entire universe of informed early adopters by reneging on their rights as 
founding shareholders? In this business, the network effect of market share is everything. Besides, if 
someone deploys an open-source DAC without honoring the social contract to its PTS holders,
someone else will simply fork the open source code, and honor that contract. Bingo, they’re in business! 
The network effect of informed early adopters will do the rest and the reneging developer’s implementation 
will go into the dustbin of history.

BitShares PTS were designed to be mined into existence according to the curves below.  This has been considerably accelerated in practice by the overwhelming amount of interest from the mining community.



picture: http://the-iland.net/static/images/ProtoSharesMoneySupply.png



How to Get Angel Shares

It couldn’t be easier.  Beginning New Year’s Day 2014,
there will be 10,000 new AGS up for grabs in a new patron competition every day for 200 days. 
5000 of them will be available to PTS holders. 
5000 of them will be available to Bitcoin holders.  
That's ultimately 2,000,000 total shares, just like PTS.

Those who donate bitcoins to this address will proportionally split 5000 AGS:

1ANGELwQwWxMmbdaSWhWLqBEtPTkWb8uDc

Those who donate PTS to this address will proportionally split 5000 AGS:

PaNGELmZgzRQCKeEKM6ifgTqNkC4ceiAWw

Every day the shares are divided among those who donated that day.

Be vigilant! Watch for slow days and anyone can snag some great bargains.

Don't send donations from anywhere but your own wallet!

DAC developers will initialize their genesis blocks to honor the key where your donation came from!

"What happens to all the donations?"

100% of the proceeds go to growing the crypto-equity industry. Zero percent  will be retained as profits Invictus.

Funds will be used to encourage new developers with salaries, grants, contracts, and bounties to build everything from small components to entire new DACs.  They will be used provide a free high-quality Developer's Toolkit giving DAC developers a huge head start.  They will be used for advertisements, conferences, promotions and give-aways to stimulate interest in the new industry and to provide opportunities for everyone to contribute.  They will be used for legal advocacy for the ecosystem in many jurisdictions.  Anything that we believe will grow the value of PTS and all DACs that honor the contributions of PTS and AGS holders.

It is beyond our control to prevent a copycat from forking our open source code in a way that fails to honor our promises.  It is up to the market to reject this, or not.  If you do not like our proposed allocation, do not trust the market to reject copycats, or do not trust us to deliver then please take your money, fund competition, and build your own DACs that fit your preferred allocation strategy.  


Merry Christmas Keyhotee Founders!!
The first 10,000 AGS are set-aside proportionally for Keyhotee Founders.  Invictus Innovations shareholders are not eligible.  Donations to Keyhotee after Dec 24, 2013 at Midnight GMT don't count.


Jan 1st, 2014 shall include all transactions sent to the Angel addresses in 2013.

Invictus Innovations will not send money from the Angel Address back to the Angel Address as this would completely undermine the entire value proposition.
If we pay bounties, sell PTS or BTC to pay salaries for services then we have no way to prevent those individuals from deciding to reinvest back into the fund.  From a block chain perspective it will be very hard to audit this behavior without us freezing the funds.   We will be as transparent as possible about where we spend the funds and this should make it clear that we are not recirculating funds.  In this business trust is everything so we will protect our integrity in this area because without it we are sunk. 

I have created a google docs XLS sheet to track all expenses paid from the Angel fund.  Our goal is to make everything as transparent as possible.

https://docs.google.com/a/invictus-innovations.com/spreadsheet/ccc?key=0AqTwk-e7yzJydFZ3bVVWT0o1OUwzXzdESHFBY0FkUWc&usp=sharing

https://docs.google.com/spreadsheet/ccc?key=0AqTwk-e7yzJydDFnQmlkTVlkbWpubnJBbzR2UG5ucnc&usp=sharing
