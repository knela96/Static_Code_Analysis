
Hi my name is Èric Canela and I'm a student of UPC Tech Talent Center from Barcelona. Today I will introduce you an interesting and useful guide about Static Analysis, and explain why you should use it when developming any game or application.

When we are developing a program there are a lot of pressure and sometimes the timelines are too heavy, and the developers can’t ensure a good quality on the code, creating more bugs and slowing down de current development. To ensure that this do not happen, exist some amazing tools to make it easier and avoid possible problems in the future.

<div style="text-align:center"><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/StaticAnalysis.png" width="500px"/></div>

# Static Code Analisis
First of all let’s talk about the concept of Static Code Analysis.

It is a method of debugging with a computer program by examining our code without having to run the program. This process provides us some feedback to find programming faults and display it to the developers. 
This analysis is made against a set of multiple coding guidelines to ensure the quality on the code with the current standards on the industry. 

<table>
<tbody>
<tr>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Misra.png" width="100px" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/iso.png" width="100px" /></td>
</tr>
<tr>
<td><em>Misra</em></td>
<td><em>ISO26262</em></td>
</tr>
</tbody>
</table>
_Quality Standards_

# TECHNIQUES
It uses different methods to detect these errors, which are:
- **Pattern-Based Static Analysis:** It looks for predefined patterns in the code and detects if they are used and reports them as a possible error.
- **Data Flow Analysis:** It checks for problematic constructions against a set of rules and detect errors such as null pointers and buffer overflows.
- **Control Flow Analysis:** It is an abstract representation on the software that aims to determine the order of instructions separated in blocks and the execution order.
- **Taint Analysis** Detects variables that could be modifiable externally, and be used in functions that could compromise the security of the application, E.g. SQL injection.
# ADVANTAGES vs. DISADVANTAGES
<table width="0">
<tbody>
<tr>
<td colspan="2" width="756">
<span style="color:blue"><p><strong>Static Code Analysis</strong></p></span>
  </td>
</tr>
<tr>
<td width="392">
<p><strong><em>Advantages</strong></em></p>
</td>
<td width="364">
<p><strong><em>Limitations</strong></em></p>
</td>
</tr>
<tr>
<td width="392">
<p>It can find weaknesses in the code at the exact location.</p>
</td>
<td width="364">
<p>Time-consuming if conducted manually.</p>
</td>
</tr>
<tr>
<td width="392">
<p>Easy to use for developers trained in that programing language</p>
</td>
<td width="364">
<p>Production of false positives and false negatives.</p>
</td>
</tr>
<tr>
<td width="392">
<p>Problems detected earlier in the production phase</p>
</td>
<td width="364">
<p>Need too much personal to do the tests</p>
</td>
</tr>
<tr>
<td width="392">
<p>Allow to fix the problems earlier</p>
</td>
<td width="364">
<p>Do not find all the problems</p>
</td>
</tr>
<tr>
<td width="392">
<p>Fast development cycle if automated tools are used.</p>
</td>
<td width="364">
<p>Only detect problems stipulated by the quality guidelines</p>
</td>
</tr>
<tr>
<td width="392">
<p>Unreachable code</p>
</td>
<td width="364">
<p>Do not find vulnerabilities in the runtime environment</p>
</td>
</tr>
<tr>
<td width="392">
<p>Variable Use(undeclared, unused)</p>
</td>
<td width="364">&nbsp;</td>
</tr>
<tr>
<td width="392">
<p>Uncalled functions</p>
</td>
<td width="364">&nbsp;</td>
</tr>
</tbody>
</table>

# WHEN SHOULD WE USE IT?
During an early stage, the creation phase, just before the unit tests. Using it in this stage allow us to detect a possible vulnerability or bug that can cause a future problem and be harder to remove it, if we had find it in an early stage.

A peer developer, someone other than the developer who wrote the code, should do these tests.

# WHY SHOULD I USE IT?

 - **Reliability**
 - **Maintainability**
 - **Portability**
 - **Efficiency**

# Available Tools
