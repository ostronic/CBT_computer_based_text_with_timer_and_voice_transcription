# PJ-CBT_Timer

This is a python estension code i wrote for the PJ-CBT collaboration project.
It is a timer that helps set a speciified time for the users answering cbt questions,
if the time elapses the program automatically haults, the question stops.
Here is the git repo. link to the project. https://github.com/praiseolotu/PJ-CBT.git

<li>
Navigate to MultQuestion
<pre>
<code>cd MultQuestion</code>
</pre>
</li>
<li>
Install the requierments
<pre>
<code>
python3 requiremen.txt
</code>
</pre>

</li>

<li>
Run the script
<pre>
<code>
python3 main.py
</code>
</pre>
</li>

## Modifying the Timer

<li>
open The main.py and find class Management
<pre>
<code>
class Management:
    score = 0
    QuizeDuaration = 15  # time in seconds
    Started = False
    Start_time = 0
    Name = ""
    quize_token = "1224"
</code>
</pre>
</li>
