# comp-598-homework-2---unix-server-and-command-line-exercises-solved
**TO GET THIS SOLUTION VISIT:** [COMP 598 Homework 2 – Unix server and command-line exercises Solved](https://www.ankitcodinghub.com/product/comp-598-homework-2-unix-server-and-command-line-exercises-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110761&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP 598 Homework 2 – Unix server and command-line exercises Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
30 pts

The goal of this assignment is for you to get more familiar with your Unix EC2 – both as a data science machine and as a server (as a data scientist, you’ll need it as both).

Task 1: Setting up a webserver (15 pts)

The objective of this task is to setup your EC2 instance to run an apache webserver on port 8008. Your goal is to have it serving up the file comp598_hw2.txt at the www root. In other words, my web browser can access it at http://X.Y.Z.W:8008/comp598_hw2.txt, where X.Y.Z.W is the public IP address of your EC2. The file itself should be empty.

One key detail to keep in mind is the security configuration of your EC2 – you’ll need to ensure that it allows port 8008 traffic through.

Task 2: Setting up a database server (15 pts)

The objective of this task is to setup your EC2 instance to run an instance of the MariaDB database on port

1. Install the MariaDB database server (try Googling “install mariadb ubuntu”…)

2. Configure the database to run on an external port

3. Create an empty database named “comp598_test”

4. Add a new user “comp598_grader” to your database server with permission to access the comp598_test database. Use the password “$ungl@ss3s” for the password for this user.

Make sure your MariaDB instance is publicly accessible, otherwise the TAs won’t be able to grade this question.

Some Tips

– This assignment will involve a substantial amount of googling and working on the UNIX command line.

– If you don’t understand a concept, google it and read up on it

– If you don’t understand how to do something, try googling it and making sense of instructions you find

– You will need to edit files on your EC2. My preferred editor is vim – but there’s a learning curve. If this is your first time really using unix, I would recommend using pico or nano.

Submission Instructions

Your MyCourses submission should contain – at minimum – the following:

– ip_address.txt o contains exactly one line containing the public IP address of your EC2 instance.

In addition to the submission file:
