# Foundation Archive ![foundation](https://github.com/user-attachments/assets/2cd6270c-d62d-4ca7-9849-ff324739e626)
The Foundation Archive (i.e. Foundation) is a corpus of video, text, music, and other media to be maintained and replicated by individuals(archivists) for use before, during, and after the collapse of civilization as we know it. 


The Foundation Archive has two primary goals.
* Provide carefully selected subset of crucial media as a reference system and curriculum for people curious to learn and explore
* Replication and distribution of our most critical achievements in the event of societal collapses which results in the loss of access to information.

## Why "Foundation"
Foundation is based on the Foundation series by Isaac Asimov in which a group of mathematicians and scientists predict the collapse of a galactic empire. They develop a way to predict the outcomes of various scenarios and set up a foundation on the planet terminus to protect the most critical information in order to greatly reduce the amount of time required to rebuild. The goal of the foundation in the book mimics the goal of the Foundation Archive with the unfortunate exception that we do not possess psychohistory and with the fortunate exception that we do not have to consider the problems of space travel. The archive itself is a tribute to Asimov as it is to society for asking the obvious question and proposing a possible action.

## Reasoning
We live in an unprecedented age of progress and growth by nearly all metrics and data supports the view that we are likely not responsible enough at scale to sustain it for much longer. We see global instability in our political, scientific, technological, and ecological systems which suggest that we are struggling to manage resources and maintain sustainability. Idealistic people have proposed solutions such as migration to space, or facilities underground, but the major proposed solutions are highly ambitious and are unlikely to mature before a major collapse occurs. Human growth is not an opaque metric and is well understood to be exponential and therefore so are its demands for food, petroleum, and waste disposal, but not our ingenuity or innovation which are much less predictable. Civil unrest, ecological destruction, over population, and poor resource management all threaten to destabilize a system that is likely less resilient than we currently believe. 

The nature of how life will change is unclear but the possibility that the world as we know it will change drastically in the next few generations is not remote, and the question of collapse is not if but when. While we still have time and means each of us can in our own way perform a task which may potentially give incalculable value to future generations. We shall preserve for them information that our society has amassed and takes for granted in hopes that whatever world future humans must inhabit they will have a corpus of high quality information possible to work with.

Many of us have not lived in a world that requires us to fight for resources and the recent global pandemic of 2020 showcased that we are likely not up to the challenge of a real epidemic on par with the black death or the Spanish flu, so our best hope is not to ensure the fate of our major works of art and science to any singular or even small group of institution but entrust it as we always have to individuals in hope that one or more of the many redundant copies survive.

## Usage
The intended usage of this repository is to be the central source of truth for the selection of media that should be archived and replicated. This framework will present a small but carefully selected corpus of critical media which each individual can reliably secure using their own backup and recovery methodology. This repository contains only things which are legally allowed acting as a manifest of items to be collected by archivits. It also includes notes and guides on how best to go about preservation efforts as well as anything that can be legally included. It is designed in a way that can be cloned with a revision system like git and then filled and modified to a personal revision system or be uploaded to a durable storage solution. Lastly the repostiroy provides a convenient archival and tagging approach that can be used to explore and enjoy the items in the archive at your leisure with little effort.

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
 