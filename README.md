
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

Now that we know what is the Static Analysis, we might think about which tools there are on the market. We can find Premium tools, which will give us more features and support by a moderate prize, or in the other hand, Open Source and Free tools that might be more limited. 

These are some of the best tools you can find:

### Premium
<table>
<tbody>
<tr>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Lint.jpg" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/helix.png" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/codesonar.png" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/visual.png" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/goanna.jpg" alt="" width="120" /></td>
</tr>
<tr>
<td><em>PC-LINT</em></td>
<td><em>Helix QAC</em></td>
<td><em>Code Sonar</em></td>
<td><em>Visual Studio</em></td>
<td><em>Goanna</em></td>
</tr>
</tbody>
</table>

### Free

<table>
<tbody>
<tr>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/cppcheck.png" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/cpplint.png" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Parasoft.png" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/eclipse.png" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/frama.jpg" alt="" width="120" /></td>
<td><img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/clang.png" alt="" width="120" /></td>
</tr>
<tr>
<td><em>Cpp Check</em></td>
<td><em>BSS Lint</em></td>
<td><em>Parasoft C/C++ test</em></td>
<td><em>Eclipse</em></td>
<td><em>Frama-C</em></td>
<td><em>Clang</em></td>
</tr>
</tbody>
</table>

## WHICH TOOL SHOULD I SELECT?
The tools above are compatible with C/C++, and other programming languages. Also if you do a little of research, you’ll find a lot more but probably you might ask “Which tool should I select?”.

Here are some basic tips for you, to select the best one for your project:
- Must support your programming language.
- Which and how many vulnerabilities can detect.
- Can it be integrated into the developer's IDE?
- How much it cost the tool, is it Free?
- Does it support Object-oriented programming?

## PROCEDURE OF USAGE
<img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Diagram.png" alt="" height="800" />

## STATIC ANALYSIS TOOL

We are going to use CppChecker as the static code analysis tool. This is because the low rate on finding possible false positives and negatives. 

We can use between two versions:

### Add-on for Visual Studio 
<img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/VS_Addon.JPG" alt=""/>

The analyzer is thought to be used in the command line, but thanks to a plugin for Visual Studio, we will be able to see it with the interface of the Visual Studio and interactuate with the errors detected.

### CppCheck GUI
<img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Installation1.JPG" alt=""/>

With the GUI version, it will allow us to see everything much better with a clean interface. But this version has a big problem, the current version hasn't implemented all functionalities of the command line or plugin version. Even that, it will work for the main purpose of identifying the errors in the code.

## Configuration
Follow these steps to configure the Add-on for Visual Studio or the GUI version:

### Add-on for Visual Studio 

_To use the addon first you will have to download CppCheck and install on your computer_
#### Step 1
Download and Install the .exe from the [Official Website](http://cppcheck.sourceforge.net/), compatible with the version of your SO.
#### Step 2
Download the add-on from this [ Repository link](https://github.com/VioletGiraffe/cppcheck-vs-addin/releases/tag/1.3.6) and install it.
#### Step 3
Open Visual Studio and you will notice that has been added new features in the "_Tool_" section.
Click on the _Tools -> Cppcheck settings_

<img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Installation_vs1.JPG" alt=""/>

#### Step 4
It will appear the next screen, set the same configuration as the next image.

<img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Installation_vs2.JPG" alt=""/>

#### Step 5
Execute the first scan on your project by clicking on "_Tools -> Check current project with cppcheck_"
You will see that has appeared a new tab at the bottom named "_Cppcheck analysis results_". Here will appear the warnings and errors that you have in your code and has to be fixed.

<img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/VS_Addon.JPG" alt=""/>

#### Step 6
To add filters and avoid some errors to appear, you only need to _right-click_ on the message and it will appear some options, select the one that you need.

<img src="https://raw.githubusercontent.com/knela96/Static-Code-Analysis/master/Images/Installation_vs3.JPG" alt=""/>
