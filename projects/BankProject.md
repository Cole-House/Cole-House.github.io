---
layout: project
type: project
image: images/bankFront.png
title: Bank Record Program
date: 2021-11-28
labels:
  - Unix
  - User Interface
  - C++
summary: I built a simple mock banking program with C++ ran on terminal
---

<img class="ui medium right floated rounded image" src="/images/bankUI.png">

I solely worked on this project for my ICS 212 Programming class, where we used C in the beginning and then converted to C++ near the end of the semester, which they worked relatively the same with a few caveats. In the class we were also introduced to the concept of unix and working on a program stored on a remote server on campus rather our local operating system and we accessed the unix through terminal. This program was made with the VI text editing software and the project was built in two parts, the first being the user-interface and then the backend database.

<img class="ui medium right floated rounded image" src="/images/bankUI.png">

First when we run the executable it displays the various options the user is able to choose by typing out specified action, or even parts of it. For example, if the user wanted to add a record they could do this by typing out "a", "ad", or "add". This goes for all of the options and if the user input's an invalid option then it will keep asking the user for input until it is valid. With this program you are able to add records, print all records currently in the database, find a specific record and print it, delete a record, and quit the program. Another cool feature of this program is that a readfile() function is called after the user quits which saves all the records to a text file and once the program is executed again the function writefile() is called and adds the records from the text file into the database.

<img class="ui medium right floated rounded image" src="/images/bankRecords.png">

A difficulty I encountered with this project was the VI text editing software was very dated and did not allow me to move around my code freely, with me having to navigate my code using the up and down arrows and only able to have one file open at time. In this ICS 212 class the professor had an emphasis on tracing and knowing what your code is actually doing and it became quite confusing with the use of double pointers in the code, but I was able to figure that part out.

Link to Repository with Project [Bank Record Program](https://github.com/Cole-House/Banking-Software-on-Unix).
Source of [cover image](https://www.google.com/search?q=bank+cartoon&sxsrf=AOaemvJj-dGetSB613bIs2VmqA4y9haoww:1643177822155&tbm=isch&source=iu&ictx=1&vet=1&fir=CK1Rh9wpWSzdLM%252CYhdjw_FTgBVxkM%252C_%253BWxEZVvdKX6_roM%252C3GSCGOnCYxDVrM%252C_%253BQAeO6tQrlCeP4M%252Cu7NPvsvBXxxh0M%252C_%253BVEIsyIzXj6l69M%252Co2UUdvWTxPWHdM%252C_%253B9XZjA3hy8mIdZM%252CJXU7JaVlDGm2XM%252C_%253BSUd36490u4MLWM%252CXzSXT5yJizfexM%252C_%253Be7oNfU-tQyl7QM%252Cz4kwrtcn-hPTEM%252C_%253BpJr-6CMYE95rtM%252CCZ6k5J5jxoH0mM%252C_%253BxhFHsORvvojaRM%252CA3oJuxoU9rvnbM%252C_%253BJbxMpyga-3G7cM%252CbWnLPHfhMDjgjM%252C_%253BpxL-6VgVYYBhbM%252CNFmf2kV-PFbTqM%252C_%253BxdEgKd7AkL6qhM%252CPi19CO9fG5C26M%252C_%253BxavIKWr8Vpww4M%252Ci7YYuQitrFw2_M%252C_%253BZDHLVgJLhzYrGM%252CJXU7JaVlDGm2XM%252C_&usg=AI4_-kQZ4ztJ8e_ReK7PSdhf3mP8puCutw&sa=X&sqi=2&ved=2ahUKEwj5jZGz4s71AhU3ppUCHQ6gBakQ9QF6BAgREAE&biw=1309&bih=647&dpr=2.2#imgrc=pJr-6CMYE95rtM).

