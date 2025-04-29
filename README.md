# cs1332-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS1332 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs1332-important-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109366&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1332  Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. All submitted code must compile under JDK 8. This includes unused code, so don’t submit extra files that don’t compile. Any compile errors will result in a 0.

2. Do not include any package declarations in your classes.

3. Do not change any existing class headers, constructors, instance/global variables, or method signatures. For example, do not add throws to the method headers since they are not necessary.

4. Do not add additional public methods.

5. Do not use anything that would trivialize the assignment. (e.g. don’t import/use java.util.ArrayList for an ArrayList assignment. Ask if you are unsure.)

6. Always be very conscious of efficiency. Even if your method is to be O(n), traversing the structure multiple times is considered inefficient unless that is absolutely required (and that case is extremely rare).

7. You must submit your source code, the .java files, not the compiled .class files.

8. Only the last submission will be graded. Make sure your last submission has all required files. Resubmitting will void all previous submissions.

9. After you submit your files, redownload them and run them to make sure they are what you intended to submit. You are responsible if you submit the wrong files.

AVL

You are to code an AVL, which is a special type of binary search tree. It must follow the same rules as binary search trees: each node has 0-2 children, all data in the node’s left subtree is less than the parent node’s data, and all data in the node’s right subtree is greater than the parent node’s data. However, a AVL differs from a BST with its self-balancing rotations, which you must implement.

All methods in the AVL that are not O(1) must be implemented completely recursively. This includes all helper methods. Good recursion with simple, focused states is strongly encouraged. For methods that change the structure of the tree in some way, we highly recommend you use a technique taught in class called pointer reinforcement.

The AVL will have two constructors: a no-argument constructor (which should initialize an empty tree), and a constructor that takes in a collection of data to be added to the tree, and initializes the tree with this collection of data.

Balancing

Each node has two additional instance variables, height and balanceFactor. The height variable should represent the height of the node. If you recall, a node’s height is max(left node’s height, right node’s height) + 1 where the height of a null is -1. The balance factor of a node should be equal to its left child’s height minus its right child’s height. Since we’ve stored this information in each node, you no longer need to recursively compute it.

The tree should rotate appropriately to make sure it’s always balanced. A tree is balanced if every node’s balance factor is either -1, 0, or 1. Keep in mind that you will have to update the balancing information stored in the nodes on the way back up the tree after modifying the tree; the variables are not updated automatically.

Important Notes

Here are a few notes to keep in mind when switching from BST to AVL:

1. For two child remove, use the successor, not predecessor.

2. After every change to the tree, make sure to update height and balance factor fields of all nodes whose subtrees have been modified.

3. Make sure the height method is O(1).

Grading

Here is the grading breakdown for the assignment. There are various deductions not listed that are incurred when breaking the rules listed in this PDF, and in other various circumstances.

Methods:

constructor 4pts

add 19pts

remove 24pts

get 5pts

contains 5pts

height 2pts

clear 2pts

predecessor 8pts

kSmallest 6pts

Other:

Checkstyle 10pts

Efficiency 15pts

Total: 100pts

JUnits

If you need help on running JUnits, there is a guide, available on Canvas under Files, to help you run JUnits on the command line or in IntelliJ.

Style and Formatting

Javadocs

Vulgar/Obscene Language

Any submission that contains profanity, vulgar, or obscene language will receive an automatic zero on the assignment. This policy applies not only to comments/javadocs, but also things like variable names. Exceptions

When throwing exceptions, you must include a message by passing in a String as a parameter. The message must be useful and tell the user what went wrong. “Error”, “BAD THING HAPPENED”, and “fail” are not good messages. The name of the exception itself is not a good message. For example:

Bad: throw new IndexOutOfBoundsException(‘‘Index is out of bounds.’’);

Good: throw new IllegalArgumentException(‘‘Cannot insert null data into data structure.’’);

Generics

If available, use the generic type of the class; do not use the raw type of the class. For example, use new LinkedList&lt;Integer&gt;() instead of new LinkedList(). Using the raw type of the class will result in a penalty.

Forbidden Statements

• package

• System.arraycopy()

• clone()

• assert()

• Arrays class

• Array class

• Thread class

• Collections class

• Collection.toArray()

• Reflection APIs

• Inner or nested classes

• Lambda Expressions

• Method References (using the :: operator to obtain a reference to a method)

If you’re not sure on whether you can use something, and it’s not mentioned here or anywhere else in the homework files, just ask.

Debug print statements are fine, but nothing should be printed when we run your code. We expect clean runs – printing to the console when we’re grading will result in a penalty. If you submit these, we will take off points.

Provided

The following file(s) have been provided to you. There are several, but we’ve noted the ones to edit.

1. AVL.java

This is the class in which you will implement the AVL. Feel free to add private helper methods but do not add any new public methods, inner/nested classes, instance variables, or static variables.

2. AVLNode.java

This class represents a single node in the tree. It encapsulates the data, the left and right references, the height, and the balanceFactor. Do not alter this file.

3. AVLStudentTest.java

This is the test class that contains a set of tests covering the basic operations on the AVL class. It is not intended to be exhaustive and does not guarantee any type of grade. Write your own tests to ensure you cover all edge cases.

Deliverables

You must submit all of the following file(s). Make sure all file(s) listed below are in each submission, as only the last submission will be graded. Make sure the filename(s) matches the filename(s) below, and that only the following file(s) are present. The only exception is that Canvas will automatically append a -n depending on the submission number to the file name(s). This is expected and will be handled by the TAs when grading as long as the file name(s) before this add-on matches what is shown below. If you resubmit, be sure only one copy of each file is present in the submission. If there are multiple files, do not zip up the files before submitting; submit them all as separate files.

Once submitted, double check that it has uploaded properly on Canvas. To do this, download your uploaded file(s) to a new folder, copy over the support file(s), recompile, and run. It is your sole responsibility to re-test your submission and discover editing oddities, upload issues, etc.

1. AVL.java
