# Season of KDE 2023 Proposal

## Title
Accessibility: Work on the new EPUB reader application - Arianna

## Contact Info
Name - `Arpit Jain`  
Matrix - `@osbins:matrix.org`  
Telegram - `arpitxj`  
Email - `arpitjain[dot]2001[at]gmail[dot]com`  
Timezone - `GMT +5:30`

## Abstract
Arianna is an EPUB reader application started by Niccolò Venerandi and Carl Schwan in December 2022. It is built using QtWebEngine and epub.js. The aim is to create a fully functional EPUB reader with features such as 
* Support different formats such as EPUB, PDF, TXT
* Highlighting text
* Creating a library
* Fast loading times
* Modern UI experience  
etc.

## Motivation
I was a KDE Plasma user for a long time and I have always liked the KDE philosophy "Simple by default, powerful when needed".  

There is a lot of appreciation for KDE applications like Kdenlive and Krita by people around me who are familiar with the KDE ecosystem, and being able to contribute to it by working on an EPUB reader for KDE is an exciting prospect for me.  

I would enjoy contributing to KDE's ecosystem and help us get closer to our long-term accessibility goal "KDE For All".  
Being a part of the communication channels and having solved a few issues for the KDE websites (`kde-org`, `plasma-bigscreen-org` and the `aether-theme`) already with Carl Schwan and Phu Ngyuen, I like how positive and helpful people in this organization are. It would be a great learning opportunity for me as I contribute to KDE.


## SoK'23 Objectives
Since this project is in it's early stages right now, we can focus on implementing core functionality. For SoK'23, I would like to implement the features -  

| S. No. | Features |
| ------ | -------- |
| 1 | Make the EPUB reader application `inherit Plasma system theme` |
| 2 | `Add reader settings`, allowing users to change font size, reader layout, switching between light and dark theme, line width, line spacing etc. |
| 3| `Add a table of contents` for the EPUBs |

## Additional Information & Details
<table>
<tr> <td> Inherit Plasma theme </td> <td> This can be achieved by using JavaScript as QT applications can pick Plasma theme colors by default </td> </tr>

<tr> <td> Add reader settings </td> <td> Since these options are already configurable using the backend, we create a page to display settings to configure these through UI using QML and JS </td> </tr>

<tr> <td> Add table of contents </td> <td> This can be implemented using the QAbstractListModel class since our use case contains one dimensional list </td> </tr>
</table>

Apart from these milestones, I will fix/maintain code whenever required.  

## 12 Week Timeline
Week 1 - Inherit Plasma theme  
Week 2 - Inherit Plasma theme  
Week 3 - Add reader settings  
Week 4 - Add reader settings   
Week 5 - Add reader settings  
Week 6 - Add table of contents  
Week 7 - Add table of contents  
Week 8 - Add table of contents  
Week 9 - Add table of contents  
Week 10 - Revisit a previous feature or work on a new feature after discussing with mentor  
Week 11 - Revisit a previous feature or work on a new feature after discussing with mentor  
Week 12 - Revisit a previous feature or work on a new feature after discussing with mentor  

## Other Commitments
I am an undergraduate student and have my university classes and project work during my semester. I will be able to give 15-25 hours per week to SoK.
* I have my first cycle of exams from 20 - 25 February 2023
* Second cycle of exams from 5 - 10 April 2023

I will not be able to work in full capacity during that time (during 5th and 11th week).

## My KDE contributions
I have contributed to KDE websites. These are the pull requests I worked on that have been merged
1. Enhanced kde.org look and images consistency - [Added shadows to application screenshots on homepage](https://invent.kde.org/websites/kde-org/-/merge_requests/168)

2. Fix Krita-art attributions on kde.org/for/creators from kde-hugo theme repository - [Removed flexbox from .swiper-slide scss class](https://invent.kde.org/websites/aether-sass/-/merge_requests/76)  

3. Update kde-hugo version for kde.org sites - [bump kde-hugo version (fix swiper-slide)
](https://invent.kde.org/websites/kde-org/-/merge_requests/170)

4. Removed redundant import in Arianna - [removed org.kde.elisa import](https://invent.kde.org/graphics/arianna/-/merge_requests/5)

## About You
I am Arpit Jain, a 3rd year university student pursuing B. Tech in Computer Science and Engineering from Jaypee Institute of Information Technology, Noida, UP, India. I enjoy exploring different technologies.  
I head the Open Source Developers Community (OSDC) of my university where we talk about and promote the spirit of open source amongst university students. We have meet-ups and discuss new technologies, and organize events such as [CodeJam](https://github.com/osdc/codejam-v3) and [OSDHack](https://osdhackjiit.com/).  
I have also mentored ~10 students in contributing to my web chat application for [KWoC](https://kwoc.kossiitkgp.org/)'21, which is a beginner level open source programme for university students all across India.


