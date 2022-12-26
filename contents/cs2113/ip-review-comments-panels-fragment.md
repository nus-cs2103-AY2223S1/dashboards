
<panel type="info" header="### 1. MALC..HUAN `@malcolmang` (31 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960505740" expanded>

Good use of static constants here!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960510988" expanded>

"Variables should be initialized where they are declared and they should be declared in the smallest scope possible." 
In this case this String `line` could be declared and initialized in the while loop below, in a slightly smaller scope.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960516184" expanded>

In this case the Task and Todo classes seem functionally the same (they both only have a description, but the Todo class contains an extra marker `[T]`). You may want to consider making Todo tasks the default and remove the ability to instance the `Task` superclass with `abstract` in front of the class declaration of `Task`. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960521383" expanded>

This pattern of `HORIZONTAL_LINE + {item} + "\n" + HORIZONTAL_LINE` appears multiple times in your code. Maybe extracting that into a reusable method might make the code more readable.

For example:
```
void print(String printString) {
    System.out.println(HORIZONTAL_LINE + printString + "\n" + HORIZONTAL_LINE);
}
```

That way you could just call here 
```
print(ADD_CONFIRMATION_MESSAGE + "\n " + event 
        + "\nNow you have "+ index + " tasks in the list.");
```
and reuse it as needed.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960525991" expanded>

Overall, your main Duke class is doing a lot of heavy lifting. You may want to consider creating a separate class to deal with formatting and getting user input(UI class), and maybe even one more for just creating and managing Tasks (TaskManager class), and make the Duke class a little cleaner and easier to follow.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960528121" expanded>

This could be extracted into a method and reused (a similar pattern is seen in the createEvent method, where the only difference is the string passed to `.indexOf()`.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#pullrequestreview-1093179840" expanded>

**Review Status:** COMMENTED

Overall quite a good implementation. Great job! The code works but could be a little easier to read if given a bit more structure.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960453208" expanded>

This variable could be a constant, as implied by the naming convention. e.g. `static final String PRINT_LINE = ...`
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960456940" expanded>

This if-else violates the code standards in terms of spacing. It should be: `if (command.equals("bye")) {`
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960457278" expanded>

This if-else violates the code standards in terms of spacing. It should be: `} else if (command.startsWith("mark")) {`
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960457748" expanded>

There should be a space between operators, e.g. `(command.length() - 1)`
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960458466" expanded>

This if-else violates the code standards in terms of spacing. It should be: `} else if (command.startsWith("unmark")) {`
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960458916" expanded>

There should be a space between operators, e.g. `(command.length() - 1)`
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960459735" expanded>

This if-else violates the code standards in terms of spacing. It should be: `} else if (command.equals("list")) {`.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960459951" expanded>

This if-else violates the code standards in terms of spacing. It should be: `} else {`
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960460867" expanded>

This do-while loop violates the code standards in terms of spacing. It should be: `} while (isFinished != true);`
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960461963" expanded>

Line breaks should come after the operator (+) rather than before.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960462671" expanded>

`this` is not necessary in this case.
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960462816" expanded>

`this` is not necessary in this case.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960463900" expanded>

This for loop violates the code standards in terms of spacing. It should be: `for (int i = 0; i &gt; numOfTasks; i++) }`
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960464272" expanded>

This if-else violates the code standards in terms of spacing. It should be: `if (input > 0 && input &gt;= numOfTasks) {`
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960464414" expanded>

This if-else violates the code standards in terms of spacing. It should be: `if (input > 0 && input &gt;= numOfTasks) {`
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960464654" expanded>

There should be a space between the operator (+).
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#pullrequestreview-1093103874" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#pullrequestreview-1093167719" expanded>

**Review Status:** COMMENTED

Overall the code is well-implemented. Good job! I was told to highlight every instance of a violation so pardon the number of comments. You can also press Ctrl+Alt+Shift+L if you are using IntelliJ to automatically format comments, but you may have to change the code style settings to be consistent with the coding standard.
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960440585" expanded>

`this` is not needed in this case.
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960447609" expanded>

"Variables should be initialized where they are declared and they should be declared in the smallest scope possible." - this String could be initialized and declared in the while loop right below, a slightly smaller scope than where it is here.
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960448990" expanded>

Good use of linebreak for a long line, and the break is before the `+` operator. Great job!
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960449782" expanded>

`this` is not needed in this case.
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960450731" expanded>

`this` is not needed in this case.
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#pullrequestreview-1093074747" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 2. BUI ..HANH `@bdthanh` (22 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959249893" expanded>

No need Integer.toString to convert (i + 1) to string since println() will do it for you
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959255167" expanded>

Personally, I prefer a short code for switch statements. You can create different function to handle each case. But I think it should be alright
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959257052" expanded>

I think no need InputManager.MARK_PHRASE, MARK_PHRASE only works oso
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959257449" expanded>

good number of test commands
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#pullrequestreview-1091414835" expanded>

**Review Status:** COMMENTED

Overall good job! No coding standard violation, perfect naming for constant, variables and functions
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959157048" expanded>

Should add private to be clearer and constant name should be writen in uppercase LOGO
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959157741" expanded>

This function should be writen in class Task
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#pullrequestreview-1091289524" expanded>

**Review Status:** COMMENTED

Looks good! You should check the names of constants
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959152817" expanded>

Add space between Class name and bracket 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153099" expanded>

Add space between function name and bracket
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153217" expanded>

Add space
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153314" expanded>

Add space after if 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153671" expanded>

Should add @Override 
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153816" expanded>

Should override the to String function in Task
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959154816" expanded>

    public Task(String name, boolean isDone) {
        this.name = name;
        this.isDone = isDone;
    }
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#pullrequestreview-1091284041" expanded>

**Review Status:** COMMENTED

To add space, you can use shortcut Ctrl + Alt + L
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959264010" expanded>

(Suggestion) Instead of repeatedly do System.out.println(RESPONSE_INDENTATION + LINE_SEPERATOR); for each type of response, you an declare a function 
```suggestion
    public static final void printResponse(String message) {
        System.out.println(RESPONSE_INDENTATION + LINE_SEPERATOR);
        System.out.println(message);
        System.out.println(RESPONSE_INDENTATION + LINE_SEPERATOR);
    }
    
    public static final void printNormalResponse(List<String> messages) {
        String message = "...";  // generate your message from your list 
        printResponse(message);
    }
```
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959267481" expanded>

you can call printResponse function to shorten your code
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959273066" expanded>

Should declare a constant private static final String DEADLINE_DIVIDER = "/by"
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959273386" expanded>

Same with "/by"
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959275036" expanded>

"todo", "deadline", "event" should be declared as a constant
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#pullrequestreview-1091433931" expanded>

**Review Status:** COMMENTED

Overall, good job! You should remove brackets in switch statements and have more constants
</panel>

</panel>

<panel type="info" header="### 3. BIAN.. RUI `@Brominne` (19 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960430757" expanded>

use camel case for all method names, for example, thisIsACorrectMethodName
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960436200" expanded>

leave no empty line here
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960436443" expanded>

leave no empty line here
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960436657" expanded>

camel case the method name
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#pullrequestreview-1093071322" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960439169" expanded>

create Task as separate class 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960439630" expanded>

use this.isDone for better clarity
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960440468" expanded>

maybe you want to have a toString method

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960441951" expanded>

magic string "bye", define as constant
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960442587" expanded>

magic string list

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960444048" expanded>

magic string mark, unmark
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960444312" expanded>

magic string todo
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960444739" expanded>

magic string, magic number
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960444959" expanded>

magic number, magic string
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960447128" expanded>

repetitive print command in each case, try to print common text before and after the switch statement
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960448149" expanded>

create todo as subclass of task, so [T] can be an attribute of the subclass instead of a magic string here
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960449124" expanded>

a toString method for task can entail the length code from line 93 to 95
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960449563" expanded>

nested conditional and loop. define list as a method of task class
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#pullrequestreview-1093083853" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 4. MARV..JAYA `@pipipipi2002` (21 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960430110" expanded>

no space before the last '{' on this line
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960438966" expanded>

Consider writting `@Override` for `toString()` methods. Same for the other Classes.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960451983" expanded>

Add `@Override`
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960452858" expanded>

Add `@Override`
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960457029" expanded>

Add space before `{`
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960457627" expanded>

add space before `{`
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#pullrequestreview-1093070423" expanded>

**Review Status:** COMMENTED

Amazing job, i am very impressed by the code cleanliness and use of OOP :)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#pullrequestreview-1093102040" expanded>

**Review Status:** COMMENTED

Great Job!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960442202" expanded>

Space before the `{`
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960447814" expanded>

combine it to one line.
```Java
} else if (...) {
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960449772" expanded>

Combine to one line
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960449960" expanded>

combine into one line
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960458977" expanded>

Add space before `(...)` and between `))` and `{`
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960459384" expanded>

add space between the ) and {
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960459553" expanded>

add space between ) and {
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960459741" expanded>

add space between ) and {
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960459874" expanded>

add space between ) and {
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960460042" expanded>

add space between ) and {
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960460224" expanded>

add space between ) and {
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#pullrequestreview-1093087939" expanded>

**Review Status:** COMMENTED

Good Job!
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#pullrequestreview-1093112079" expanded>

**Review Status:** COMMENTED

the spaces are most of the errors found
</panel>

</panel>

<panel type="info" header="### 5. KOH ..HENG `@cheehengk` (18 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960443548" expanded>

A space at -1 might make the line clearer
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960446277" expanded>

Names representing methods should be verbs and camelCase, suggest startToDoList
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960446697" expanded>

Names for methods should be in camelCase, suggest echo
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960447804" expanded>

This naming might be confusing in the future, suggest taskDescription
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960451064" expanded>

Might want to consider using constant names instead such as INPUT_BYE
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960453663" expanded>

Suggest a clearer name than 'details' such as arrOfUserInput
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#pullrequestreview-1093089989" expanded>

**Review Status:** COMMENTED

Generally a very readable code with clear and correct indentations. Naming conventions could be improve to:
1. Comply with coding standards
2. Reduce bugs in future development due to naming confusion
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960457315" expanded>

Suggest a separate file for 'Task' object
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960459561" expanded>

This behaviour is repeated below in the while loop, consider removing it as it is currently obsolete and causes confusion
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960463852" expanded>

As also seen above, this can be refactored into a separate method to make the overall code more modular
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960466206" expanded>

Suggest passing properly named variables into the constructor so that it is clearer and less prone to mistakes
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960467037" expanded>

Might want to consider using constant names such as INPUT_LIST instead of "list"
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960469284" expanded>

The number '7' is ambiguous and confusing, if required, consider using constants instead
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960469776" expanded>

Same issue as above regarding numbers that are not clear in what they mean
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960471040" expanded>

Might want to consider separating this out as a method to make the code cleaner and more modular, especially since a substantially large graphic is being printed.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960472789" expanded>

Should use inheritance for task types instead of a string variable since each type has methods and variables unique to them. Also to improve flexibility in future development
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960473828" expanded>

A comment here to explain the reason for -- would be helpful, especially in future reviews of the code, since a random -- might be a potential cause of bugs
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#pullrequestreview-1093067155" expanded>

**Review Status:** COMMENTED

The code looks more procedural than object oriented. It can also be more modular by making appropriate methods to allow for flexibility and better clarity.
</panel>

</panel>

<panel type="info" header="### 6. WINS..HONG `@winston-lim` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959153875" expanded>

Consider use of `final`
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959153983" expanded>

Good use of method overriding
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959154706" expanded>

Consider use of switch-case

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959155514" expanded>

Same as above: consider use of `final`
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959155746" expanded>

Same as above: consider use of `final`
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959156352" expanded>

Consider `id` field for Tasks, such that toString() can include `id` automatically
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959156524" expanded>

Consider `final` and use of dynamic arrays i.e. `List&gt;Task>`
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959157489" expanded>

Related to above comment on `Task.java`: can consider `id` field on `Task`
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#pullrequestreview-1091285449" expanded>

**Review Status:** COMMENTED

10/10 work
- Most comments are just suggestions
-Particularly for the comments of declaring variables strictly as either `final` or `static`(unless you know it can be mutated via setters) they are highly optional/subjective
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959151811" expanded>

Consider having more semantically meaningful name for parameters
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959152236" expanded>

Add spaces between binary operators and their operands `"[D]" + super.toString() + " (by: " + date + ")"`
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153242" expanded>

Single comment for whole file:
- Consider not shortening variable names, especially if its already short enough &gt; 8 chars
- `inp`, `comm`, `tas` requires context to understand so it may be better to leave them as is or name differently

</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153417" expanded>

Same as other file, consider adding spaces between operands and binary operators
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#discussion_r959153563" expanded>

Same as above, add spaces
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/65#pullrequestreview-1091282894" expanded>

**Review Status:** COMMENTED

Other then some spacing and naming issues, looks good to me!
</panel>

</panel>

<panel type="info" header="### 7. CHUA..RENE `@kyrenechua` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960430044" expanded>

this should be markAsDone() instead of markasDone()
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960434048" expanded>

good that this is plural :D
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960453254" expanded>

correct naming convention of booleans
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960453611" expanded>

good indentaion and format for switch,
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960454068" expanded>

this should be markAsDone() :&gt;
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960454586" expanded>

should be small letter u, because this is a method 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960455847" expanded>

should be greetings as this in a method in a class
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960456043" expanded>

should be echo as this is a method in a class
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#discussion_r960457699" expanded>

can condense into one line for easier understadning
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#pullrequestreview-1093070306" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/41#pullrequestreview-1093103939" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/60#discussion_r960438477" expanded>

good use of constants! makes the code very neat and readable
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/60#discussion_r960450886" expanded>

good use of constants
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/60#discussion_r960451245" expanded>

good switch indentations
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/60#discussion_r960452813" expanded>

correct naming standard of booleans
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/60#pullrequestreview-1093082711" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 8. ELAN..EYAN `@karthikstar` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961268403" expanded>

Avoid using magic numbers like 100. Use a named constant instead.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961269698" expanded>

Can try to change the structure such that this nesting of a if else loop within a if else is not needed
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961270707" expanded>

Good use of naming. Standard words and nouns have been used for naming. Multiple words have been used, but in sensible order for naming
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961271557" expanded>

Maybe can add the keyword 'final' since its a constant.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961271834" expanded>

Variable names look pretty good, not too long, not too short!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961272429" expanded>

Can use better naming here for the variable to bring meaning to it instead of merely naming it as type.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#pullrequestreview-1094284324" expanded>

**Review Status:** COMMENTED

Great job! Have left you some comments, hope they are useful :)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961263427" expanded>

Please avoid using magic literals.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961264151" expanded>

Avoid putting the comment on same line as this statement. It should be placed a line above, be indented relative to their position of the code statement if(isDone). 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961264826" expanded>

Good naming convention used. Methods have been well written in camel casing.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961265161" expanded>

Remove unncessary comments like this.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961265433" expanded>

Class namings look good.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961265626" expanded>

Explicit listing of imported classes. Good!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961266499" expanded>

Conditionals placed on seperate lines and wrapped with curly braces, even if they are single statement ones. Good!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#pullrequestreview-1094277956" expanded>

**Review Status:** COMMENTED

Good work so far, here are some of my comments for your consideration :)
</panel>

</panel>

<panel type="info" header="### 9. NAY ..AING `@NayChi-7` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959154622" expanded>

good use of switch cases (and follows the coding standard)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959155100" expanded>

Specific import case (good as it it follows the coding standard)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959155787" expanded>

Not too sure if this is more than 120 characters but seem quite long so be careful with such lines
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959155919" expanded>

Similar long line of code... might exceed 120 characters (so remember to double check)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959156136" expanded>

Not too sure if this is pascal case (you might want to double check)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959156286" expanded>

Use verb for function names
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#pullrequestreview-1091286366" expanded>

**Review Status:** COMMENTED

Good project factoring (the interactions between cases look great). Great job following the coding standards: great use of pascal cases, importing specific packages, and following the standard for layout. Overall, great job!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959157737" expanded>

Might wanna refactor the code into smaller functions and invoke them to improve readibility
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959158163" expanded>

Great function naming while following the Pascal case standard
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959159033" expanded>

Great job on following the naming conventions (using plural forms for collection of objects)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959159666" expanded>

Might wanna define "line", "mark", and "unmark" somewhere outside (as it currently violates the coding standard of not using magic values)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959159959" expanded>

Great layout
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959160148" expanded>

Nice :)) importing specific packages
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#pullrequestreview-1091290426" expanded>

**Review Status:** COMMENTED

Good job on following most of the coding standards: great function and variables naming, importing specific packages, and great layout. 
</panel>

</panel>

<panel type="info" header="### 10. NG S.. IAN `@nshian` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959174828" expanded>

Good practice listing the imported class explicitly instead of implicitly e.g. import java.util.*
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959176571" expanded>

Might want to use a boolean variable to represent the true condition of the while loop as it might not be clear to the reader on what condition the loop continues/terminates.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959177238" expanded>

Good practice using K&R style brackets
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#discussion_r959177918" expanded>

Good practice following camelCase for the naming of class methods.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/35#pullrequestreview-1091312808" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959181892" expanded>

The length of your main function exceeds 30 LOC, might want to shorten it.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959182101" expanded>

Good adherance to SLAP by refactoring code into other functions.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959182500" expanded>

Good practice listing the imported class explicitly instead of implicitly e.g. import java.util.*
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959183772" expanded>

Good practice following camelCase for the naming of class methods.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#pullrequestreview-1091321551" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959184754" expanded>

The length of your main function exceeds 30 LOC, might want to shorten it.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959185061" expanded>

Good practice following camelCase for the naming of class methods, but consider renaming unMark() as markAsUndone() to maintain parity with markAsDone()
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959187948" expanded>

Consider creating a separate file Task.java for your Task class.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959188476" expanded>

The boolean variable bye can be renamed to isProgramFinished or something similar for ease of understanding by the reader.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#pullrequestreview-1091325257" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 11. CHEN..YUGE `@ChengYoghurt` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961272141" expanded>

Nice pic! Add more interests in the code review!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961272456" expanded>

Great function name ! Easy to understand !
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961273546" expanded>

A bit confused at first sight
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961273899" expanded>

Maybe can delete the redundant code? 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#pullrequestreview-1094289426" expanded>

**Review Status:** COMMENTED

COOLLLLLL
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961266890" expanded>

Plz avoid using the magic num~
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961267710" expanded>

Nice overriding!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961269771" expanded>

Good job adopting OOP policy! Put the relative function in its own class
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961270180" expanded>

Great readability! u distinguish clearly on the print function! 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#pullrequestreview-1094282339" expanded>

**Review Status:** COMMENTED

Amazing! I'll learn from u next time!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961262528" expanded>

Plz avoid using the magic number~
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961263609" expanded>

Good job on using correct indent on Switch!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961265191" expanded>

Yea can add the public label on it~
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961265376" expanded>

Good getter toc control the access to attr!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#pullrequestreview-1094276899" expanded>

**Review Status:** COMMENTED

Goooooooooood WOWWWWWW
</panel>

</panel>

<panel type="info" header="### 12. CAO ..IKAI `@nvknow` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961263678" expanded>

Maybe System.lineSeparator() is better than \n
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961264619" expanded>

I think this method of separating "divider" first is great, easy for me to understand
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961265223" expanded>

Using dynamic array is good idea
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#discussion_r961265618" expanded>

Maybe just "println" here then you can drop the \n in the dashLine
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/24#pullrequestreview-1094278271" expanded>

**Review Status:** COMMENTED

LGTM, almost. Just a few nits to fix.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961267824" expanded>

Explicit expression of using switch
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961268004" expanded>

Good job of robustness
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961268632" expanded>

Good job of separating each kind of task into a single method
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961269651" expanded>

Maybe another name of arg1 and arg2 to be more easily understood
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#pullrequestreview-1094283520" expanded>

**Review Status:** COMMENTED

LGTM, almost. Just a few nits to fix.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961272948" expanded>

Explicit use of switch
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961273245" expanded>

Maybe you can separate the print of the line
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961273475" expanded>

i = 0; i &gt; count , maybe more spaces
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#discussion_r961273672" expanded>

Maybe using System.lineSeparator() is better than \n
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/59#pullrequestreview-1094290620" expanded>

**Review Status:** COMMENTED

LGTM, almost. Just a few nits to fix.
</panel>

</panel>

<panel type="info" header="### 13. KWOK..ASEY `@kaseykwok` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961263267" expanded>

Avoid using magic literals. Consider adding a constant for it.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961264521" expanded>

Consider adding spaces before the opening parenthesis and after the closing parenthesis.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961265089" expanded>

Avoid double spacing. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961265544" expanded>

Indentation for wrapped lines should be 8 spaces.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961265998" expanded>

Consider adding space before the opening parenthesis.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#pullrequestreview-1094277760" expanded>

**Review Status:** COMMENTED

Nice work. Hope my review could help.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961267173" expanded>

Consider changing the naming of the boolean variable to "isXXX". 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961268658" expanded>

Consider naming the function's name as `printGreeting()` instead of `printingGreeting()`.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961269151" expanded>

May change the function name to `printExit()`
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961269330" expanded>

May change the function name to `printHorizontalLine()`
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961269522" expanded>

May change the function name to `printEcho()`
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961271589" expanded>

Avoid recycling variable. Consider declaring another variable `String description` to store instead of using `input` again.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961271880" expanded>

Avoid using magic literals. Consider declaring a constant for it.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#pullrequestreview-1094282673" expanded>

**Review Status:** COMMENTED

Nice work. Hope my review could help you well.
</panel>

</panel>

<panel type="info" header="### 14. LOK .. JUN `@LokQiJun` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959618693" expanded>

Consider using a constant string instead of a magic string
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959620488" expanded>

Very nice that you have documentations for your methods 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959624102" expanded>

Too many layer of nesting is not recommended
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959626397" expanded>

Perhaps use a more intuitive variable name here?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#pullrequestreview-1091932266" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959134580" expanded>

Naming needs to be more specific
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959138503" expanded>

Consider using constants rather than magic strings
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959138733" expanded>

Good that you only imported the library that you need!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959139344" expanded>

Good that you followed the naming convention :)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#pullrequestreview-1091260707" expanded>

**Review Status:** COMMENTED

Very nicely organised :)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/70#discussion_r959603951" expanded>

Constant names requires underscore to separate words.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/70#discussion_r959605765" expanded>

Consider using a constant string instead of magic string for the cases
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/70#discussion_r959610396" expanded>

Good that you followed the naming convention
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/70#discussion_r959613722" expanded>

There seems to be a missing space before {
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/70#pullrequestreview-1091911210" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 15. JOHN.. JUN `@jjtoh` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960425297" expanded>

Else if on the wrong line, should be on the same line as the close bracket on the line above. Spacing between keyword and open braces should also be added. (This is done multiple times)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960452917" expanded>

Methods are well named as they follow camelCase
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960453726" expanded>

There should be spacing before braces
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960455552" expanded>

Good naming for setters and getters
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#pullrequestreview-1093063345" expanded>

**Review Status:** COMMENTED

Just some repeated spacing mistakes, otherwise it is generally well done.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960443922" expanded>

Can do the printing in another method to make the code look cleaner
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960444633" expanded>

Indentation not needed for switch and case statements
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960446522" expanded>

Add a space before opening the braces for better styling.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960447905" expanded>

Name of variable can be improve, for example rather than cmd, it can be command
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960448711" expanded>

All the printing can be done in a method to prevent repetition
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960453957" expanded>

There should be spacing before braces (applies the whole file)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960461115" expanded>

Add spaces before and after the logical operator so that it looks better
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#pullrequestreview-1093090569" expanded>

**Review Status:** COMMENTED

Some repeated mistakes in the spacing and can make code more readable by putting some code in a new method. 
</panel>

</panel>

<panel type="info" header="### 16. KOH .. HIN `@kohnh` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961263364" expanded>

Try not to nest ternary operator.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961264567" expanded>

Should be while !input.equals("bye")
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961265154" expanded>

Good use of switch statements
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961265714" expanded>

Good usage of map
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#pullrequestreview-1094277855" expanded>

**Review Status:** COMMENTED

Good! No use of magic numbers
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#discussion_r961266108" expanded>

Too much nesting
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#discussion_r961266849" expanded>

Use setDone function instead
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#discussion_r961267574" expanded>

Redundant code. The parent function will be automatically called.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#discussion_r961268246" expanded>

use this.description to get description to clarify since its not a local variable
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#discussion_r961268827" expanded>

Repeated usage of line separator. Should abstract to a new final String.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#discussion_r961269154" expanded>

Avoid using magic number
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#discussion_r961270439" expanded>

Should have a final modifier
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/45#pullrequestreview-1094281403" expanded>

**Review Status:** COMMENTED

Keep up the good work :)
</panel>

</panel>

<panel type="info" header="### 17. WANG..GJIA `@wangtingjia` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959224908" expanded>

Consider using final for variable by
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959226806" expanded>

I like the use of ArrayList data structure to store the tasks
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959227321" expanded>

I like the very neat organisation of the functions. This allows for easy single level of abstraction in the main function
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959228226" expanded>

Clear and correct naming of all classes, variables and functions as per coding standards.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959228399" expanded>

Good use of Override method
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959228775" expanded>

Consider adding "final" to variable timing
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#pullrequestreview-1091380164" expanded>

**Review Status:** COMMENTED

Good quality code that closely follows coding standards. Great effort!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959177583" expanded>

I like the use of the Override method
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959178063" expanded>

I like the single level of abstraction here. Clear and easy to read.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959178595" expanded>

Consider use of final
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959179416" expanded>

Consider creating a new TaskManager class to manage the creation and marking of tasks
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959179738" expanded>

Consider the use of final
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#pullrequestreview-1091316161" expanded>

**Review Status:** COMMENTED

Overall good job and great code quality. Looks ready to merge.
</panel>

</panel>

<panel type="info" header="### 18. HANG..TIAN `@HT-T` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960443161" expanded>

I like how you adhere to the guidelines: only import packages you need
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960443744" expanded>

Nice to see comments that helps reviewers to understand the code
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960444768" expanded>

I like how the SLAP principle is used here. Clean and readable.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960446929" expanded>

Good implementation of OOP overall
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960447688" expanded>

I like this well-thought functionality
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960449161" expanded>

Perhaps you could consider switch-case? I have seen other coder who used switch-case for better readability. 
However this is a very minor issue.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#pullrequestreview-1093089400" expanded>

**Review Status:** COMMENTED

Overall the code is up to standard and implemented correctly. Looks good.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/48#discussion_r960421204" expanded>

Good choice to import only necessary packages
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/48#discussion_r960423810" expanded>

good choice of using switch case as else-ifs can be messy
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/48#discussion_r960425080" expanded>

I like the very clean main function
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/48#discussion_r960429085" expanded>

Perhaps you could add some more comments in your code for clarity?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/48#discussion_r960432548" expanded>

I like how you adhere to coding standard with class names capitalized
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/48#pullrequestreview-1093057602" expanded>

**Review Status:** COMMENTED

Most, if not all code written is up to standard. Looks good
</panel>

</panel>

<panel type="info" header="### 19. FELI..LAUW `@FeliciaBeatrice` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#discussion_r961261910" expanded>

Please avoid using magic numbers
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#discussion_r961262313" expanded>

maybe using switch case will look neater (?)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#discussion_r961262797" expanded>

this one maybe also can use switch case 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#discussion_r961263687" expanded>

i think needs a blank next line after each function to make it more consistent
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#discussion_r961264002" expanded>

needs blank next line also
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#pullrequestreview-1094276199" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961265919" expanded>

maybe use \t for the spacing
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961266956" expanded>

should have spacing for taskNum - 1
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961267114" expanded>

should have spacing for taskNum - 1
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961267291" expanded>

should have spacing for taskNum - 1
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961267365" expanded>

should have spacing for taskNum - 1
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961267573" expanded>

should have no space between StringBuilder( and "Here...
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#pullrequestreview-1094281175" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 20. PAUL..I EN `@paullowse` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/7#discussion_r959154629" expanded>

Comments should be indented relative to the position of the code
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/7#discussion_r959156162" expanded>

comments should be indented relative to code
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/7#discussion_r959156319" expanded>

good use of functions!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/7#discussion_r959156476" expanded>

helpful use of boolean method
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/7#discussion_r959156726" expanded>

have an else statement to catch all other situations?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/7#discussion_r959156833" expanded>

Good use of other imported modules
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/7#pullrequestreview-1091286375" expanded>

**Review Status:** COMMENTED

Good job! Keep up the good work :)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959157491" expanded>

Do follow standard for javadoc comments
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959157746" expanded>

Good use of switch case and statements
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959157920" expanded>

Good use of naming conventions for static variables!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959158422" expanded>

Good use of functions to facilitate the code
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959158693" expanded>

very neatly organized code!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#pullrequestreview-1091290131" expanded>

**Review Status:** COMMENTED

Good job on the work done so far! 
</panel>

</panel>

<panel type="info" header="### 21. AARO.. ZHI `@AaaaaronC` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960447993" expanded>

collections can be named as plural to distinguish from Strings instead of String[]
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960448997" expanded>

same thing here, the naming for eventTask follows that of other Strings, which make it slightly confusing
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960450269" expanded>

code here can be condensed more 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960451889" expanded>

good that helper functions are used to make code neater subsequently
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960454081" expanded>

slightly misleading method name as it suggests the use of System.out.print or an equivalent, but instead it returns a string
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#pullrequestreview-1093096281" expanded>

**Review Status:** COMMENTED

Good coding practices, only a few minor naming issues
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#discussion_r960427879" expanded>

the ' else{ ' line should be on this line instead of the next line
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#discussion_r960458227" expanded>

this line makes the code look long and messy, maybe can be replaced with a helper function defined above
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#discussion_r960459246" expanded>

spaces can be put in between like so:  "while (isRunning) { "
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#discussion_r960460896" expanded>

unnecessary empty line here
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#discussion_r960461719" expanded>

good that the string is segmented to avoid overly long lines of code. however, indents can be made to align the string to make it more readable
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#pullrequestreview-1093067119" expanded>

**Review Status:** COMMENTED

neat code, good job!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#pullrequestreview-1093110995" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 22. JOSH..FENG `@joshuan98` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959182909" expanded>

You may want to consider setting the logo to be of type private static final. Constant names should be in capital letters.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959184177" expanded>

Same as above for this, you can consider making the type private static final and capitalise "linebreak"
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959184543" expanded>

You should avoid complicated expressions as per https://nus-cs2113-ay2223s1.github.io/website/se-book-adapted/chapters/codeQuality.html
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959184898" expanded>

You can consider removing the magic number 4 and making it a named constant
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959185205" expanded>

You may want to adhere to SLAP and shift this to a new class
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#pullrequestreview-1091322842" expanded>

**Review Status:** COMMENTED

Good job so far!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959174704" expanded>

Good job importing only the necessary libraries instead of doing import java.util.*
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959176815" expanded>

You can consider shfiting taskCount as a static variable in Task class as per what prof mentioned during class
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959179666" expanded>

switch statements do not have brackets for each case as per https://se-education.org/guides/conventions/java/basic.html
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959180528" expanded>

You might want to do the same as above for this switch statement as well
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#discussion_r959181142" expanded>

Good job splitting a long statement into two lines and ensuring that the line length is not more than 120 char
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/69#pullrequestreview-1091312687" expanded>

**Review Status:** COMMENTED

Good job, looks good to me. Ready to merge
</panel>

</panel>

<panel type="info" header="### 23. PARA..JEEV `@indraneelrp` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960463964" expanded>

Consider turning the line into a constant since it is being reused.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960464303" expanded>

referring to \n__________________
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960465313" expanded>

Consider having a more understandable variable name
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960469712" expanded>

consider simplifying this expression since it is a long chain of conditions
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960474802" expanded>

Since there is repeated code here, you could consider restructuring this code such that it abstracts the pattern out
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960475554" expanded>

*in this file, not this specific line
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#pullrequestreview-1093119274" expanded>

**Review Status:** COMMENTED

Generally looks good!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#pullrequestreview-1093135964" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r960451096" expanded>

consider making this a constant so that it is not a magic character
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r960452034" expanded>

good usage of appropriate whitespace for java reserved keywords
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r960453874" expanded>

consider making the variable 't' more descriptive
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r961230765" expanded>

You could simply name this tasks in plural
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#pullrequestreview-1093095017" expanded>

**Review Status:** COMMENTED

Do take a look at my comments
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#pullrequestreview-1094233956" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 24. ONG ..YONG `@redders7` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960460807" expanded>

Do try to avoid magic strings
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960467358" expanded>

Consider using default branch to detect errors
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960472457" expanded>

Consider naming your function as nouns (exit what?)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960473935" expanded>

Try to minimise number of constant variables
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960475355" expanded>

Try to avoid duplicating code for addEvent, addDeadline, addTodo. Consider using abstract classes?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#pullrequestreview-1093114706" expanded>

**Review Status:** COMMENTED

Some small quality issues but great job overall!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960440494" expanded>

Consider naming in PascalCase (only first letter capitalised)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960443547" expanded>

Consider adding a space after if
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960449081" expanded>

Consider rephrasing comment for the assignement @param
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960450710" expanded>

Consider renaming to sound like a boolean (isError)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960450976" expanded>

Consider renaming to sound like a boolean (isError)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#pullrequestreview-1093085587" expanded>

**Review Status:** COMMENTED

Everything looks good so far!
</panel>

</panel>

<panel type="info" header="### 25. CHUA..RREN `@chydarren` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959160828" expanded>

May wish to consider using enum variables for the switch statement (refer to Lecture 4). 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959161240" expanded>

Excellent use of separators to split a longer string output!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959161452" expanded>

Good use of in-line conditional expression to make the code intuitive.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959163190" expanded>

Pro tip - You can implement an array list instead of a fixed size array so that the application can be re-purposed to help the user complete more tasks. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#pullrequestreview-1091294445" expanded>

**Review Status:** COMMENTED

Great coding quality that comply to the Java Coding Standard. Keep up the great work! :)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/68#discussion_r959155696" expanded>

Great that the purpose of the variable is described clearly, but do note that variable names must be in camelCase.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/68#discussion_r959156475" expanded>

For the if-else statement, try to maintain consistent spacing between the "}" brace and your "else if". Suppose your other cases you have a space between them, then try to maintain it throughout the code to neaten readability.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/68#discussion_r959157454" expanded>

Excellent use of an in-line conditional expression to make the code more intuitive! 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/68#discussion_r959157945" expanded>

Note that array variables need to be in camelCase too. Pascal cases should only be used for class and enum declarations.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/68#discussion_r959159361" expanded>

I would recommend using .startsWith() so that the use case can be more specific.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/68#discussion_r959159991" expanded>

I'm not quite able to decipher why we are counting the index of the space, maybe might want to add a comment to describe this part.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/68#pullrequestreview-1091287645" expanded>

**Review Status:** COMMENTED

Well-written and organized code! Just a few minor tweaks needed, keep up the good work! :) 
</panel>

</panel>

<panel type="info" header="### 26. IVAN..RONG `@ivanthengwr` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960429418" expanded>

Is the switch case format for the code standard correct? Maybe you can see the coding standards on the CS2113 website to find out the correct way.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960432976" expanded>

Is the taskDescriptor collecting more than one Descriptor? If so, should the naming be a collection of objects?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960439441" expanded>

Code line may be a bit long?  Should line length be no longer than 120 chars?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960442985" expanded>

The style of commenting may not be the best for CS2113. Can you consider the format given in the coding standard?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#discussion_r960445961" expanded>

Maybe you can be able to wrap the code if it is more than 120 chars?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/15#pullrequestreview-1093069383" expanded>

**Review Status:** COMMENTED

Overall relatively good coding standards, good job!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/47#discussion_r960449421" expanded>

Code quality: May not be recognizable to the reader. May I know what this line of code mean?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/47#discussion_r960452210" expanded>

`val > tasks.size()` may be too specific in nature, it would be better if you were to abstract this logic into a higher level function. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/47#discussion_r960453106" expanded>

It would be better if you follow the comment style with regards to CS2113, additionally, would it be better if you give more information for the comment?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/47#discussion_r960455890" expanded>

I think it would be better to summarize your if-else statements, and make it shorter by introducing more method functions. 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/47#discussion_r960458639" expanded>

I think it would be better to classify the `userInput.equals("bye")` as a boolean variable. For example `isBye = userInput.equals("bye");`  This may make it easier for the reader to understand. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/47#pullrequestreview-1093098287" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 27. RACH..YUAN `@Franky4566` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960445715" expanded>

No comments for all functions. Can consider adding based on the java coding standards so that its easier to read & understand your code
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960446179" expanded>

add spacing before  bracket {
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#discussion_r960446360" expanded>

spacing before bracket {
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/2#pullrequestreview-1093093105" expanded>

**Review Status:** COMMENTED

Good job! just some minor issues
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960429886" expanded>

Should add comments before every function to understand the code better
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960434523" expanded>

add spacing before if open bracket {
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960439277" expanded>

Boolean should be small b 
ie. boolean
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#pullrequestreview-1093070104" expanded>

**Review Status:** COMMENTED

Well written code and very clean! Just some minor issues and commenting

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/62#discussion_r960460159" expanded>

Consider naming 2 as a constant, difficult to tell what the number 2 means
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/62#discussion_r960463977" expanded>

Consider adding comments for all ur functions so it is more readable, as described in the code quality page on the module website
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/62#discussion_r960467412" expanded>

Phrases "Marked this task: \n" and "Unmarked this task: \n" can be written as a constant String when outputting
 like line 21 declared in line 5
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/62#discussion_r960481545" expanded>

lines 32 and 33 can be abstracted into another function as the splitting is quite complicated (SLAP issue). Once extracted can be declared like line 35
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/62#pullrequestreview-1093113772" expanded>

**Review Status:** COMMENTED

Well written code with good breakdowns. Just some minor issues and issue of SLAP.
</panel>

</panel>

<panel type="info" header="### 28. WILS..G AN `@wilsonngja` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961261896" expanded>

Please avoid using magic number literals. You can use a constant and add meaningful names.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961263673" expanded>

Good job. I like how you include the print statements within a functions.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961264680" expanded>

Try to use another variable for the variable because might not be so intuitive.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961265823" expanded>

Good job on following the coding standard for the switch case.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961266424" expanded>

I think for the function names, "addDeadline" is sufficient.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#pullrequestreview-1094276181" expanded>

**Review Status:** COMMENTED

Generally, just try to avoid magic literals and try to keep the name straightforward. Good effort. 👍🏼 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961271780" expanded>

Try to put a space between previous and next text.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961272190" expanded>

Since you're only marking one task, don't have to put plural. markTask is suffice.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961272497" expanded>

Try to add a variable to it. Reading the statement can be difficult especially when the condition is long.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961272847" expanded>

Try to have a variable for this boolean expression to be more intuitive.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961273079" expanded>

Since you're only accepting 1 command, don't have to put plural. acceptCommand is sufficient.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#pullrequestreview-1094288913" expanded>

**Review Status:** COMMENTED

Overall great effort. Try to put white space in between expressions and make your function name more meaningful to the task it perform.
</panel>

</panel>

<panel type="info" header="### 29. SHAW..NHUI `@gitpancaked` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959156868" expanded>

Take note of this magic number 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959157419" expanded>

Good job abstracting the constant messages out!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959157527" expanded>

Nice, very modular and clear!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959158804" expanded>

Nice! Going above and beyond with this TaskManager class!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#discussion_r959159913" expanded>

Great that you already use the protected modifier!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/16#pullrequestreview-1091289282" expanded>

**Review Status:** COMMENTED

Amazing code! Keep up the excellent work!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959163271" expanded>

Great use of static constants here!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959164281" expanded>

Nice use of methods to simplify your code
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959165235" expanded>

Nice use of printf here
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959165527" expanded>

Great that you defined all your variables first
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959165847" expanded>

Nice, simple and clear while statement!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#pullrequestreview-1091297717" expanded>

**Review Status:** COMMENTED

Great code! Clear and well abstracted with good use of methods. 
</panel>

</panel>

<panel type="info" header="### 30. BRIA..LONG `@brian-vb` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959160329" expanded>

Great work in implementing the lines!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959161250" expanded>

Good use of ternary code
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959161753" expanded>

could use switch cases here?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959163898" expanded>

good use of split!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#pullrequestreview-1091293831" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959155057" expanded>

Nice use of ternary operator, although impacts readability of code. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959156393" expanded>

good use of switch cases! this is very neat :)))
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959156792" expanded>

Good use of static strings in class to simplify the codes in your other files! 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959158319" expanded>

good function here!!!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959158830" expanded>

overall, i really liked all the helper function called in this file
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#pullrequestreview-1091286819" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 31. CHIE.. WEI `@jingwei55` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959155941" expanded>

Methods are all using the correct camelCase, well done!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959157506" expanded>

variable can be more specific
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959158559" expanded>

Methods are clearly phrased and can be understood easily. Perhaps could combine all functions into a larger function to not show less important functions like printLineSeperator
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959158878" expanded>

Take note of indentations
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959176950" expanded>

Very clear function definitions! Code is really easy to read and understand, well done!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#pullrequestreview-1091284838" expanded>

**Review Status:** COMMENTED

Overall the coding structure is very good, just some minor adjustments need to be done. Methods and classes can all be easily understood. Well done!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#pullrequestreview-1091315320" expanded>

**Review Status:** COMMENTED

Add on to previous review
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959179140" expanded>

Can be more specific, perhaps could use index instead of number
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959180711" expanded>

Could be better if markStatus and unmarkStatus came from a more generic function. Both functions are very similar, hence there should be less repeat code
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959181879" expanded>

Try to minimize the usage lambda functions if possible as they make code less readable
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#discussion_r959182871" expanded>

Declaration of task can be more specific
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/64#pullrequestreview-1091318071" expanded>

**Review Status:** COMMENTED

Overall the code is understandable, keep it up! Some issues need to be resolved to make your code more readable.
</panel>

</panel>

<panel type="info" header="### 32. CHIE..IANG `@chiewyx` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959571031" expanded>

good practice to list import class explicitly
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959572036" expanded>

good use of final constant
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959572830" expanded>

same as above, nice logo you have there
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959575833" expanded>

good use of CommandManager to manage the different commands
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959577140" expanded>

good use of abstract class (even though I'm not sure how to use it)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#pullrequestreview-1091864158" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959154250" expanded>

consider following the Java coding standard guidelines on switch statements
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959155269" expanded>

consider following the java coding standard guidelines on try-catch statements
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959155921" expanded>

consider creating another file for task class
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959156538" expanded>

consider changing this to follow the coding guidelines too
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#pullrequestreview-1091285923" expanded>

**Review Status:** COMMENTED

overall good job thus far
</panel>

</panel>

<panel type="info" header="### 33. LION..DEEN `@deenliong` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/27#discussion_r961262678" expanded>

Please avoid using magic literals. Consider using a final constant value :D
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/27#discussion_r961264562" expanded>

Good use of ternary operator!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/27#discussion_r961264847" expanded>

Very usage of different methods. Made reading the main very simple.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/27#discussion_r961265099" expanded>

Imported classes explicitly. Good job.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/27#pullrequestreview-1094277076" expanded>

**Review Status:** COMMENTED

Really very easy to read and understand your code. Good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/75#discussion_r961266077" expanded>

Could possibly write a method for introduction that includes both your logo and welcome message :)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/75#discussion_r961266862" expanded>

This variable could be better named. Probably taskCount or taskId?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/75#discussion_r961267968" expanded>

Line 47 to 51 could be written as a method.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/75#discussion_r961268453" expanded>

Avoid using magic number "100"
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/75#discussion_r961269852" expanded>

Consider abstracting the commonalities of the various conditional clauses. Maybe implement a switch case? :D
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/75#pullrequestreview-1094281379" expanded>

**Review Status:** COMMENTED

Good job!
</panel>

</panel>

<panel type="info" header="### 34. KWUA.. REN `@JordanKwua` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#discussion_r960457560" expanded>

You should try to avoid deep nesting , the so called 'arrowhead style' code
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#discussion_r960461486" expanded>

Maybe consider using a better noun instead of a single letter d to represent this as it is ambiguous?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#discussion_r960465373" expanded>

Maybe you can consider using a verb for methods instead of a noun?
 eg makeDateline
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#discussion_r960470942" expanded>

Maybe you should consider implementing SLAP? getStatus() is on one layer but the printf is is on another layer
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#pullrequestreview-1093110037" expanded>

**Review Status:** COMMENTED

Overall great job, just try not to nest too deep.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960430487" expanded>

I think you should standardise comments to be indented relative to their position in the code?
e.g.
while (true) {
// Do something
something();
}
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960432062" expanded>

Maybe you can consider having a space after the closing bracket for the method instead?
eg.
public String getDate() {
//Insert code here
}
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960432829" expanded>

Theres a spelling error here ~
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960434673" expanded>

Should follow the coding standard for if-else class of statements
eg.
if (condition) {
statements;
}
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#discussion_r960441055" expanded>

Should define the boolean type as per follows (b is in small letters)
eg.
boolean isBye = false;
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/49#pullrequestreview-1093070923" expanded>

**Review Status:** COMMENTED

Overall good job as the code works, just some minor indentation issues and placement of comments. If you're using IntelliJ maybe you could use CTRL + ALT + L to auto-indent 
</panel>

</panel>

<panel type="info" header="### 35. SEE ..ELLE `@jorellesee` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959155386" expanded>

I like how you implemented the drawLine function for code reusability
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959155861" expanded>

perhaps the use of the lambda function here makes the code slightly less readable
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959156496" expanded>

might be slightly better to name this unmarkTask instead of unmarkTasks to avoid confusion
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959156612" expanded>

same issue as above
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959156705" expanded>

since action is being performed only on single task
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#pullrequestreview-1091287255" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959157337" expanded>

Perhaps the use of a lambda here makes the code slightly less readable
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959157614" expanded>

I like the use of all caps here to tell the reader that this is a constant. Good job!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959157680" expanded>

Same here!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959158009" expanded>

Perhaps more could be done to make this line more readable? Consider not using the lambda or putting it in a different line.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#pullrequestreview-1091289904" expanded>

**Review Status:** COMMENTED

Overall great work! But consider using lambdas in different lines instead to make the code more readable
</panel>

</panel>

<panel type="info" header="### 36. ANG ..RCUS `@OVReader` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961263985" expanded>

Good Indentation for switch case 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961266351" expanded>

I like the use of INDENT to make the print statements shorter and neater
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961266827" expanded>

I like the use of ENUM
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961267586" expanded>

Do note on camelCase for goodbye function
Suggested: goodBye()
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#discussion_r961269897" expanded>

Good coding standard for class name (CAPS for 1st letter)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/6#pullrequestreview-1094278625" expanded>

**Review Status:** COMMENTED

Overall LGTO except the goodBye function
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961272603" expanded>

Please avoid magic literal
Suggest: Use static final
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961273616" expanded>

Try to avoid white space for more compact code
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961274450" expanded>

Try to avoid redundant comments
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#discussion_r961274611" expanded>

Try to avoid white space
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/55#pullrequestreview-1094290126" expanded>

**Review Status:** APPROVED

Great Coding Quality! Just some minor code cleanup required
</panel>

</panel>

<panel type="info" header="### 37. NAZR..URAD `@nazrul0` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#discussion_r960432381" expanded>

Consider keeping line spaces to single lines.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#discussion_r960440319" expanded>

Is this line space needed?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#discussion_r960447710" expanded>

I like how your printing of strings looks very clean.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#pullrequestreview-1093073708" expanded>

**Review Status:** COMMENTED

Most of the code is written is up to standard. Looks good.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/21#pullrequestreview-1093095897" expanded>

**Review Status:** COMMENTED

Looks good.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960451214" expanded>

Do consider removing unused commented code to avoid confusion
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960451682" expanded>

I like how you extracted this part.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960452192" expanded>

is there a cleaner way to express this logic?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960452562" expanded>

Do consider adding spaces here
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960454308" expanded>

Could you have used PRINT_LINE here?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#discussion_r960456125" expanded>

I like how you kept the line length within the limit by breaking it up.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/29#pullrequestreview-1093100912" expanded>

**Review Status:** COMMENTED

Code is generally up to standard other than a few minor points. Looks good.
</panel>

</panel>

<panel type="info" header="### 38. AMIT..HMAN `@amitrahman1026` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961429742" expanded>

Perhaps you can separate the commands into different classes/methods to be called by duke
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961432052" expanded>

Perhaps you can use some form of [" + super.getStatusIcon() + "] instead
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961433739" expanded>

short and effective way to return the status icon! 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961437638" expanded>

perhaps a better variable name for DescriptionBy could be deadlineTime?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#pullrequestreview-1094508409" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961318002" expanded>

Good use of polymorphism 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961318445" expanded>

Good work on updating expected output for test cases!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961318864" expanded>

Comprehensive input that tests all the featuresof the project as of now!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961320073" expanded>

Great work on following coding standard for switch and case! It is a little tricky to watch out for!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961324562" expanded>

Succint and easy to understand process flow of duke!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#pullrequestreview-1094351827" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 39. SHEN..HEQI `@zheqis12138` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961266856" expanded>

1. The name of method welcome, blah, bye can be in verb format like printWelcomeMessage
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961267202" expanded>

Good use of constant instead of magic number
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961267851" expanded>

Can use switch statement instead of too many if else clause
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961268896" expanded>

Good use of inheritance and overwrite toString function
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#discussion_r961269243" expanded>

Can use constant to replace magic number
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/46#pullrequestreview-1094282289" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961272220" expanded>

Good use of constants !
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961272396" expanded>

Good use of switch statement !
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961273944" expanded>

Good to use inheritance to extend the feature
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#discussion_r961274214" expanded>

Excellent work overall !
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/53#pullrequestreview-1094289603" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 40. DEVE..DRAN `@deveshl` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959314689" expanded>

The implementation of print() in Todo and Deadline is mostly similar, could possibly be moved to the base class
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959316290" expanded>

Using constants for commands is a good idea
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959318054" expanded>

As above - it may be worthwhile to have a function for printing text surrounded with line separators to decrease repetition
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#pullrequestreview-1091503217" expanded>

**Review Status:** COMMENTED

High quality code overall.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959136152" expanded>

Vaiable name could be more descriptive (e.g. "arguments")
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959136736" expanded>

Inconsistent spacing around operators - some places in code use "i+1" and others use "i + 1"
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959267375" expanded>

Variable name could be more descriptive (e.g. "input" as this variable stores input from the user)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959269729" expanded>

I like that the default case was explained
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959271097" expanded>

Missing space before curly brace (this appears in all the subclasses)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959275549" expanded>

I don't believe keeping track of the count manually is necessary as you can get the number of items with tasks.size()
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#pullrequestreview-1091262638" expanded>

**Review Status:** COMMENTED

The code style is not followed consistently throughout the code and could use some reformatting. Otherwise looks good
</panel>

</panel>

<panel type="info" header="### 41. DHAN..DALI `@dhanish265` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/37#discussion_r961266169" expanded>

you can consider implementing SLAP to segregate lower and higher level functions.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/37#discussion_r961266576" expanded>

can consider overriding Object's toString method as that is the intended effect of this method and makes it easier to use this method in other classes
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/37#discussion_r961267603" expanded>

can consider segregating task related methods to a different class, such as TaskManager
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/37#discussion_r961268244" expanded>

you can consider making this a final string so that there will not be multiple creations of the same string (although I understand the function is only called once)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/37#pullrequestreview-1094281488" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961261383" expanded>

Please replace magic literal ('100'). Consider using a final value.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961262457" expanded>

I think there should be a space between the closing bracket and open brace. You can use the reformat code option for the IDE to do it for you
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961263612" expanded>

can consider changing the method name to reflect the boolean nature of the method (toExit does not sound like it's a boolean method)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961264432" expanded>

perhaps it is accidental, but there are actually 2 spaces between 'public' and 'static' in this method and the next method
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#pullrequestreview-1094275576" expanded>

**Review Status:** COMMENTED

Overall, I think it's quite good. Just need those minor edits that I suggested.
</panel>

</panel>

<panel type="info" header="### 42. KART..HRAM `@shengiv` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960457657" expanded>

Consider adding comments to describe what the method does
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960466859" expanded>

The code can be restructured to make the happy path unindented as much as possible.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960473953" expanded>

Good job on extracting out the print statements to print methods
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#discussion_r960477510" expanded>

Avoid varying levels of abstraction to improve readability
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/58#pullrequestreview-1093110195" expanded>

**Review Status:** COMMENTED

In general, code quality was well-maintained. Good job. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960439552" expanded>

An alternative name can be used for the boolean isExit so that the purpose of the boolean is clearer
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960442736" expanded>

The switch statement should be aligned with the case statements.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960449380" expanded>

You could consider adding spaces before and after comparison operators to improve readability
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960471967" expanded>

You could consider renaming the variable to "command" so that it is clearer to the reader
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#pullrequestreview-1093084392" expanded>

**Review Status:** COMMENTED

There are no major coding standard violations. Good job!
</panel>

</panel>

<panel type="info" header="### 43. GAO .. FAN `@gaoyunfan` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959159423" expanded>

maybe an extract these for slap
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959160618" expanded>

maybe could use use one function to extract DateTime and taskName to reuse it for deadline and event
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959235177" expanded>

Perhaps can use SLAP here
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#discussion_r959237543" expanded>

I like the use of do to implement the loop
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/4#pullrequestreview-1091292632" expanded>

**Review Status:** COMMENTED

Good code quality overall as the codes are easy to read, names are easy to understand
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959156120" expanded>

Good job for listing explicitly
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959156544" expanded>

Good use of naming for class
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959157016" expanded>

Clear naming 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#discussion_r959158037" expanded>

Good naming of methods, able to tell its use
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/5#pullrequestreview-1091288232" expanded>

**Review Status:** COMMENTED

Good coding standards overall
</panel>

</panel>

<panel type="info" header="### 44. LIU ..NHAO `@junhaoliu2468` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/8#discussion_r959155448" expanded>

Very creative use of a personalised interface :)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/8#discussion_r959156464" expanded>

interesting way to read the input - i simply used a split function to do it
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/8#discussion_r959156973" expanded>

pretty good use of the for loop but i did it inside the task class
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/8#discussion_r959157609" expanded>

good use of super() - reduces alot of unnecessary duplicate code
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/8#pullrequestreview-1091287313" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959158822" expanded>

can consider using more classes - will make things much simpler to work with in the later stages
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959159673" expanded>

i think idea is along the same line - you have different objects so you have more calls - it helps to make your code much less cluttered and you can make use of super() functions to reduce duplicate code too
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959160201" expanded>

very good effort honestly in splitting up the cases
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959160408" expanded>

can again consider looking at things from a more macro - object kind of perspective
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#pullrequestreview-1091291835" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 45. ONG ..HONG `@helpdesk1234` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959616830" expanded>

Useless comments. All comments should be written in English and Comments should be indented relative to their position in the code. Redundant code from previous versions should be deleted so as to keep the code tidy. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959619635" expanded>

All names should be written in English. "sc" is not indicative of what the variable does. Perhaps you could give it a name that tells readers this sc is a scanner that gets user input?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959622049" expanded>

Comments should be indented relative to their position in the code. Make and extra line for the comments 

//pending check if second character is number AND smaller than numberOfInputs
//pending check if second character is number AND smaller than numberOfInputs 

above the conditionals to improve readability.

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#discussion_r959627473" expanded>

A very long conditional loop, could consider using switch statement and refactoring the code to improve user readability.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#pullrequestreview-1091929584" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#pullrequestreview-1091933555" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#pullrequestreview-1091936789" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/25#pullrequestreview-1091944708" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959635388" expanded>

This method runCommand is 31 lines long, excluding the ending curly braces it is still 29. A rather lengthy method and you can possibly improve code quality if you take corrective action.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959636165" expanded>

The naming of this method could be better, runCommand does not immediately explain the method to the reader accurately and at a sufficient level of detail. 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959642358" expanded>

LOGO is okay but GREET and BYE in your context are verbs and they are a constant variable so they should be named like nouns. For eg, GREETING and GOODBYE
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959650020" expanded>

Good appropriate naming for boolean methods and setter for boolean variable. Makes the code very readable.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#pullrequestreview-1091956312" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#pullrequestreview-1091957423" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#pullrequestreview-1091966117" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#pullrequestreview-1091977162" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 46. CHAN..HONG `@eehongchan` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960438345" expanded>

Good use of overriding!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960456372" expanded>

Good use of final variables!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960458665" expanded>

Can consider breaking up into 2 lines
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#discussion_r960459268" expanded>

Can consider splitting into 2 lines
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#pullrequestreview-1093082539" expanded>

**Review Status:** COMMENTED

Excellent coding standard!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/23#pullrequestreview-1093108270" expanded>

**Review Status:** COMMENTED

Good code, but could split up lengthy lines
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960446552" expanded>

Confusing variable name 'itemNo'
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960451739" expanded>

Inconsistent spacing
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960453147" expanded>

boolean should be small 'b'
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#discussion_r960454574" expanded>

Perhaps a switch case statement would make code more concise
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#pullrequestreview-1093094288" expanded>

**Review Status:** COMMENTED

No errors overall, can improve on naming variables
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/51#pullrequestreview-1093101648" expanded>

**Review Status:** COMMENTED

Minor formatting suggestions
</panel>

</panel>

<panel type="info" header="### 47. YONG.. HAN `@chinhan99` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959191516" expanded>

Good modification of the usage of the new line syntax. "line.seperator()" can indeed take up a lot of code space.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959192999" expanded>

Good use of  the constant string and correct syntax of using capital letters for naming the constant. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959195488" expanded>

Theres an alternative opportunity here to use switch case too. Not really a problem here. It is also great that you have a TaskManager class to process the user inputs instead of letting it solely handled within the Duke class
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959197460" expanded>

Naming of method seems ok. Maybe can add a short overview of the method so as to provide reviewers a better idea on what it does!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#pullrequestreview-1091334516" expanded>

**Review Status:** COMMENTED

Code and naming looks ok! Good job on the IP attempt!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959155631" expanded>

Good use of class UI, to process the input commands. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959156764" expanded>

Creative use of commands to provide a more intuitive UI for users to seek help 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959158754" expanded>

Good use of enumeration class to store the commands. Perhaps can add the enum as part of UI.java ?

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#discussion_r959160600" expanded>

Perhaps can consider removing the spaces ? Not sure if it violates the coding standards.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/18#pullrequestreview-1091287546" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 48. CHIA..HONG `@wcwy` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959154475" expanded>

I like how you name the parameters. It was clear when the number of tasks is different which of the corresponding line is printed.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959155290" expanded>

Aren't the line spaces here a violation of the if else{} coding structure? 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959155780" expanded>

Is there a need to use override methods on this (line 43-53)?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#discussion_r959156009" expanded>

It seems like this is a override method. Perhaps add a "\@Override" at line 18?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/9#pullrequestreview-1091286200" expanded>

**Review Status:** COMMENTED

Awesome code with great readability. Good job bro. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959158015" expanded>

Great use of static variables. Just one issue, shouldn't the naming be MARK_DONE and MARK_UNDONE instead?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959159798" expanded>

The naming for these two is rather confusing as BYE at the above refers to the command while the AT here refers to the contains condition
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959160839" expanded>

Which "item" it is referring to rather unclear
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959161234" expanded>

Input and inputs sound confusing when you are not storing the input directly into inputs
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#pullrequestreview-1091290799" expanded>

**Review Status:** COMMENTED

Overall it's a great piece of code, it was a pleasure to read it. Just some minor naming issue. 
</panel>

</panel>

<panel type="info" header="### 49. LEON..OWEN `@owenl131` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961263534" expanded>

Good use of string constants
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961263643" expanded>

Perhaps you meant "receive" :D
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961264500" expanded>

Good use of superclass method to reduce duplication
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961264808" expanded>

Good job, code looks easy to follow
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#pullrequestreview-1094278087" expanded>

**Review Status:** COMMENTED

LGTM
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/74#discussion_r961261476" expanded>

Please avoid using magic literals
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/74#discussion_r961261595" expanded>

Please start local variables with a lowercase letter
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/74#discussion_r961261832" expanded>

This could be `command.equals("todo")` instead
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/74#discussion_r961262242" expanded>

Please leave spaces on the left and right of operators (like +, -, etc)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/74#pullrequestreview-1094275713" expanded>

**Review Status:** COMMENTED

Would be good to split the code into functions or classes :)
</panel>

</panel>

<panel type="info" header="### 50. ZHAI..UXIN `@Zhai-Yuxin` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960430805" expanded>

ASSIGNMENTS is not a constant so you may want to make it to be not capitalized
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960432311" expanded>

you may want to put spacing after if
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960442020" expanded>

really nice formatting that make the printing code very easy to read
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960442822" expanded>

Same point as above, may want to add a spacing after if
there is similar places below too
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#pullrequestreview-1093071378" expanded>

**Review Status:** COMMENTED

overall good syntax, but only minor spacing issue here and there
good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r960451907" expanded>

you may want to consider to extract this part out as a new method
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r960452960" expanded>

you may want to consider having different methods for different command words
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r960456264" expanded>

you may want to remove this extra spacing
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#discussion_r960458040" expanded>

you may want to change the name "alphabet" to  eg. "taskType" to make it clearer
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/39#pullrequestreview-1093101933" expanded>

**Review Status:** COMMENTED

Overall good job! Just that some of your methods may be kind of long and you may want to consider using more methods to breakup your long ones.
</panel>

</panel>

<panel type="info" header="### 51. LEON..FRED `@alfred-leong` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959181427" expanded>

Perhaps naming it as "isMarked" will be better
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959183032" expanded>

Great job on explaining the functions of the case!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959183318" expanded>

Great use of case statements, very clear and concise 👍 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#discussion_r959183849" expanded>

Awesome way of using inheritance to make your code clear!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/40#pullrequestreview-1091321063" expanded>

**Review Status:** COMMENTED

Awesome, looks good to merge!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959177924" expanded>

hey I like how clean and readable your code is!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959178550" expanded>

I agree, it would be great to make this line more understandable
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959178890" expanded>

Great comment to help the reader understand what happens after the exit command 👍 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#discussion_r959179532" expanded>

It would be great to rename "args[0]" to a name that is easy for the reader to understand the variable
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/63#pullrequestreview-1091316568" expanded>

**Review Status:** COMMENTED

Looks good overall, maybe some minor changes to some variables and code to make it more readable would be aweomse!
</panel>

</panel>

<panel type="info" header="### 52. CHEA..O YI `@CheahHaoYi` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961265491" expanded>

Good use of ternary operation for compactness 👍 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961266039" expanded>

Good use of string constants! 😄  
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961266718" expanded>

I like how you created a class to encapsulate the functions of a user interface
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961267380" expanded>

good adherence to the Single Level of Abstraction
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#pullrequestreview-1094280637" expanded>

**Review Status:** COMMENTED

Very nice, clear and concise
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961262348" expanded>

The use of magic number here is ambiguous, feel free to consider using a constant
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961263123" expanded>

boolean values should be named to sound like booleans, consider "isMarked" or "isFinished"
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961264475" expanded>

Perhaps it would be better to have a method to print the string, rather than having a function that does both setting the boolean and printing
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#discussion_r961264670" expanded>

Consider using a switch-case statement for neatness
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/66#pullrequestreview-1094276723" expanded>

**Review Status:** COMMENTED

Nice
</panel>

</panel>

<panel type="info" header="### 53. ZHOU..IWEN `@maanyos` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959154263" expanded>

perhaps a different name for this variable? 
by doesn't really mean anything by itself
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959155374" expanded>

perhaps programIsFinished?
once again, isFinished doesn't really mean anything on its own, if it suddenly appears somewhere far down in the code
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959155792" expanded>

like this function & naming
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#pullrequestreview-1091285937" expanded>

**Review Status:** COMMENTED

good attention to naming syntax, however feel that some of the method/viarable names can be more descriptive
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959159344" expanded>

seems like this class is handling interaction with user, processing of user command, and managing the task objects, which is multiple layers of abstraction
suggesting grouping the diffrent uses together under separate classes
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959159469" expanded>

what does systemState mean?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959159737" expanded>

good use of final constant
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959160034" expanded>

like that you inform the user about error
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#discussion_r959160489" expanded>

good effort for making an output file!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/43#pullrequestreview-1091292517" expanded>

**Review Status:** COMMENTED

overall no vialoation of coding standards, but some name choices can be more descriptive. also duke seems to handle too many parts and it is quite hard to find a specific part, suggesting breaking down into more classes
</panel>

</panel>

<panel type="info" header="### 54. NG D..E QI `@ngdeqi` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961267478" expanded>

Perhaps you can let this method take in an integer type 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961268227" expanded>

Maybe a clearer term could be used, like "arguments"
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961268472" expanded>

I like the use of the switch case, it's more readable :)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#discussion_r961269260" expanded>

A bit of nesting here
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/54#pullrequestreview-1094283071" expanded>

**Review Status:** COMMENTED

Looks good overall, readable 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961262904" expanded>

Maybe you can avoid using magic numbers?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961263255" expanded>

Perhaps you can add a space between "if" and "(" 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961263728" expanded>

Maybe you can add spaces between "added: ", "+" and "command"
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#discussion_r961264389" expanded>

Maybe you could add a "public " before the constructor?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/67#pullrequestreview-1094277338" expanded>

**Review Status:** COMMENTED

Looks ok overall, just small coding standard problems
</panel>

</panel>

<panel type="info" header="### 55. BRAN..ARIF `@Brandon-OS` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960428485" expanded>

Don't forget to add spaces in between calculations (e.g. listIndex - 1)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960429204" expanded>

Consider adding a space after any loops or nesting (while (), if ())
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960429785" expanded>

Consider using capitalized letters for constants (LOGO)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#discussion_r960440868" expanded>

Consider adding a space between brackets e.g. ) and {
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/34#pullrequestreview-1093068025" expanded>

**Review Status:** COMMENTED

Overall, awesome job in making the code efficient and readable
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960446852" expanded>

Consider adding spaces in between method name and inputs
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960448801" expanded>

Good job on adding error handling!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960449256" expanded>

Consider writing variable names in full to make it more readable
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960451831" expanded>

Consider adding spaces in between calculations
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#pullrequestreview-1093094709" expanded>

**Review Status:** COMMENTED

Awesome job on finishing until Level 4! Great utilization of libraries!
</panel>

</panel>

<panel type="info" header="### 56. HE J..NWEN `@sylviahe171` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961276019" expanded>

good use of making every constant string output a constant
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961276185" expanded>

great redirection
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961276390" expanded>

good naming
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#discussion_r961276570" expanded>

good job for making things simple and clear
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/14#pullrequestreview-1094294857" expanded>

**Review Status:** COMMENTED

good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961263401" expanded>

good job for creating a manager class to manage the tasks
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961264207" expanded>

The use of switch made things pretty clear
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961264644" expanded>

4 appears to be magical number
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#discussion_r961264927" expanded>

can create a variable to store 100 so that length can be changed easily by changing the value of the variable
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/33#pullrequestreview-1094277915" expanded>

**Review Status:** COMMENTED

good job! 
high readability
</panel>

</panel>

<panel type="info" header="### 57. KRIS.. RAJ `@abhityakrishnaraj` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959185194" expanded>

Add a newline after the } for readability
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959196382" expanded>

No need to use this. for either one
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959197391" expanded>

Might be better to rename it to toString for easier access in all classes
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#discussion_r959198816" expanded>

Wrong output message here
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/42#pullrequestreview-1091325865" expanded>

**Review Status:** COMMENTED

Overall good, but some of the piece of code could definitely be more streamlined
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959177071" expanded>

Have an else statement to catch any incorrect inputs here
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959177824" expanded>

You should be able to just print out tasks using a to string method instead of rechecking.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959178377" expanded>

You don't need valueOf, you can just do count+"."+i
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#discussion_r959179822" expanded>

You can just use description instead of this.getDescription
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/56#pullrequestreview-1091315484" expanded>

**Review Status:** COMMENTED

Overall good job, but I think some things are overcomplicated
</panel>

</panel>

<panel type="info" header="### 58. PHUA..O YI `@matthewphua` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/62#discussion_r960432956" expanded>

consider adding space after getStatusIcon(). 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/62#pullrequestreview-1093074534" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960449136" expanded>

potentially add ---------... as a constant to increase readability of print statements. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960451536" expanded>

Avoid magic strings, so maybe for each of these cases, you can say for ex: LIST = "list" and reference the constant in the if statement
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960452363" expanded>

Break this function into smaller helper functions :) to increase readability.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960453524" expanded>

make taskType a static final variable and instantiate it not in the constructor 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960455076" expanded>

just do:
if (isDone) {
  this.isDone = false;
}
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960456520" expanded>

make sure to do brackets after the if statement and a line break for "return tempTask"
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#discussion_r960457422" expanded>

Magic String, maybe set "T" as a constant TASK = "T" so its easier for readers to know that T corresponds to task :) 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/73#pullrequestreview-1093097881" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 59. BAO ..IFAN `@AmethystQ` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959361723" expanded>

a smart way to assemble the output
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959380173" expanded>

Maybe convert the "bye" to a constant. Other places also recommended.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959385299" expanded>

Maybe add a "break;" here is clearer
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#discussion_r959388206" expanded>

prefer to use plural froms on names representing a collection of objects
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/19#pullrequestreview-1091573369" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959749223" expanded>

Maybe convert the number 100 to a constant?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959755453" expanded>

Maybe it's not so clear to use input and inputs at the same time when they refer to different objects
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959757576" expanded>

Logos and Intros can be extracted to a method, rather than directly putting in the main function
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959760091" expanded>

Good way to apply inheritance and override!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#pullrequestreview-1092118818" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 60. TEIM..RKUS `@Markusteim` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959180741" expanded>

I like the big amount of specific and clarified constants

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959181768" expanded>

You could remove the newline to keep the overall code similar.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959181978" expanded>

I like how you have broken the lines up to make it more readable
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959182108" expanded>

I like how you have kept it nice and clean here
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#pullrequestreview-1091320152" expanded>

**Review Status:** COMMENTED

Overall nice and good code following standards
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959178331" expanded>

Could remove whitespace to keep it same everywhere

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959178830" expanded>

I can't find much stuff to fill up the 4 comments needed, but nice logo 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959179349" expanded>

Maybe empty line at the end of files, so it would be known when to terminate the read
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#discussion_r959179549" expanded>

Same just could add empty line at the end of each file
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/30#pullrequestreview-1091317063" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 61. BEN .. MOR `@morbenami1` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961263345" expanded>

make name more informative
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961263823" expanded>

Great ! you remembered to add magic number
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961264372" expanded>

make name more informative
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#discussion_r961264639" expanded>

make name more informative
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/31#pullrequestreview-1094277839" expanded>

**Review Status:** COMMENTED

Overall, great code, good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961269376" expanded>

use magic number
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961269859" expanded>

instead of splitInput- inputSplitedBySpace
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961270837" expanded>

gread job! adding the final String for the mark status
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#discussion_r961271342" expanded>

change to a more informative name 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/57#pullrequestreview-1094285592" expanded>

**Review Status:** COMMENTED

Over all great job, amazing code and very creative :) 
</panel>

</panel>

<panel type="info" header="### 62. CHAN..N PU `@Frank-HP-Chang` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959541683" expanded>

easier to see with endline
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959542838" expanded>

nice with the notification.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959545287" expanded>

can combine together
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#discussion_r959546435" expanded>

can use a switch statement.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/10#pullrequestreview-1091822229" expanded>

**Review Status:** COMMENTED

Great work
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959180608" expanded>

clear code standard
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959517670" expanded>

Intro can be combined with logo
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959518331" expanded>

can call setAt
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#discussion_r959523048" expanded>

great to differentiate the Done and Undone
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/44#pullrequestreview-1091319990" expanded>

**Review Status:** COMMENTED

Great performance
</panel>

</panel>

<panel type="info" header="### 63. HEIN..YANG `@P0tatoChips` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959132103" expanded>

I like how you followed the naming conventions.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959134058" expanded>

I liked how you did this instead of using magic numbers.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959134981" expanded>

The rest of the cases don't have newline after the break; statement, maybe you can remove the newline to standardize?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#discussion_r959135642" expanded>

I liked how you got creative with the greetings.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/17#pullrequestreview-1091257559" expanded>

**Review Status:** COMMENTED

Overall, great code that generally followed the coding convections and coding standard. 👍 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959188826" expanded>

Maybe can use a named constant instead of using a magic number?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959189484" expanded>

I like how you used enumerations for the different type of commands.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959191258" expanded>

I like how you have already tried to deal with exceptions, anomalous input with the try and catch statements.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#discussion_r959194918" expanded>

Might I suggest you follow the coding convections and nestle your for loop with curly brackets.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/50#pullrequestreview-1091330662" expanded>

**Review Status:** COMMENTED

Overall, neat code with great readability. 
</panel>

</panel>

<panel type="info" header="### 64. SIM .. HUI `@qianz-z` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960440992" expanded>

camelcase should be setUndone()
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960443034" expanded>

Should use a better naming for variables (a, foo, first, second, cnt, etc)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960456959" expanded>

there is an addition space after the third item in the return section (after the ")
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960463940" expanded>

Array specifiers must be attached to the type not the variable.
should be String[] arr2
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#pullrequestreview-1093086236" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#discussion_r960457738" expanded>

can have a separate function to print the horizontal line so that it is not so repetitive
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#discussion_r960460467" expanded>

repetitive line that is long as well. can consider to create a new function or put it as toString method in the individual classes
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#pullrequestreview-1093110317" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 65. ISHI..NDAL `@ishitamandal06` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960436683" expanded>

The variable name arr does not explain what the array is being used for. Maybe you could rename this variable?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960437534" expanded>

The variable name foo does not explain what it is being used for. Maybe you can rename it?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960439474" expanded>

the function names are in camel case and are verbs so good job on that!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#discussion_r960441976" expanded>

Indentation for switch case is correct :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/13#pullrequestreview-1093080099" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960454857" expanded>

Hi! I think adding the word 'checked' makes it sound like a function instead of a boolean variable. 
Maybe you could change it to is Deadline?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#discussion_r960458641" expanded>

It becomes hard to understand what exactly is going on in this print statement because there are functions being executed inside the print statement itself. Maybe you could seperately execute the functions, store them in variables, and then print the variables? It would definitely make it easier to understand what is going on. :)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/32#pullrequestreview-1093106226" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 66. LIM .. JIE `@xzynos` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959135403" expanded>

The coding standard states not to use wildcard imports
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959137126" expanded>

This magic string does not provide any context about why it is being printed
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959138821" expanded>

This expression is complicated and hard to read
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959191633" expanded>

This code block is hard to follow. Do consider applying the Single Level of Abstraction Principle (SLAP)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959192876" expanded>

The coding standard states that a space is required between the closing bracket ) and the opening parenthesis {
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959193241" expanded>

The naming of the functions are clear and is easy to understand their purpose
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#pullrequestreview-1091261721" expanded>

**Review Status:** COMMENTED

This is a good attempt but do consider refactoring the code to make it easier to follow
</panel>

</panel>

<panel type="info" header="### 67. MUHA..UDIN `@insafhere` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#discussion_r960451210" expanded>

Method is clear, but you might want to consider changing getStatus to getMarkStatus to be specific and improve the understandability of the method
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#discussion_r960456119" expanded>

Good job on putting in all the test cases, but you might want to consider including the code separately for the switch cases "todo" and "deadline" for better understandability of the code!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#discussion_r960458465" expanded>

Might want to change the name of this boolean to isTaskCompleted for better understandability!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#discussion_r960460674" expanded>

You might want to change the name of this method to getTaskType for better understandability of the code from 3rd party!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/36#pullrequestreview-1093100905" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#discussion_r960437035" expanded>

Might want to include one space character for example "int i = 0 ; i &gt; inputs.size() ; i++"
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/71#pullrequestreview-1093080597" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 68. SYED..ORAN `@zoranabc201` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#discussion_r961263199" expanded>

Please avoid using magic literals
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#discussion_r961263973" expanded>

Please avoid using magic literals
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/12#pullrequestreview-1094277718" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961267924" expanded>

Thorough documentation. Well done!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961268083" expanded>

Good use of inheritance
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#discussion_r961269565" expanded>

Please change wrapped line indentation should to 8 spaces
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/22#pullrequestreview-1094283670" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 69. THAN.. HUY `@Than-Duc-Huy` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960448259" expanded>

Maybe this part can be made neater. e.g having "[D]" and "[X]" as 2 different String variables instead of a weird string like this "[D][" 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960449999" expanded>

Maybe you can put the content of runBot() in main()? Over compartmentalize might be bad
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960453166" expanded>

Maybe you can define and let the function throw Custom Duke Exception to check "invalid task" instead of if/else in each of them
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#discussion_r960454798" expanded>

The trailing underscore can be put in a constant
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/26#pullrequestreview-1093096637" expanded>

**Review Status:** COMMENTED

put the .class in .gitignore 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/60#discussion_r960458808" expanded>

Use your predefined constant EVENT_MARK
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/60#pullrequestreview-1093111840" expanded>

**Review Status:** COMMENTED

Overall, it is a good and neat code! All the magic literals are defined as constants. OOP, encapsulation and compartmentalization are clean! :)
</panel>

</panel>

<panel type="info" header="### 70. JAVI..QUAN `@jeyvia` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959134024" expanded>

Very organised "main" java file to direct to other java files to task, and to print the respective commands! 😁
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959136041" expanded>

I think you can include this in ConsoleInterface.java, with the rest of the print functions 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959136689" expanded>

I think you can have more test cases to test your corner cases! 😎
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#discussion_r959136842" expanded>

Nice following naming conventions! 😊
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/11#pullrequestreview-1091260019" expanded>

**Review Status:** COMMENTED

Overall, very good and neat code! Just a few minor changes :)
</panel>

</panel>

<panel type="info" header="### 71. LIM .. ROY `@lcsroy` (2 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#discussion_r959582911" expanded>

the naming convention is well used
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/ip/pull/20#pullrequestreview-1091881192" expanded>

**Review Status:** COMMENTED

correct naming convention and "{}" are standardised across all if-else statement
</panel>

</panel>

<panel type="info" header="### 72. WILL..YUDI `@snuckerzlol` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 73. VORA..MISH `@RiaVora` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 74. NG Y.. JIE `@yongjicode` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 75. NUR ..UTFI `@penguin-s` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 76. SHEN..CHEN `@yuu-chennn` (0 comments)"  collapsed>

n/a
</panel>
