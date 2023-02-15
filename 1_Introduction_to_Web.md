# Lesson 1: Introduction to the Web

In this lesson, we briefly discuss the architecture of the web. This allows you to solidify your understanding of the client/server architecture before we begin scripting. First we delve into better understand the internet and the world wide web, then we move onto networking basics, followed by a very important topic, web server basics. Lastly, we wrap this session up with languages of the web, which includes HTML and CSS.

## Internet and the world wide web

- Internet consists of multiple computers over a network that communicate with each other using a specific set of rules.
- The internet orginated from **_ARPANET_** (a defense program by us government).
    ### Internet of Things (IoT)
    - A subset of internet that includes computers and sensors connected to each other for communication and automatic transaction processing.
    - Autonomous devices connected to each other.
    - includes usage of censors, cameras etc.
    - requies little to no human intervention.

## Networking

> ### Packet-Switched Networks
> - In a packet-switched network, files are broken down into smaller pieces called packets, that are labelled electronically with their origins, sequences and destination addresses.

### **Two types of networks**
- **WAN** and **LAN**
- _`LAN`_ - Local Area Network
    + devices are located close together
    + Ideal for an office setup
    + Restricted by geographical location
- _`WAN`_ - Wide Area Network
    + Connects mutiple LANs
    + Extens beyond the boundaries of an office.
    + Better for enterprise scale network.
    + Extends to larger geographical areas, including globe.

### **Public vs Private**
- `Public Network` - A computer network available to public, less secure than private.
- `Private Network` - More secure than public network, can be quite expensive.

## Virtual Private Network (VPN)
A connection  that uses public networks and their protocols to send data in a way that protects the data much like that of a private network.
- It encrypts your data
- IP tunneling creates a private pathway over public internet.
- Less expensive than private network.
- Hides internet activity from entities such as your _`ISP`_ (Internet Service Provider)

## Web Server Basics
> A web server is a computer that hosts web content or files that make up the structuer of a website.
- Responds to clients by
    + transferring files and scripts to the web client(browser)
    + Generating a response by invoking scripts and querying a database.

### **Two-tier Client/Server Architecture**
- teir-1: `Web Client`(Browser in our PC)
- teir-2: `Web Server`
- Web client sends a `http request` over internet to the web server
- Web server sends back a `http response` over the internet to the web client
- and the content is displayed on the web client
### **Three-tier Client/Server Architecture**
- similar to two tier but the web server communicate with `database servers` which is teir-3.

## Web Languages
> Key technologies of web 
> 1. HyperText
> 2. Styling
> 3. GUI (Graphical User interface)

### **HTML** - Hypertext Markup Language
- Basically the content on the website
- Structured text
- tags provide formatting
- most tags have opening and closing tags <></>

### **CSS** - Cascading Style Sheets
- that gives style to the content of our webpage (like colors, font style, backgroung etc.)
- We can include it inside a html doc but for better development purposes we write css in a seperate file and link it to html doc.

