Python fundamentals - Functions

file:///E:/ScrapeBook/Python%20Fundamentals/data/20190218223949/index.html

Most other programming languages \(for example, Java and C++\) require a special function, called **main\(\)**, which tells the operating system what code to execute when a program is invoked. This is not necessary in Python, but you will find that it is a good and logical way to structure a program.

**Before the Python interpreter executes our program, it defines a few special variables. One of them is \_\_name\_\_, and it will automatically be set to \_\_main\_\_ if our program will be executed by itself, in a standalone fashion.**

**However, if our program will be imported by another program, then \_\_name\_\_ will be set to the name of that other program. We can easily determine whether the program is standalone or is being used by another program as an import. Based on that, we can decide to either execute or exclude some of the code in a program.**



def summation\(first, second\):

 total = first + second

 return total

def main\(\):

 outer\_total = summation\(10, 20\) \* 2

 print\("Double the total is " + str\(outer\_total\)\)



if \_\_name\_\_ == "\_\_main\_\_":

 main\(\)

Without the **if \_\_name\_ == \_\_main\_\_** check and declaration, our script would still be executable. All we would have to do is declare or call our **summation\(\)** function.

In Python, there is nothing special about the name **main**. We could have called this function anything that we wanted. We chose **main** to be consistent with some of the other languages.

