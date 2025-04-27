# cmpt225-assignment-1--word-lists-solved
**TO GET THIS SOLUTION VISIT:** [CMPT225 Assignment 1- Word Lists Solved](https://www.ankitcodinghub.com/product/cmpt225-assignment-1-word-lists-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120189&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT225 Assignment 1- Word Lists Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Your task is to create a class called Wordlist that stores words without any duplicates. When it’s done, you’ll be able to add and remove words from it, and also create an index of all its words in alphabetical order.

Wordlist must use a doubly-linked list as its underlying representation. Vectors, arrays, or other container data structures are not allowed, except for one case described below: the method get_sorted_index(), which returns a vector&lt;string*&gt;.

Getting Started

All the code you’ll submit for this assignment goes in Wordlist.h. Don’t put main in Wordlist.h. Instead, put main in a1_main.cpp. In main you should call the testing code for your Wordlist class.

Note You can download all the files for this assignment in a single .zip archive from the Github repository for the course. Click on the green “Code” button, and then click on “Download ZIP”.

Implement the Methods in Wordlist_base

Write your implementation of Wordlist in Wordlist.h. It must publicly inherit from Wordlist_base, and use the Node struct (given in Wordlist) to implement a doubly-linked list.

Wordlist.h has the class Wordlist where you should implement all the virtual methods listed in the Wordlist_base class (in Wordlist_base.h).

Most of the methods in Wordlist_base are virtual and abstract, and so you must write your own version of them in Wordlist. first_word() and last_word() have implementations that you cannot change.

Important!

Do not change Wordlist_base.h in any way: keep it exactly as-is.

Do not use vectors, arrays, or any other data structures in Wordlist.h. The one and only exception is the method get_sorted_index() that returns a vector&lt;string*&gt;.

Implement Constructors, and a Destructor

In addition to the virtual methods listed in Wordlist_base, in your Wordlist class write a default constructor that takes no parameters and creates an empty Wordlist object:

cpp // // Pre-condition: // none // Post-condition: // Creates an empty Wordlist object. // Performance: // It should always take a very small, constant amount of time. // Wordlist();

You would use it like this:

“`cpp Wordlist lst;

// … lst is an empty Wordlist object … “`

Write a copy constructor that takes another Wordlist as input, and initializes the new Wordlist to contain copies of all the strings in the other Wordlist. The copied Wordlist should not be modified in any way:

cpp // // Pre-condition: // other is a valid Wordlist object // Post-condition: // Creates a new Wordlist object that is a copy of other; other is not modified // in any way, and other and the new object do not share any values. If other // is frozen, then the new object is also frozen. // Performance: // The running-time should be proportional to the number of words in other. // Wordlist(const Wordlist&amp; other);

Write one more constructor that takes the name of a text file as input, and initializes the list by adding all the words in the file to the list. For simplicity, you can assume that the file is a text file that always exists:

cpp // // Pre-condition: // filename is the name of a text file that exists // Post-condition: // Creates a new Wordlist object that contains all the words in the file // filename. If the file contains duplicate words, then the new Wordlist // object will contain only one copy of each word. // Performance: // The number of calls to add_word should be proportional to the // length of other (or better). // Note: // For this constructor a “word” is defined as the string return by the // &gt;&gt; operator. See the read_from_terminal() function for example of how // to use &gt;&gt; to read words. // Wordlist(const string&amp; filename);

Write a destructor for Wordlist that de-allocates all the nodes in the list. Make sure to test this by running your program with valgrind (described below). Note that in Wordlist_base the destructor is called ~Wordlist_base(), while the one you write for Wordlist is called ~Wordlist().

Frozen and Unfrozen Wordlists

A Wordlist is either frozen or unfrozen. Initially, a Wordlist is unfrozen, and any method can be called on it.

When the get_sorted_index() method is called, the Wordlist automatically becomes frozen. This means that it can no longer be modified: calling add_word() or remove_word() on a frozen lists causes them to throw a runtime_error exception. All other methods work the same as on an unfrozen list.

The reason for this feature is that by freezing the list after calling get_sorted_index() we can guarantee that the pointers in the returned vector are always valid as long as the list still exists.

Note As you implement and test Wordlist, think about whether or not you believe this freezing feature is a good one. Maybe it is too inconvenient, or makes some code more complicated to write? But if you don’t use freezing, then how could you be sure that the pointers in the returned vector are always pointing to valid values?

Testing Your Code

You can use the read_from_terminal() function in a1_main.cpp to help test your code. For example, small.txt contains:

“` This is a test or is this a test?

“`

When you run:

“`cpp // …

void read_from_terminal() { Wordlist lst; string w; while (cin &gt;&gt; w) { lst.add_word(w); }

// print the words in sorted order

vector&lt;string *&gt; index = lst.get_sorted_index(); for (int i = 0; i &lt; index.size(); i++)

{

cout &lt;&lt; (i + 1) &lt;&lt; “. ” &lt;&lt; *index[i] &lt;&lt; endl; } }

int main() { read_from_terminal(); } “`

You should get this output:

â¯ ./a1_main &lt; small.txt 1. This 2. a 3. is 4. or 5. test 6. test? 7. this

Notice that case matters, e.g. “This” and “this” count as different words. Also, punctuation matters, e.g. “test” and “test?” are different.

Note Real life programs would likely strip out punctuation and perhaps ignore letter case. But in this assignment we want to count every word exactly as it appears in the file. This makes the code a littler simpler, and more consistent across students.

Here’s another example using the file sonnet30.txt:

bash â¯ ./a1_main &lt; sonnet30.txt 1. All 2. And 3. But 4. For 5. I 6. The 7. Then 8. When 9. Which 10. a 11. account 12. afresh 13. an 14. and 15. are 16. as 17. at 18. before. 19. can 20. cancellâ€™d 21. dateless 22.

dear 23. deathâ€™s 24. drown 25. end. 26. expense 27. eye, 28. flow, 29. fore-bemoaned 30. foregone, 31.

friend, 32. friends 33. from 34. grievances 35. grieve 36. heavily 37. hid 38. if 39. in 40. lack 41. long 42. losses 43. loveâ€™s 44. many 45. moan 46. moan, 47. my 48. new 49. night, 50. not 51. of 52. old 53. on 54. oâ€™er 55. paid 56. past, 57. pay 58. precious 59. remembrance 60. restorâ€™d 61. sad 62. sessions 63. sigh 64. sight: 65. silent 66. since 67. sorrows 68. sought, 69. summon 70. sweet 71. tell 72. the 73. thee, 74. thing 75. things 76. think 77. thought 78. timeâ€™s 79. to 80. unused 81. up 82. vanishâ€™d 83. wail 84. waste: 85. weep 86. while 87. with 88. woe 89. woe, 90. woes

Checking output manually is hard to do with long lists, so here is another handy trick:

bash â¯ ./a1_main &lt; sonnet30.txt &gt; sonnet30_sorted_output.txt

The expression &gt; sonnet30_sorted_output.txt re-directs everything a1_main writes to cout into the file sonnet30_sorted_output.txt. You can view sonnet30_sorted_output.txt in a text editor, or by running these commands: “`bash â¯ cat sonnet30_sorted_output.txt … contents of sonnet30_sorted_output.txt … â¯ more sonnet30_sorted_output.txt … contents of sonnet30_sorted_output.txt a page at a time … “`

Another useful command is diff fileA fileB, which finds differences between text files fileA and fileB. You can use it to check the output of your program. For example, if you run sonnet30.txt through read_from_terminal() and save the output to my_sonnet30_sorted_output.txt, then you can check your output like this:

“`bash diff my_sonnet30_sorted_output.txt sonnet30_sorted_output.txt

“`

If the files have the same content, then nothing is printed. Otherwise, all differences are printed.

Here’s one more example. The file tiny_shakespeare.txt has over 200,000 words: bash â¯ ./a1_main &lt; tiny_shakespeare.txt &gt; tiny_shakespeare_sorted_output.txt

The file tiny_shakespeare_sorted_output.txt lists 25,670 unique words in alphabetical order.

What to Submit

When you’re done, submit just your Wordlist.h on Canvas, and nothing else.

The marker will use their own a1_main.cpp that #includes your Wordlist.h and will test the methods in it.

The marker will compile their code on Ubuntu Linux using makefile like this:

“`bash

make a1_main g++ -O3 -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g a1_main.cpp -o a1_main “`

A copy of Wordlist_base.h will be in the same folder as your Wordlist.h when it’s compiled.

Important The compilation command is very strict: no warnings, errors, or unused variables are allowed. Make sure to compile your code with this command before submitting it.

Grading

The marker will test the correctness of your code on data you have not seen before, and they will also test individual method calls using test functions you have not seen.

They will run your program with valgrind to check for memory leaks and other memory errors, e.g.:

“`bash

==13731== in use at exit: 0 bytes in 0 blocks ==13731== total heap usage: 10 allocs, 10 frees, 78,160 bytes allocated ==13731== ==13731== All heap blocks were freed — no leaks are possible ==13731== ==13731== For lists of detected and suppressed errors, rerun with: -s ==13731== ERROR SUMMARY: 0 errors from 0 contexts (suppressed: 0 from 0) “`

Be sure to test your program thoroughly with valgrind before submitting it.

valgrind should report “no leaks are possible”, and should not print any other errors. Note that it is possible for your program to have a memory leak that does not occur on some runs of your program, so be sure to test your program thoroughly.

Marking Scheme

All code is sensibly and consistently indented, and all lines are 100 characters in length, or less. Hint: In the Linux command-line you can print all the lines in a file with more than 100 characters with this command (the initial &gt; is the prompt character, so don’t type it):

“`bash awk ‘length &gt; 100’ some_file.cpp “`

If this prints nothing, then the file has no lines over 100 characters long.

Whitespace is used to group related pieces of a code to make it easier for humans to read. All whitespace has a purpose.

Variable and function names are self-descriptive.

Appropriate features of C++ are used, as discussed in the course. Note If you use a feature that we haven’t discussed in class, you must explain it in a comment, even if you think it’s obvious.

Comments are used when needed to explain code whose purpose is not obvious from the code itself. There should be no commented-out code from previous versions.

Deductions

change Node in a way, if you modify anything in Wordlist_base, or if you use a vector, array, or any other data structure other than a list; the one exception is for the method get_sorted_index() that returns a vector&lt;string*&gt; have no statement of originality, or it’s modified in any way. at least -1 mark if your file has an incorrect name, or you submit it in an incorrect format, etc.; possibly multiple deductions if there are multiple problems

at least -1 mark if you submit a non-working file

if the marker can easily fix your file and make it work, then there is only a small deduction if the marker has to spend a lot of time fixing your file, then there is a larger deduction; if they can’t make it work, then they you will get 0

Hints

Test as you go! Don’t wait until after you write all the code to test it. When you write a method, add a few test cases for it, e.g. using assert or ifstatements.
