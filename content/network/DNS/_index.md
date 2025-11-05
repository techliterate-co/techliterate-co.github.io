+++
date = '2025-09-23T16:55:51-06:00'
title = 'Domain Name System (DNS)'
linkTitle = 'DNS'
weight = 3

[params]
  menuPre = '<i class="fa-solid fa-address-book"></i> '
+++

{{< youtube NiQTs9DbtW4 >}}

---

### Domain Name System (DNS)

The **Domain Name System (DNS)** is often called the “phonebook of the
internet.” Computers don’t actually understand website names like
`example.com`; they need numerical IP addresses to connect. DNS is the system
that translates those human-friendly names into machine-readable IP addresses.
Without DNS, you’d have to remember long strings of numbers for every site you
wanted to visit.

When you type a website into your browser, your device asks a DNS server, “What
is the IP address for this name?” The DNS server then responds with the correct
address, and your browser connects. This all happens in fractions of a second,
usually handled by your internet service provider (ISP) by default. But just
like looking up a number in a phonebook, the accuracy and trustworthiness of
that answer matter a lot.

Because DNS is such a core part of how the internet works, it’s also a **target
for attackers**. Hackers may try to spoof DNS responses, sending you to a fake
website that looks real, or they may hijack DNS settings on your router to
monitor your traffic. If your DNS is unreliable or compromised, even typing the
right address can lead you to the wrong place.

Another important concept is that DNS queries are often sent in the clear,
without encryption. That means whoever runs the network you’re on can see which
websites you’re visiting, even if the content itself is encrypted with HTTPS.
To solve this, modern approaches like **DNS over HTTPS (DoH)** or **DNS over
TLS (DoT)** scramble the queries so outsiders can’t easily snoop on your
activity.

For learners, the key takeaway is this: **DNS is invisible until it breaks, but
it’s critical to everything you do online.** Understanding DNS helps you
appreciate why your internet works (or doesn’t), why changing DNS providers can
improve speed and privacy, and why securing it is an essential part of
cybersecurity hygiene.  

---

### DNS Firewalls

A **DNS firewall** is like a protective filter for your internet lookups.
Instead of blindly resolving every request, the firewall checks the domain name
against a blocklist of known malicious or suspicious sites. If you try to visit
a phishing page, malware download, or command-and-control server, the DNS
firewall intercepts the request and stops it before your computer ever
connects.

The benefit here is **prevention at the very first step**. Traditional
firewalls act on traffic after it’s already moving, but a DNS firewall can
block threats at the name-resolution stage. This means even if you click on a
bad link in an email, the request won’t resolve, protecting you from
accidentally loading a harmful site. It’s a lightweight, high-leverage defense.

Another major advantage is **visibility and control**. Organizations can use
DNS firewalls to enforce policies—blocking gambling sites, adult content, or
distracting services during work hours. For individuals, it’s a way to add a
safety net that protects your devices and family members from common threats
without installing heavy software on every machine. In short, a DNS firewall
gives you both security and peace of mind, quietly working in the background
while you browse.

