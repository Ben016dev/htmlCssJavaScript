**Before you start:** rename this file to `html12c_Protocols_lastname.md`, using your own last name. Watch videos 7–11 and use **Part 3** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**

---

# Task 12c — Internet Protocols

Type your answers on the blank line under each **Answer:**, or fill in the tables. Explain in your own words where a question asks why.

## 1. Which protocol?

**a.** For each situation, write the protocol that does the job: **HTTP, HTTPS, FTP, SFTP, DNS, TCP, or IP**.

| Situation | Protocol |
|---|---|
| You type `example.com` and your computer needs its IP address | DNS |
| You upload your website's files to a web host | FTP |
| You log in to your bank's website | HTTPS |
| A server sends a plain web page to your browser | HTTP |
| Packet 7 of a file never arrived, so it gets sent again | TCP |
| Each packet needs an address so it reaches the right computer | IP |
| You upload files to a server and want the transfer encrypted | SFTP |

**b.** In your own words, what is a protocol? Give an example from everyday life of two people following the same "rules" so they understand each other.

**Answer:**
A way for computers to communicate to one another, each protocol has its own rules. A rule for humans would be like if a specific gesture meant to speak quieter so others dont hear.

## 2. IP addresses and DNS

**c.** Which of these are valid IPv4 addresses? Write **Valid** or **Not valid**, and give the reason for any that are not.

| Address | Valid? | Reason |
|---|---|---|
| `192.168.0.1` | valid | breaks neither rule |
| `10.0.300.5` | not | 300 > 255 |
| `172.16.4` | not | 3 numbers only |
| `8.8.8.8` | valid | breaks neither rule |

**d.** DNS is called the internet's "phone book." Explain why that comparison makes sense.

**Answer:**
Because each server (each computer) has a unique ip adress, the same how each person/house would have a unique phone number

## 3. Packets

**e.** A photo is sent across the internet. It is split into 20 packets, and they take different paths. Packet 12 arrives last and packet 5 never arrives at all. Explain what happens, and which protocol handles it.

**Answer:**
IP checks to make sure each packet is sending to the oroper location.
TCP checks to make sure each packet arrives to there destinations, if they dont it will send any that dont again.

## 4. HTTP and HTTPS

**f.** Write the status code for each situation.

| Situation | Status code |
|---|---|
| The page loaded fine | 200 |
| You typed a page name that does not exist | 404 |
| Something broke on the server | 500 |

**g.** A website has a login form but uses `http://` instead of `https://`. What is the risk? What would the browser show?

**Answer:**
Https is safer because it encrypts the code for the page, not using it risks anyone who intercepts the page being able to read it.

**h.** What do SSL and TLS have to do with HTTPS? Which one is newer?

**Answer:**
They are certificates proving a website to be legitimate, shown by the lock beside the url. Tls is newer

## 5. FTP

**i.** What is FTP used for in web design? Why is SFTP a better choice than plain FTP?

**Answer:**
File Transfer protocol, it moves files from the user's device to the server, including html, css, images. SFTP is secure because its enccrypted, its safer to use

## 6. The parts of a URL

**j.** Break each URL into its parts.

`https://www.medinapets.com/dogs/grooming.html`

| Part | Answer |
|---|---|
| Protocol | https:// |
| Subdomain | www |
| Domain name | medinapets |
| Top-level domain (TLD) | .com |
| Path | /dogs/ |
| File name | grooming.html |

`http://library.edu/books/index.html`

| Part | Answer |
|---|---|
| Protocol | https:// |
| Subdomain | www |
| Domain name | library |
| Top-level domain (TLD) | .edu |
| Path | books |
| File name | index.html |

**k.** Is the second URL secure? How can you tell?

**Answer:**
No, http instead of https

## 7. Putting it together

**l.** These steps happen when you type a URL and press Enter, but they are out of order. Number them 1–5.

| Order | Step |
|---|---|
| 5 | The browser puts the packets back together and draws the page |
| 1 | DNS finds the server's IP address |
| 2 | The browser sends an HTTPS request for the page |
| 3 | TCP/IP opens a connection to the server |
| 4 | The server sends back the HTML, CSS, and images in packets |

**m.** FTP is not one of those steps. When does FTP get used instead?

**Answer:**
When uploading a site

## Closing 12c — Vocabulary

| Term | Your definition |
|---|---|
| Protocol | rules for communication between servers and devices |
| IP address | The unqiue string that correlates to a server/device for communication between them |
| DNS | The sustem that turns a domain name into an ip adress and the other way around |
| Packet | A chunk of data broken up from a longer piece, reassembled once sent to the device that requested the larger piece |
| HTTPS | The protocol that loads a website |
| URL | The link for a site that combines the different parts needed to specify that site being, Protocol, Subdomain, Domain name, Top-level domain, Path, and File name in that order.