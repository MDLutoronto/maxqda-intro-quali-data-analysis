---
created_date: 2025-08-08
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
title: Work with Codes and Activation
parent: Part 1 - Import/Export, Coding, and Memos
nav_order: 1.07
layout: default
grand_parent: Introduction to Using MAXQDA for Qualitative Data Analysis
---
### Work with Codes and Activation

Let’s talk more about Codes.

37. First, you can see now there are useful counts associated with our codes to see how many segments have been coded into that code.

    <img src='{{ '/assets/images/maxqda_part1_37_new_0.png' | relative_url }}' alt='Code counts highlighted' title='' width='557' height='257' />
38. If you want to see all the segments that you’ve coded with a particular code, this is where the Retrieved Segments panel comes into play. Before we retrieve segments, we need to talk about a powerful feature of MAXQDA called activation. To pull up all the segments in the Retrieved Segments panel that we’ve coded in this project to a particular code, let’s say Energy Efficiency, we need to first activate all of our documents in the project. There are a number of ways to activate a document, but the easiest way is, in the Document System panel, click on a small circle to the left of the name of a document. That should highlight the document in purple. <img src='{{ '/assets/images/maxqda_part1_38a_new.png' | relative_url }}' alt='Activate highlighted' title='' width='556' height='306' /><img src='{{ '/assets/images/maxqda_part1_38b_new.png' | relative_url }}' alt='Example of activated document highlighted' title='' width='559' height='292' />
39. Click on the circle again to deactivate it. If we want to activate all the documents in a document group, we could click on the small circle to the left of the document group name. And to activate all the documents in a project, we could click on the small circle to the left of the Documents folder.

    <img src='{{ '/assets/images/maxqda_part1_39a_new.png' | relative_url }}' alt='Activation buttons highlighted at Focus Groups' title='' width='559' height='445' />

    <img src='{{ '/assets/images/maxqda_part1_39b_new.png' | relative_url }}' alt='All documents highlighted' title='' width='555' height='441' />
40. So, make sure you have all the documents activated, then go to the Code System panel and activate a code that you want to see all the segments for. In our case, let's activate Energy Efficiency. Again, click on the small circle to the left of the name of the code.

    <img src='{{ '/assets/images/maxqda_part1_40_new.png' | relative_url }}' alt='Energy Efficiency code activation highlighted' title='' width='557' height='249' />
41. Finally click on the Retrieved Segments tab at the bottom to maximize the panel again so we can see the results. Here you will see all the snippets of text that were coded to this code from all documents in the project, listing what document it is from below it. It’ll even show you the part of the image you drew a box around, if it corresponds to this code. If you click on a coding stripe of a segment, it’ll show you the document with that segment highlighted, so you can see it in context.

    <img src='{{ '/assets/images/maxqda_part1_41a.png' | relative_url }}' alt='MAXQDA interface, highlighting the Retrieved Segments tab at the bottom' title='' width='2135' height='1333' /><img src='{{ '/assets/images/maxqda_part1_41b_0.png' | relative_url }}' alt='A retrieved segment is highlighted and the corresponding segment is also highlighted in the open document above' title='' width='2116' height='1327' />
42. You can see that there are circular handles at each end of the quote displayed in the Document Browser panel. You can adjust what is highlighted by dragging those handles. It’ll ask you if you want to adjust the coding, and when you say yes, it will now also be updated in the Retrieved Segments panel. <img src='{{ '/assets/images/058.png' | relative_url }}' alt='Handles to adjust highlighted text' title='' width='1692' height='994' />
43. If you later realize that you mistakenly coded something you didn’t mean to code, you can uncode it. Right click on one of the retrieved segments' coding stripe, and then select Delete. <img src='{{ '/assets/images/maxqda_part1_43_new.png' | relative_url }}' alt='Delete highlighted' title='' width='1063' height='1165' />
44. If we think a bit more about what we did to get these retrieved segments and how we activated documents and codes, you can start to see how powerful this can be. You can use activation to customize and filter what you see in the Retrieved Segments panel by what documents and codes you have active. Try also activating Budget to also get those segments. Now it is showing retrieved segments for both codes that are activated. Activation comes up in a lot of places in MAXQDA, so it is important to understand the basics of how it works. <img src='{{ '/assets/images/maxqda_part1_44_new.png' | relative_url }}' alt='Energy Efficiency and Budget codes activated' title='' width='1307' height='1123' />
45. Now if we want to quickly deactivate all the codes we have activated, we can click on the Reset activations icon next to the Code search box. There’s a similar icon for documents, but for now, let’s just deactivate our codes. That icon also tells you how many documents or codes were activated.

    <img src='{{ '/assets/images/maxqda_part1_45_new.png' | relative_url }}' alt='Reset Activations icon highlighted' title='' width='555' height='252' />
46. Next, let’s look a bit more at our Code System panel. You will notice that all of our codes are top\-level or parent codes, meaning we haven’t established a hierarchy, none of our codes are nested under other codes; however, MAXQDA can help you organize your codes in a hierarchical structure. You are often in the end trying to create a hierarchical codes list to group common codes together into broader categories and themes to help make sense of your coding. For example, create a new code and call it Sustainability.

    <img src='{{ '/assets/images/maxqda_part1_46a.png' | relative_url }}' alt='New code pop-up window with the name Sustainability highlighted along with the OK button' title='' width='344' height='347' />
47. You could use this code to group some of your existing codes. For example, drag Energy Efficiency and Water Consumption onto the Sustainability code. Now you can see that they are grouped beneath. Codes beneath another code are called Child Codes or Subcodes.

    <img src='{{ '/assets/images/maxqda_part1_47_new.png' | relative_url }}' alt='Showing codes panel, with Sustainability and its child codes Energy Efficiency and Water Consumption highlighted' title='' width='555' height='271' />
48. You can use Sustainability as its own broader code now in coding or just keep it as a heading in the hierarchy. Activate Sustainability. You will notice that the child codes are also activated and all the related segments for parent and child codes will show in the Retrieved Segments panel.

    <img src='{{ '/assets/images/maxqda_part1_48a.png' | relative_url }}' alt='Interface showing that Sustainability and its child codes are activated and the retrieved segments window highlighted showing segments from the child codes' title='' width='2880' height='1643' />
49. You might notice that the count of segments for Sustainability still says 0, even though its child codes are associated with segments. Try clicking on the arrow next to Sustainability to collapse the code group. Now you should see the counts aggregated from the child codes.

    <img src='{{ '/assets/images/maxqda_part1_49a_new.png' | relative_url }}' alt='Code panel showing that the count is zero for Sustainability when it is expanded' title='' width='554' height='270' /><img src='{{ '/assets/images/maxqda_part1_49b_new.png' | relative_url }}' alt='Code panel showing the code count is 12 for Sustainability when it is collapsed' title='' width='556' height='226' />
50. Right click on Sustainability and change its colour to green. You should see a pop\-up asking if you want to colour the child codes with the same colour, which can be helpful to see what codes are related, at a glance. Click on Yes to make the change.

    <img src='{{ '/assets/images/maxqda_part1_50a_new.png' | relative_url }}' alt='Shows Sustainability highlighted on the code panel and the colour green highlighted on the properties pop-up window' title='' width='802' height='839' /><img src='{{ '/assets/images/068.png' | relative_url }}' alt='Yes highlighted' title='' width='362' height='319' />
51. Finally, sometimes after you’ve done some coding, you may want to merge two or more codes together into one, as they are very similar. Let’s try this with Maintenance and Upgrades. You can do this in MAXQDA by dragging one code on top of another code but keep holding the mouse click down until you see the word Merge appear to the right of the highlighted code and then hover over there to select Merge instead. Let’s do this by dragging Maintenance over to Upgrades, and selecting Merge.

    <img src='{{ '/assets/images/maxqda_part1_51_new.png' | relative_url }}' alt='Merge highlighted' title='' width='679' height='270' />
52. This will merge the segments from the code you dragged (Maintenance), into the code you dragged into (Upgrades). It shows that the code is the result of a merge by adding a \+ sign to the name. If you regret this, you can always undo! <img src='{{ '/assets/images/maxqda_part1_52_new.png' | relative_url }}' alt='Upgrades (+) code highlighted' title='' width='559' height='213' />
53. So far, we’ve been manually selecting segments to code, but you can use a text search to do some simple autocoding. For example, go to the Analysis menu and select Text Search & Autocode. Choose the first option from the drop\-down menu, Text Search & Autocode.

    <img src='{{ '/assets/images/071_0.png' | relative_url }}' alt='Analysis, ABC Text Search & Autocode, and Text Search & Autocode drop-down highlighted' title='' width='472' height='216' />
54. You can use this feature to search for words or phrases and then code matching segments. For example, let’s search for the word “infrastructure” and select Find all word forms (lemma list) to find not just infrastructure, but also its plural form, then click on Run search. <img src='{{ '/assets/images/072.png' | relative_url }}' alt='infrastructure, Find all word forms (lemma list) and Run search highlighted' title='' width='821' height='538' />
55. Here we see a list of results in the Preview column. If we’d like to code these results to a new code called Infrastructure, we can click on the new code icon at the top (looks like a red circle with a green plus sign). We have the option here to code to an existing code or create a new code. Let’s create a new code by selecting Autocode Results with New Code. <img src='{{ '/assets/images/073.png' | relative_url }}' alt='Autocode Results with New Code highlighted' title='' width='1080' height='487' />
56. It will give you a default name that makes it clear this code was created from autocoding. This can be a good reminder. It also auto populates the code memo with details of the text search. In terms of what we code, we can select how much text will be a part of the segment around the word infrastructure. For this example, let’s select sentence to code sentences with the word infrastructure. This option even allows you to specify how many sentences before and after, but in this case, if we keep it at 0 for both, it’ll just code the one sentence with the word. Click on OK.

    <img src='{{ '/assets/images/074.png' | relative_url }}' alt='Sentence with 0 as settings and OK highlighted' title='' width='464' height='583' />
57. This will automatically create this new code and apply it to the results and tell you how many segments were coded. Click on OK to close the window. Also, close the search results window. Now we have autocoded some of our text to a new code using a text search.

    <img src='{{ '/assets/images/075.png' | relative_url }}' alt='OK highlighted' title='' width='304' height='313' />

    <img src='{{ '/assets/images/maxqda_part1_57b.png' | relative_url }}' alt='Interface showing a segment in a document coded to the new Autocode for Infrastructure' title='' width='2023' height='1330' />


**Technique**: [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools**: [MAXQDA](https://mdlutoronto.github.io/tutorials-search/?tool=MAXQDA) 