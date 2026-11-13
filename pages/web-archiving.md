---
title: "Web archiving guide"
layout: page
permalink: /guides/web-archiving
parent: Topic guides
---

Want to save a copy of research material, your favourite website, a cooking recipe, or your professional site? You might need to do some **web archiving!**

According to the Society of American Archivists, web archiving is "the process of collecting, preserving, and providing enduring access to web content."[^1]

Practically, this means creating a copy of a webpage as it appears at a very specific point in time, with the intention of being able to access that capture of the webpage as-is in the future.

### Why isn't the entire web archived?

Large-scale web archiving is often done by **crawlers.** Crawlers are automated programs that scrape the web for pages related to a specific URL or collection. Crawlers are capable of making distinctions about what pages to preserve, but those decisions are based on human direction and input. Given the sheer size and scope of the World Wide Web today, the labour demand to train crawlers to archive is way too high. Before they can be crawler, many webpages will disappear as domains break, are blocked, and expire, as servers go down, as web hosts and builders give up their projects, and as transitions between managers create massive changes to existing sites.
### What kinds of copies can I make?
The most common two types of archived copies are compressed files, snapshots, and screenshots. **Compressed files** include all of the code, files, documents, images, etc. that make up a page. **Snapshots** are usually similar to compressed files, but may omit some larger files from the archived copy, such as a particularly huge image. Some tools also use "snapshot" to refer to a screenshot, so make sure to check your archived copy! **Screenshots** are static images or PDFs of the page, without any interactive elements.

### Why archive my webpages?
Things are constantly disappearing off of the Internet, and scholarly material is becoming increasingly born-digital, meaning that it was first published on the web or in digital format. Web archiving is the primary way to preserve the things on the web that you find important. If you have sources you use often on the web, resources you consult, memes you enjoy sharing, or even social media posts that you find important to you, your process, or your research, you should save them so that they do not become inaccessible if/when they disappear off of the Internet. Web archiving is also a great deterrent against censorship, since no matter what external forces decide to remove from public view, you’ll still be able to view the content that matters to you using an archived copy.

### Ways to archive
#### 1. Use a web-hosted archiving tool
Web hosted web archiving tools allow you to make an account, then submit a URL to be archived and saved on a company or organization's server. Cornell University has a service with **perma.cc**, a robust and free web archiving tool that lets you make snapshots of your pages. See the Library's [**perma.cc** LibGuide](https://guides.library.cornell.edu/perma) for instructions on getting started! Another accessible hosted tool is the [Internet Archive's Wayback Machine](https://web.archive.org/). You can submit the link to a single webpage to be archived for free, with no account needed. Another great option is [**🌲 Conifer**](https://conifer.rhizome.org/), which lets you scroll through multiple pages on a website to capture everything you need.

#### 2. Use a self-hosted archiving tool
Self-stored and self-hosted web archiving tools allow you to create a compressed file that you can store on your computer, which you can then serve to your computer’s local server or view through a browser-based viewer like WebRecorder’s Replay Webpage. The file stays on your computer and is fundamentally controlled and owned by you, but you can use a variety of methods to view the archived page or site.

[🍨 Scoop](https://github.com/harvard-lil/scoop) and [ArchiveBox](https://archivebox.io/) are two great, command line interface (CLI) options for a self-hosted tool. If you're unfamiliar with the command line, see Research Data and Open Scholarship's open source lessons, or Programming Historian's.

### Which tool is best for me?
So which one should you use? There are many pros and cons to both self-managed and service-managed web archives, so the decision you make can be informed by those positive and negatives. Here are just a few:

#### Self-hosted
- Storage limits dependent on your computer and external harddrives (way beyond 5G)
- Full control over the archived page
- Can experiment with code of archived page
- Relatively stable copy of page DOM
- Accessible on the fly
- Can view on local server or choose own viewer

#### Service-hosted
- Almost no work
- Easily accessible
- Viewer built into the platform
- Links are easily sharable with others
- Can download WARC and WACZ if needed
- PDF or png conversion of snapshot
- Automated provenance summaries

### What if I need to archive an entire website?
The difference between one-page tools and full-site tools is effectively the difference between taking a snapshot and fully crawling a site. One-page web archiving tools will only capture the page for the single URL you give the tool. Full-site web archiving will almost always require a **crawler**. Crawler’s take physical and digital energy, and are often difficult to use if you’re unfamiliar with web archiving. For this reason, archiving of entire websites is usually only done by institutions, memory organizations, and other larger groups and polities.

One of the best options for multi-page saving is [**🌲 Conifer**](https://conifer.rhizome.org/), which lets you navigate through pages on a website to save them. As long as you're able to click through all of the pages on a site, you'll be able to record every page on one site in a series of captures.

### What other tools are out there?
Michael Hucka, a Staff Software Engineer at Google, has compiled a gigantic web archiving software comparison list assessing a broad range of web archiving tools, both open-source and closed-source. 

### I need help getting started! Where do I go?
The Library is happy to help! Start by exploring Michael Fleming, the Library's Web Archiving Technician's, [**perma.cc** LibGuide](https://guides.library.cornell.edu/perma). If you need additional assistance, or want help with a different tool, reach out to the Digital CoLab at digitalcolab@cornell.edu to schedule a consult, or drop by our [weekly open office hours](https://www.library.cornell.edu/about/staff/central-departments/digital-scholarship/colab-programs/co-working/).

[^1]: Society of American Archivists. “SAA Dictionary: Web Archiving.” Dictionary of Archives Terminology. Accessed November 11, 2026. https://perma.cc/U5ZY-NSDF.

