---
title: Data Broken Removal - Bandaid on a Bullet Wound
description: A short look into the "justifications" of data broker removal services. It's most likely not for you.
date: 2026-09-18T13:42:35.610Z
github_link: https://jvbond.github.io/
author: Jeff
preview: ""
draft: false
tags:
    - Data Broker
    - Rant
categories:
    - Rants
toc: null
---


Services like DeleteMe and Incogni are, a bit, bullshit. 

Why would someone want to utilize these services? Lets assume a couple reasons:
- Perceived Spam Marketing (Phone, email, etc)
- Physical Privacy
- Online Privacy

Generally speaking, people don't want to be tracked and identified everywhere they go both physically and digitally. People are uncomfortable with having what they consider personal information stored and analyzed by corporations and potentially exposed to networks of unknown other people. The explosion of these data brokerage removal services proves that.

Though I concede similar executive services can be reasonable, and relevant SLIGHTLY to some executive staff to SLIGHTLY minimize data exposure. Generally the cost of these services is similar to the reduction in a cyber insurance policy so the business math makes sense. No reason to not do it.

For regular people? Absolutely not. That is to say, the intention is absolutely justified but the solution is snake oil meant to add another monthly subscription to your bill. People are rightly justified in their fear and concern over the exposure of their data. Data breaches are unfortunately commonplace (See [HaveIBeenPwned](https://haveibeenpwned.com/)), unauthorized data sharing happens (See [Cambridge Analytica](https://www.ftc.gov/news-events/news/press-releases/2019/07/ftc-imposes-5-billion-penalty-sweeping-new-privacy-restrictions-facebook)) but we'll get a little more into that in a moment, and it seems like scammers know more about you than you know about yourself.

First bit of history, Cambridge Analytica. This was a scandal that rocked Facebook and the general public in 2018. It centered around Facebook actively trying to "[undermine users’ privacy preferences](https://www.ftc.gov/news-events/news/press-releases/2019/07/ftc-imposes-5-billion-penalty-sweeping-new-privacy-restrictions-facebook)" which led to Cambridge Analytica having MUCH more data than it was supposed to. It is also important to note that this mattered mostly because it was a violation of a separate 2012 FTC order requiring user consent to share data after Facebook "[deceived consumers by telling them they could keep their information on Facebook private, and then repeatedly allowing it to be shared and made public](https://www.ftc.gov/news-events/news/press-releases/2012/08/ftc-approves-final-settlement-facebook)" Both of these suits were settled with Facebook. 


## Legal Framework (In the U.S.)  

The laws, where they even exist, are too late to the party and do not control this industry enough to make a meaningful difference. Lets review the relevant statues.

The US legal framework:
- Federal
	- Protecting Americans’ Data from Foreign Adversaries Act of 2024 (PADFAA)
- State
	- California - Delete Act and Delete Request and Opt-Out Platform (DROP)
	- New Jersey - Bill No. 5328
	- Connecticut - Amended Connecticut Data Privacy Act
	- Texas - Business and Commerce Code §509
	- Oregon - HB 2052
	- Vermont - Amended Bill No. 138

The PADFAA prohibits data brokers from selling, releasing, disclosing, or providing access to personally identifiable sensitive data about Americans to foreign adversaries. Which is a hilariously inadequate legal requirement to serve any true purpose.
The state laws, with the exception of California, effectively only require data broker companies to register with the state if they collect information on people which they do not have a "direct relationship". Eventually, several of these will require some kind of deletion request requirement, but as of this time only California has a requirement and system for this. California requires processing of these requests every 45 days. 
While these state laws are the absolute and very least that can be done they have come WAY too late and cover way too little. Additionally, they cover a limited number of entities and ignore the ease at which new companies can be stood up and torn down to collect information.

While those protections exist, there are also laws that effectively provide information to data brokers. Voter registration information is legally required to be publicly available in 21 states. 15 other states only have restrictions on the information's "usage". The information provided varies slightly but generally it will include name, address, date of birth, and often phone number. Most counties also make their property tax records public and accessible online. 


## Corporate Policy  

The important takeaway from Cambridge Analytica and the existing legal framework, is not that a company has a responsibility to keep data private, but only that it must tell you what it will do with your data. Where this begins to leave the realm of understanding and generally understood common sense is in HOW it tells you. These "disclosures" are hidden in the complex legalize language of privacy policies, hundreds of pages long, often hidden behind links. Not only are they hidden and complex, but they usually reserve the right to change them at any time.

Lets take a quick look at Walmart. [Walmart's privacy policy](https://web.archive.org/web/20260908174839/https://corporate.walmart.com/privacy-security/walmart-privacy-notice) (as of Aug. 2026) states that they collect the following:
> - **Basic Personal Identifiers**, such as name, telephone number, email address, government-issued identifiers (e.g., national identification numbers, driver’s license numbers), signatures, and physical, shipping, and billing address.
> - **Device and Online Identifiers**, such as account login information, MAC address, IP address, cookie IDs, mobile ad IDs, social media information, and VIZIO OS device identifiers.
> - **Internet and Other Network Activity Information**, such as information about your browsing or search activity as well as your interactions with our websites, mobile applications, emails, or advertisements (for example keystroke patterns which help us determine if it is you or a bot who is interacting with us).
>     - If you opt in to the collection of Viewing Data, Activity Data, Mobile App Data, and Mobile Streaming Data (“VIZIO OS Data”) through your VIZIO OS products or services, and agree to the [Consent to Combine VIZIO OS Data with Your Walmart Account Data](https://web.archive.org/web/20260908174839/https://www.vizio.com/en/terms/privacy-policy/combine-VIZIO-OS-data-with-your-walmart-account-data), Walmart will also receive that information.
> - **Commercial Information**, such as purchase and transaction history information (products or services you have purchased, rented, or returned), details about products associated with services you receive from or through us (e.g., car make, model, year, odometer reading, and Vehicle Identification Number for auto related services), product reviews, travel and vacation information, and sweepstakes and contest entries.
> - **Communications**, such as the content of emails, text messages, interactions with our bots (AI assistant chatbots), or other communications, call logs, and calendar information, where Walmart is a party to the exchange.
> - **Demographic Information**, such as age, gender, citizenship, ethnicity, date of birth, family or marital status, household income, education, professional and employment information, family health, number of children, number of cars owned, and software or virtual assets owned.
> - **Financial Information**, such as credit or debit card numbers, and financial account numbers.
> - **Biometric Information**, such as voice prints, imagery of the iris or retina, face geometry, and palm prints or fingerprints.
> - **Geolocation**, such as data about the location of your device, which may be imprecise (i.e., inferred from your device’s IP address). If you provide your consent, this data may be precise. For more information about precise geolocation, see the _How Do We Collect Personal Information? > Collected Through Automated Means_ section below.
> - **Sensory Information**, such as audio, visual information, and other sensory information such as photographs (e.g., for virtual try-on services) and audio and video recordings.
> - **Background Information**, such as background checks and criminal convictions.
> - **Inferences**, such as individual preferences and characteristics. This may include inferences drawn from and related to shopping patterns and behaviors, intelligence, and aptitudes.

Good lord that is a lot of data collection.  And to think, that doesn't include their "Automated Means" data collection OR what they collect through their VIZIO brand. The "Automated Means" section is not parsed out into a nice bullet list for easy consumption. I can only theorize as to why this would be, but my assumption is that it is because the net cast for collection is too wide to make a simple list that would not obviously make a privacy policy pointless. So, lets make a couple bullets from the provided info:
> - We obtain **personal information** about you, in our stores or online (including activity on third party sites)
> - Also, we collect **precise geolocation information**, through bluetooth and GPS, to recognize the location of your mobile device in our stores
> - We operate cameras and automated technologies in-store and on Walmart property outside of our store. These cameras and automated technologies may capture **images of you**.
> - **Automated License Plate Readers (ALPR)**, Personal information is collected from ALPRs. (Links to ANOTHER privacy policy)

ALL of this information is compiled on you, stored, and then released or sold to the companies listed by Walmart in their privacy policy... If only it were so easy though. This section begins with a blanket statement, that frankly, reads as if this section is pointless and they can do what they want with all your data:
> All of the categories of personal information that we collect have been disclosed to other companies, including those within our corporate family, for a business purpose.

So we've got an idea of WHAT data a single company collects on you as well as what it has the "right" to share and with WHO. Next we'll take a very quick look at where this data goes. 


## Data Sharing Landscape  

There are obvious and not so obvious reasons for companies to monitor and store data on you, a few of those reasons aren't even nefarious. This data however, is another product for a company to sell and sell it they will.  
This leads us into what, I'm going to call, the data sharing space. You will often see this identified as ad-tech (advertising), mar-tech (marketing), customer intelligence, or any number of other names. For our purposes, in this "data sharing" space the output and purpose doesn't matter but your information does.   
In this space companies have direct business relationships (which means legal protection to sell your information) with companies for business purposes. Walmart even has their own data marketplace, [Walmart Connect](https://www.walmartconnect.com/partners/partner-directory), of 3rd party companies who get Walmart data and can assist other companies with making that data actionable. Currently, they list 310 companies as partners.  
Generally speaking, this data sharing space exists for companies to identify people or persons to be specifically targeted. Again, their stated reasons don't matter because the end result is often the same; Enough information to specifically identify and manipulate. A data purchasing platform [Datarade](https://datarade.ai/) currently lists "data products" from over 2700 sources and over 240 use cases. These use cases include credit risk scoring, behavioral targeting, telemarketing, and most nefariously of all, "identity resolution". Identity resolution (and similar names) effectively identifies individuals from large groups of information.  
Companies will often tout that they "anonymize" data before selling it. I'm not going to get into the math here but what is often touted as "anonymous" data is almost never actually anonymous. Identification of an individual is trivial with enough information and these platforms provide more than enough.  

A general picture of this landscape can be found in crackedlabs "[Corporate Surveilance](https://crackedlabs.org/en/corporate-surveillance/#7)" post. 

![Digital Tracking and Profiling Landscape](/images/tracking-landscape.jpg)

This is just the perfectly legal side of the industry. There are innumerable number of ways to obtain data in legally dubious or illegal ways. Systems like Real Time Bidding (RTB) rapidly disseminate information on users in order to run an auction style sale on online advertisements. This system does not require much in the way of provenance for placing advertisements but provides data to all potential bidders.  [Examples of this information](https://brave.com/static-assets/files/3-bid-request-examples.pdf) has been published by Brave.  
In the illegal side are the breaches and exposures. The same legal marketplace that exists in plain view also exists as an underground illegal marketplace. The main difference here is that these data sets often come complete with complete data such as credit card numbers and/or social security numbers. Companies collect and store all your information but rarely protect it well enough. This information is then stolen and sold repeatedly.  
But even beyond all that are the records that are just available to the public. Your phone number is listed publicly. Property taxes are public records. Your voter registration information is public record. Occasionally there is a small fee but more often than not it is all just available online. The companies or nefarious actors who use this information against you will not loose access to it if you sign up for a "data removal" service.  


## What Can You Do?  

I wish I could offer better and more comprehensive advice. I wish this system wasn't built like many others where the problems are systemic but the proposed solutions are individual. The **best** advice I can give is to become active in politics. Get out there. Support laws and lawmakers who will address this. Don't stop yelling. 
In the mean time, the standard general advice would apply. There are certainly some things you can do to go above and beyond this if you require additional protection but, in general, this is the generally free baseline starting point;
- Disposable emails - Use a separate email or fill out forms using the '+' format to add info. e.g. myemail+purpose@email.com. Everything after the '+' sign is ignored so you can add whatever you want and have an idea of where your email was sold from. If you have Apple, use their [Hide My Email](https://support.apple.com/guide/icloud/what-you-can-do-with-icloud-and-hide-my-email-mme38e1602db/icloud) service.
- Ad Blockers - Utilize services like [AdGuard](https://adguard.com/en/welcome.html) and/or browser extensions like [ublock](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh) 
- Lock your credit - Follow [these instructions](https://www.usa.gov/credit-freeze) to lock your credit with all 3 agencies. This will prevent new credit lines from being opened.
- Implement some personal and family protection processes.
	- Have a code word or better yet, a series of codewords. For example, a code word to verify your family on the phone for general instructions. This system can be expanded to cover friends, family, and any situations you need for your specific circumstances.
	- Do not just follow directions if they are given to you. Verify information on your own first. If there is something going on with your bank, navigate to your bank's website how you normally would and check first. Do NOT blindly follow instructions given to you. There is almost nothing you will ever legitimately have to deal with immediately without thinking.


## Conclusion  

What we've reviewed here is just a small portion of the *legal* data sharing landscape in the U.S. One of selling points of these data removal companies is monitoring the "dark web". This type of language invokes quite a bit of fear of the unknown from regular folks but the reality is both more sinister and more banal than you would expect. Getting into the details wouldn't serve to add to anything here so my advice would be to just assume your data is out there and your standard protections are the best way to manage this.

The data collection and abuse landscape in the U.S. is bleak. Services that purport to remove your information from data brokers may try, but their marketing convinces you of something that isn't quite the reality. Your information is out there. It is being shared. It is being harvested and abused. Unfortunately, at this point in time, the responsibility to protect yourself from the consequences of this fall entirely on you and while data deletion services may stem the bleeding, it will not stop.


  


**Additional Resources**:  

[EFF's Behind the One Way Mirror](https://www.eff.org/files/2019/12/11/behind_the_one-way_mirror-a_deep_dive_into_the_technology_of_corporate_surveillance_0.pdf)  
[Runbox - The Hidden World of Privacy Policies](https://runbox.com/blog/2024/12/the-hidden-world-of-privacy-policies/)  
[UPENN - American's Can't Consent](https://www.asc.upenn.edu/sites/default/files/2023-02/Americans_Can%27t_Consent.pdf)  
