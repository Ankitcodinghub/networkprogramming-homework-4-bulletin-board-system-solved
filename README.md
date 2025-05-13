# networkprogramming-homework-4-bulletin-board-system-solved
**TO GET THIS SOLUTION VISIT:** [NetworkProgramming Homework 4-Bulletin Board System Solved](https://www.ankitcodinghub.com/product/networkprogramming-homework-4-bulletin-board-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92811&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;NetworkProgramming Homework 4-Bulletin Board System Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. Introduction

In this part, you are going to implement the subscription features for the BBS service. The event will be raised whenever the client creates a new post that title contains the keyword subscribed by any other client.

2. Example Architecture using Apache Kafka

The middleware server will get a message/record from the producer when there has a new post and also notify the client(s) who have subscribed to the specified topic.

A. BBS server is a producer, and each client is a consumer

B. Each client act as both a producer and a consumer

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. Requirements

The service can serve at least 10 clients. Your server and client program must be able to handle all commands in the previous part (output results must be the same as the previous part). For some commands such as whoami, exit, logout, create-board, list-board ##&lt;key&gt; and list-post &lt;board- name&gt; ##&lt;key&gt;, your client program only sends the command to the server and gets the corresponding result from the server. However, there are new commands that your client program will subscribe to the new post. These commands are described as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
Command format

subscribe –board &lt;board-name&gt; –keyword &lt;keyword&gt;

(command and arguments are in the same line)

</div>
<div class="column">
Description

Subscribe the board with a keyword, notify the client whenever the event be raised.

Note [1]: Can subscribe the same board multiple times with different keywords. Notify user once someone creates a new post with a specified board and the title contains one of the keywords

Note [2]: Subscribe objective (board)

can be nonexistent

Subscribe the author with a keyword, notify the client whenever the event be raised.

Both notes [1] and [2] are same as the previous one (change objective to author) ↑

Unsubscribe the board from the server (or middleware server) and remove all the keywords associated with a specified board.

Unsubscribe the author from the server (or middleware server) and remove all the keywords associated with a specified author.

List the information about the subscribed board(s) and author(s).

</div>
<div class="column">
Result

Please login first

Already subscribed

same as the previous one same as the previous one

same as the previous one

Unsubscribe successfully

Please login first

You haven’t subscribed &lt;board-name&gt; Unsubscribe successfully

Please login first

You haven’t subscribed &lt;author-name&gt;

List all the subscribed info Please login first

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Success

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Subscribe successfully (The notify message should at least include board, title, and author)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Fail (2)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
[Invalid option] usage: subscribe –board &lt;board- name&gt; –keyword &lt;keyword&gt;

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
subscribe –author &lt;author-name&gt; –keyword &lt;keyword&gt;

(command and arguments are in the same line)

unsubscribe –board &lt;board-name&gt;

unsubscribe –author &lt;author-name&gt;

list-sub

</div>
<div class="column">
Fail (1)

Fail (3)

Success Fail (1)

Fail (3) Success

Fail (1) Fail (2)

Success

Fail (1) Fail (2)

Success Fail (1)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Fail (2)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
[Invalid option] usage: subscribe –author &lt;author- name&gt; –keyword &lt;keyword&gt;

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
4. Scenario

Run your server first, and run your client program to connect to your server. The sample outputs of the

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
client program are listed as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
Client 1

</div>
</div>
<div class="layoutArea">
<div class="column">
Client 2

</div>
</div>
<div class="layoutArea">
<div class="column">
Client 3

</div>
</div>
<div class="layoutArea">
<div class="column">
bash$ ./client 127.0.0.1 7777

</div>
</div>
<div class="layoutArea">
<div class="column">
******************************** ** Welcome to the BBS server. ** ******************************** % register Paul paul@cs.nctu.edu.tw 12345

</div>
</div>
<div class="layoutArea">
<div class="column">
Register successfully.

</div>
</div>
<div class="layoutArea">
<div class="column">
bash$ ./client 127.0.0.1 7777

</div>
</div>
<div class="layoutArea">
<div class="column">
******************************** ** Welcome to the BBS server. ** ******************************** % register Brad brad@cs.nctu.edu.tw 12345

</div>
</div>
<div class="layoutArea">
<div class="column">
Register successfully.

</div>
</div>
<div class="layoutArea">
<div class="column">
bash$ ./client 127.0.0.1 7777

</div>
</div>
<div class="layoutArea">
<div class="column">
******************************** ** Welcome to the BBS server. ** ******************************** % register Gary gary@cs.nctu.edu.tw 12345

</div>
</div>
<div class="layoutArea">
<div class="column">
Register successfully.

</div>
</div>
<div class="layoutArea">
<div class="column">
% login Paul 12345

</div>
</div>
<div class="layoutArea">
<div class="column">
% login Brad 12345

</div>
</div>
<div class="layoutArea">
<div class="column">
login Gary 12345

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
%

Welcome, Paul. Welcome, Brad. Welcome, Gary.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
% subscribe –board –keyword Project Subscribe successfully

</div>
</div>
<div class="layoutArea">
<div class="column">
HW4_Board

</div>
</div>
<div class="layoutArea">
<div class="column">
% subscribe –author Jason –keyword hw4 Subscribe successfully

</div>
</div>
<div class="layoutArea">
<div class="column">
% create-board HW4_Board

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Create board successfully.

</div>
</div>
<div class="layoutArea">
<div class="column">
% subscribe –board –keyword Project

Already subscribed

% subscribe –author Bryant –keyword exam

Subscribe successfully

</div>
</div>
<div class="layoutArea">
<div class="column">
HW4_Board

</div>
</div>
<div class="layoutArea">
<div class="column">
% subscribe –author Paul –keyword HW Subscribe successfully

% subscribe –author Paul –keyword post Subscribe successfully

% unsubscribe –author Brad You haven’t subscribed Brad

</div>
</div>
<div class="layoutArea">
<div class="column">
% create-post HW4_Board

–title About Project –content HW4… Create post successfully.

</div>
</div>
<div class="layoutArea">
<div class="column">
% *[HW4_Board] About Project – by Paul* % list-board ##HW

Index Name Moderator 1 HW4_Board Paul

</div>
</div>
<div class="layoutArea">
<div class="column">
% create-post HW4_Board

–title About HW and Exam –content blablabla

Create post successfully.

</div>
</div>
<div class="layoutArea">
<div class="column">
% unsubscribe –author Bryant Unsubscribe successfully

</div>
</div>
<div class="layoutArea">
<div class="column">
% list-sub

Board: HW4_Board: Project

</div>
</div>
<div class="layoutArea">
<div class="column">
% *[HW4_Board] About HW and Exam – by Paul*

% list-sub

Author: Jason: hw4; Paul: HW, post

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
5. Notes

1. About implementation:

<ul>
<li>There is no limitation on your implementation. You can choose whatever which framework, library, or even implement the logic by yourself, as long as it can achieve the goal of spec.</li>
<li>The output message should show the information at least greater or equal to mentioned in the requirements. In addition, it not restricted in any format.</li>
</ul>
3. About Kafka clients: • C/C++

• https://github.com/edenhill/librdkafka

<ul>
<li>Python</li>
<li>Node.js</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<ul>
<li>&nbsp;</li>
</ul>
</div>
</div>
</div>
</div>
