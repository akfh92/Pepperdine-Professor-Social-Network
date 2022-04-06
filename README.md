![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

# Pepperdine-Professor-Social-Network
Social Network Service for professors at Pepperdine University.

<br/>
**Description**:<br/>
Welcome Onboard fellow Students and Developers, This is where you can find resources to make a Social Netwrok Service for professors at Pepperdine University. Currently, professors at Pepperdine are having problem communicating with each other when collaborating on a research or when they want to ask fellow professors for guidance. In order to solve this problem, I have decided to launch a social network for them where they can look up each others past research papers and gather information about other professors. You are free to contribute in anyway. You can also use it to make a Social Network Service for professors at your school or perhaps any organzation. Unfortunately I cannot share some of the database information because they have sensitive information on professors at Pepperdine, but since almost every institution are having the same problems, you can use this as a guidance to a SNS for your institution. <br/><br/>

**Contribution Guideline**: 
* Reporting a bug
* Discussing the current state of the code
* Submitting a fix
* Proposing new features
<br/><br/>

**Skills Used**:
* Python
* MySQL
* API
* Auto-scripting using beautifulsoup4
* Automate uploading RESTful API to MySQL using python libraries (Pandas, json, mysql.connector)
* NLP clustering 
<br/><br/>
Note: Please do not put the project link to reference your local forked repo. Always link it to this repo after it's been merged with main.

<br/><br/>
**STEPS**
1. Get a list of members of the social network in an excel format.
2. Using Python, upload members to the database (MYsql). 
3. [Create a tables in MYSQL database as described in Data Diagram PDF](https://github.com/akfh92/Pepperdine-Professor-Social-Network/blob/2df8c282bb8ebb9f13823ef532f48148f14aced5/Data_Diagram.pdf)
4. [Using Python, upload data into authors](https://github.com/akfh92/Pepperdine-Professor-Social-Network/blob/ee27e19e9b005045cb98cb9c12678f67aa534c64/Python-Codes/Professor_Author_ID_Getter)
5. Using Python, gather data for all the tables
* [Get Abstract on Papers](https://github.com/akfh92/Pepperdine-Professor-Social-Network/blob/e44d8585c64f506eb47838e14e9b423532e8328b/Python-Codes/Professor_Paper_Getter)
* [Get Specter Embedding](https://github.com/akfh92/Pepperdine-Professor-Social-Network/blob/d2abed99b74924161398861d1fa20520407de9e4/Python-Codes/Professor_Embedding_Getter)
* [Get Field of Study](https://github.com/akfh92/Pepperdine-Professor-Social-Network/blob/350f7ee799034a7092f0ed76cdd187460b27a7a0/Python-Codes/Professor_Field_Of_Study_Getter)
6. After uploading data into the database, create a new table by using the join function in MYSQL with columns that you want to display.
7. Upload data into [Graphhext](https://www.graphext.com/), and manipulate it the way you want. - Complete!

Here is an example of completed project:

Copyright (c) [2022] [Sang Hyeok Park]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

