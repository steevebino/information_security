## x) Read and summarize

## 7 Things You Should Know About Tor

**1.Tor Still Works**

Despite revelations from the NSA leaks, Tor remains one of the most effective tools for online anonymity. 
While intelligence agencies have occasionally compromised specific users, they typically do so by exploiting
browser bugs (like in Firefox) or user misconfiguration rather than breaking Tor’s underlying cryptography.

**2.Tor is Not Only Used by Criminals**

While often associated with the "dark web," Tor is a vital tool for a wide range of people, including:

**Activists and Whistleblowers**: To bypass censorship and report safely.

**Journalists**: To communicate securely with sources.

**Military and Law Enforcement**: For secure communications and undercover operations.

**Average Families**: To protect their children’s privacy and prevent tracking.

**3.Tor Does Not Have a Military Backdoor**

Although the U.S. Navy initially funded Tor's development, the software is open-source. This means its 
code is publicly available for anyone to audit. Many independent security experts and cryptographers 
have reviewed it and confirmed there are no "backdoors" for the government.

**4.Running a Tor Relay is Legal (in the U.S.)**

As of the article's publication, no one in the U.S. has been prosecuted for simply running a Tor relay. 
While running an "exit relay" (the final hop before the internet) might lead to inquiries from law enforcement 
due to traffic originating from your IP, the act of helping the network itself is not illegal under U.S. law.

**5.Tor is Easy to Use**

You don't need to be a computer expert to use Tor. The Tor Browser Bundle is a pre-configured version of Firefox that works right out of the box. For even higher security, users can use Tails, a live operating system that routes all internet traffic through Tor automatically.

**6.Tor is Faster Than You Think**

While Tor is naturally slower than a direct connection—because your data is bounced through three different volunteer servers around the world—the network's speed has improved significantly over the years. Speed increases as more people volunteer to run relays.

**7.Tor is Not Foolproof**

Tor protects your identity, but it cannot protect you from your own actions. You can still be de-anonymized if you:

-Log into personal accounts (like Facebook or Gmail) while using Tor.

-Install browser plugins that leak your real IP address.

-Are targeted by a "traffic correlation attack," where an adversary monitors both your home connection and the website you are visiting simultaneously.

## The Tor Browser

The Chapter focuses on de-mystifying the Tor browser, explaining its internal mechanics, and showing investigators that even "anonymous" tools leave trails when users make mistakes.

Key Topics:- 

**History and Purpose of Tor**: The chapter discusses the origins of The Onion Router, which was originally developed by the U.S. Naval Research Laboratory to protect government communications. It explains how it evolved into a public tool used by everyone from journalists and activists to cybercriminals.

**How Tor Works (Onion Routing)**: It provides a technical but accessible overview of the "onion" layer mechanism. This includes how data is encrypted in multiple layers and passed through a series of volunteer nodes (Entry/Guard, Middle, and Exit nodes) so that no single node knows both the source and the destination of the traffic.

**The Anonymity vs. Security Gap**: The authors highlight that while Tor provides high levels of anonymity (hiding who you are), it does not necessarily guarantee security (protecting the data from being seen at the exit node or protecting against user error).

**Investigative Techniques & Tracking**: A significant portion of the chapter is dedicated to how forensic investigators and law enforcement can track users on Tor. It emphasizes that investigators often don't "break" Tor itself; instead, they capitalize on:

-User Error: Sloppy security habits (like logging into personal accounts while using Tor).

-Exit Node Monitoring: The vulnerability of data as it leaves the Tor network.

-Browser Artifacts: Traces left on the local machine (the "forensic footprint") that prove the Tor browser was used and what activities were performed.

**Case studies**

The chapter often uses real-world examples, such as the 2013 Harvard bomb threat incident, to illustrate how a suspect using Tor can still be identified through a combination of network analysis and traditional "gumshoe" detective work.

## a) installation and access of TOR network.

<img width="1753" height="843" alt="Screenshot 2026-03-13 010224" src="https://github.com/user-attachments/assets/aa2956ae-d1d7-45c3-98d7-15bd7e283944" />

I accessed one onion address, I tried to to access duckduckgo, I couldn't access it

<img width="1762" height="997" alt="Screenshot 2026-03-13 012127" src="https://github.com/user-attachments/assets/2fe3e357-eb46-4c2e-82d2-e482f9720a15" />

## Browse TOR network

-Search engine - Ahmia

<img width="1776" height="1001" alt="Screenshot 2026-03-13 012659" src="https://github.com/user-attachments/assets/30cf963f-d3af-40c4-a018-84672810b524" />
Ahmia features a minimalist, clean white interface that mimics a standard search engine. i searched formula 1 and gave me some kind of formula forum, it didn't search those links.

-Marketplace - TorZon Market

<img width="1779" height="983" alt="Screenshot 2026-03-13 014150" src="https://github.com/user-attachments/assets/db604543-1576-48e0-b187-a4f7afa78d19" />

I found this address from a website , using the ahmia 

- forum
  <img width="1776" height="1015" alt="image" src="https://github.com/user-attachments/assets/720865fb-77ed-4799-abfc-68bd04399bf2" />
As of 2026, this is the primary hub for leaked databases. If a major company gets hacked, the data usually ends up here first. Note: This site is a high-profile target for law enforcement, so use a secondary identity. I tried other forums first, but couldn't access that for some reason, and I didn't know how to fix. this was only one atleast loading.
  
-  a well known site
  <img width="1787" height="1006" alt="Screenshot 2026-03-13 014853" src="https://github.com/user-attachments/assets/3c074fb3-1846-4a0f-a25a-612aab9bd7fd" />

  it works.....

