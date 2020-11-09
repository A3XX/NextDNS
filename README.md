## What is DNS? 
The Domain Name System (DNS) is like the yellow pages of the Internet. Computers on a network need IPs addresses of the web servers. 
 
 
## Do you know what DNS service YOU are using?

The answer to the above is usually no.


## What’s the risk?
Ever since DNS was created in 1987, it has been largely unencrypted. Everyone between your device and the resolver is able to snoop on or even modify your DNS queries and responses. This includes anyone in your local Wi-Fi network, your Internet Service Provider (ISP), and in-transit providers (or your government). This may affect your privacy by revealing the domain you are visiting.

Imagine, you sit down in a cafe, and open your laptop. I am sitting in the corner and I have decided I am going to learn about you. I watch your unencrypted DNS requests go to cat-memes.com and every few minutes you check out webmd.com. I can easily tell maybe that you’re sick and have a cat. A lot can be learned by watching someone’s internet usage and privacy becomes an issue from other users or your ISP (or government).


## NextDNS = Pihole + DNS over TLS 

NextDNS  take a different approach to DNS. They not only encrypt your requests, but they also block ads, trackers and malicious websites on all your devices. 

## Cost 
300,000 queries/month1
Unlimited devices
Unlimited configurations
Access to all features
$0/month

## Sign up 
Create free account by visiting [https://nextdns.io](https://nextdns.io )

![ND1](https://github.com/A3XX/NextDNS/raw/main/img/1.PNG)

## Setup NextDNS on iPhone
1. Open https://apple.nextdns.io on your iPhone. 
2. copy ID from your account and enter the ID e.g. 75ca5f
3. Enter device name e.g. John's iPhone, Sara's iPhone
4. Open the Settings app.
4. Tap Profile Downloaded.
5. Tap Install in the upper-right corner, then follow the onscreen instructions.

## Setup NextDNS on Andriod (Android 9 or higher)
1. Go to Settings → Network & internet → Advanced → Private DNS.
2. Select the Private DNS provider hostname option.
3. Copy and enter DNS-over-TLS address from your account e.g. 75ca5f.dns.nextdns.io and hit Save.

