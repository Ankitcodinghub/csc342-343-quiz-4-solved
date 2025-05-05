# csc342-343-quiz-4-solved
**TO GET THIS SOLUTION VISIT:** [CSC342_343 Quiz 4 Solved](https://www.ankitcodinghub.com/product/csc342_343-quiz-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95475&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC342_343 Quiz 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Question 1:&nbsp; Pipelined MIPS processor from the book.

Show or list all of the dependencies in this program. For each dependency, indicate which instructions and

register are involved.

You can draw the dependencies using ARROWS, or describe them in words:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Last NAME: First Name:

</div>
</div>
<div class="layoutArea">
<div class="column">
Question 2: Pipelining performance

One CPU manufacturer has proposed the 10-stage pipeline above for a 500MHz (2ns clock cycle) machine. Here are the correspondences between this and the MIPS pipeline:

• Instructions are fetched in the FET stage.

• Register reading is performed in the REG stage.

• ALU operations and. memory accesses are both done in the EXE stage. • Branches are resolved in the DET stage.

• WRB is the writeback stage.

Q 2.1

How much time is required to execute one million instructions on this processor, assuming there are no dependencies or branches in the code?

</div>
</div>
<div class="layoutArea">
<div class="column">
2.1.1 2.2.2 2.2.3

</div>
<div class="column">
Number of Cycles to fill the pipeline = ???? Number of Cycles to complete 1 million instructions= ???? Total time in (ns) to compute 1 million instructions is = ??????

</div>
</div>
<div class="layoutArea">
<div class="column">
IPG FET ROT EXP REN WLD REG EXE DET WRB 1 2 3 4 5 6 7 8 9 10

</div>
</div>
<div class="layoutArea">
<div class="column">
Q 2.2 If a branch is mispredicted, how many instructions would have to be flushed from the pipeline?

Q 2.2.1 Branches aren ‘t resolved until the ?????? stage (please write the stage label).

Q 2.2.2 Number of instructions that have to be flushed from the pipeline is =

</div>
</div>
<div class="layoutArea">
<div class="column">
Q

</div>
<div class="column">
3 Reordering Code to Avoid Pipeline Stalls

Consider the following code segment in C:

A=B+E; C=B+ F;

Here is the generated MIPS code for this segment, assuming all variables are

in memory and are addressable using relative addressing mode i.e. using offsets from register $t0:

lw $tl, 0($t0) lw $t2, 4($t0) add $t3, $tl,$t2 sw $t3, 12($t0) lw $t4, 8($t0) add $t5, $tl,$t4 SW $t5, 16($t0)

Find the hazards in the following code segment explain, and reorder the instructions to avoid any pipeline stalls.

</div>
</div>
</div>
