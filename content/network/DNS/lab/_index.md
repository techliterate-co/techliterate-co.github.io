+++
date = '2025-09-25T14:24:44-06:00'
title = 'Lab'

[params]
  menuPre = '<i class="fa-solid fa-flask"></i> '
+++

## Lab: Configuring Quad9 DNS

**Goal:** Replace your device’s default DNS with
[Quad9](https://www.quad9.net), a free security-focused DNS service that blocks
known malicious domains.

### Step 1: Record Your Current DNS
1. On **Windows**:  
   - Open Command Prompt → type `ipconfig /all` → look for “DNS Servers.”  
2. On **macOS**:  
   - Go to System Settings → Network → Advanced → DNS tab.  

Write these down so you can revert if needed.

---

### Step 2: Change DNS Settings
#### Windows 10/11
1. Open *Settings* → *Network & Internet*.  
2. Click *Change adapter options*.  
3. Right-click your active network → *Properties*.  
4. Select **Internet Protocol Version 4 (TCP/IPv4)** → *Properties*.  
5. Choose **Use the following DNS server addresses**.  
   - Preferred DNS: `9.9.9.9`  
   - Alternate DNS: `149.112.112.112`  
6. Repeat for **IPv6** if enabled:  
   - Preferred DNS: `2620:fe::fe`  
   - Alternate DNS: `2620:fe::9`

#### macOS
1. Open *System Settings* → *Network*.  
2. Select your active connection → *Details*.  
3. Go to the *DNS* tab → click `+` → add:  
   - `9.9.9.9` and `149.112.112.112`  
4. Apply changes.

---

### Step 3: Test Your Setup
1. Visit: [https://www.dnsleaktest.com](https://www.dnsleaktest.com)  
2. Run the **Standard Test**.  
3. Confirm your DNS servers show as **Quad9**.  

---

## Bonus Lab: Configure DoH (DNS over HTTPS) with Quad9 in Your Browser

**Goal:** Encrypt DNS traffic so it can’t be snooped by your ISP or a public
Wi-Fi provider.

### Firefox
1. Open *Settings* → *General*.  
2. Scroll to *Network Settings* → click *Settings…*.  
3. Check **Enable DNS over HTTPS**.  
4. In *Use Provider*, choose **Custom** → enter:  
   - `https://dns.quad9.net/dns-query`  
5. Click *OK*.

### Google Chrome / Microsoft Edge
1. Open *Settings* → *Privacy & Security*.  
2. Look for *Use secure DNS*.  
3. Select **Custom** → enter:  
   - `https://dns.quad9.net/dns-query`  

### Test DoH
Visit [https://browserleaks.com/dns](https://browserleaks.com/dns).
You should see that **DNS over HTTPS is enabled** and Quad9 is the resolver.

---

✅ **What You Learned**:  
- How to change system-wide DNS to a secure provider.  
- How to encrypt DNS lookups inside your browser.  
- How to confirm the changes with online tools.  

💡 **Why This Matters**: Quad9 not only resolves domains but also blocks known
malicious ones, reducing your risk of phishing and malware. Adding DoH means
your queries are encrypted end-to-end, even on untrusted networks.

