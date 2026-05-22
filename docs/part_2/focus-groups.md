---
created_date: 2025-08-08
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
title: Focus Groups
parent: Part 2 - Document Variables, Queries, Visualizations, Focus Groups, and Survey Data
nav_order: 2.14
layout: default
grand_parent: Introduction to Using MAXQDA for Qualitative Data Analysis
---
### Focus Groups

1. Finally, let’s talk about two common types of data, and some of MAXQDA’s special features to help analyze them. For this, we need to go back to our other project file that we were working on at the beginning of the workshop. Go to the Home menu and select Open Project. You should see a list of recently opened projects, including our “MAXQDAPart2Project” file in the list. Select it.

    <img src='{{ '/assets/images/194.png' | relative_url }}' alt='Open Project and MAXQDAPart2Project highlighted' title='' width='231' height='323' />
2. Okay we’re ready to get started. The first one to look at is Focus Group transcripts. We actually already have one in this project file called “NYC Data Center FG1 Transcript.” Double click on that to open it up in the Document Browser panel. <img src='{{ '/assets/images/195.png' | relative_url }}' alt='NYC Data Center FG1 Transcript highlighted' title='' width='1256' height='490' />
3. You can see that to denote who is speaking in the transcript, we have all cap labels, such as MOD, MALE, MALE2, and FEMALE. When you have transcripts where you might want to isolate what someone has said, or exclude what the interviewer or moderator has said, you might want to use the Focus Group functionality in MAXQDA. Just to note, this will also work on our interview transcripts as well.

    <img src='{{ '/assets/images/196.png' | relative_url }}' alt='MOD and MALE highlighted' title='' width='577' height='404' />
4. In Part 1 of the tutorial, you might recall that we imported these Word documents from the Import menu using the Texts, PDFs, Tables option. Instead we could have used the Focus Group Transcripts option from the Import menu. If you click on the drop\-down arrow for that option, you will see that MAXQDA can bring in transcripts from a number of tools and will understand their formatting. This is actually a great list to see transcription tool options! The first two items in the list are when your tool isn’t listed or you did your transcription manually. You have the option to select with or without timestamps. When you import something with timestamps, it will also ask for the associated audio or video file and match the two together. In our case, we only have text transcripts, so we don’t need to worry about that.

    <img src='{{ '/assets/images/197.png' | relative_url }}' alt='Import and Focus Groups Transcripts highlighted' title='' width='489' height='709' />
5. As we’ve already imported in the file as a regular text file, we don’t need to reimport it using the Focus Group Transcripts options. Instead, with our focus group transcript highlighted in the Document System panel, we can just select Convert Text to Focus Group Transcript from the Import menu (the option is to the far right on the menu), and then select Convert Displayed Document. <img src='{{ '/assets/images/198.png' | relative_url }}' alt='Import, Convert Text to Focus Group Transcript and Convert Displayed Document highlighted' title='' width='1071' height='210' />
6. Here MAXQDA shows us a table where it has identified all the unique speakers in the document. It was confused by the title and transcriptionist’s note and picked those up as speakers as well, but we can deselect the first two items to ignore those during the conversion.

    <img src='{{ '/assets/images/199.png' | relative_url }}' alt='First two codes in list deselected buttons highlighted' title='' width='310' height='376' />
7. Also, click on the code color icons to set unique colours for each speaker that make sense to you. Then click on Convert.

    <img src='{{ '/assets/images/maxqda_part2_88a.png' | relative_url }}' alt='Speaker Selection window with the Code colours for the speaker names highlighted and the Convert button highlighted.' title='' width='564' height='335' />
8. You’ll see that the document’s icon has changed in the Document System panel and now you can expand it to see a listing for each speaker. If you look at the Document Browser with the transcript open, you will see that the content has now been coded by these special focus group speaker codes. These codes also show up in a special section in the Code System panel.

    <img src='{{ '/assets/images/maxqda_part2_89_new.png' | relative_url }}' alt='Interface with the transcript expanded to show new speaker documents, and new focus group speakers codes all highlighted, along with a document coded and highlighted with the new speaker codes. ' title='' width='892' height='509' />
9. Now you can use these special documents and codes to filter your data. For example, activate the Focus Group transcript we have been working with in the Document System panel (NYC Data Center FG1 Transcript 03_17_15_11_28AM). And then activate the FEMALE code in the Code System panel. If we open up the Retrieved Segments panel, we can see only statements made by the FEMALE participant in that focus group. <img src='{{ '/assets/images/202.png' | relative_url }}' alt='NYC Data Center FG1 Transcript and FEMALE code highlighted' title='' width='561' height='983' />

    <img src='{{ '/assets/images/203.png' | relative_url }}' alt='NYC Data Center FG1 Transcript with FEMALE codes only highlighted' title='' width='926' height='458' />
10. Now let’s say that you want to only see what the FEMALE participant has said about Energy Efficiency specifically. You might think that you should activate Energy Efficiency from the Code System panel, but this then just adds all of the Energy Efficiency segments to the Retrieved Segments panel. You can see that the segment count increased from 69 to 73\. <img src='{{ '/assets/images/204_0.png' | relative_url }}' alt='69 coded segments highlighted in Retrieved Segments panel' title='' width='1358' height='391' />

    <img src='{{ '/assets/images/205_0.png' | relative_url }}' alt='69 coded segments highlighted in Retrieved Segments panel' title='' width='1349' height='435' />

    <img src='{{ '/assets/images/maxqda_part2_91c.png' | relative_url }}' alt='Retrieved segments windows showing a mix of an energy efficiency coded segment and a FEMALE coded segment, all highlighted.' title='' width='1820' height='679' />
11. Instead, if you want the intersection of the two, activate only the FEMALE document in the Document System panel and only Energy Efficiency in the Code System Panel. Now you should see only the three segments from the FEMALE participant that were coded with Energy Efficiency.

    <img src='{{ '/assets/images/206.png' | relative_url }}' alt='FEMALE highlighted under Documents and Energy Efficiency code highlighted' title='' width='560' height='984' />

    <img src='{{ '/assets/images/207.png' | relative_url }}' alt='3 coded segments (from 1 document, 1 document group) highlighted under Retrieved Segments panel' title='' width='846' height='328' />

**Technique**: [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools**: [MAXQDA](https://mdlutoronto.github.io/tutorials-search/?tool=MAXQDA) 