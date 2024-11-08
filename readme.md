# <center>Foundation</center> ![foundation](https://github.com/user-attachments/assets/2cd6270c-d62d-4ca7-9849-ff324739e626)

The Foundation is a corpus of video, text, music, and various other media for the purpose of replication and distribution by individuals(archivists) for use before, during, and after the collapse of civilization.

The Foundation Archive has three primary goals.
* Provide recommendations for how data should be formatted, stored, structured and retrieved for ease of personal use and consistancy
* Curate a carefully selected manifest of crucial media that can be used as a broad education for current and future generations
* Replicate and distribute this archive in order to decentralize it in the hope that our most critical achievements survive a societal collapse

## Why "Foundation"?
In the Foundation series by Isaac Asimov a group of mathematicians and scientists predict the collapse of a galactic empire. They predict the outcomes of various scenarios through a complex formula and build a foundation of followers on the planet terminus. They commit to protect the most critical information in hopes of greatly reducing the amount of time required to rebuild galactic civilization. The goal of the foundation in the book mimics the goal of this archive with the unfortunate exception that we do not possess psychohistory. The archive itself is a tribute to Asimov for asking an obvious question, namely what should you do if you knew the world was ending.

## Motivation
We live in an unprecedented age of progress and growth by any metric and data supports the view that without drastic and unlikely changes we will be unable to sustain it for much longer in its current state. We see global instability in our political systems and alarming decline in our  ecological systems which suggests we are struggling to handle our most fundamental problem, resource management. Idealistic people have proposed solutions such as space colonies, weather manipulation, global migration, or even underground facilities, but all proposed solutions are highly ambitious and unlikely to mature before collapse occurs. Human growth is well understood to be exponential as are its resource and logistic demands. Sadly our capacity for ingenuity, innovation, and discovery are much less predictable and are not in healthy competition with our ability to create new problems. Civil unrest, ecological destruction, and over population all exhaserbate our resource management issues and threaten to destabilize a system likely less resilient than we currently grasp. 

The nature of how life will change is unclear but the possibility that the world as we know it will change drastically in the next few generations is not remote, and the question of collapse is not theoretical. While we still have time and means each of us can perform a task which may provide incalculable value to future generations. We shall preserve for them information that our society has amassed and takes for granted in hopes that whatever world future humans must inhabit they will have a corpus of high quality information. Many of us have not lived in a world that requires us to fight for resources and the recent global pandemic of 2020 showcased that we are likely not up to the challenge of a real epidemic on par with the black death or the Spanish flu, so our best hope is not to ensure the fate of our major works of art and science to any singular or even small group of institution but entrust it as we always have to individuals in hope that one or more of the many redundant copies will survive.

## Usage
The manifests in this repository are the central source of truth for media that should be archived and replicated. Cloning this repository will provide a framework for archiving a small but carefully selected corpus of critical media which can be reliably secured using a common and affordable backup and recovery methodologies. This repository contains only things which can legally be included in a public distribution and therefore can only include resources in the public domain or similar permissive license. Regardless of their inclusion in this repository, a manifest of items to be collected by archivits is included as well as a storage structure. It also includes notes and guides on how best to go about preservation efforts. The foundation repository designed such that it can be cloned with a revision system like git and the items listed can be procured for upload to a private revision system or durable storage solution. Lastly the repostiroy provides a convenient archival and tagging approach that can be used to explore and enjoy the items in the archive at your leisure with little effort.

## Structure
The structure of this archive will mimic the structure of institutions for higher education including the study of liberal arts and sciences classified as major areas of study. Science, Mathematics, and Engineering will be roughly separate from Art, Music, and Literature. The system will not be perfect and some things like Social Sciences might overlap between the two, and some works of art might have science as their underpinning and vice versa but the goal is to produce a structure that can be searched by hand without the ready assistance of tools, meaning that there should be a limited depth and a wide and flat hierarchy at the top.

## Fidelity
It is unlikely that compression or encryption mechanisms will be easily accessible during a collapse and as such items should be stored in universally accessible formats such as plain text whenever possible, with formats such as Markdown or HTML being acceptable as the core information is still encoded as plain text and can be parsed as such with some minor effort. In the event that works must be preserved or are only available in specialized formatting such as epub, mp3, or jpg they should come with full and cross platform copies of the utilities required to interpret them, ideally with source code and compilers.

It is unclear what mechanisms or mediums of retrieval might survive such as magnetic, optical, flash, or solid state storage and as such we should strive to replicate the entire dataset across as many mediums as possible for each individual acting as archivist. In those cases mechanisms that might be required should accompany the media such as USB adapters, CD/DVD readers, and SATA/NVME to USB adapters should be procured and stored with the dataset as an extra measure of precaution.

## Selection
The items in this archive are carefully selected based on their criticality to both the fundamental elements of our society as well as the demands of a theoretical post-collapse society meaning that some works are excluded because they could post a danger to future civilizations and some works are included because they provide fundamental concepts about the world such as wood working and germ theory. This makes determining things to add from the perspective of science and engineering somewhat straight forward but difficult when it comes to social siences and a delicate process at best for the arts.

I encourage archivists to consider carefully anything they add beyond the itemized list but it is a moral imperative for each to put personal beliefs aside for the purpose of this task and perform their due diligence. Works selected for inclusion are done so based on generations of consensus in the hope that this metric showcases a particularly unique value or insight into our condition and improves our species, not because individuals or particular generations find value in them but because a large group of people across multiple time periods considered them critical and of preservation for our use. It is in their honor and sacrifice that we do the same, regardless of our personal feelings.

## Archivists
* Each person is responsible for their own dataset and their own backup methodology.
* Each person should be mindful of how, where, and why they store this data. Many storage providers will likely not survive and may consider the duplication of material against their usage policy or against a particular nations laws or regulations and therefore each dataset is to be stored locally by each archivist regardless of any replicated sets on external providers.
* Each archivist is expected to be respectful, helpful, and supportive because it is in the interest of our species that this dataset be gathered and replicated by as many people as possible, a task which is tedious and not easily achieved and as such should be encouraged, promoted, and commended. Considering this it should be customary that your particular dataset should store in its root a single text file containing the entirety of whatever message you find best to tell your story, such that if only a few of these survive the successful dataset will award its archivist memorandum much the same way we now know the works of antiquity through the diligent efforts of scribes and scholars who copied the works across generations for their preservation, leaving little more than names and dates to reward them.

## Syntax and Conventions
Uniformity is important for archival as it gives us a system to agree upon for petty decisions such as case and space. The following are the recommended conventions and guidelines for folder structure, naming, and organization. File encoding conventions are chosen based on the most common and therefore most likely to have good documentation, support, and compatibility.

Filename Conventions

* No spaces, all spaces should be replaces with '-'(Hyphen)
* All files should use lower case letters
* No special characters


* All text files should be encoded using UTF-8
* Video should be encoded using H.264 and AAC with MP4 as its container
* Audio should be in AAC or optionally WAV
* Plain text readable files are preferred over encoded filetypes
* Software should include source and static linked portable builds for MacOS, Windows, and Linux. Mobile should include Android and iOS
* Photos should be in JPEG format
* Dates should adhere to ISO 8601:2004 such as YYYYMMDD
 