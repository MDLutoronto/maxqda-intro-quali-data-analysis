---
created_date: 2025-08-08
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
title: Survey Data
parent: Part 2 - Document Variables, Queries, Visualizations, Focus Groups, and Survey Data
nav_order: 2.16
layout: default
grand_parent: Introduction to Using MAXQDA for Qualitative Data Analysis
---
### Survey Data

19. The second special data type we’re going to look at is Survey data. As part of the download package, I provided you with an Excel file called SurveyData.xlsx. This is a Survey of Millennials on their thoughts about work from a database called Kaggle. Let’s open it up and take a look. You’ll see that in the data tab, each row is a participant and their responses. Each column is a code that corresponds with a question in the survey. To see how the codes and questions match up, you could look at the questions tab.

    <img src='{{ '/assets/images/214.png' | relative_url }}' alt='SurveyData Excel file highlighted in File Explorer' title='' width='1376' height='302' />

    <img src='{{ '/assets/images/maxqda_part2_100b.png' | relative_url }}' alt='Excel spreadsheet showing the survey data sheet.' title='' width='1437' height='1001' /><img src='{{ '/assets/images/maxqda_part2_100c.png' | relative_url }}' alt='Excel spreadsheet of the Survey data showing the Question sheet.' title='' width='1437' height='1001' />
20. Okay, let’s import this Excel file in. Close Excel and go back to MAXQDA. Highlight the Documents folder. Then go to the Import menu and select Survey Data. You’ll see that you are able to import survey data from Excel, Survey Monkey, and SPSS. For us, we need to select Import Data from Excel Spreadsheet.

    <img src='{{ '/assets/images/216.png' | relative_url }}' alt='Import, Survey Data and Import from Excel Spreadsheet dropdown highlighted' title='' width='667' height='213' />
21. Browse to the SurveyData excel file and click on Open. <img src='{{ '/assets/images/217.png' | relative_url }}' alt='SurveyData Excel file and Open highlighted in File Explorer' title='' width='1176' height='703' />
22. The first screen just asks you to rename the survey, if needed, before proceeding. That name will be the name of the document group that will store all the survey responses. It also provides a preview of the data. We can keep the name as is, then click on Next. <img src='{{ '/assets/images/survey%20data%20name_0.png' | relative_url }}' alt='SurveyData in Survey Name and Next highlighted' title='' width='1307' height='1192' />
23. You then have to go through and identify which questions are closed\-ended questions (those questions should have quantitative selected), and which questions are open\-ended questions (those questions should have qualitative selected). Unfortunately, you need to do this manually, as it often has issues detecting the questions correctly. In our case the first few questions are all closed ended. All the rest are open\-ended questions, starting with the MaQ1 to the end. To select them quickly, you can use the toggle boxes for qualitative and quantitative. First click on the boxes beneath qualitative and quantitative until all check boxes are cleared. Then click on the box beneath qualitative to select qualitative for all items. Then manually deselect qualitative for the closed\-ended questions and instead select quantitative. When you’re done you should have quantitative selected for the closed\-ended questions and qualitative selected for the open\-ended questions. For the quantitative variables, it also detects the type of data, Boolean, text, etc. Make sure that these are also correct. In our case, it all looks good, so click on Next. <img src='{{ '/assets/images/survey%20data%20types.png' | relative_url }}' alt='Next highlighted' title='' width='1306' height='1192' />
24. The next screen asks how to name your cases and whether to group them into folders. We can use the column Sr No as our Case IDs, which should be selected automatically. We don’t want any grouping, so we can leave that blank. Finally, we can click on Import. <img src='{{ '/assets/images/survey%20data%20import.png' | relative_url }}' alt='Import highlighted' title='' width='1304' height='1192' />
25. A window will pop\-up to tell you that the survey imported successfully. You should have one document for each survey respondent, all grouped together in a New Document Group, SurveyData. Each document lists all the open\-ended question responses for that survey respondent. For now, we can click on OK.

    <img src='{{ '/assets/images/maxqda_part2_106a_new_0.png' | relative_url }}' alt='OK highlighted' title='' width='302' height='317' />

    <img src='{{ '/assets/images/maxqda_part2_106b_new_1.png' | relative_url }}' alt="SurveyData document group with numbered documents corresponding to survey respondent's answers." title='' width='616' height='462' />
26. Along with creating documents, it also creates a code for each survey open\-ended question’s responses, under a Parent Code, which is the same name as the document group, in this case, SurveyData.

    <img src='{{ '/assets/images/maxqda_part2_108a_1.png' | relative_url }}' alt='SurveyData parent code with each question as a child code highlighted in the Codes list.' title='' width='607' height='401' />
27. Another window should also open up automatically, which is the Survey Analysis window. On the left, it lists our survey questions. If you click on a closed\-ended question, such as Industry, it will display a bar graph of the various responses to this question. <img src='{{ '/assets/images/maxqda_part2_108a_2.png' | relative_url }}' alt='Industry highlighted' title='' width='1202' height='688' />

    <img src='{{ '/assets/images/maxqda_part2_108b_new_0.png' | relative_url }}' alt='Industry bar graph shown' title='' width='1212' height='689' />
28. If you click on an open\-ended question on the left, it will display the responses in the centre panel to that question, and on the right, it will display the new code system for our questions. For example, click on MaQ3\. <img src='{{ '/assets/images/maxqda_part2_109_new_0.png' | relative_url }}' alt='MaQ3 highlighted' title='' width='1212' height='686' />
29. Now we can use the code system on the right to create new codes we can use to code our data. For example, if you hover over MaQ3 parent code, click on the green plus sign and create a new subcode called Flexibility. Do that one more time to create another subcode called Risk Taking. Then try coding some of the responses to those codes. You can now see the codes listed to the right of the responses in the centre panel. If you hover over a code there, you can click on the X to remove that code being applied to that response if you make a mistake.<img src='{{ '/assets/images/maxqda_part2_110a_new_0.png' | relative_url }}' alt='Green plus sign highlighted' title='' width='1253' height='313' />

    <img src='{{ '/assets/images/maxqda_part2_110b_0.png' | relative_url }}' alt='New Flexibility code' title='' width='408' height='412' />

    <img src='{{ '/assets/images/maxqda_part2_110c_new_0.png' | relative_url }}' alt='Flexibility and Risk Taker codes highlighted' title='' width='1619' height='695' /><img src='{{ '/assets/images/maxqda_part2_110d_new_0.png' | relative_url }}' alt='X highlighted' title='' width='1349' height='689' />
30. You can also do a text and search autocode as we've done with other documents. Select question MaQ6 on the left.

    <img src='{{ '/assets/images/maxqda_part2_111_updated_0.png' | relative_url }}' alt='MaQ6 highlighted' title='' width='1384' height='752' />
31. Click on search Search & Autocode, search for WhatsApp, and click on Run search.

    <img src='{{ '/assets/images/maxqda_part2_112a_new_0.png' | relative_url }}' alt='Search & Autocode highlighted' title='' width='1375' height='758' />

    <img src='{{ '/assets/images/maxqda_part2_112_new_0.png' | relative_url }}' alt='WhatsApp in search for' title='' width='810' height='429' />
32. You should have two results. You can create a new code and code these items by clicking on the coding icon just above the responses (looks like a red circle with a green plus sign).

    <img src='{{ '/assets/images/maxqda_part2_113_new.png' | relative_url }}' alt='Coding icon highlighted' title='' width='1353' height='755' />
33. You can choose to code entire responses, paragraphs, sentences, or just the search hit. In our case, let’s code responses (as the responses are short). Select Autocode Responses Containing Search Hits. <img src='{{ '/assets/images/maxqda_part2_114_new_1.png' | relative_url }}' alt='Autocode Responses Containing Search Hits highlighted' title='' width='1349' height='722' />
34. A new code pop\-up window should appear. Click on OK to keep the defaults. <img src='{{ '/assets/images/survey%20autocaode%20save.png' | relative_url }}' alt='OK highlighted' title='' width='365' height='421' />
35. Now your responses are coded with the new code. Click on the X above the search results to go back to seeing all the responses for this question. <img src='{{ '/assets/images/maxqda_part2_116_new_0.png' | relative_url }}' alt='X highlighted above search results' title='' width='1352' height='720' />
36. Finally, we can use a tool to analyze sentiment of responses. Select MaQ1 on the left.<img src='{{ '/assets/images/maxqda_part2_117_new_0.png' | relative_url }}' alt='MaQ1 highlighted' title='' width='1356' height='746' />
37. Select Analyze Sentiments from the top ribbon menu. It will create additional columns next to the responses and assign a sentiment for each response looking for positive and negative words. <img src='{{ '/assets/images/maxqda_part2_118_new_0.png' | relative_url }}' alt='Analyze Sentiments highlighted' title='' width='1352' height='577' />
38. The Analyze Sentiments window will open. Select Apply stop word list (English) and then click OK.

    <img src='{{ '/assets/images/maxqda_part2_119_new_0.png' | relative_url }}' alt='Apply stop word list (English) and OK highlighted' title='' width='364' height='220' />
39. You should always read through the results to see if you agree with the sentiment assigned. If we're happy with the sentiment, we can have it autocode the responses. Click on Autocode Response with Sentiment. Keep the defaults and click OK.<img src='{{ '/assets/images/maxqda_part2_120a_new_1.png' | relative_url }}' alt='Autocode Response with Sentiment highlighted' title='' width='1679' height='569' />

    <img src='{{ '/assets/images/maxqda_part2_120b_new_0.png' | relative_url }}' alt='OK highlighted' title='' width='346' height='290' />
40. New codes have been added. If we click on the Codes column heading, we can sort the coding together. Take a look at the Negative codes. We see that \[No response] has been grouped under there, when we might prefer to have it coded as No sentiment. Hover over the Negative code for each \[No response] entry and click on the red X to remove the Negative coding for those entries.

    <img src='{{ '/assets/images/maxqda_part2_121a_new.png' | relative_url }}' alt='OK highlighted' title='' width='289' height='299' />

    <img src='{{ '/assets/images/maxqda_part2_121b_new_0.png' | relative_url }}' alt='Codes highlighted' title='' width='1686' height='1061' /><img src='{{ '/assets/images/maxqda_part2_121c_new_0.png' | relative_url }}' alt='X highlighted' title='' width='1679' height='509' /><img src='{{ '/assets/images/maxqda_part2_121d_new_0.png' | relative_url }}' alt='Negative codes grouped together under Sentiment' title='' width='1684' height='1054' />
41. Then select all 8 \[No response] entries and drag them over to the No sentiment code on the right. You can now see them all categorized as No sentiment if you scroll down. This kind of sentiment analysis can work really well on simple responses to a question that asks for an opinion. But it is always good to read through the results to see how accurate the coding has been.

    <img src='{{ '/assets/images/maxqda_part2_122a_new_2.png' | relative_url }}' alt='Negative codes and No sentiment code highlighted' title='' width='1686' height='1071' />

    <img src='{{ '/assets/images/maxqda_part2_122b_new_1.png' | relative_url }}' alt='There are now 8 coded segments in No sentiment' title='' width='1682' height='1003' />
42. You can learn more in the MAXQDA manual, [Analyzing Surveys section](https://www.maxqda.com/help/analyzing-surveys/survey-analysis).

That’s it for today! For more information, see our [MAXQDA Guide](https://mdlutoronto.github.io/maxqda-info-resources-tutorials-workshops/).

**Technique**: [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools**: [MAXQDA](https://mdlutoronto.github.io/tutorials-search/?tool=MAXQDA) 