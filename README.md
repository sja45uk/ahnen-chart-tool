README.md for ahnen-chart-tool

This is a WikiTree visual display tool designed to run on the https://apps.wikitree.com/apps/ server, which 
generates an indented format Ahnentafel chart of the ancestors for a selected WikiTree root profile. 
The idea for a novel Ahnen Chart layout was first described on one of my Free Space Pages (FSPs):
https://www.wikitree.com/wiki/Space:Ahnen_Chart_View_user_guide during October 2022. Over time, development 
& testing was done using tools on a variety of operating system environments (Windows, Ubuntu & Raspberry Pi).  
However, the source code was never added to the https://GitHub.com/sja45uk/ahnen-chart-tool repository.
Instead, each version of the main source file was given some simple combination of a version letters and numbers  
to identify its revision history. Multiple copies were installed on https://apps.wikitree.com/apps/adey271/
as various ahnenChart*.js* variants. Not all of these were successfully implemented, hence the vaiety of names 
when development was forced to backtrack.

Implementation was started during Hacktoberfest 2022, and development continued but was never completed during 
2023, because of difficulties with, and changes to, the WikiTree API.

During Hacktoberfest 2024, an attempt was made to learn more about WikiTree App programming, by assisting
Greg Clark with debugging his Super Big Family Tree app. This showed how difficult it is to manage multiple 
development threads, even with the support of GitHub version control.

It is intended to complete enough of the Ahnen Chart app development, during Hactoberfest (October) 2025, 
so that it can be added to the standard set of WikiTree chart tools for testing and comment by WikiTree members. 

The following analyses absolute file sizes to help identify the main development path:

53,743 ahnenChart.js _SAVED Aka Q3 ?
63,879 ahnenChart.js Aka R7b ?
53,745 ahnenChart.js_SAV Aka Q1 ?
53,733 ahnenChart.js_SAV-1 Aka Q1 ?
53,743 ahnenChart.js_SAV-2 Aka Q4 ?
54,808 ahnenChart.js_SAV-3 Aka Q5 ?

24,635 ahnenChart.js_2023-01-21 Aka H1 ?
24,450 ahnenChart.js_2023-01-29 Aka H2 ?

20,359 ahnenChart3.js See ahnenChartF.js ?

19,643 ahnenChartA.js
18,495 ahnenChartB.js
19,667 ahnenChartC.js
20,334 ahnenChartD.js
22,000 ahnenChartE.js
20,359 ahnenChartF.js
20,629 ahnenChartG.js
20,910 ahnenChartH.js
24,675 ahnenChartI.js
24,826 ahnenChartJ.js
24,824 ahnenChartK.js
27,609 ahnenChartL.js
25,405 ahnenChartM.js
32,098 ahnenChartN.js
26,906 ahnenChartN0.js
27,279 ahnenChartN1.js
31,238 ahnenChartN2.js
32,468 ahnenChartN3.js
39,963 ahnenChartO.js
48,246 ahnenChartP.js
53,733 ahnenChartP.js SAV Aka Q1 ?
48,208 ahnenChartP1.js
48,211 ahnenChartP2.js
48,363 ahnenChartP3.js
57,512 ahnenChartQ.js Aka Q3 ?
53,733 ahnenChartQ1.js_2023-02-01 SAV
53,736 ahnenChartQ2.js_2023-02-01 SAV
61,502 ahnenChartR.js Aka R0b ?
63,819 ahnenChartR.js_SAV Aka R2c ?
51,994 ahnenChartR0.js
63,517 ahnenChartR1.js
63,731 ahnenChartR2.js
63,529 ahnenChartR2a.js
63,518 ahnenChartR2b.js
64,553 ahnenChartR3.js
64,285 ahnenChartR3b.js
64,553 ahnenChartR3c.js
62,583 ahnenChartR4.js
63,700 ahnenChartR5.js
63,081 ahnenChartR5a.js
63,359 ahnenChartR5b.js
63,695 ahnenChartR5c.js
61,322 ahnenChartR6.js_SAV
61,306 ahnenChartR6a.js
62,055 ahnenChartR6b.js
61,478 ahnenChartR6d.js
61,761 ahnenChartR6g.js
75,840 ahnenChartR7.js
63,768 ahnenChartR7a.js
64,261 ahnenChartR7c.js
64,534 ahnenChartR7d.js
68,600 ahnenChartR7e.js
69,258 ahnenChartR7f.js
69,292 ahnenChartR7g.js
73,905 ahnenChartR7h.js
73,956 ahnenChartR7i.js
75,840 ahnenChartR7j.js
48,925 ahnenChartS0.js
48,921 ahnenChartS1.js
49,912 ahnenChartS2.js


This 2025 project will be the first time that an attempt is made to better track the code development.
