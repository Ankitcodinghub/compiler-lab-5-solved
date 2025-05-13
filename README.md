# compiler-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [Compiler Lab 5 Solved](https://www.ankitcodinghub.com/product/compiler-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91897&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Compiler Lab 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
NOTE: Refer lecture notes, Chapter 4 (until sec 4.4).

For each of the grammars, perform the following steps and implement a predictive

LL(1) parser.

STEP (1) Manually transform the grammar to LL(1) (without affecting/changing the language) by (remove left-recursion etc). As discussed, you may have to introduce new non-terminals in the process of transforming the grammar to LL(1). Write the LL(1) grammar in a file called “grammarLL.txt”.

OPTIONAL: You may implement functions/programs to perform some of the transformation steps such as elimination of left-recursion (which takes any grammar as input and returns the transformed grammar as output).

STEP (2) For the LL(1) grammar obtained from step 1, manually compute the FIRST() set of all symbols in the grammar, and also compute the FOLLOW() set for all non-terminals. Store this information in another file e.g., file named “First- Follow.txt”.

OPTIONAL: You may implement a program for computing FIRST(), FOLLOW() sets for any grammar given as input.

STEP (3) Write a C program to implement a table driven predictive parser for the LL(1) grammar obtained in step 1. Your implementation should contain two different modules/functions. The first module should construct the LL(1) parsing table from the (a) input grammar (“GrammarLL.txt”) and (b) computed FIRST, FOLLOW sets (“First-Follow.txt”). You may represent the parse table either in a file or in a temporary data structure. The second module, take an input expression and parses it using the parse table. In case the input expression satisfies the given grammar, the output of the program should print “Accepted” along with the ordered sequence of productions (leftmost derivation). In the event of errors, provide reporting of both lexical and syntactic errors.

NOTE: Use Lex/Flex to generate a lexical analyzer for recognizing tokens.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Submission: Along with the source-code (step 3), for each example input grammar, submit files “grammarLL.txt”. and “First-Follow.txt”. Provide additional README file with other information (e.g., instructions to run, sample test inputs considered).

——————————————————————————————————-

Example grammars are given below. Please note that only the steps that need to be done manually (steps 1, and 2) should be redone when you consider a different grammar.

Grammar 1:

Grammar 2:

For the following grammar,

the non-terminals are

N = { AE, BE, D, DL, E, F, ES, IOS, IS, NE, P, PE, RE, S, SL, T, TY, VL, WS },

the terminals are

T = { + , −, ∗, /, =, &lt;, &gt;, (, ), {, }, :=, ; , and, else, end, ic, id, if, int, do, fc, float, not, or, print, prog, scan, str, then, while },

Most of the terminals are self-explanatory (id is an (identifier), ic is an integer constant, fc is a floating-point constant, str is a string of characters, := is an assignment etc.

The production rules are given in the next page (the start symbol is P).

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
P → prog DL SL end DL → D DL | ε

D → TY VL ;

TY → int | float

VL → id VL | id

SL → S SL | ε

S → ES | IS | WS | IOS ES → id := E ;

IS → if BE then SL end |

if BE then SL else SL end WS → while BE do SL end

IOS → print PE | scan id

PE → E | str

BE → BE or AE | AE

AE → AE and NE | NE

NE → not NE | { BE } | RE

RE → E = E | E &lt; E | E &gt; E

E →E + T|E− T |T

T → T ∗F | T / F | F

F → ( E ) | id | ic | fc

</div>
</div>
</div>
