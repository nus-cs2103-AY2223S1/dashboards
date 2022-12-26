%%[This page was last updated on Dec 05 2022]%% [**<span class="text-warning">:octicon-eye:</span> indicates those _watching_ the forum** (kudos :+1:)]


<panel type="info" header="### 1. NICH..RANG `@RussellDash332` (93 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Minor issues on Week 12 Project page**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/400" expanded>

- Duplicate QnA as seen in the image below.
  ![image](https://user-images.githubusercontent.com/63991775/198904499-bc8a9806-300f-43f3-bcc1-77442118e7eb.png)

- This should be "all (or almost all) the PE-D **bugs**" instead.
  ![image](https://user-images.githubusercontent.com/63991775/198904537-3e5d75fd-630f-423e-a955-6e88c9656077.png)

</panel>

<panel  header="**2. :fas-info-circle: Unable to retake Week 11 in-video quizzes**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/371" expanded>

n/a
</panel>

<panel  header="**3. :fas-info-circle: Bugs on Week 7 Topics**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/211" expanded>

- [x] Section 7.1, word 'UML' makes the page not scrollable upon embed preview
- [x] Cannot retake quizzes at 7.1, 7.3, and 7.7
</panel>

<panel  header="**4. :fas-info-circle: Help for smoke test for Mac and Linux users**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/197" expanded>

JAR file and user guide are given [here](https://github.com/RussellDash332/ip/releases/tag/A-Release). Appreciate any help!
</panel>

<panel  header="**5. :fas-info-circle: Unable to retake video quiz for Week 6**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/167" expanded>

Similar to #139 and many other issues.
</panel>

<panel  header="**6. :fas-info-circle: JavaFX UnsupportedOperationException: Unable to open DISPLAY**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/118" expanded>

Currently unable to launch the `Launcher` class due to this exception. One can take a look at the current status [here](https://github.com/RussellDash332/ip/tree/branch-Level-10).

* IntelliJ version: 2022.0
* Java JDK version: 11.0.8
* JavaFX version: 11
* Gradle version: 6.2
* OS: Linux Ubuntu 20.04.2 LTS focal (inside Windows 10 but not dual booting)

Approaches done so far:
* `export DISPLAY=:0`, but no effect
* Closing the project after deleting `.idea`
* Changing to other versions of JavaFX, such as version 18.0.2, on both local and Gradle, to no avail
* Actually using the Windows Command Prompt to no avail

The exact same issue seems to be discovered in other repos but they are pretty much repository-dependent. I was wondering if anyone can help me on this. Thanks!

```
Exception in thread "main" java.lang.UnsupportedOperationException: Unable to open DISPLAY
	at javafx.graphics/com.sun.glass.ui.gtk.GtkApplication.lambda$new$6(GtkApplication.java:173)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at javafx.graphics/com.sun.glass.ui.gtk.GtkApplication.<init>(GtkApplication.java:171)
	at javafx.graphics/com.sun.glass.ui.gtk.GtkPlatformFactory.createApplication(GtkPlatformFactory.java:41)
	at javafx.graphics/com.sun.glass.ui.Application.run(Application.java:144)
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumToolkit.startup(QuantumToolkit.java:258)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:269)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:834)
```
</panel>

<panel  header="**7. :fas-info-circle: Cannot scroll after opening embedded page**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/109" expanded>

Similar to #1, but [this link](https://nus-cs2103-ay2223s1.github.io/website/se-book-adapted/chapters/codeQuality.html) instead.

(Issue was found when clicking `SLAP Hard -&gt; "abstraction"` but I think other embedded pages within the same page have similar issues)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/2#issuecomment-1214135463" expanded>

Currently, the colors do help in differentiating the 4-star topics from the non-4-star ones, but it will still be (slightly?) hard to differentiate the importance among the 1-3 star topics. Since it's too late to do this now, I guess we'll try our best to get used to the current system, we definitely can :)

Also, the current star system reminds me of DEFCON 😅
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/10#issuecomment-1217191230" expanded>

While it is not stated whether the use of `ArrayList` is permitted for `Level-2`, it should be allowed as there is no restriction. The use of `Arrays` is just a suggestion. You will actually use `ArrayList` on `Level-6` anyways.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217911842" expanded>

I think this is the supposed workflow, CMIIW.
1. Fill in the input at input.txt
2. Run runtest and copy the actual execution result to expected text file
3. Rerun runtest, should be passing now
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/16#issuecomment-1218246275" expanded>

You can change the permission of the file (that should be allowed for now?)
```sh
$ chmod 744 runtest.sh
```
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1219117250" expanded>

Have you fed `input.txt` some input commands?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/40#issuecomment-1221240344" expanded>

The question is answered [here](https://stackoverflow.com/questions/23791999/why-does-git-commit-amend-change-the-hash-even-if-i-dont-make-any-changes).

However, you can force push the tags because they are just your own bookmarks for the project, and just add a new commit instead of overwriting the previous one.
```
git tag -f Level-x
git push -f --tags
```
(assuming you only want to change the tag)
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/40#issuecomment-1221243408" expanded>

> Hi. Does the answer suggests that the only way to change the title or description of the commit is to create a new commit with a different timestamp?

You mean the same timestamp, in order not to change the commit ID? I believe so.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/32#issuecomment-1221244673" expanded>

To some extent, it depends on your code. While the five things you mentioned above are definitely applicable to almost all of us, we can definitely add more depending on the code and how are you planning to exploit it.

For example, using `Integer.parseInt`? We can exploit with supplying a with non-integers of different types just like what you said on point 5.

Another example, my command handlers executes the input like it's a Java code (let's say) so I can add a test whether injecting a malicious Java code will work or not, who knows I can input a Java code that runs a shell script to remove files from your end :)
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/101#issuecomment-1230489260" expanded>

Good intermezzo 😆 
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/108#issuecomment-1231114320" expanded>

This is because it's not under the `duke` directory. You can simply nest everything in `java` directory into `java/duke` directory.

Note: imo this is better than renaming `java` to `duke` as it might mess up your Gradle/JUnit build
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/108#issuecomment-1231122902" expanded>

You might need to modify `build.gradle` as well as the Gradle setup in the project accordingly
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/108#issuecomment-1231128361" expanded>

Nice, glad to see it finally worked! 😌
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/110#issuecomment-1231904042" expanded>

Looking at [Parser.java here](https://github.com/se-edu/addressbook-level2/blob/master/src/seedu/addressbook/parser/Parser.java), you can see that giving names to the capturing group helps you to capture the respective keywords. I guess you can make use of that and hopefully will make it easier to extract.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/110#issuecomment-1231916337" expanded>

An example of this would be something like this.
```java
String task = "[E][ ] dancing (at: 14 Aug 2022 1200)";
Pattern pattern = Pattern.compile("\\] (?<description>[&hat;\\(]*)\\(at: (?<time>.*)\\)"); // might not work
Matcher matcher = pattern.matcher(task);
String description = matcher.group("description");
String time = matcher.group("time");
```
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/110#issuecomment-1231925917" expanded>

> > '''java
> > String task = "[E][ ] dancing (at: 14 Aug 2022 1200)";
> > Pattern pattern = Pattern.compile("\\] (?&gt;description>[&hat;\\(]*)\\(at: (?&gt;time>.*)\\)"); // might not work
> > Matcher matcher = pattern.matcher(task);
> > String description = matcher.group("description");
> > String time = matcher.group("time");
> > '''
> 
> Thanks for replying and I just tried your code via an online compiler and it shows error.
> '''
> /MyClass.java:4: error: cannot find symbol
>         Pattern pattern = Pattern.compile("\\] (?&gt;description>[&hat;\\(]*)\\(at: (?&gt;time>.*)\\)"); // might not work
>         &hat;
>   symbol:   class Pattern
>   location: class MyClass
> /MyClass.java:4: error: cannot find symbol
>         Pattern pattern = Pattern.compile("\\] (?&gt;description>[&hat;\\(]*)\\(at: (?&gt;time>.*)\\)"); // might not work
>                           &hat;
>   symbol:   variable Pattern
>   location: class MyClass
> /MyClass.java:5: error: cannot find symbol
>         Matcher matcher = pattern.matcher(task);
>         &hat;
>   symbol:   class Matcher
>   location: class MyClass
> 3 errors
> '''
> 
> I believe I have found the solution already. 
> the trick is to add `timeMatcher.find();`.

Glad you managed to solve it. Seems like you didn't import `java.util.regex` on the online compiler yet?

Update: you commented faster haha
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/114#issuecomment-1232761658" expanded>

Have you taken the xml files from the addressbook3 repository?
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/118#issuecomment-1233941954" expanded>

> - Switch to zulu-11's jdk 11.0.16 from [here](https://www.azul.com/downloads/).
> - Update fx:controller="MainWindow"> to fx:controller="stashy.launcher.MainWindow"> in line 9 of MainWindow.xml.
> - Add an images folder to the resources directory.

Thanks for this @kxrt! Switching to zulu is one possible solution for me to run the GUI outside WSL, which definitely does not support GUI when it comes to mine. I purposely haven't added an image the moment you cloned it because I wasn't ready with a good one 😆

> Changing javaFxVersion to 14 in build.gradle seems to fix the garbled text, but I'm not sure if that's a hack or a proper solution to this issue.

Interesting, mine works with JavaFX 11 but I'll try it with a Mac laptop sometime later. Thanks for letting me know about this.

> A common cause of Unable to open DISPLAY is using an environment that doesn't support GUI applications. At least some versions of WSL don't support GUI applications.

You are right Prof @damithc, I do suspect both my Ubuntu CLI and Windows Command Prompt don't support GUI. This happened to another GUI application I had with Python back then. Based on what is said above, opening directly with the JDK (not even Gradle since it makes use of the command line) is the solution

> I agree that it could be a WSL error. WSLg is currently only for Windows 11 so you might need to run the application on your Windows system.

Right, new knowledge indeed, thanks @malwaregarry!

Closing the issue now, thanks for the help!
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1235348810" expanded>

Changes:
- Smaller image
- Add background for both dialog box (rounded corner rectangles) and main window (gradient background)
- Random image for the bot
- Add prompt `Write a message...` on text field

Small rant, `minHeight="-Infinity"` is important to not collapse the dialog box when it has too many lines 😖 

![image](https://user-images.githubusercontent.com/63991775/188122843-07725ceb-0bc4-4c04-bbff-80bcf9ab6113.png)

</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/128#issuecomment-1235436752" expanded>

You need to set `minHeight="-Infinity"` for `DialogBox`. Hope this helps!

Edit: Just copy this FXML I updated for you. There should be a button to copy everything so no need to drag the whole thing.
```xml
<fx:root alignment="TOP_RIGHT" minHeight="-Infinity" maxHeight="1.7976931348623157E308" maxWidth="1.7976931348623157E308" prefWidth="400.0" type="javafx.scene.layout.HBox" xmlns="http://javafx.com/javafx/18" xmlns:fx="http://javafx.com/fxml/1"> <children> <Label fx:id="dialog" style="-fx-background-color: yellow; -fx-background-radius: 20; -fx-label-padding: 8;" text="Label" wrapText="true"> <HBox.margin> <Insets /> </HBox.margin></Label> <ImageView fx:id="displayPicture" fitHeight="99.0" fitWidth="99.0" pickOnBounds="true" preserveRatio="true"> <HBox.margin> <Insets left="5.0" right="5.0" /> </HBox.margin></ImageView> </children> <padding> <Insets bottom="5.0" left="15.0" right="5.0" top="15.0" /> </padding> </fx:root>
```
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/128#issuecomment-1235600617" expanded>

> Ohhh thank you so much! Can I just ask what does adding that setting do to the DialogBox and why it makes things work HAHA
> 
> Does it like set the minimum height of the DialogBox to negative infinity and does that mean like infinitely small

It's somewhat a long-term issue, even it can be discovered until [2 years ago](https://github.com/nus-cs2103-AY2021S1/forum/issues/125#issuecomment-683547168).

I didn't try to figure out the rigour on why is this the case but it seems that Slaw's comment on [StackOverflow](https://stackoverflow.com/questions/54441636/dynamically-changing-height-with-prefheight-is-not-working) kind of makes sense.

Speaking about this, I wonder why is this not set by default on the JavaFX tutorial's FXML? It would be a good thing 😄
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/138#issuecomment-1236195626" expanded>

Hi @xav168, I managed to fork your repository and here's what I did:
1. Add images to `src/main/resources/images` accordingly
2. Generate the JAR from command line, i.e. `./gradlew shadowJar`
3. Run the JAR file located at `build/libs/duke.jar` by double-clicking it

After step 3, I managed to get this
![image](https://user-images.githubusercontent.com/63991775/188287053-192b96bc-8a2e-4cdf-99a4-4540e9f1c177.png)

So I guess what @AllardQuek said is true, you might need to specify how did you build the JAR file, so you can compare with what I did. Hope this helps!
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/142#issuecomment-1236196930" expanded>

By right, it should be placed in `[root]\.github\workflows`. However, it's not a necessary condition.

[This repository](https://github.com/RussellDash332/test-repo/actions) tests how you can setup GitHub Actions without putting the YAML file on that directory structure.

You can do it manually by creating a workflow, choose "setup a workflow by yourself", and edit the YAML file as you wish.
![image](https://user-images.githubusercontent.com/63991775/188287343-38abf679-2458-4997-b6a7-2197b32402aa.png)

</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/143#issuecomment-1236267124" expanded>

It could be the similar case to #118 where GUI is not supported. To run the whole application, you need to double-click the JAR file that you can build.
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/147#issuecomment-1237507022" expanded>

@izzahaj Looking at [this page](https://github.com/AY2223S1-CS2103T-T12-4/tp/runs/8188649343?check_suite_focus=true), the issue is just checkstyle. You simply need to add a newline at the EOF of Main.java.
```
Run ./run-checks.sh
  ./run-checks.sh
  shell: /usr/bin/bash -e {0}
ERROR:../src/main/java/seedu/address/Main.java:[2](https://github.com/AY2223S1-CS2103T-T12-4/tp/runs/8188649343?check_suite_focus=true#step:5:2)6: no newline at EOF.
Error: Process completed with exit code 1.
```

Note that you can commit without doing any modifications at all, you can see how Prof did the same thing at [the iP dashboard](https://github.com/nus-cs2103-AY2223S1/ip-dashboard)
```sh
git commit --allow-empty
```
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/149#issuecomment-1239012387" expanded>

You can see [this comment](https://github.com/nus-cs2103-AY2223S1/forum/issues/89#issuecomment-1229195856) on how to rename a branch
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/150#issuecomment-1239122621" expanded>

See #118. Hope it helps!
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/149#issuecomment-1239795455" expanded>

> Thanks, @RussellDash332 But if I rename it now, the dashboard still reflects as overdue, is it?

Yup, as Prof said, those are soft deadlines so that you can keep on track 💪🏻 
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/151#issuecomment-1239796815" expanded>

You'r'e right 😮 the ad-hoc solution is to indeed rotate it into landscape mode, but still I suppose they need to make the div smaller in size 😅 
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/157#issuecomment-1240535854" expanded>

#104 #117 #125 might help you resolve the issue!
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/195#issuecomment-1247710372" expanded>

Works on my Windows 10 as well! 🚀 
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/194#issuecomment-1247711486" expanded>

Works on my Windows 10, good work! 🚀 
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/197#issuecomment-1247808023" expanded>

> Hello @RussellDash332, all your commands in your UG works on macOS, just remove the comma for deadline and event example in your UG and should be good to go.
> 
```
> event Go to Jurong /at Aug 10 2022 13:30
```

Great, thanks for your help!
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/210#issuecomment-1248539303" expanded>

Nope, but do tag with A-Release as the tag name
</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/225#issuecomment-1249328410" expanded>

<img src="https://user-images.githubusercontent.com/63991775/190643198-14f812c6-649e-4e24-9519-90bd1be380f5.png" width="40%">
Works on Windows 10!
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249347112" expanded>

Works on Windows 10! The quick start and detailed guide also works adding on to the previous comment
<img src="https://user-images.githubusercontent.com/63991775/190646208-dd2c8410-c561-4dd1-b9d9-156f51d325b9.png" width=40%>
</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/218#issuecomment-1249350360" expanded>

Works on Windows 10!

![image](https://user-images.githubusercontent.com/63991775/190647045-1ae9f2fc-0aba-41d1-b1dc-a2e61cb1e637.png)

</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249393240" expanded>

Resizing is disabled now so that's good. The application title seems to be weird now
![image](https://user-images.githubusercontent.com/63991775/190655017-8697e629-54bd-4864-9036-b00df22ca64e.png)

</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/235#issuecomment-1249624054" expanded>

As stated, you need to set up the JDK first for this current project.
</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/237#issuecomment-1249660651" expanded>

According to [this](https://stackoverflow.com/questions/5751585/how-do-i-rename-a-repository-on-github), it's fine since you're the only one working on that particular repo, but do take a look on how to reconfigure the git configs correctly
</panel>

<panel  header="**47 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/237#issuecomment-1249667125" expanded>

> Thank you @RussellDash332! But I was wondering if this was a CS2103T requirement? 

What do you mean with requirement? The repo name should be "ip" only so
</panel>

<panel  header="**48 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/244#issuecomment-1250055207" expanded>

Works like a charm! Nice header btw!
![image](https://user-images.githubusercontent.com/63991775/190854561-4402ec1c-eb84-4ea5-904c-0e398c79917a.png)

</panel>

<panel  header="**49 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/243#issuecomment-1250056708" expanded>

Change line 16 of `runtest.sh` to
```sh
if ! javac -cp ../src/main/java -Xlint:none -d ../bin ../src/main/java/duke/*.java
```
and line 23 to this.
```sh
java -classpath ../bin duke/Duke < input.txt > ACTUAL.TXT
```

Similarly, line 10 in `runtest.bat`
```bat
javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\duke\*.java
```
and line 18.
```bat
java -classpath ..\bin duke\Duke < input.txt > ACTUAL.TXT
```

Let me know if this works 😁 
</panel>

<panel  header="**50 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/243#issuecomment-1250075003" expanded>

Yup, that seems like an unsupported GUI issue, and since this test is just for text UI testing, it should run the non-GUI version instead.
</panel>

<panel  header="**51 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/249#issuecomment-1250211577" expanded>

See #118. (edit: sorry, tagged the wrong issue :D)
</panel>

<panel  header="**52 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/259#issuecomment-1250377387" expanded>

<img src="https://user-images.githubusercontent.com/63991775/190926187-9804e5bc-8b35-40a1-aae8-6b0c4e7e4dde.png" width="50%">
Works on Windows, but this is what happens when I resize it.
</panel>

<panel  header="**53 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/267#issuecomment-1251048412" expanded>

Seems correct to me if you're referring to `reasonable` as it's for `tasks`, a plural.
</panel>

<panel  header="**54 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251051088" expanded>

[This is the JAR](https://github.com/DarrenCsAcc/ip/releases/tag/A-Jar) for quick reference.

Same as @rui-han-crh, I have the same issue so the JAR doesn't open. The suggestion given above might help fixing it!
</panel>

<panel  header="**55 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/229#issuecomment-1251054709" expanded>

Works for me as well, even when I try to resize the window. Awesome work, Artemis!

![image](https://user-images.githubusercontent.com/63991775/191033933-49603964-90bc-4084-bf7a-335eaa7c0cd3.png)

</panel>

<panel  header="**56 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251102654" expanded>

It creates a text file `help.txt` right away and the application doesn't open on my end. Let me see what happens and get back to you.
</panel>

<panel  header="**57 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251114214" expanded>

Fixed by changing the application name on `build.gradle`
```
application {
    mainClassName = "duke.Launcher"
}
```

Once changed, this happens on my end.
![image](https://user-images.githubusercontent.com/63991775/191043781-322e50ca-1357-4b73-821e-53cd853ab170.png)

</panel>

<panel  header="**58 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/267#issuecomment-1251116687" expanded>

> Is `reasonably sized, standalone tasks` better?

Agree, this sounds better 😆 
</panel>

<panel  header="**59 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251171773" expanded>

> @rui-han-crh @RussellDash332 Thanks guys for putting in so much effort in helping me i will work on it and get back to you guys.

No problem, pleasure to help!
</panel>

<panel  header="**60 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/279#issuecomment-1252849724" expanded>

Everything works fine in Windows, but I managed to "crash" the app by typing this input, I suppose it happens analogously to deadlines.

<img src="https://user-images.githubusercontent.com/63991775/191353874-719969bd-ea83-4e0b-a1f3-a9f0812a5366.png" width="45%">
</panel>

<panel  header="**61 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280#issuecomment-1252858767" expanded>

LGTM! (Windows)
Resizing is also okay.

![image](https://user-images.githubusercontent.com/63991775/191354844-5e54e0e2-4a60-4148-b284-d3fbe08329f7.png)

</panel>

<panel  header="**62 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/281#issuecomment-1252865342" expanded>

Hi, currently using Windows. Overall it looks fine to me.

<img src="https://user-images.githubusercontent.com/63991775/191355319-0885c78f-5e76-4dc6-be25-507ca5ea48e6.png" width="50%">

Some inputs that might cause an error (not sure if this is a feature to not handle anything or a bug):
- `event a /at`
- `mark 3` (only < 3 tasks in the list)

But it would be a good if there's exception handling for this.

Your windows seems to be off when being resized. If you don't want to fix this, you can disable resizing by adding `            stage.setResizable(false)` to your `Main.java` code. (example: [this line](https://github.com/RussellDash332/ip/blob/master/src/main/java/stashy/launcher/Main.java#L28))
</panel>

<panel  header="**63 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/282#issuecomment-1253155315" expanded>

Works on Windows for all the happy paths :)

I like how this happens when I change the data file.
![image](https://user-images.githubusercontent.com/63991775/191406891-3836b95f-1de0-46cd-ba49-980631f6817f.png)

However, some non-happy paths to consider:
- `event test /by`
- `event test /at`
![image](https://user-images.githubusercontent.com/63991775/191406745-54d48535-19ba-49c0-83c2-b648f0adbb48.png)

</panel>

<panel  header="**64 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/283#issuecomment-1253173739" expanded>

Can you try changing [this line](https://github.com/SpecOps2016/ip/blob/master/build.gradle#L44) to `Launcher`?

Source: #111 #176 #190
</panel>

<panel  header="**65 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/284#issuecomment-1253360779" expanded>

I downloaded your `v0.2` jar and clicked on it directly, `deadline deadline` already gave me an error even when you specify the `build.gradle` correctly...
</panel>

<panel  header="**66 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/284#issuecomment-1253385868" expanded>

I tried using the text UI testing to see what's wrong.
Here's what I did:
- Modifed `runtest.sh` on these two lines
  - `if ! javac -cp ../src/main/java -Xlint:none -d ../bin ../src/main/java/duke/*.java`
  - `java -classpath ../bin duke/Duke < input.txt > ACTUAL.TXT`

I found that your `ACTUAL.txt` is not overwritten somehow, so it passes only if I put nothing on `EXPECTED.txt`.

Furthermore, if I have `deadline deadline` on `input.txt`, I get this which might help resolving your error. (Line 221 of TaskList has been stated by @rui-han-crh, this is thus a further verification)
```
Exception in thread "main" java.lang.ArrayIndexOutOfBoundsException: Index 1 out of bounds for length 1
        at duke.TaskList.addDeadlineTask(TaskList.java:221)
        at duke.TaskList.addTaskType(TaskList.java:196)
        at duke.Parser.editTask(Parser.java:112)
        at duke.Parser.reply(Parser.java:93)
        at duke.Ui.run(Ui.java:31)
        at duke.Duke.run(Duke.java:41)
        at duke.Duke.main(Duke.java:61)
```
</panel>

<panel  header="**67 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1253459478" expanded>

> hi prof, can I check if the resizing of window is a requirement? @Yongbeom-Kim i checked with my friend on linux and he can run using java -jar duke.jar

Not Prof but I don't think so, it's up to us how we want to optimize the GUI
</panel>

<panel  header="**68 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/285#issuecomment-1253500358" expanded>

Hi, can you push your code to the branch `tutorial-adding-command` first so we can take a look directly?
</panel>

<panel  header="**69 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/281#issuecomment-1253520129" expanded>

#128 might [help](https://github.com/nus-cs2103-AY2223S1/forum/issues/128#issuecomment-1235436752) to resolve the issue!
</panel>

<panel  header="**70 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/285#issuecomment-1253548441" expanded>

This **did** happen to me once but it's not reproducible.
```
> Task :jacocoTestReport
[ant:jacocoReport] Classes in bundle 'tp' do not match with execution data. For report generation the same class files must be used as at runtime.
[ant:jacocoReport] Execution data for class seedu/address/model/person/Person does not match.
[ant:jacocoReport] Execution data for class seedu/address/model/person/Remark does not match.
```
The next few runs of `jacocoTestReport` are all a success.
</panel>

<panel  header="**71 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/285#issuecomment-1253554557" expanded>

I suggest what you can do is reopen the project or delete the ignored directories as they might store some cache.
</panel>

<panel  header="**72 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/286#issuecomment-1254013058" expanded>

#128 might help you!
</panel>

<panel  header="**73 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/287#issuecomment-1254233038" expanded>

You can do it in another class method. It shows the bye string first aka printing the function's return value, then it exits.
</panel>

<panel  header="**74 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/289#issuecomment-1254661713" expanded>

Overall, the happy path works for me, but `find a` seems to not return the correct list, unless you're including the time as well.

The window seems to be weird when I resize it.

![image](https://user-images.githubusercontent.com/63991775/191690127-f2c1686f-c918-457f-ac19-c722e3b08eb5.png)
</panel>

<panel  header="**75 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/291#issuecomment-1254978230" expanded>

![image](https://user-images.githubusercontent.com/63991775/191751452-6712d944-facf-4ddb-ad02-3da5e36aca22.png)

Works like a charm on Windows!
</panel>

<panel  header="**76 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/289#issuecomment-1255031781" expanded>

> Thanks for the help @RussellDash332 and @RezwanArefin01! I have fixed the bug in "find", disabled resizing, and changed the Duke image to .png. Do you guys mind helping me check one more time to see if all's good? The newest release is [here](https://github.com/JonathanWiguna/ip/releases/download/v0.2/duke.jar). Thank you so much!

LGTM!
</panel>

<panel  header="**77 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/292#issuecomment-1255213317" expanded>

Works on Windows! I was confused on why one of the commands that you provide didn't work until I realize I had an extra leading space. Would suggest to strip them but other than that the syntax is friendly enough to me as you provided multiple prefixes!

<img src="https://user-images.githubusercontent.com/63991775/191791379-78315461-8a3b-4326-a4f7-79ed73c733c0.png" width=40%>
</panel>

<panel  header="**78 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/295#issuecomment-1255410574" expanded>

![image](https://user-images.githubusercontent.com/63991775/191826133-d0932da8-f5ae-414c-b4e6-574e8fc5f584.png)
Works fine on Windows!
</panel>

<panel  header="**79 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/294#issuecomment-1255415285" expanded>

Tested with Windows. The two inputs below seem to be an issue to resolve.

<img src="https://user-images.githubusercontent.com/63991775/191826634-41df0f77-0887-4220-a979-5341f33cdf8e.png" width=40%>

The `find` command seems to have an issue as well.

<img src="https://user-images.githubusercontent.com/63991775/191826841-ef1a9a90-04d5-4f28-adbf-a6a84a3b1d2c.png" width=40%>

</panel>

<panel  header="**80 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/296#issuecomment-1255870864" expanded>

Works fine on Windows except I don't see where my file is saved and I can say goodbye multiple times.
Update: found the file, it's at its parent directory 😅 

![image](https://user-images.githubusercontent.com/63991775/191909373-5d1f0bde-f66c-4020-bd6b-cbdca41baabf.png)

</panel>

<panel  header="**81 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/300#issuecomment-1255935287" expanded>

Normal scenarios work well on Windows, except for this: the month of deadline/event.
<img src="https://user-images.githubusercontent.com/63991775/191920883-6d20f402-64cf-44f9-918b-e1ce51f70f1b.png" width=40%>

Is this error message supposed to be exposed to the user?
<img src="https://user-images.githubusercontent.com/63991775/191920770-3f2eb45b-4476-4e8d-9e8a-ed8889da9abd.png" width=40%>
</panel>

<panel  header="**82 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/300#issuecomment-1255942301" expanded>

> it should be 15/03/2022 not 15/3/2022. That's why it caused that error. It has to be specifically that way. I should write this clearer in the UG. Thank you for testing

No problem. Yup, it's `15/3/2022` in your UG.
</panel>

<panel  header="**83 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1256519829" expanded>

Works well on Windows!
![image](https://user-images.githubusercontent.com/63991775/192029669-55bd826f-af1c-42a9-8243-b67c94a6f153.png)

This is what happens when I mess with the task data file.
![image](https://user-images.githubusercontent.com/63991775/192029884-44dd44bd-c016-4244-8363-9127e329396a.png)

</panel>

<panel  header="**84 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/303#issuecomment-1257004478" expanded>

  Works fine in Windows but I have these issues:
- Resize issue + broken Duke logo?
  <img src="https://user-images.githubusercontent.com/63991775/192108069-f20daf1a-8065-46ad-bc1d-8eab61ec14a5.png" width=50%>
- Some bugs on event and deadline, where the error message doesn't really match the input's intention
  <img src="https://user-images.githubusercontent.com/63991775/192108149-382b955b-f1dd-4861-bff5-92f42dd6cfe3.png" width=50%>

Also tried to mess up the data file and the JAR doesn't open.
</panel>

<panel  header="**85 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/308#issuecomment-1257975799" expanded>

What's currently on top of my head is to reset by (your number of commits in tutorial-adding-command) + 1 commits (the merge commit), then push force.

Edit: However since it's not your team repo, there's no harm repulling the master branch from the team repo (by force), which is unmodified, and make a PR directly from the tutorial-adding-command branch
</panel>

<panel  header="**86 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/310#issuecomment-1259518994" expanded>

Have you tried rerunning your jobs? It seems indeterministic
</panel>

<panel  header="**87 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/310#issuecomment-1259637429" expanded>

> Have you tried rerunning your jobs? It seems indeterministic

The same thing goes to Codecov issue with an extra step of regenerating the API token
</panel>

<panel  header="**88 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/306#issuecomment-1261120474" expanded>

@junlee1991

- Windows: no issue other than the functionalities (#300)
- Linux-Ubuntu: #246 (as said by @Yongbeom-Kim)
- Mac:
  This depends on what the error below what is stated by @yuehernkang is. It can be either of these issues: #88, #190, #234, #276
- Linux-Arch:
  - You can set the stage to be unresizable by adding the line `stage.setResizeable(false);` at `Main.java`
  - Image not loading: [this comment](https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249137283), credits to @RezwanArefin01

All the best on fixing them!
</panel>

<panel  header="**89 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/305#issuecomment-1261125962" expanded>

> Hi I've attempted to fix it, any kind soul would help with a simple smoke test [here](https://github.com/Isaaclhy00/ip/releases) ?

JAR file can be opened now!
Here's some snapshots of the test that I did and see whether it's a feature or not.
By the way, `mark/unmark <invalid index>` will not give me anything. It could be an error reflected on the logger, e.g. `mark 0`

<img src="https://user-images.githubusercontent.com/63991775/192828617-af86ce19-2536-4e28-ab3d-29bf6243233f.png" width=40%>
<img src="https://user-images.githubusercontent.com/63991775/192828663-f52de22a-8e71-4eed-9060-a3e1083025c3.png" width=40%>

Typing `bye` will give you the OOPS idk what it means but it closes the app. Furthermore it doesn't save the task list.
</panel>

<panel  header="**90 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1262472015" expanded>

Have you tried re-running the CI on your own tp repo? I don't see the github-pages workflow as well. This is what I see from your AboutUs branch
![image](https://user-images.githubusercontent.com/63991775/193078124-31711548-f405-4120-be8a-1e7b83187b4d.png)

This is from your PPP branch
![image](https://user-images.githubusercontent.com/63991775/193078200-961f1962-4f50-4222-bbaf-c4276931c8fd.png)

</panel>

<panel  header="**91 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1262490211" expanded>

See #309.
</panel>

<panel  header="**92 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/335#issuecomment-1278982049" expanded>

Codecov errors are actually nondeterministic. Another job retry or refresh on codecov token will fix.
</panel>

<panel  header="**93 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/493#issuecomment-1326031824" expanded>

Related issue at #489
</panel>

</panel>


<panel type="info" header="### 2. REZW..EFIN `@RezwanArefin01` (65 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Reconsider use of web-browser in finals**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/488" expanded>

> Do not use Web Browsers, even to view local files. 
> Reason: invigilators will not be able to distinguish viewing local files from visiting online websites. 

Does the invigilator need to check accessing online websites, when Exemplify already blocks access to the internet? I guess it is to stop communication in between the parts of the exam. But does just not allowing use of a browser prevent that? Since the examinees will have internet access in the venue anyway. 

Also the reason given for the restriction does not seem very rational, as web-browsers can look like PDF readers and vice versa. It is likely that invigilators will still not be able to tell the difference from far away even with this restriction. 

And for many of us, web-browser is the way to view PDFs; uncomfortable using other readers. This restriction gives slight advantage to those using PDF readers regularly.

IMO, the restriction adds very little security while making it inconvenient for many. Please reconsider the restriction. :pensive: 

</panel>

<panel  header="**2. :fas-info-circle: Including font inside jar vs asking users to install fonts**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/208" expanded>

I am using a specific font (albeit very common) as the main font in my iP. However, the user may not have the font installed. In that case I think he won't be able to view it properly, since I don't see the font being shipped with the jar. However, I think including the font inside the jar may have some LICENSE issues, which I know nothing of. 

Also I use some unicode emojis as the task type symbols. Some people are also not being able to view them (and some can)! It is most likely caused by not having a font that can render those specific unicodes. What should I do in this case? I cannot find the font that contains the emojis.

For iP grading, is this considered a defect? In case the user don't have proper fonts installed. Some systems (at least some linux fontconfig) define an order in which fonts are tried. So, it may happen the emoji is not rendering even though the user has the proper fonts for it. So I think if the fonts are not working properly, it is a fault of the user's system and not mine?
</panel>

<panel  header="**3. :fas-info-circle: Modules policy on code / documentation written by GitHub Copilot**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/51" expanded>

What is this module's policy on code written by GitHub Copilot? Since there are a lot of public repository implementing this project, copilot will almost be copying code from them. The current code reuse policy for external sources says: 

> You clearly give credit to the original author. Acknowledge use of third party resources clearly e.g. in the welcome message, splash screen (if any) or under the 'about' menu. If you are open about reuse, you are less likely to get into trouble if you unintentionally reused something copyrighted.

In case of Copilot, it would be almost impossible to give credit. ~~Should I write `@@author GitHub Copilot`?~~

Also the javadoc generated by Copilot is almost accurate. Multiple students using Copilot to write javadocs may result in incorrect plagiarism verdict. 

</panel>

<panel  header="**4. :fas-info-circle: Upstream ip repository has ACTUAL.txt in .gitignore**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/21" expanded>

Should be `ACTUAL.TXT`, as in the scripts. Otherwise `git` would prompt to add the file `ACTUAL.txt`. 
</panel>

<panel  header="**5. :fas-info-circle: Abstract method with same pre and post behavior**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8" expanded>

Suppose you have an abstract method. Now every class that implements that method have a common beginning and common ending code. How would you reduce code duplication? My idea is the following:
```java
abstract class Test {

  private void preMethod() {} 
  private void postMethod() {}
  
  public void callThisMethod() { 
    preMethod(); 
    method();
    postMethod(); 
  }
  
  public abstract method(); 
}
```
However this approach doesn't prevent anyone from calling `method()` directly, which will be a problem. Making it `private` isn't an option, since abstract method cannot be `private`.
With this approach, a proper access modifier would be one that only sub-classes can access and inherit, but other package classes cannot. But I don't think any of the access modifier does that. So my current option is to ensure that I don't call `method()` directly from other classes myself.

Any thoughts on how to improve this? 
</panel>

<panel  header="**6. :fas-info-circle: The Star Rating System feels the reverse way**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/2" expanded>

> We use a star rating system to indicate the importance of module components.
> Start with things that are rated one-star and progress to things with more stars.

It seems to me that these two statements are in contradiction. In general (at least from my experience), more star means more importance.

Whenever I am browsing the website, all the 4 star topics are catching my eye. However, for the modules this shouldn't be the case, since those are the less important and optional topics. The color of the stars also affects this. The 4 star topics are given a green color with the background filled behind the text, which catches the eye even more!

I believe reversing the order of the stars would greatly improve user experience.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1214436431" expanded>

@RichDom2185 
> expose the preMethod and postMethod to subclasses and call them from there.   

This is the code duplication I am trying to avoid. Also I would not prefer to involve functional programming. 

The use case for this is: `method()` runs a command with arguments, and the `preMethod()` checks whether the command and the arguments are compatible. What I am trying to achieve is: 
```java 
callThisMethod(args) { 
  if (!preMethod(args)) return; 
  method(args);
}
```
(This isn't actually what I wrote in the post though; because of the `return`). 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1214438047" expanded>

Yes, it is input validation but I want to do this in one place only. 
I'll have to read more about decorators. On first look, it doesn't seem very appealing... 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1217902102" expanded>

@deeyonn I think you linked the wrong `Producer` documentation page (`Producer` was cs2030s specific, it is actually called `Supplier` in Java), but yes it would work. I think this approach is identical to what @RichDom2185 suggested. We'd need to wrap the `method()` in an object (`Methodable` / `Producer` / `Runnable` / `Consumer` etc) and the sub-classes would need to provide that object. 
However, how would you enforce the sub-classes to provide the wrapper object? For methods it would be checked by compiler, since sub-classes must provide implementation of abstract methods. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217921077" expanded>

@cliftonfelix Can you verify that they are different by opening the two files?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217927195" expanded>

@cliftonfelix Can you post the output you get from running the script?
I tried running the tests from your repository. It seems to work fine on my end. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217943575" expanded>

@cliftonfelix You can add the command `PAUSE` at the end of the `.bat` file in a newline. Then you'll be able to run it by double clicking and it won't close. 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1218591280" expanded>

@Eclipse-Dominator `protected` is not ideal for this case. It doesn't prevent other classes of the same package calling the function. We'd still need to ensure that we don't call the function ourselves, compiler won't check! 
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/51#issuecomment-1224296179" expanded>

@deeyonn Try it for some time. You'll find out what it is capable of. 
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1234035711" expanded>

Cosmetic changes: 
- Circular images. 
- Chat bubbles with alternating colors and round corners. 
- Custom font.

Behavior updates: 
- Support for scrolling with mouse wheel.
- Disabled send button when the text box is empty. 
- Ability to resize the window, with all texts and chat bubbles being correctly wrapped. 
- Prompting the user to create (or not) new data file in case of a corruption. 

<table> 
<tr>
<td> <img src="https://user-images.githubusercontent.com/22095441/187884570-189117cd-a6ca-4242-b673-b6ea8feb7d2e.png"> </td> 
<td><img src="https://user-images.githubusercontent.com/22095441/187884597-75a401aa-8229-4f1f-ad4b-abea5ff30e94.png"> </td> 
</tr>
<tr>
<td colspan="2" align="center"><img src="https://user-images.githubusercontent.com/22095441/187884867-a29988d7-da08-46eb-a063-2823aee29ff0.png"></td>
</tr>
</table>


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180#issuecomment-1244116808" expanded>

I would suggest you to go to the [iP Code Dashboard](https://nus-cs2103-ay2223s1.github.io/ip-dashboard/) and look at how others have organized their repository. It might be useful to sort the dashboard by contributions. _Generally_ the ones with more lines of code have better organization. 
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/193#issuecomment-1247945632" expanded>

If you are not using any JavaFX 18 / advanced features, then you can manually remove the `/18` part from `xmlns="http://javafx.com/javafx/18` in the `.fxml` files. Scene builder automatically adds this, which is probably tied to the version of scene builder app. I could not find a way to specify the version of JavaFX to use. 
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199#issuecomment-1248102762" expanded>

> `private static final Path DIRECTORY_PATH = Paths.get(System.getProperty("user.dir"), "data");`

Try replacing the `System.getProperty("user.dir")` with a `"."`. The `"user.dir"` on OSX is not defined properly. With `"."` you will be getting the location from where the jar was executed. So, if you call `java -jar folder/duke.jar`, the data folder will be `./data` not `./folder/data`. 
There is also a way to get [the location of the jar file](https://stackoverflow.com/questions/320542/how-to-get-the-path-of-a-running-jar-file), but that is a bit more complex. 
EDIT: It seems `user.dir` is set properly, but double-clicking on Mac may not set it properly. Has something to do with java permissions. 
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199#issuecomment-1248115266" expanded>

@ryanlml I believe he is already doing that. The problem is that the `filePath` is created by concatenating `user.dir` and `/data/data.txt`. But the `user.dir` returns some weird location on OSX; works fine on Windows / Linux. 
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/200#issuecomment-1248193952" expanded>

Some pictures are not being loaded on Linux (ArchLinux with KDE). 
![Screenshot_20220915_223508](https://user-images.githubusercontent.com/22095441/190432193-3bd7a36e-01ef-454f-ae46-af808fe88bcb.png)

</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/203#issuecomment-1248354614" expanded>

Not working on Linux (Arch). Getting a 0 width/height window and cannot even resize. Maybe something wrong with the resources? 
![Screenshot_20220916_004308](https://user-images.githubusercontent.com/22095441/190460629-ca336a44-9581-417d-9812-4d39935fde2b.png)

</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/204#issuecomment-1248358362" expanded>

Works OK on Linux (Arch): 
![Screenshot_20220916_004621](https://user-images.githubusercontent.com/22095441/190461213-1b43c663-9917-44ee-8bdb-4e60d49e23d9.png)
However, a little bit of problem: the text is not wrapped properly when width is small. Is this the correct behavior? 
![Screenshot_20220916_004713](https://user-images.githubusercontent.com/22095441/190461379-f65306e8-5e7b-458f-a3a9-eb9b127c80f6.png)


</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/205#issuecomment-1248363645" expanded>

Just use `![](Ui.png)`. Github pages will just build the site from `/docs` directory, so no need to include the `/docs` in the path. So you may assume your site's root directory is the `/docs` directory. 
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/201#issuecomment-1248366581" expanded>

It would be better ask whether this would break a specific OOP principle, and why you think it might break. With the given description, it is not enough to conclude anything. Having two constructors of course doesn't necessarily break any principle. 
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/194#issuecomment-1248375292" expanded>

Works OK on Linux (Arch), but text seems broken?:  
![Screenshot_20220916_010259](https://user-images.githubusercontent.com/22095441/190466314-fec3c48a-c8e4-4b8c-a8c7-5bf0f8062030.png)
However, resizing the window seems to break everything :laughing: Check if this is the correct behavior: 
![Screenshot_20220916_010416](https://user-images.githubusercontent.com/22095441/190466727-8b86e179-7d94-42c5-abe1-b31c83b0c2db.png)
(command box not visible, text got broken)
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/206#issuecomment-1248440738" expanded>

Worked OK on Linux (Arch) until I resized the window: 
![Screenshot_20220916_021344](https://user-images.githubusercontent.com/22095441/190479179-327840bc-5cbc-4225-97e2-473b69a107b9.png)
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/207#issuecomment-1248445720" expanded>

Did not work on Linux (Arch): 
![Screenshot_20220916_021630](https://user-images.githubusercontent.com/22095441/190479710-d05cc371-5d44-4e72-893d-1d8d289744a8.png)

In `build.gradle`: 
```
javafx {
    version = "11.0.2"
    modules = [ 'javafx.base', 'javafx.controls', 'javafx.fxml', 'javafx.graphics' ]
}
```
is not enough to include all modules for win/mac/linux (even though the [linked page](https://openjfx.io/openjfx-docs/#gradle) in javafx tutorial gave this approach). Try including each one of them individually for different OSs as done in the [se-edu page tutorial](https://se-education.org/guides/tutorials/javaFxPart1.html#setting-up-java-fx). 
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/216#issuecomment-1249003901" expanded>

Tested on Linux (Arch). Deku's picture is not being loaded. Also can resize the window beyond the preferred size. 
![Screenshot_20220916_151257](https://user-images.githubusercontent.com/22095441/190578693-45aac61e-4181-456f-b1cc-22d03edfa753.png)

</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/212#issuecomment-1249008057" expanded>

Tested on Linux (Arch).
![Screenshot_20220916_151511](https://user-images.githubusercontent.com/22095441/190579108-4076c6de-3444-4de4-9f54-b6ca27a47f22.png)

However, I can't seem to be able to run it with double clicking; then I get a 0 width/height window like this: 
![Screenshot_20220916_151653](https://user-images.githubusercontent.com/22095441/190579439-2251c684-0f89-467a-bb73-56819c0e92dc.png)


</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/207#issuecomment-1249015743" expanded>

Working fine on Linux (Arch) now: 
![Screenshot_20220916_152021](https://user-images.githubusercontent.com/22095441/190580607-307e953a-80aa-47cc-b481-b1448484e5ed.png)

For the window distortion problem, you can add `stage.setResizable(false);` in `Main` for a quick fix. Wrapping the text with window resize is a bit more complex. 
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/203#issuecomment-1249023717" expanded>

@marclzh Still having the same issue on Linux. I tried compiling it locally from master branch but still got the same result. 
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/206#issuecomment-1249031859" expanded>

For a quick fix of the window resize problem, you can add `stage.setResizable(false);` in `Main`. 
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/213#issuecomment-1249046920" expanded>

I also get the same error in Linux (Arch). For fixing the issue: remove the `javafx {}` block at the end of `build.gradle`. That part is actually restricting the packages. 

After that it runs, but the images are not being loaded: 
![Screenshot_20220916_155239](https://user-images.githubusercontent.com/22095441/190586950-0f261a83-01ea-41a0-80a7-dae399f38436.png)

</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249065524" expanded>

The fonts are not included in the jar. So we have to reply on the user having the fonts installed :disappointed: I am seeing it like this on Linux (Arch with KDE too, but different from above): 
![Screenshot_20220916_161843](https://user-images.githubusercontent.com/22095441/190591649-c6ad7298-23b8-492f-9804-9d97fcf3394a.png)

</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/218#issuecomment-1249082371" expanded>

Works as expected on Linux (Arch)! Fonts, images loaded. Resize also working properly. :+1: 
![Screenshot_20220916_163338](https://user-images.githubusercontent.com/22095441/190594446-bbfef9b0-38b5-4587-962e-a08fd64e3564.png)

</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/218#issuecomment-1249088545" expanded>

@sltsheryl By the way, can you give me a summery of how did you include the fonts? I would also like to include my fonts. I have some emojis that do not show up in other's PC. :disappointed: 
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249114730" expanded>

Yes I got the same error message: 
```
Image loading error? ReadOnlyObjectProperty [bean: javafx.scene.image.Image@e2cb9ac, name: exception, value: java.io.IOException: Wrong JPEG library version: library is 80, caller expects 70]
Image loading error? java.io.IOException: Wrong JPEG library version: library is 80, caller expects 70
```

The `.fxml` files seems to be using javafx version 8 (probably due to installing older version of scene builder?). I changed them to 11, but that didn't fix it.

I've done a lot of smoke testing. Seems like a lot of students have this issue. Only a few ran correctly on my system. 
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249137283" expanded>

Okay, I managed to fix the problem. Googling seemed to suggest that the problem is with the images themselves. So I converted the `.png`s to `.jpg` and then converted them back to `.png`. Now the images are loading correctly: 
![Screenshot_20220916_172137](https://user-images.githubusercontent.com/22095441/190604206-89c830aa-c339-4241-9964-fcda476bdb9c.png)

If I have to guess: the images are corrupted somewhere. Maybe copied from web and pasted locally and not downloaded properly? 
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249143669" expanded>

Tested on Linux (Arch). Some images are not being loaded: 
![Screenshot_20220916_172730](https://user-images.githubusercontent.com/22095441/190605552-efbcfae3-aebd-4423-8c3f-72a324f37a18.png)
Read [this thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/217) for possible fix.
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249450773" expanded>

Working as expected on Linux: 
![Screenshot_20220916_223547](https://user-images.githubusercontent.com/22095441/190664471-d31c3a7c-0e91-4cba-8e77-49d96c6b2fed.png)

</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/225#issuecomment-1249454233" expanded>

Everything seems to be working correctly on Linux (Arch): 
![Screenshot_20220916_223848](https://user-images.githubusercontent.com/22095441/190665101-0a3f5768-0b29-49f9-beb3-eca98c0d2446.png)

</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/228#issuecomment-1249457032" expanded>

On Linux (Arch) it gets into an infinite loop of printing exceptions: 
```
Exception in thread "JavaFX Application Thread" java.lang.IllegalArgumentException: Image must be non-null
        at com.sun.prism.paint.ImagePattern.<init>(ImagePattern.java:44)
        at com.sun.javafx.tk.quantum.QuantumToolkit.createImagePatternPaint(QuantumToolkit.java:924)
        at com.sun.javafx.tk.Toolkit.getPaint(Toolkit.java:661)
        at javafx.scene.paint.ImagePattern.acc_getPlatformPaint(ImagePattern.java:292)
        at javafx.scene.paint.Paint$1.getPlatformPaint(Paint.java:48)
        at javafx.scene.shape.Shape.updatePGShape(Shape.java:963)
        at javafx.scene.shape.Shape.doUpdatePeer(Shape.java:998)
        at javafx.scene.shape.Shape.access$000(Shape.java:123)
        at javafx.scene.shape.Shape$1.doUpdatePeer(Shape.java:131)
        at com.sun.javafx.scene.shape.ShapeHelper.updatePeerImpl(ShapeHelper.java:74)
        at com.sun.javafx.scene.shape.CircleHelper.updatePeerImpl(CircleHelper.java:64)
        at com.sun.javafx.scene.NodeHelper.updatePeer(NodeHelper.java:102)
        at javafx.scene.Node.syncPeer(Node.java:710)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2380)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.synchronizeSceneNodes(Scene.java:2356)
        at javafx.scene.Scene$ScenePulseListener.pulse(Scene.java:2512)
        at com.sun.javafx.tk.Toolkit.lambda$runPulse$2(Toolkit.java:412)
        at java.base/java.security.AccessController.doPrivileged(Native Method)
        at com.sun.javafx.tk.Toolkit.runPulse(Toolkit.java:411)
        at com.sun.javafx.tk.Toolkit.firePulse(Toolkit.java:438)
        at com.sun.javafx.tk.quantum.QuantumToolkit.pulse(QuantumToolkit.java:519)
        at com.sun.javafx.tk.quantum.QuantumToolkit.pulse(QuantumToolkit.java:499)
        at com.sun.javafx.tk.quantum.QuantumToolkit.pulseFromQueue(QuantumToolkit.java:492)
        at com.sun.javafx.tk.quantum.QuantumToolkit.lambda$runToolkit$11(QuantumToolkit.java:320)
        at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
        at com.sun.glass.ui.gtk.GtkApplication._runLoop(Native Method)
        at com.sun.glass.ui.gtk.GtkApplication.lambda$runLoop$11(GtkApplication.java:277)
        at java.base/java.lang.Thread.run(Thread.java:829)
```
</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/221#issuecomment-1249616259" expanded>

Some images not being loaded on Linux (Arch):
![Screenshot_20220917_013150](https://user-images.githubusercontent.com/22095441/190698700-0bef6a26-3ce9-4d5b-a296-971d463d158f.png)
Also got the following error in terminal: 
```
Sep 17, 2022 1:31:31 AM com.sun.javafx.css.StyleManager$ImageCache getCachedImage
WARNING: Error loading image: jar:file:/home/rezwanarefin01/Downloads/duke.jar!/images/starry_sky.jpg
Sep 17, 2022 1:31:32 AM com.sun.javafx.css.StyleManager$ImageCache getCachedImage
WARNING: Error loading image: jar:file:/home/rezwanarefin01/Downloads/duke.jar!/images/starry_sky.jpg
```
[This thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/217) might be useful. 

</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249619171" expanded>

I got a completely blank screen on Linux (Arch): 
![Screenshot_20220917_013548](https://user-images.githubusercontent.com/22095441/190699369-7165236c-a99a-4ba2-b3cc-12cbf1b54d10.png)
And it also gets into an infinite loop of printing exceptions:
```
Exception in thread "JavaFX Application Thread" java.lang.IllegalArgumentException: Image must be non-null
        at com.sun.prism.paint.ImagePattern.<init>(ImagePattern.java:44)
        at com.sun.javafx.tk.quantum.QuantumToolkit.createImagePatternPaint(QuantumToolkit.java:924)
        at com.sun.javafx.tk.Toolkit.getPaint(Toolkit.java:661)
        at javafx.scene.paint.ImagePattern.acc_getPlatformPaint(ImagePattern.java:292)
        at javafx.scene.paint.Paint$1.getPlatformPaint(Paint.java:48)
        at javafx.scene.shape.Shape.updatePGShape(Shape.java:963)
        at javafx.scene.shape.Shape.doUpdatePeer(Shape.java:998)
        at javafx.scene.shape.Shape.access$000(Shape.java:123)
        at javafx.scene.shape.Shape$1.doUpdatePeer(Shape.java:131)
        at com.sun.javafx.scene.shape.ShapeHelper.updatePeerImpl(ShapeHelper.java:74)
        at com.sun.javafx.scene.shape.CircleHelper.updatePeerImpl(CircleHelper.java:64)
        at com.sun.javafx.scene.NodeHelper.updatePeer(NodeHelper.java:102)
        at javafx.scene.Node.syncPeer(Node.java:710)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2380)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
        at javafx.scene.Scene$ScenePulseListener.synchronizeSceneNodes(Scene.java:2356)
        at javafx.scene.Scene$ScenePulseListener.pulse(Scene.java:2512)
        at com.sun.javafx.tk.Toolkit.lambda$runPulse$2(Toolkit.java:412)
        at java.base/java.security.AccessController.doPrivileged(Native Method)
        at com.sun.javafx.tk.Toolkit.runPulse(Toolkit.java:411)
        at com.sun.javafx.tk.Toolkit.firePulse(Toolkit.java:438)
        at com.sun.javafx.tk.quantum.QuantumToolkit.pulse(QuantumToolkit.java:519)
        at com.sun.javafx.tk.quantum.QuantumToolkit.pulse(QuantumToolkit.java:499)
        at com.sun.javafx.tk.quantum.QuantumToolkit.pulseFromQueue(QuantumToolkit.java:492)
        at com.sun.javafx.tk.quantum.QuantumToolkit.lambda$runToolkit$11(QuantumToolkit.java:320)
        at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
        at com.sun.glass.ui.gtk.GtkApplication._runLoop(Native Method)
        at com.sun.glass.ui.gtk.GtkApplication.lambda$runLoop$11(GtkApplication.java:277)
        at java.base/java.lang.Thread.run(Thread.java:829)
```
Keeps printing this non stop.
[This thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/217) might be related.
</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/229#issuecomment-1249623740" expanded>

Works as expected on Linux (Arch): 
![Screenshot_20220917_013949](https://user-images.githubusercontent.com/22095441/190700114-1f79f2d9-40ee-49d2-b6c1-51a6384e148c.png)

Minor issue: It keeps printing the following in terminal: 
```
Sep 17, 2022 1:39:43 AM javafx.fxml.FXMLLoader$ValueElement processValue
WARNING: Loading FXML document with JavaFX API of version 18 by JavaFX runtime of version 11
```
This issue can be fixed as described in [this thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/193).
</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230#issuecomment-1249627046" expanded>

Could not get it working on Linux (Arch): 
![Screenshot_20220917_014236](https://user-images.githubusercontent.com/22095441/190700520-ed5b467b-b3c3-4b88-8467-c547c7e7a614.png)
I'm getting a ~0 width/height window, which is also not resizeable. Maybe setting a minimum size of the window will help? 
</panel>

<panel  header="**47 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/232#issuecomment-1249639324" expanded>

Working as expected on Linux (Arch): 
![Screenshot_20220917_014604](https://user-images.githubusercontent.com/22095441/190701188-1bd1c8f0-9ab2-4cf3-87fa-d3dba800747e.png)

</panel>

<panel  header="**48 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1249645341" expanded>

Tested on Linux (Arch). When I first ran it, it threw me this: 
```
Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class anya.Main
        at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:890)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
        at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.reflect.InvocationTargetException
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstance(Constructor.java:490)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:802)
        at com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
        at com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
        at java.base/java.security.AccessController.doPrivileged(Native Method)
        at com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
        at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
        at com.sun.glass.ui.gtk.GtkApplication._runLoop(Native Method)
        at com.sun.glass.ui.gtk.GtkApplication.lambda$runLoop$11(GtkApplication.java:277)
        ... 1 more
Caused by: java.lang.ArrayIndexOutOfBoundsException: Index 1 out of bounds for length 1
        at anya.Storage.readTask(Storage.java:78)
        at anya.Storage.readFile(Storage.java:70)
        at anya.Anya.<init>(Anya.java:27)
        at anya.Main.<init>(Main.java:22)
        ... 13 more
```
Turns out that I had a `data/duke.txt` in the directory from previous testing, containing their saved data. But Anya seems to have the same name for the data file. So it failed to handle the datafile corruption... The contents of the datafile were: 
```
T|0|Return Book
D|0|Submit iP|2022-12-15
```
Maybe try with this to debug the data loading. It is having some array out of bound somewhere.

After removing the file it works as expected. However, I'd suggest you to turn of screen resizeability by `stage.setResizeable(false)`. 
![Screenshot_20220917_015203](https://user-images.githubusercontent.com/22095441/190702023-e93265d0-60bc-43ac-99a1-1dc3be2dd534.png)
</panel>

<panel  header="**49 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/236#issuecomment-1249651721" expanded>

The thing being null means it couldn't get the image from the directory specified. The path specified is `/image/kiwi.png`. But as I can see from the left bar: the folder is named `Images`, with capital `I`. 

I have cloned and fixed it. Then I can build and run the Duke, on Linux (Arch): 
![Screenshot_20220917_015902](https://user-images.githubusercontent.com/22095441/190702965-7a9a0104-a061-4b97-9a96-eb973f2bbd35.png)

Also nice aesthetics! The KIWI logo on the top makes it stand out from other Dukes. 
</panel>

<panel  header="**50 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1249924804" expanded>

@xhphoong I think it is still not fixed; I still got the exception thrown. You can test it locally too: create a data/anya.txt file with the contents that I gave above. Then run Anya.
Possible fix: before [this line](https://github.com/xhphoong/ip/blob/master/src/main/java/Storage.java#L77), check for the array length and throw an exception. 
</panel>

<panel  header="**51 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/240#issuecomment-1249998517" expanded>

~~How is your jar 52.9MB... are you giving us some malware~~
The background image did not show up in Linux (Arch): 
![Screenshot_20220917_123924](https://user-images.githubusercontent.com/22095441/190840727-0c3480cb-f32c-4e62-99f2-bf8457004c39.png)
Try re-downloading the background image / convert it to another format and back. This problem happens mostly due to some sort of corruption in the image file. 
</panel>

<panel  header="**52 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/241#issuecomment-1250039170" expanded>

Tested on Linux (Arch). Works as expected: 
![Screenshot_20220917_174034](https://user-images.githubusercontent.com/22095441/190850534-5a2a9373-7b9b-4614-a04a-0bb3a64df2fd.png)

</panel>

<panel  header="**53 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/250#issuecomment-1250222701" expanded>

Working as expected on Linux (Arch). But resize doesn't work properly. You may disable it by `stage.setResizable(false);`. 
![Screenshot_20220918_164209](https://user-images.githubusercontent.com/22095441/190893568-ed9fe4d1-5987-4fc8-8eb0-0fa598d805a6.png)

</panel>

<panel  header="**54 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/252#issuecomment-1250276037" expanded>

Getting a window like this on Linux (Arch), with no way to resize too: 
![Screenshot_20220918_212114](https://user-images.githubusercontent.com/22095441/190904271-9c1aae99-1359-46d2-8054-1eef9ecfd091.png)

</panel>

<panel  header="**55 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250313357" expanded>

Works as expected on Linux (Arch). However I'd suggest you to disable window resize by `stage.setResizeable(false);`, if you are not planning on wrapping it properly.
![Screenshot_20220918_215017](https://user-images.githubusercontent.com/22095441/190909302-472ab2a9-e807-45cc-89a6-4f26073a4c2a.png)

</panel>

<panel  header="**56 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/256#issuecomment-1250348468" expanded>

Working as expected on Linux (Arch): 
![Screenshot_20220919_010152](https://user-images.githubusercontent.com/22095441/190919329-27b51709-c73d-49b4-9164-1af212845bd0.png)

</panel>

<panel  header="**57 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/267#issuecomment-1250985737" expanded>

Where is the mistake? 

</panel>

<panel  header="**58 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/263#issuecomment-1250989024" expanded>

Working as expected on Linux (Arch). Turn off the resizeability though: 
![Screenshot_20220919_210021](https://user-images.githubusercontent.com/22095441/191022980-e1571227-93db-4c4a-82fd-61c919847bad.png)

</panel>

<panel  header="**59 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/269#issuecomment-1252157626" expanded>

I think it is because you included `javafx.web`. Are you using that anywhere? If not you may just remove the `javafx {}` block from `build.gradle`. The lines in `dependencies` is sufficient for the app to run. 
</panel>

<panel  header="**60 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/266#issuecomment-1252161542" expanded>

Getting an unresizable window like this on Linux (Arch): 
![Screenshot_20220920_183434](https://user-images.githubusercontent.com/22095441/191236185-17b164e7-d9fe-42e4-8b9c-3ba138e821ae.png)

</panel>

<panel  header="**61 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/289#issuecomment-1254663693" expanded>

On Linux (Arch) one of the picture is not being loaded. 
![Screenshot_20220922_155647](https://user-images.githubusercontent.com/22095441/191690489-af058ad2-c0f5-4995-a578-3549245d68a0.png)
For a fix, you may try converting the `.png` to a `.jpg`, then convert back to `.png`. It likely that the `.png` is not in correct format. 
</panel>

<panel  header="**62 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/290#issuecomment-1254664884" expanded>

Tested on Linux (Arch). On of the pictures did not load, and the window can be resized weirdly: 
![Screenshot_20220922_155847](https://user-images.githubusercontent.com/22095441/191690912-c3e699d2-61e1-422d-99f0-afa6d72f9d0c.png)

</panel>

<panel  header="**63 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/300#issuecomment-1257245160" expanded>

Tested on Linux (Arch). The images did not load, and also the window can be resized weirdly: 
![Screenshot_20220926_015544](https://user-images.githubusercontent.com/22095441/192157988-598a6b1a-5409-4edf-b286-0e51a449d20f.png)
Try looking into solved issues. These problems are very common. 

</panel>

<panel  header="**64 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/331#issuecomment-1271348356" expanded>

There are two bidirectional association here: 
![Screenshot_20221007_172704](https://user-images.githubusercontent.com/22095441/194521393-3be24a2e-afce-491d-a528-ec7d11a2b9b8.png)

</panel>

<panel  header="**65 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/488#issuecomment-1326170036" expanded>

> We don't want students to access other online resources during part 2.

@damithc How about setting a dummy exam in Examplify during Part II? There is a slight problem that a student may start late / submit early and use the rest of the time to access the internet :joy:. But this could be countered by verifying the start / end times later, as Examplify keeps track of those. 

Another solution would be to merge Part II and III in one and give the PDF as attachment in Examplify. But I guess this is unwanted as we cannot impose ~2 min per question in Part III then.
</panel>

</panel>


<panel type="info" header="### 3. TAN ..HENG `@cheeheng` (59 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Reposense does not recognise @@author tags for Markdown comments**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/501" expanded>

`[//]: #(some comment text here)` is a Markdown comment. However, the following, which is a minor deviation of only 1-2 non-empty extra lines, occurred:

<img width="423" alt="image" src="https://user-images.githubusercontent.com/13196670/204099826-71e4a932-527c-486d-a626-1196dcbd1419.png">

</panel>

<panel  header="**2. :fas-info-circle: Query regarding p1.15 of Practice Exam (Part 1)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/496" expanded>

<img width="488" alt="image" src="https://user-images.githubusercontent.com/13196670/203755253-c74cbc9c-2f3b-4d96-847a-62574c0761f8.png">

While it is true that pushing code to the fork will update the PR, the implicit assumption is that the branch matches? 
This is because pushing code to the `master` branch in the fork will only update the PRs merging from the `master` branch in the fork. Is this right?
</panel>

<panel  header="**3. :fas-info-circle: Clarification on best match for the code**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/481" expanded>

Sometimes, I feel that I have to make judgement calls for Part 3, when it comes to UML diagrams (because none fit exactly what I have drawn). I would like to clarify regarding the criteria for "best match for the code", in particular the following:
1) If the UML notation contradicts the code or is syntactically incorrect, it is not the correct answer.
2) If two or more UML diagrams match the code, then pick the diagram which has the most detailed optional notation.
</panel>

<panel  header="**4. :fas-info-circle: Outcome of tutor moderation phase**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/472" expanded>

Will both the tester and the dev team be notified of the final severity and type of the bug (i.e., whether the teaching team sided with the tester or the dev team)?

Pros: It will be a good learning opportunity for both the tester and the dev team to understand why the bug is actually of a certain severity or a certain type. 

Cons: If additional explanation is given, there will be more work from the teaching team because they have to adjudicate a few thousand disputed bugs. If additional explanation is not given, it could defeat the purpose because the tester and the dev team may not fully understand why the severity and type of the bug is judged as such.
</panel>

<panel  header="**5. :fas-info-circle: Possible Feature Flaw: CATcher does not allow the tester to revise the initial bug severity during the tester rebuttal phase**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/463" expanded>

CATcher does not explicitly allow the tester to revise the initial bug severity and/or type during the tester rebuttal phase. Is there a reason behind this? 

There is a possible use case for that:

Suppose the tester put the severity as Medium during the Practical Exam.
During the dev team response phase, the dev team downgraded the severity to VeryLow.
The tester disagrees with the dev team, but now realises that the severity should be Low, and would want to correct the error.

Currently, a workaround is to explain in the response box that the tester is revising the severity, but I am not sure if that is allowed.
</panel>

<panel  header="**6. :fas-info-circle: Total number of marks does not add up?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/441" expanded>

In [this website](https://nus-cs2103-ay2223s1.github.io/website/admin/tp-grading.html), I found out that the sum of team and individual marks does not sum to 50. 

When I checked the bottom sections, it looks like 45 marks are individual marks, while the last 5 marks are team marks.

<img width="610" alt="image" src="https://user-images.githubusercontent.com/13196670/201367878-f25623ae-878d-4c6b-9c31-56c9f2492f5d.png">

Should this be considered a very low severity documentation bug?

</panel>

<panel  header="**7. :fas-info-circle: Clarifications Regarding Practical Exam Readiness Quiz Answers**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/436" expanded>

For the practical exam, there are some questions which I would like to clarify because of some edge cases not explicitly mentioned. May I know the rationale behind excluding such edge cases?

<img width="881" alt="image" src="https://user-images.githubusercontent.com/13196670/200486418-261cc4da-b5d3-4cbf-b39c-3741fa896f7f.png">

While this is true in general, there is a rare case when I have to report to the head TA.
<img width="460" alt="image" src="https://user-images.githubusercontent.com/13196670/200487026-c46c2bb9-5530-445f-9ae0-c45867f288f8.png">

<img width="881" alt="image" src="https://user-images.githubusercontent.com/13196670/200487191-9ca81f1e-094b-4091-9189-e17e629125ea.png">
In Phase 4, there is no need to use CATcher because the tutors will decide on whether to side with the tester or the developer team, but it is true that I should not use the GitHub interface because there is no need to, as shown below:
<img width="524" alt="image" src="https://user-images.githubusercontent.com/13196670/200487341-e8279777-fbc1-4beb-b04c-d9429353caf0.png">
Perhaps it would be clearer to explictly exclude Phase 4?

<img width="880" alt="image" src="https://user-images.githubusercontent.com/13196670/200487811-74126d9c-4a98-4e15-b929-9f9013967722.png">
First, should I login to MS teams just before the PE (because logging in during the PE will eat up into the time I have for finding bugs)?
Is there a reason why MS teams is not explicitly written in the list of allowed websites here? 
<img width="474" alt="image" src="https://user-images.githubusercontent.com/13196670/200487901-2b5d09b9-11fe-4f93-8ffe-d7f74c5f0ca0.png">





</panel>

<panel  header="**8. :fas-info-circle: Week 12 Project tab: Admin  tP → Deliverables → Project Portfolio Page**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/399" expanded>

In Week 12 Project tab: Admin  tP → Deliverables → Project Portfolio Page, clicking on `team-based-tasks` does not trigger a popup.

<img width="569" alt="image" src="https://user-images.githubusercontent.com/13196670/198877482-8df962d3-89c6-487e-8ae2-ba12c23ffcc4.png">

</panel>

<panel  header="**9. :fas-info-circle: Code reuse declaration form points to wrong semester**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/398" expanded>

Code reuse declaration form points to wrong semester, it should be AY22/23 Semester 1 instead.

<img width="694" alt="image" src="https://user-images.githubusercontent.com/13196670/198876193-8d377634-00d1-4513-915d-cf777200c738.png">

</panel>

<panel  header="**10. :fas-info-circle: Rationale behind policy on reuse declaration form**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/391" expanded>

What is the rationale behind the declaration form of the policy of reuse? Is it to ensure that every student is aware of the reuse policy, so that if there is any case of academic dishonesty, then it cannot be that the student is unaware of the reuse policy?
</panel>

<panel  header="**11. :fas-info-circle: Clarification of LumiNUS Week 11 Quiz Q29**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/387" expanded>

<img width="879" alt="image" src="https://user-images.githubusercontent.com/13196670/198564665-a7a3a395-25fe-4297-ba81-6ac368ad8c20.png">

Test case heuristics are not exact hard-and-fast rules, hence I thought that in some cases it might be ok to test multiple invalid inputs. In fact, I have seen multiple invalid input values testing for AB3 so as to enforce which particular invalid error message will be returned.

When the question was asked, is the intended context 'based on only heuristics covered in the textbook'?
</panel>

<panel  header="**12. :fas-info-circle: Can compiler warnings be considered bugs for tP?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/377" expanded>

As above: Can compiler warnings be considered bugs for tP?
</panel>

<panel  header="**13. :fas-info-circle: Definition of programmatically accessible services for service-oriented architecture**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/369" expanded>

I am confused about the definition of programmatically accessible services. From the textbook, I can infer that programmatically accessible services include web APIs. Are there any other examples of programmatically accessible services? If possible, is there a precise definition of programmatically accessible services?
</panel>

<panel  header="**14. :fas-info-circle: Wrong spelling of microkernel?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/368" expanded>

In Design - Architecture - Styles video, is the word microkernel misspelt?

<img width="464" alt="image" src="https://user-images.githubusercontent.com/13196670/197373311-14986c02-ae22-4486-9e68-27b1e9fc3001.png">

As a side note, the explanation of service-oriented architecture styles is missing in the video even though it is a three-star topic in the textbook.

</panel>

<panel  header="**15. :fas-info-circle: Precise definition of boundaries**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/345" expanded>

What is the precise definition of boundaries? I would like to clarify on some questions:

1. Does boundaries need to be with respect to a contiguous range, or can it be further generalised?
2. Is null a boundary value of the equivalence partition [null]?
3. It is mentioned in the textbook that the equivalence partition of prime numbers has no specific boundary, but I could argue that 2 is the smallest prime number, and hence can be considered a boundary. What is wrong with this argument? In the same token, I could argue that numbers which are products of two prime numbers (not necessarily distinct) can be considered boundaries within the equivalence partition of positive non-prime integers not lesser than 2 because those numbers must be the product of at least two prime numbers (not necessarily distinct) whereas prime numbers are the product of exactly one prime number.
</panel>

<panel  header="**16. :fas-info-circle: Bug: wrong activity diagram**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/338" expanded>

I tried this exercise, and when I wanted to check my answer, I found out that the activity diagram does not correspond to the question.

<img width="247" alt="image" src="https://user-images.githubusercontent.com/13196670/194854356-94e7d7a9-92d4-4370-a1cb-9364cbe3eb44.png">

</panel>

<panel  header="**17. :fas-info-circle: Request for smoke test help (Windows, Linux or Mac)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280" expanded>

My release can be found [here](https://github.com/cheeheng/ip/releases/tag/A-Release). Could you please help me test the jar file?
</panel>

<panel  header="**18. :fas-info-circle: Clarification of definition of single-level design**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/231" expanded>

The quiz in Week 6 Question 31 claims that the statement is "given" or at least implied in the textbook. However, in the textbook (at least for Week 6 content), I can't find the precise definition of "single-level" design under the section "Multi-level Design". Does a single-level design mean that the UML class diagram can fit within a page without the text getting too small? 

<img width="878" alt="image" src="https://user-images.githubusercontent.com/13196670/190660325-7f02c211-7b01-4741-99bb-5897aae58c97.png">

</panel>

<panel  header="**19. :fas-info-circle: Questions about Reuse Policy**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/170" expanded>

1. Is using code generated for Codecov badge considered reuse under reuse policy?
1. Is a separate credits file for where the third-party resources come from (e.g. profile pic images in iP), considered giving sufficient credit to the original author?
</panel>

<panel  header="**20. :fas-info-circle: Bug: Scrollbar disappears after I click on non-functional requirements**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/133" expanded>

On [https://nus-cs2103-ay2223s1.github.io/website/schedule/week5/topics.html](https://nus-cs2103-ay2223s1.github.io/website/schedule/week5/topics.html), go to Week 5.3e, then click on link 'non-functional requirements'. Then, once the link is clicked, a popup modal shows. After the modal disappears, the scrollbar disappears, and I have to reload the page. This bug is similar to #1 and #109.
</panel>

<panel  header="**21. :fas-info-circle: Bug: Cannot retake failed attempt (Week 5.3 Video)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/132" expanded>

I can't retake the quiz even though I got the question wrong. This bug is similar to the issue #49.

<img width="514" alt="image" src="https://user-images.githubusercontent.com/13196670/188180348-968be430-6b2f-4e8e-bbd6-e15f195095bd.png">

</panel>

<panel  header="**22. :fas-info-circle: Number of stars does not match (Part 3)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/130" expanded>

In CS2103/T Week 5 Admin Page, I found this three star heading with four star content: 

<img width="572" alt="image" src="https://user-images.githubusercontent.com/13196670/188166539-ea972541-07b2-4a0b-a563-c7679b64fc19.png">

</panel>

<panel  header="**23. :fas-info-circle: Is 1..0 multiplicity the same as 0..1?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/78" expanded>

Is 1..0 multiplicity the same as 0..1? I saw 1..0 multiplicity in the following image. 

If so, when is it preferable to use 1..0 instead of 0..1?

<img width="334" alt="image" src="https://user-images.githubusercontent.com/13196670/186936282-de1a8bab-fa10-4f65-8a62-530dec251b49.png">

</panel>

<panel  header="**24. :fas-info-circle: Is a class name considered an association notation?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/77" expanded>

Is a class name considered an association notation? The explanation below did not explain anything about class names being an association notation while the answer does include (d).

<img width="499" alt="image" src="https://user-images.githubusercontent.com/13196670/186918182-4cba7868-3866-4568-a10f-98c09f745d23.png">

</panel>

<panel  header="**25. :fas-info-circle: Missing textbox to write answer**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/74" expanded>

I don't know whether this is a bug. However, the lack of a textbox to write a template answer makes it tempting to look at the hint directly, which is not consistent with the teaching style of CS2103/T. This is found in Week 4, section 4.1b.

<img width="499" alt="image" src="https://user-images.githubusercontent.com/13196670/186885128-c0db48f0-ff19-4f0b-80f2-dae9fd050bed.png">

</panel>

<panel  header="**26. :fas-info-circle: Bug: Number of stars do not match**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/43" expanded>

On this webpage (which was in Week 12 but I found it while searching for code reuse policy) [https://nus-cs2103-ay2223s1.github.io/website/schedule/week12/admin.html#policy-on-reuse](https://nus-cs2103-ay2223s1.github.io/website/schedule/week12/admin.html#policy-on-reuse), I found another case where the number of stars of the headers do not match.

<img width="578" alt="image" src="https://user-images.githubusercontent.com/13196670/185759076-eef859ff-2c1a-4a87-92a3-605ddbf08cd7.png">

</panel>

<panel  header="**27. :fas-info-circle: Bug: number of stars do not match**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/4" expanded>

In this website: [https://nus-cs2103-ay2223s1.github.io/website/schedule/week2/project.html](https://nus-cs2103-ay2223s1.github.io/website/schedule/week2/project.html)

Scroll down to the following appendix, which is labelled as 4 stars on the header, but the content shows 2 stars.

<img width="602" alt="image" src="https://user-images.githubusercontent.com/13196670/184499478-154980c8-927b-4da2-a39d-9ef4e6dddade.png">

</panel>

<panel  header="**28. :fas-info-circle: Question about coding standards in individual project**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/3" expanded>

I read that one of the criteria of the individual project is that coding styles need to fit standards. After some searching, I realised that the standard used in the module is this one: [https://se-education.org/guides/conventions/java/intermediate.html](https://se-education.org/guides/conventions/java/intermediate.html)

I have also done a quick search on the module website and found out that coding standards will only be covered on Week 3. Do I have to worry about fitting coding standards for the individual project milestone on Week 2? If so, will linters be provided to check coding standard compliance?
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/73#issuecomment-1228330954" expanded>

[https://softwareengineering.stackexchange.com/questions/100959/how-do-you-unit-test-private-methods](https://softwareengineering.stackexchange.com/questions/100959/how-do-you-unit-test-private-methods)

According to this link, testing private code should be avoided as much as possible, but there are ways around this issue.
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/77#issuecomment-1228598449" expanded>

Thanks so much prof. The reason behind the confusion is that class names on its own do not show an association, yet they are needed to indicate association.
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/83#issuecomment-1229142140" expanded>

You could refer to these two links for help.

[https://stackoverflow.com/questions/3634853/how-to-create-a-directory-in-java](https://stackoverflow.com/questions/3634853/how-to-create-a-directory-in-java)
[https://stackoverflow.com/questions/8197049/how-to-get-just-the-parent-directory-name-of-a-specific-file](https://stackoverflow.com/questions/8197049/how-to-get-just-the-parent-directory-name-of-a-specific-file)
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1235556349" expanded>

Similar to JavaFX UI tutorial (except that title is included, and image is changed)

![image](https://user-images.githubusercontent.com/13196670/188167838-1ce51d5e-40cd-4df1-bf47-f9057364c2c7.png)


 
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/170#issuecomment-1242993894" expanded>

Thanks so much Prof. I have another question regarding the reuse policy:
Is reusing configuration file code (or parts of it) considered reuse under reuse policy (e.g. when using [this file](https://github.com/se-edu/duke/blob/full-template/.github/workflows/gradle.yml) to set up GitHub Continuous Integration)?

I believe it is important to make clear which is considered reuse and which is not so as to reduce the risk of miscommunication.
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/170#issuecomment-1243001717" expanded>

Thanks prof!
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249384349" expanded>

I would like to help but it appears that you forgot to upload the binary file on the Release section.

Update: I have tested on Windows 11 and the jar file seems to be working.
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/225#issuecomment-1249387252" expanded>

I tested this on Windows 11: It works, but with the following warning:
```
Sep 16, 2022 9:46:46 PM javafx.fxml.FXMLLoader$ValueElement processValue
WARNING: Loading FXML document with JavaFX API of version 18 by JavaFX runtime of version 11
```
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1249547502" expanded>

I have found the binary file in the link. Anya works fine on Windows 11, although an exception is thrown on this particular input: ```mark node as visited```.

<img width="302" alt="image" src="https://user-images.githubusercontent.com/13196670/190683267-4e0a74f9-3f4d-4ace-ad3b-3591cd78a06a.png">

</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280#issuecomment-1254140007" expanded>

Thanks @rui-han-crh for the great help! I followed your suggestion and got it to work on Linux (at least on my machine). I have updated my jar file. Please help me test again to make sure the jar file works.
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280#issuecomment-1254655132" expanded>

Thanks @rui-han-crh for your feedback. I have updated my release. For Linux users, does `java -jar jude-0.3.jar` work now?
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/290#issuecomment-1254668173" expanded>

I found a copy-paste bug on the user guide.
<img width="363" alt="image" src="https://user-images.githubusercontent.com/13196670/191690145-bd84db6e-7e1b-4410-99cb-ea0499d4df35.png">

Update: The bug has been mostly fixed except for this part
The command should be `deadline` not `event`.
<img width="325" alt="image" src="https://user-images.githubusercontent.com/13196670/191760623-17c13987-d19d-44f5-bd62-aae641a41b41.png">


</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/338#issuecomment-1273359983" expanded>

Thanks so much. So this is not a bug.
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/345#issuecomment-1286931828" expanded>

Thanks prof
</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/368#issuecomment-1288732336" expanded>

> @cheeheng Yes, it should be ~~microkernal~~ (EDIT: microkernel)

Does it mean that the original spelling is correct?

Thanks so much for the clarification about the omission of SoA architecture.
</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/369#issuecomment-1288733164" expanded>

Thanks so much prof! This is very informative.
</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/368#issuecomment-1291393076" expanded>

Thanks so much prof!
</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/377#issuecomment-1292862966" expanded>

Thanks prof!
</panel>

<panel  header="**47 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/387#issuecomment-1296227299" expanded>

Thanks prof. Perhaps it would be better to make the context more explicit for future semesters.
</panel>

<panel  header="**48 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/399#issuecomment-1296256608" expanded>

I tried on Chrome version 108 (beta) and Microsoft edge version 107 and it did not work. 

From the image, it looks like you are in the wrong page. It should be this one: https://nus-cs2103-ay2223s1.github.io/website/schedule/week12/project.html 
</panel>

<panel  header="**49 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/398#issuecomment-1296257597" expanded>

I did not see the fix. Did you change the wrong survey, prof?
</panel>

<panel  header="**50 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/399#issuecomment-1296259270" expanded>

Sorry for not being clear earlier. But now, I am experiencing what it means by 'a poorly-written bug report is better than no bug report at all'.
</panel>

<panel  header="**51 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/398#issuecomment-1296269145" expanded>

It's correct. Thanks prof for fixing the bug.
</panel>

<panel  header="**52 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/436#issuecomment-1307398920" expanded>

Thanks so much for fixing it, prof. It was very frustrating for me to take the question very literally and get it wrong. Hopefully, those who will do the quiz afterwards will not face this issue.
</panel>

<panel  header="**53 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/463#issuecomment-1314754183" expanded>

Oops, I did not notice this. Perhaps it can be implemented in the following semesters so that it would be more intuitive to users.

Thanks prof!
</panel>

<panel  header="**54 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/472#issuecomment-1315676900" expanded>

Indeed, this is also one of my biggest concerns. Thanks prof for your quick reply.
</panel>

<panel  header="**55 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/481#issuecomment-1324607988" expanded>

Thanks prof! That was very helpful.
</panel>

<panel  header="**56 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/482#issuecomment-1324617439" expanded>

Please refer to [this comment](https://github.com/nus-cs2103-AY2223S1/forum/issues/478#issuecomment-1321884140).
</panel>

<panel  header="**57 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/495#issuecomment-1326158621" expanded>

[StackOverflow Reference](https://stackoverflow.com/questions/20782902/uml-diagram-inheritance)

Since `ProgressWatcher` does not overwrite `update()` from `Watcher`, we do not write `update()` in the UML diagram.

However, for `UiWidget()`, `update()` method overrides `update()` from the parent class `ProgressWatcher` (which in turn inherits the `update()` method from `Watcher`), hence we have to explicitly write `update()` to indicate that it is overwritten. I believe it would be better to explicitly include this inside the textbook to prevent confusion of future batches.

From the StackOverflow source, {redefines} could be added after the method name, but since this is not covered in the module, we can just leave it out?

I am not so sure whether this is correct. Please correct me if I am wrong.
</panel>

<panel  header="**58 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/496#issuecomment-1326414942" expanded>

Thanks prof.
</panel>

<panel  header="**59 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/501#issuecomment-1328168513" expanded>

Prof Damith is right, `&gt;!-- @@author JohnDoe -->` inside Markdown files indeed work. If it didn't, then it would have been a major deviation since some parts of my team's developer guide have `&gt;!-- @@author JohnDoe -->` comments to ensure correct authorship, in particular to prevent minor changes in formatting from changing the authorship.

This is a feature flaw and not a bug, but there isn't a label 'Feature flaw', hence I had no choice but to put the label 'Bug'. 

Perhaps prof could include 'Feature flaw' or 'Feature request' label in the forum for future semesters?
</panel>

</panel>


<panel type="info" header="### 4. SHER.. TAN `@sltsheryl` (43 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Defining Feature Flaw**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/462" expanded>

Could I ask does it count as a feature flaw if the app behavior seems not very realistic but this is written in the UG, though without much justification why?

Eg. The app is not case sensitive with people's names (treat them as different people) or 

The app does not allow people with the same name (people can have the same name in real life like John Tan but different particulars)

but it is written in the UG that "Person name input must strictly match the name of an existing person, even the casing, extra whitespaces should be regarded as the same person", though not justifying why in the UG.

Does this constitute a feature flaw? 

It is not a functionality bug since it aligns to the UG, but disallowing people with same names and being case sensitive seems to be quite unrealistic for the app in the real world and it makes things more cumbersome for a fast typist (the case sensitive part)
</panel>

<panel  header="**2. :fas-info-circle: PlantUML Sequence Diagram: Destroyed object**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/376" expanded>

In this [section](https://nus-cs2103-ay2223s1.github.io/website/se-book-adapted/chapters/uml.html#object-deletion) of the textbook, it says the lifeline should end where the object is deleted. 

<image src="https://user-images.githubusercontent.com/96589109/197993714-82bc014c-ad35-447a-963e-c2f1b0d31413.png" height="100">

However, I think [PlantUML doesn't support ending the lifeline](https://forum.plantuml.net/9324/end-participant-line-after-destroy) and the given `DeleteSequenceDiagram` in AB3 does not align with the textbook, where the lifeline for ```DeleteCommandParser``` is extended till the bottom after it is destroyed. 

<image src ="https://user-images.githubusercontent.com/96589109/197995104-978e3db9-f19e-44e6-a6cb-e27f81a71f16.png" height="450">

Could I ask if there is a way around this? Thanks!
</panel>

<panel  header="**3. :fas-info-circle: Use of assert x != null and requireNonNull(x)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/367" expanded>

Could I clarify more about the use of ```assert x != null``` and ```requireNonNull(x)```?
I think a few differences between them are 
1. ```requireNonNull(x)``` throws a NullPointerException when x is null instead of an assertion (assertion handles more of developer side errors while exceptions include users input errors)
2. ```assert``` will work only if we put ```-ea```/enable assertions but ```requireNonNull``` will always work

But I'm still not entirely sure when we use which. Is it right to think in this way,

For instance, in the current ```EditCommand``` in ab3, 
for ```Index``` in ```EditCommand(Index index, EditPersonDescriptor editPersonDescriptor)```, we will do ```requireNonNull(Index)```.

But after we have gotten the ```personToEdit``` from ```Index```, we will then do ```assert personToEdit != null``` in the method ```createEditedPerson``` given.

Thanks!
</panel>

<panel  header="**4. :fas-info-circle: Updating the DG: Other Members Implementation**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/353" expanded>

Hi for updating of the DG Implementation, it says that we should do a writeup for a feature we have implemented ourselves. Could I ask if a member can do a write-up for another member's implemented feature? Because some features are quite similar and we feel it's better to include the features that may have been done by the same person.

Eg. Person X implemented a feature similar to Person Y, but Person Y has written about that feature already and has other more worthy features to be written in the DG), can Person X do the writeup for other features implemented by Person Y?

Thanks!

<img width="688" alt="Screenshot 2022-10-19 at 2 22 07 PM" src="https://user-images.githubusercontent.com/96589109/196612632-a567cf4a-de8f-4475-98ba-1cb03941b8fe.png">

</panel>

<panel  header="**5. :fas-info-circle: Sync fork button to sync team repo**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/324" expanded>

Hi can I ask on the website, it says to sync our team repo, we should do git pull then git push to our own fork.

<img width="400" alt="Screenshot 2022-10-01 at 1 55 51 PM" src="https://user-images.githubusercontent.com/96589109/193395086-cfd50143-f299-45e7-9cd9-f1738dddc9a1.png"> 

Just to check, we can also use Sync fork on GitHub? It won't affect how the grading checks for our forks, etc.?
Thanks!

<img width="400" alt="Screenshot 2022-10-01 at 1 56 38 PM" src="https://user-images.githubusercontent.com/96589109/193395097-92640300-0edc-426b-a78d-757fe47f1310.png">

</panel>

<panel  header="**6. :fas-info-circle: Pull request to teams TP repo failing codecov check**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/239" expanded>

Hi I was following this week's tutorial to add a Remark feature to addressbook and create a PR to the team's repo from my fork. 
However, I'm failing this check. My team has set up codecov already. This is found in the branch `tutorial-adding-command` in my fork of my team's repo. Thanks!
<img width="1104" alt="Screenshot 2022-09-17 at 11 02 19 AM" src="https://user-images.githubusercontent.com/96589109/190838203-b36b3dba-0b12-4dfe-b693-fd56caa4ba34.png">

</panel>

<panel  header="**7. :fas-info-circle: Request for help for smoke test (Linux, Windows)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/218" expanded>

Hi sorry for the trouble! Could anyone help to smoke test for Linux and Windows? I have packaged the app with the fonts, but I'm checking if it shows. The jar file is attached [here](https://github.com/sltsheryl/ip/releases/tag/A-Release). Thank you!
</panel>

<panel  header="**8. :fas-info-circle: Jar file able to open on Mac and Windows, but fonts do not show up**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/186" expanded>

Hello, I've pushed my latest version v0.4 for my .jar file in my repo. While asking my friends to test my programs on their computers (Mac and Windows), they can open it, but the fonts that I have included in the .fxml file and shown on my side are not shown on theirs. I am not sure what is the cause of this. Thanks!

The fonts are rendered correctly on my side.
<img width="597" alt="Ui" src="https://user-images.githubusercontent.com/96589109/189917475-64aedf17-d412-47d1-80a9-986d44ba2061.png">

This is what shows up on others' computers.
![photo_2022-09-13 21 45 15](https://user-images.githubusercontent.com/96589109/189917850-312f0a96-a299-4712-9ce9-83a10148c04d.jpeg)


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/18#issuecomment-1218777477" expanded>

Hi after creating a PAT, 
 you can try going to Sourcetree -&gt; Preferences -&gt; Account , click ‘add’. Then, in the Host dropdown choose ‘GitHub’; in AuthType dropdown choose ‘Basic’.
Then key in the pat as your password? In my case, I just used my username as username and PAT as password and it worked.
You can check this out method 2 https://medium.com/geekculture/using-personal-access-token-in-sourcetree-to-connect-to-github-3702a29554d3
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/20#issuecomment-1218944174" expanded>

Hi I faced the same issue and I followed these steps.
https://macappstore.org/dos2unix/
And afterwards that line went away
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/44#issuecomment-1221461429" expanded>

Hi there're a few examples here which said that it's usually placed before 
https://stackoverflow.com/questions/3109950/codestyle-put-javadoc-before-or-after-annotation
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/72#issuecomment-1228115316" expanded>

Hi I'm not sure if this helps but you can try 
https://www.jetbrains.com/help/idea/reformat-and-rearrange-code.html#reformat-on-save
⌘ , to open the IDE settings and select Tools | Actions on Save.
Enable the Reformat code option.

Eg. as mentioned by other comments on removing the indent for switch cases, you can do ⌘ , and search for switch, and modify it in Editor > Java > 'switch' statement.

Also, after you have the Preferences tab (⌘ , ) opened, you can search Smart Keys and check the ones you want are ticked.
 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/82#issuecomment-1229136387" expanded>

Hi if you see under stretch goal, they included Event as well. It’s a good idea to be able to handle Event too because its arguments can be in the form of a standard date too.

As said by the rest, we have quite a lot of freedom to customise how we want to utilise the date time and how we take in inputs and outputs. 

I think the interval idea is nice because it gives us extra features eg. a deadline can have different starting time. Other extensions are handling different date formats. But it requires more work like how we split the string and additional things to keep track. But if it’s something that we want, we should go for it. To be safe, before doing extra, make sure our program can handle the minimum requirement ie. the example input yyyy-mm-dd.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229363612" expanded>

> I firstly created a add-gradle-support branch for my remote repo, then forked it from https://github.com/nus-cs2103-AY2223S1/ip, afterwards I created a local branch following the remote add-gradle-support and has all the gradle files, then merged the gradle branch and my master branch locally before pushing it to my master branch on github

After merging the add-cradle-support branch, did you
1. Close the IDEA project
2. Delete the .idea folder
3. Open the project again 
https://se-education.org/guides/tutorials/gradle.html (scenario 2)
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/91#issuecomment-1229410185" expanded>

I feel performing TaskList methods in the Parser class may not be that ideal because we would need to pass the list of tasks around which is quite clumsy . 

It may be better to have an abstract class Command (written in A-More-OOP) and in the Parser class, create instance of the different types of commands. And each command class handles adding or removing task from the task list. I find this more natural as the job of task management (adding and removing tasks) and parsing the input string are handled separately.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/114#issuecomment-1232764553" expanded>

I think a few things you can try is 
1. Ensure you have the checkstyle.xml and suppressions.xml files in a config folder in your project. They should be filled, the content copied from the address book.
2.  Check the tool version in the build.gradle file and the Checkstyle version that you set should be the same as that (for me it was initially different)
3. Remember to add the plugins in your build.gradle file (saw some people encountered this error on stack overflow because of this)
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1233640810" expanded>

Hi here's my GUI :)
I changed the following: 
- Modify the avatars for both parties. 
- Changed the background to black. 
- Minimise the spaces between each dialogbox.
- Changed the font to monofur. Resized it to be bigger. 
<img width="398" alt="Screenshot 2022-09-01 at 1 13 18 PM" src="https://user-images.githubusercontent.com/96589109/187837247-54283aab-108c-4884-9949-53035956b4a9.png">




</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/126#issuecomment-1235318992" expanded>

Not sure if it works but I think there's a missing / before images. 
```
private Image user = new Image(this.getClass().getResourceAsStream("/images/DaUser.png"));
private Image duke = new Image(this.getClass().getResourceAsStream("/images/DaDuke.png"));
```
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/144#issuecomment-1236325761" expanded>

Hi it’ll be clearer if you can specify the issue or error, but it seems like you don't have the build.gradle file.
The other comments are referring to this, it really helped me so you can check it out too.
https://github.com/nus-cs2103-AY2223S1/forum/issues/55
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180#issuecomment-1244101862" expanded>

Hi I talked abit about this here https://github.com/nus-cs2103-AY2223S1/forum/issues/91.
I think we can think of it as handling different concerns in different classes. 
So the parser, as the name suggests, could handle taking in the user input and deciding which command to call and its argument. 
While, the UI could handle displaying user interface messages such as the different task messages, welcome and bye messages. 
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/186#issuecomment-1246335233" expanded>


> I assume that the code will be tested on a java 11 environment so I changed the settings in the fxml files to follow java 11. I guess what you can consider is to inform users to download the required fonts for your program or like what @waynezsy has mentioned, to use an OS common font to avoid font not displaying issues. Hopefully this has helped you.

Oh I see, thanks! @NicsunXnus @waynezsy
I added the font via Scene Builder so I thought it was one of those standard fonts like Comic Sans but it makes sense it's not an OS common font. 

Yup, I'll heed your advice to give an option to download or change to another font. 
Or per prof advice, https://guigarage.com/2014/10/integrate-custom-fonts-javafx-application-using-css/

Thanks both!
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/186#issuecomment-1246337245" expanded>

> 

👍 Thanks prof
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/218#issuecomment-1249084084" expanded>

> Works as expected on Linux (Arch)! Fonts, images loaded. Resize also working properly. 👍 ![Screenshot_20220916_163338](https://user-images.githubusercontent.com/22095441/190594446-bbfef9b0-38b5-4587-962e-a08fd64e3564.png)

Thank you for the swift response!
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/218#issuecomment-1249105277" expanded>

> @sltsheryl By the way, can you give me a summery of how did you include the fonts? I would also like to include my fonts. I have some emojis that do not show up in other's PC. 😞

Yep sure, I followed this [repo](https://github.com/TheItachiUchiha/FontLoad) to set custom fonts in JavaFX.  
1. I downloaded the font ttf file, add it to a `fonts` folder in `resources` folder.
2. I created a `Font.css` in a `css` folder under `resources`.
```
@font-face {
    src: url('../view/fonts/Monofur.ttf');
}
```
3. I used inline css to add the fonts in the respective DialogBox.fxml files in this way
`style="-fx-font-family: 'monofur for Powerline'; `in the `Label` tag
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/218#issuecomment-1249479596" expanded>

> Works on Windows 10!
> 
> ![image](https://user-images.githubusercontent.com/63991775/190647045-1ae9f2fc-0aba-41d1-b1dc-a2e61cb1e637.png)

Thanks :)
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/232#issuecomment-1249482626" expanded>

Working fine on Mac
<img width="395" alt="Screenshot 2022-09-16 at 11 06 01 PM" src="https://user-images.githubusercontent.com/96589109/190670978-6751047b-47e1-4df9-add1-89f2d73085d6.png">

</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/239#issuecomment-1249987985" expanded>

Ah okay, [here](https://github.com/AY2223S1-CS2103T-T11-4/tp/actions/runs/3071873273/jobs/4962935988) is the page showing the logs.
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/239#issuecomment-1249993969" expanded>

> This is kinda a guess (i might be wrong)
> 
> https://codecov.io/gh/AY2223S1-CS2103T-T11-4/team-repo
> 
> so the name is `team-repo` on code-cov
> 
> but your team repo name is `tp`...
> 
```
> Pinging Codecov: https://codecov.io/upload/v4?package=github-action-2.1.0-uploader-0.3.1&token=*******&branch=tutorial-adding-command&build=3071873273&build_url=https%3A%2F%2Fgithub.com%2FAY2223S1-CS2103T-T11-4%2Ftp%2Factions%2Fruns%2F3071873273&commit=c355cf412815532ec32ef29d9bf3b05517bdf2db&job=Java+CI&pr=4&service=github-actions&slug=AY2223S1-CS2103T-T11-4%2Ftp&name=&tag=&flags=&parent=
> [2022-09-17T03:01:18.215Z] ['error'] There was an error running the uploader: Error uploading to [https://codecov.io:](https://codecov.io/) Error: There was an error fetching the storage URL during POST: 404 - {'detail': ErrorDetail(string='Could not find a repository, try using repo upload token', code='not_found')}
```
> 
> and the error is it cannot find the repo and it is trying to find `tp`
> 
> i think this is a codecov repo name wrong problem and not really your code

Hmm thanks for helping to look at this, I'm still abit confused.

I think my team named our repo as `team-repo` but yup, that one member forked it from the CS2103T's `tp` repo. So I thought the naming (`team-repo`) matches? Or is our repo supposed to be named `tp` because its default is to find a repo called `tp` (?) or can/should we change it to find `team-repo` instead? (currently, we only modified `index.md` to display the codecov badge but I'm not sure if we are to change other areas)


</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/239#issuecomment-1249994795" expanded>

> > Or is our repo supposed to be named `tp` because its default is to find a repo called `tp` (?) or can/should we change it to find `team-repo` instead?
> 
> It should be `tp`.

Alright I will make the necessary changes and see if it works. Thanks!
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/239#issuecomment-1249997541" expanded>

Thank you both for troubleshooting! It's working now, we will read more carefully next time.
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/247#issuecomment-1250162905" expanded>

Can open on Mac! But doesn't support resizing
<img width="389" alt="Screenshot 2022-09-18 at 8 31 22 AM" src="https://user-images.githubusercontent.com/96589109/190880626-071e0871-7c24-4947-9fd8-7b36b319422b.png">

</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/271#issuecomment-1252363186" expanded>

It's working fine on mac, nicely done design and transitions! 
I think there's a slight typo in a few examples in the user guide under Adding Loans. It should be ```loans add Lynette /amount $50``` instead of ```loans add Lynette -amount $50```. A small nitpick is marking the task via the GUI doesn't update the checkbox if I do ```tasks list``` again.


<img width="772" alt="Screenshot 2022-09-20 at 9 30 04 PM" src="https://user-images.githubusercontent.com/96589109/191270886-a21e395b-5d26-48d8-8929-4c01ff92062b.png">

</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/281#issuecomment-1253142540" expanded>

The pictures are okay on mac. But yea, I can't input invalid commands like what the others mentioned, it's not handled. 
<img width="586" alt="Screenshot 2022-09-21 at 10 51 31 AM" src="https://user-images.githubusercontent.com/96589109/191403619-936b3c01-91ae-490b-97b4-f8bd408dd9f1.png">

</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280#issuecomment-1253143891" expanded>

It's working well on mac. It resizes correctly too!
<img width="588" alt="Screenshot 2022-09-21 at 10 54 50 AM" src="https://user-images.githubusercontent.com/96589109/191404106-4eb741eb-d714-43cd-a65c-550fb05cbab1.png">

</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/324#issuecomment-1264262850" expanded>

> @sltsheryl yes you can use that too, but we recommend you learn (and use for a while at least) the more basic method given in our website. Reasons:
> 
> 1. 'Sync fork' is a Github-specific feature while our method works even if you are not using GitHub. This is important as the companies you will intern at might not be using GitHub.
> 2. You have more control (e.g., you can decide the exact commit message) when you sync locally rather than remotely

Yes I see, thank you!
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/353#issuecomment-1283541864" expanded>

Alright thank you!
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/367#issuecomment-1287858269" expanded>

Ah I see, sorry I missed the duplicate question. Thank you
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/376#issuecomment-1293263836" expanded>

> > Could I ask if there is a way around this? Thanks!
> 
> IIRC it was mentioned during my tutorial that due to restraints with PlantUML, it is fine to leave it as it is and that it is for our learning that the textbook sticks with the version where the lifeline should end where the object is deleted. This is just a vague memory, so someone please correct me if I'm wrong.

Ah I see thanks for replying, yep just checking so this won't count as a documentation bug. Thank you!
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/376#issuecomment-1293338401" expanded>

Noted thanks!
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/384#issuecomment-1295177025" expanded>

I was also looking if there’s a special way to get `sd`, but I think the closest is to use 
```
group sd reference_frame_name
// insert what’s inside sd
end
```
</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/412#issuecomment-1301065874" expanded>

Could I also check if we should put the `//@@author` comment before or after all the import statements because if we changed the names of the packages, all the import statements would be allocated to us? Or does this not matter since this is just to check the code quality of what we wrote?
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/462#issuecomment-1314753796" expanded>

Thanks!
</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/489#issuecomment-1325884836" expanded>

It's on Edurec > Academics > Exams > View exam schedule
</panel>

</panel>


<panel type="info" header="### 5. TJAN..EVIN `@Nephelite` (40 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Question regarding practice exam part 2/3 (Composition vs Aggregation)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/483" expanded>

In the part 2 sample answer/part 3, the relation used between activities was a composition relation, but I personally interpreted the relationship to not be a composition because of the following reasons:

1) I don't think that deleting the main activity would necessarily delete all connected activities since you could do sub-activities without the need for a main activity. E.g: "Having fun" has a sub-activity "Play piano", but deleting the "Having fun" activity may not result in the deletion of the "Play piano" sub-activity. Perhaps at some point, the user no longer finds the piano fun, but still does it because it's their job.

2) "Play piano" could also exist as an activity by itself without the need of a "Having fun" activity.

Should the relation then be aggregation instead, or is my logic wrong here, or am I overthinking this?
</panel>

<panel  header="**2. :fas-info-circle: Duplicate rejection dependent on result of other bug report**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/467" expanded>

I reported 2 similar bugs that cannot be fixed independently if ruled as functionality bugs. However, the dev team reported them as documentation bugs and set one of them as a duplicate. Indeed, if ruled as documentation bugs, they would be fixed by the same changes.

I believe I have good reason to reject their reasoning for why the bug should be a documentation bug, i.e I believe I was right about both bugs being functionality bugs, but if my reasoning is not accepted, my duplicate rejection is also going to be rejected by default. Is there some way to indicate that I only reject a duplicate declaration in the event another bug report gets accepted by the tutor?
</panel>

<panel  header="**3. :fas-info-circle: Duplicate issues with differing severity levels**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/449" expanded>

For the same exact documentation bug, one tester reported it as a medium severity bug, and another reported it as very low. Funnily enough, our team feels that the bug is of low severity, right in the middle. 

Medium: https://github.com/nus-cs2103-AY2223S1/pe-dev-response/issues/5645

Very Low: https://github.com/nus-cs2103-AY2223S1/pe-dev-response/issues/2891

What is the right action in this scenario, after reporting one of them as a duplicate? And for that matter, which should be the duplicate?


</panel>

<panel  header="**4. :fas-info-circle: Between Reject and Cannot Reproduce, which should take precedence?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/448" expanded>

In this bug report, the tester both provided steps that do not accurately reflect how to achieve the bug they found (task description of added task is different from the command they claimed to have inputted), and also tested the product using extreme user input that is not expected in normal usage.

I would like to pin this as both 'CannotReproduce' and 'Rejected', but am not sure which is more applicable in this context.

Issue in question: https://github.com/nus-cs2103-AY2223S1/pe-dev-response/issues/1406
</panel>

<panel  header="**5. :fas-info-circle: Github CI Gradle interface method overriding bug**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/346" expanded>

Initially, my method's signature was
```void updateFilteredTaskList(Predicate<Task> predicate)```
in both the Model interface and the ModelManager class (public in the class).
This compiles fine in IntelliJ, so I pushed it and made a PR.
Github CI then tells me that it cannot compile because of the following error in the build:
![image](https://user-images.githubusercontent.com/97427604/196030928-417990ae-7175-4f52-8ae3-4372ea5baf66.png)
I can guarantee that the method is properly overridden. I can also 100% guarantee that there is no duplicate method. There is no other method with the same name.
I did not know what to do, so I tried a lot of things, and eventually, I just renamed the method to 
```void changeFilteredTaskList(Predicate<Task> predicate)```
and it worked. Github CI passed the check.

As a final test, I changed the method name back to update, and it fails again.

I suspect the reason is that I have another method in the class that is similar, it is updateFilteredPersonList. It has the same arguments too. 
</panel>

<panel  header="**6. :fas-info-circle: Automated Smoke Test Reports Invalid/Corrupt Jar Files**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/274" expanded>

This is my [jar file](https://github.com/Nephelite/ip/releases/tag/A-Release) and my [user guide](https://nephelite.github.io/ip/).

These are the errors reported by the automated smoke tests in the email.
>    An automated smoke testing of your iP JAR file found the application crashes with the following error(s) upon launching:
>    On Windows, using Java 11, for the duke.jar uploaded on 09-18-2022 (MM-DD-YYYY) at 19:04:43:
>    Error: Invalid or corrupt jarfile duke.jar
>    On Linux, using Java 11, for the duke.jar uploaded on 09-18-2022 (MM-DD-YYYY) at 19:04:43:
>    Error: Invalid or corrupt jarfile duke.jar
>    On Mac, using Java 11, for the duke.jar uploaded on 09-18-2022 (MM-DD-YYYY) at 19:04:43:
>    Error: Invalid or corrupt jarfile duke.jar

The email, in short, informs me that my jar file fails to run in any of the 3 environments due to an invalid or corrupt jar file.

In spite of what the email says though, I can run it fine on my Windows environment, and my Linux VM. My friends can also run it fine on their Windows, MacOS and Linux systems as well. I do not see these errors anywhere. 

Can someone check if my jar file works on their system? Does anyone know of what could possibly be the issue that the automated smoke tests are detecting?

I have performed all the checks I can think of on my end. My Java environment is 11.0.13. My `./gradlew run` in IntelliJ opens the jar file properly. My file on Windows opens on double click, and `java -jar duke.jar` works fine for all 3 systems from my friends. 

I'm at my wits' end and don't know what could be the cause of the errors that the automated smoke tests are detecting.
</panel>

<panel  header="**7. :fas-info-circle: Using ```-Djdk.gtk.version=2``` to open jar file in Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/246" expanded>

I cannot run my jar file in Linux VM using only ```$ java -jar duke.jar```, nor double clicking. I have to use ```$ java -jar -Djdk.gtk.version=2 duke.jar``` in order to open it. From there, it runs properly as intended.

This is not a Linux VM only issue, my friend (not taking the module this semester) also had to run the latter command to get my jar file to work. He also could not double click to open the jar files.

Are incompatible gtk versions going to be considered as a bug? Do we have to fix this such that Linux users can simply run ```$ java -jar duke.jar``` or simply double click?

![image](https://user-images.githubusercontent.com/97427604/190856185-81599e7e-8e9d-45b7-88f7-8a2ae3fc27e4.png)
The exception if I run the former command. Screenshot because I cannot copy and paste from a VM.
</panel>

<panel  header="**8. :fas-info-circle: Request for Help to Smoke Test (Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/221" expanded>

Hello, could anyone help me to test my [Jar file](https://github.com/Nephelite/ip/releases/tag/A-Release) in Linux? 
Here is the [User Guide](https://nephelite.github.io/ip/).

Thanks in advance!
</panel>

<panel  header="**9. :fas-info-circle: Clarification regarding the detection of final JAR release**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/173" expanded>

In Week 5, the first task said that a JAR release was optional (and we were welcome to). I released by JAR file because I felt compelled to.

Now in Week 6, the progress tracker detected my Week 5 release before I finished by Week 6 release (which I have finished at the time of writing).

I just wanted to seek clarification if the JAR file marked is the latest release tied to A-Release and not the release titled v0.2, in the case where there are 2 releases in the stipulated detection period.
</panel>

<panel  header="**10. :fas-info-circle: Seeking clarification regarding Luminus Quiz week 6 questions 27 and 30**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/161" expanded>

The area of confusion for me is the line
'A call to f() can result in any of the following'.
which can be interpreted as
A call to f() can result in (any of the following) -&gt; All listed results are valid outcomes of f()
or
A call to f() can result in any (of the following) -&gt; At least 1 listed result is a valid outcome of f()

I believe the intention is the former, but I would just like a confirmation that the former interpretation is the intended one.
</panel>

<panel  header="**11. :fas-info-circle: Added Gradle Manually**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/59" expanded>

I saw the instruction where they mentioned the add-gradle-support branch and didn't connect the dots that we were supposed to merge from a branch in the original repo until just now. I instead added Gradle manually for all the subsequent parts. Is this going to cause an issue later down the line for the iP? Do I have to merge from the original branch to show I know how to merge from there?
</panel>

<panel  header="**12. :fas-info-circle: Question about the answer for the W3.5a video quiz question 3**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/37" expanded>

The solution for Q3 of the W3.5a video quiz feels wrong to me.

The correct answer is true, meaning we should change our opinions to fit the module coding guidelines given by the professors. However, the video (and the answer description) both say we should hang on to our opinions but still follow the guidelines given to us (i.e we _shouldn't_ change our opinions). 

I feel that this is a direct contradiction. The video and description implies false is correct, but the correct answer is true.

Seeing the solution, I get what the question is trying to ask, but I think it is phrased incorrectly. Actions taken do not reflect our opinions, and just because I agree to follow a coding guideline, it doesn't mean I think it is correct.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/37#issuecomment-1221365532" expanded>

Yep, it's correct now.

P.S Just for reference, this was what I was seeing before.
![image](https://user-images.githubusercontent.com/97427604/185757957-1998adef-7fe2-40a4-bf77-06023e61801b.png)

</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/59#issuecomment-1225738851" expanded>

Oh, thank you prof! 

Hopefully my brain doesn't give out on me like this again in the future...
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/161#issuecomment-1242012293" expanded>

@damithc Thank you for the clarification prof! 
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/173#issuecomment-1245102294" expanded>

Thanks prof!
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/190#issuecomment-1246755383" expanded>

Hello, I think I know the problem here, but I may be wrong. Could you try the following change and see where this gets you?

Under ./build.gradle, line 45, change the ```mainClassName``` to the appropriate package path to your Launcher. It is currently ```sally.Sally```. Change it to ```sally.main.Launcher```. (At least, I think that is the right package path?)

One of the reasons for the ```Launcher``` class to begin with was to workaround the classpath issues. However, you aren't making use of the ```Launcher``` class right now as is. You do not want Sally to be the entry point of the application. You want ```Launcher``` to be that instead.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/221#issuecomment-1249984884" expanded>

@RezwanArefin01 Thanks for the help! In accordance with your recommendation in that thread, I have tried converting the images to .png. I have thus updated my [jar file](https://github.com/Nephelite/ip/releases/tag/A-Release). Could you check this new jar file? Thanks!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/221#issuecomment-1250030147" expanded>

Nevermind, I went and installed a Linux VM to test it and it should be working now. Thanks for the alert though!
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/241#issuecomment-1250033484" expanded>

As far as I can tell, your jar file works fine on Linux. However, I ran your jar file via a VIrtualBox Linux VM, so it might be best if someone else with an actual Linux system also tests this.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230#issuecomment-1250046593" expanded>

@jetlfj 
![image](https://user-images.githubusercontent.com/97427604/190852435-f6e76c53-36aa-4223-9b6c-03ab9c82734d.png)
I ran this on a Linux VM and the images aren't displaying properly. I will refer you to this [thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/217) where RezwanArefin01 discusses the solution to this problem.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250051207" expanded>

I ran your jar file in my Linux VM. Perhaps this isn't an accurate test, but...

![image](https://user-images.githubusercontent.com/97427604/190853004-c23a5229-9d67-4895-a0bf-9cf11d7b031a.png)
![image](https://user-images.githubusercontent.com/97427604/190853020-e0a9d837-2ee5-44d4-a6cd-f7a188efdf2a.png)

Below is the first block of exceptions I get before an infinite loop of NPEs
![image](https://user-images.githubusercontent.com/97427604/190853087-e4ee303d-7941-4c85-b094-705c5f7370a8.png)

Apologies, but I can't paste the block of exceptions as a code block because I am running your jar file on a VM. 

Your jar file starts up fine on Linux VM.

However, I got this exception whenever I try to run any command on Linux. I suspect the reason is that your userImage is an image in ```.jpg``` format. According to RezwanArefin01 in [this thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/217), changing the image to a ```.png``` format should fix the issue. 
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/246#issuecomment-1250073703" expanded>

@damithc I used Windows to make the JAR file.

I can run JAR files by all the other students I've tested on if I use the ```-Djdk.gtk.version=2``` flag. In particular, I have tried it on at least 6 other students (semi-smoke testing for them, some not on the forum), and I could run the JAR file without the flag in only one of them. 

In other words, 5/6 of the JAR files I tried to open with ```$ java -jar duke.jar``` failed to open due to the exact exception in the image of the post. They all needed the flag to be run. Only 1 of the 6 could be double clicked or opened with ```$ java -jar duke.jar```.

And just to clarify, this is likely not an issue with my VM. I have a friend that also uses Linux, and he has the same issues. Not saying this issue is definitely a Linux issue though, it might be an issue only affecting a subset of Linux users.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/246#issuecomment-1250202363" expanded>

@deepimpactmir @parnikkapore Thank you both so much for the input! 

Since this is an issue with newer Ubuntu systems, it should definitely be treated as a bug and addressed. I added the following to my ```build.gradle``` and now it works properly with just double clicking.

```java
javafx {
    version = "11.0.2"
    modules = [ 'javafx.controls', 'javafx.fxml' ]
}
```

I'm not actually sure if the module part is needed, but I referenced @njxue when adding this code (His iP was the one I was talking about that worked on double click in Ubuntu).

Thanks again for the advice!

Post-closure edit: Also, I had ```id 'org.openjfx.javafxplugin' version '0.0.7'``` in my plugins block in ```build.gradle```, but njxue uses ```id 'org.openjfx.javafxplugin' version '0.0.10'```. This is needed for the javafx block to work.

Post-closure edit 2: Apparently the javafx block MUST be above dependencies/below plugins. 
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250203909" expanded>

@sugiyem Everything seems in order
![image](https://user-images.githubusercontent.com/97427604/190889198-8c2b3a73-f234-48ea-9371-4937cf8f6963.png)

However, before you close this thread (if you are only waiting on a Linux response), I wanted to mention [this thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/246). This issue applies to your JAR file too, so do give it a look. I didn't mention it in my prior post because I did not know about it at the time. If you want me to test this again, let me know!

Edit: Also, add ```id 'org.openjfx.javafxplugin' version '0.0.10'``` into your plugins in ```build.gradle``` if you want to do the changes in the thread I mentioned
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230#issuecomment-1250244415" expanded>

@jetlfj Well, the images still do not display properly. This is now not a format error, but is actually image corruption. I recommend converting both images to jpg and back to png (edit: I used an online converter), then replacing your current ones. If you see that Git detects changes to the images, you'll know you succeeded. 

Edit: Just for the record, I did those steps and the images displayed properly after. 

Also, I recommend reading [this thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/246) that I posted very recently, just in case.
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250264817" expanded>

To add on, the javafk block should be directly below the plugins block.
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250312999" expanded>

@sugiyem 

![image](https://user-images.githubusercontent.com/97427604/190907783-13bb3ce0-5adb-4860-98f7-4e1e1f438a79.png)

Yep, works for me now with just ```java -jar```.

Do ask for a mac user to test again though, since you have made big changes to your build. Ensure they are using zulu jdk 11 as indicated by the module website.
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/274#issuecomment-1252498445" expanded>

@damithc Will my jarfile be retested?
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/274#issuecomment-1252505453" expanded>

@damithc Thank you prof!
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/346#issuecomment-1279969881" expanded>

@damithc Sure, here are links to the relevant PRs
'Problematic' code:
https://github.com/AY2223S1-CS2103T-T13-4/tp/pull/152
Working code:
https://github.com/AY2223S1-CS2103T-T13-4/tp/pull/150
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/346#issuecomment-1280270064" expanded>

Thanks!
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/393#issuecomment-1296150210" expanded>

@damithc What exactly constitutes as extreme input in this context? For my group, dates are appended at the end of the description, making it fairly likely that the user will overrun the box.

My group wants to enable line wrapping (and also mention that the user can resize the window if needed in the UG)
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/393#issuecomment-1296154199" expanded>

@damithc Then in the case where our tP does not wrap lines even if there are multiple words, that is not an extreme situation and my team is allowed to fix it?
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/448#issuecomment-1312724921" expanded>

@damithc In the end, I chose 'cannot reproduce', explained all the attempts I made to reproduce the bug, and just to cover every base, also mentioned that the inputs were extreme and why.

My only worry is if the tester rejects, and the tutor somehow manages to find out how to reproduce the bug. In that case, would I be marked down still, or can I then change the label to 'Rejected'?
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/448#issuecomment-1312732674" expanded>

@damithc Ok, I will mark as rejected then. Thank you!
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/449#issuecomment-1312739208" expanded>

@damithc I see, thanks!
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/467#issuecomment-1314979968" expanded>

@damithc Thanks!
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/483#issuecomment-1324809814" expanded>

In addition, assuming i.e means 'for example', then sub-activity can just be an example of a relationship between activities, and not the only one. Then, suppose that an activity tracks 'alternative-activities' to do if the user does not want to do the activity in question. Clearly, this relationship can thus potentially be cyclic, which directly contradicts the usage case of compositions in this module.
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/483#issuecomment-1324881693" expanded>

@Devanshshah1309 I see, that is probably the intent of the question then. Thanks!
</panel>

</panel>


<panel type="info" header="### 6. KART..KEYA `@kxrt` (39 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Question 17 in Lecture 13s discussion on software design**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/499" expanded>

<img width="216" alt="Screenshot 2022-11-24 at 8 48 34 PM" src="https://user-images.githubusercontent.com/73589885/203790131-66cc003b-069e-4472-9f56-ac1ba834697f.png">

Hi! I don't seem to be able to find the meaning of padding here in relation to software design, unless it's a reference to UI padding or the padding files from the PE.
</panel>

<panel  header="**2. :fas-info-circle: CodeCov alternatives for future batches**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/434" expanded>

CodeCov suffers from recurring issues with the GitHub Actions API, as identified in [this 4-day-old post](https://community.codecov.com/t/upload-issues-unable-to-locate-build-via-github-actions-api/3954) by a CodeCov staff member. This has been going on for months now. I'm sure quite a few of the other students have encountered this over the past few tP weeks, as I've heard over discussions. It was never debilitating to our processes but definitely a nuisance now and again.

Some issues from the [CodeCov action repo](https://github.com/codecov/codecov-action/issues):

- codecov/codecov-action#595
- codecov/codecov-action#598 (Main issue with consolidated reports, prompted the staff response.)
- codecov/codecov-action#680
- codecov/codecov-action#754
- codecov/codecov-action#776 

Would it be possible to provide students in future batches with possibly one other coverage tool so that they can work around this issue without decreasing the coverage requirement severity/disabling CodeCov?
</panel>

<panel  header="**3. :fas-info-circle: Clarification on v1.3s deadline**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/385" expanded>

Does v1.3 end at 10am or at 3pm today? 

If the latter, are we allowed to play around with UI/features up until 3pm and close v1.3 then? I'm aware the mock PE will be based on the jar released by 10am, however.
</panel>

<panel  header="**4. :fas-info-circle: PlantUML restrictions**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/366" expanded>

Given that we're required to follow the pre-defined style guide for PlantUML in `style.puml`, and the file [hides members](https://github.com/nus-cs2103-AY2223S1/tp/blob/77a32bf67b69274221eb3a6b3b1db2a16683ee46/docs/diagrams/style.puml#L74) from being visible in diagrams, would it be alright to have a `show members` line for class diagrams within the feature section to show methods and attributes?

The diagram looks like this if the above is possible:
![AppointmentClassDiagram](https://user-images.githubusercontent.com/73589885/197226731-676268ce-361d-4bf0-b045-d3119ae012f9.png)

`skinparam classAttributeIconSize 0` sets the visibility identifiers to +, -, ~, # instead of icons, for anyone else wondering.
</panel>

<panel  header="**5. :fas-info-circle: Clarification on hard deadline for week 10**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/356" expanded>

Since the lecture has been shifted to Saturday, does the deadline follow suit?
</panel>

<panel  header="**6. :fas-info-circle: Requesting for smoke testing help (Windows/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/229" expanded>

Hi! I’d appreciate some help getting this tested. My release is [here](https://github.com/kxrt/ip/releases/tag/A-Release) and my user guide can be found [here](https://kxrt.github.io/ip). 

Thank you!
</panel>

<panel  header="**7. :fas-info-circle: Considerations about code for date-time formatting**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/98" expanded>

Where do you think it would be better to store the code for parsing and converting the input date-time string to a specified output format? 

At the moment I have the code stored as a public static method in a [separate class](https://github.com/kxrt/ip/blob/master/src/main/java/duke/parser/DukeDateTimeFormatter.java) in my `duke.parser` package. I first thought this made sense since I'm breaking down the input string into a recognizable date-time format for output. Furthermore, since I employ the `LocalDate.parse()` and `LocalTime.parse()` methods in my code, the package name should fit the location.

However, my dilemma arises when I consider the method is only called by my `Deadline` and `Event` classes. Would it be better to turn this into a private command in the `DukeTask` for better encapsulation, as the only use case is for task strings to be shown to users? 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/36#issuecomment-1221230512" expanded>

Similar to @Thing1Thing2 above, I plan on making different input files based on possible user stories and a separate one for just collating as many erroneous inputs as I can find. I feel like the latter will be helpful in the long run to help with regression testing.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/34#issuecomment-1221230839" expanded>

@ReubenChay If you're using CLI, maybe [this](https://stackoverflow.com/questions/7438313/pushing-to-git-returning-error-code-403-fatal-http-request-failed) will be helpful. Alternatively, have you recently changed your GitHub username and are on MacOS? If so [this](https://stackoverflow.com/questions/47465644/github-remote-permission-denied) might be worth looking into.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/38#issuecomment-1221234801" expanded>

It stands for `Project Portfolio Page` - more info here: https://nus-cs2103-ay2223s1.github.io/website/admin/tp-deliverables.html#deliverable-project-portfolio-page-ppp
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/48#issuecomment-1222054272" expanded>

Maybe [this](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/fc) website might be helpful - focusing on the excerpt about `/lb&gt;n>` which is explained as

"Sets the number of lines for the internal line buffer to N. The default length of the line buffer is 100 lines. If the files that you are comparing have more than 100 consecutive differing lines, fc cancels the comparison."
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/105#issuecomment-1231079132" expanded>

I took a quick peek at your code for `Storage.java`. Looks like you're not creating a directory if the filepath for your storage file doesn't exist, and the "IOException e" print comes from there. The Level-7 task description specifies this needs to be handled. 

A possible reason for this could be the hardcoded path in `Duke.java` - it might be worth reconsidering the implementation here!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111#issuecomment-1232488144" expanded>

@janelleljt Hi! I think the "runtime components are missing" error occurs when you try running from `Main.java`, because I faced that error too. Could you try running from `Launcher.java` instead?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/98#issuecomment-1232490442" expanded>

@nehcuy @huzaifa1712 Thanks for the responses! I think I'll keep it as is then.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/119#issuecomment-1233675121" expanded>

Sounds like a Gradle lock error, going off of [here](https://stackoverflow.com/questions/68759744/cannot-lock-java-compile-cache-as-it-has-already-been-locked-by-this-process) and [here](https://stackoverflow.com/questions/62038122/cannot-lock-file-hash-cache-when-gradle-was-aborted). 

Could you try killing Gradle processes and restarting the IDE? If that doesn't work, perhaps try deleting the `.gradle` directory and rebuilding the project. 
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/118#issuecomment-1233689433" expanded>

Hi! I cloned your branch and executed the following steps:

- Switch to zulu-11's jdk 11.0.16 from [here](https://www.azul.com/downloads/).
- Update `fx:controller="MainWindow">` to `fx:controller="stashy.launcher.MainWindow">` in line 9 of MainWindow.xml.
- Add an images folder to the `resources` directory.

After this your application launches, but I seem to get garbled text. Running this on an Intel MacBook Pro 2020.
<img width="512" alt="Garbled text" src="https://user-images.githubusercontent.com/73589885/187824860-866a879c-fd2f-4b73-ba4a-dc1809e1b799.png">
Changing `javaFxVersion` to 14 in `build.gradle` seems to fix the garbled text, but I'm not sure if that's a hack or a proper solution to this issue.
<img width="512" alt="No garbled text" src="https://user-images.githubusercontent.com/73589885/187825389-b414d876-843c-4178-a0b0-9a3f8e538541.png">


</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/120#issuecomment-1233997196" expanded>

Hi, could you push the current contents of your branch to GitHub?
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/124#issuecomment-1234625846" expanded>

An error in line 9/10 is probably an issue with your controller's location (incorrect declaration). In your `MainWindow.fxml` file, replace `fx:controller="MainWindow"` with `fx:controller="duke.gui.MainWindow"` at the end of line 9/10. If this is already done, could you push your current work on the branch up to GitHub?
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/141#issuecomment-1236156886" expanded>

Hi! Constants require the `static` keyword too.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165#issuecomment-1242684073" expanded>

[This](https://community.atlassian.com/t5/Sourcetree-questions/How-do-I-use-a-personal-access-token-PAT/qaq-p/1263836) and [this](https://community.atlassian.com/t5/Sourcetree-questions/Adding-a-github-personal-access-token-to-sourcetree/qaq-p/1755393) post from the Atlassian forums mention placing the PAT in your password field when using basic auth. Perhaps try that?

Alternatively, if all else fails, you could manually add the file from the GitHub website and pull to refresh changes. 
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165#issuecomment-1242714519" expanded>

Glad to see it worked!

One way to get past the PAT expiry issue is using Git CLI and connecting over SSH.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165#issuecomment-1242773191" expanded>

> > Glad to see it worked!
> > One way to get past the PAT expiry issue is using Git CLI and connecting over SSH.
> 
> I see, but does that use OAuth? And does it give 'workflow' permissions too?

OAuth is a separate authentication system from SSH. SSH keys are generated on a different page from OAuth tokens in your Settings. And yep, it does give the `workflow` permission - I use it myself. I recommend reading up on [this](https://stackoverflow.com/questions/67077837/in-what-ways-is-an-ssh-key-different-from-tokens-for-git-authentication) post for a quick description of the differences in the two. PAT is probably safer since it's limited in comparison.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/229#issuecomment-1249530222" expanded>

> Yes it works fine in windows and the data file is created as well. 
> 
> ![Screenshot (404)](https://user-images.githubusercontent.com/92239144/190671310-f0fc7f32-e145-40a8-8480-625141d5ef7a.png)
> 
> 

Thanks mate!
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1263027459" expanded>

> See #309.

@RussellDash332 I tried following that on the main repo itself and it didn't fix the PR issue. PR in question is [here](https://github.com/AY2223S1-CS2103T-W16-3/tp/pull/9) but the same issue stands with all the current PRs from her.

It's also interesting to note that [her fork](https://github.com/PeiYee88/tp) shows an X for CI even though all checks are passing, as visible in the screenshot below. Super confused here.
<img width="612" alt="Screenshot 2022-09-30 at 10 20 28 AM" src="https://user-images.githubusercontent.com/73589885/193176352-9689cef6-ad29-4a41-a388-28d2431d7b92.png">

(Tagging @MarcusPeh for reference)
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1263172086" expanded>

> It is also 'unusual' that other team members have no PRs so far. Otherwise we could have at least figured out if the problem is specific to one team member or common to all members of the team.

@damithc I understand, we were erroneously waiting for the first PR to go through as confirmation before making each of our own. I have made a pull request with the same error being encountered here, though: https://github.com/AY2223S1-CS2103T-W16-3/tp/pull/16 
@seelengxd The PR above includes the front matter for Markdown too. 
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1263175854" expanded>

Just a slight update: Unchecking the option in the image below seems to fix the issue.

I believe this is because while setting up branch protection rules in the repository, I had checked this without being required to as additional protection outside of the scope of the instructions, yet didn't set up deployment testing leading to blocked merges. Unchecked it and we can merge now!

<img width="763" alt="Screenshot 2022-09-30 at 2 44 42 PM" src="https://user-images.githubusercontent.com/73589885/193207945-08a1ffa8-aeed-40a4-b52e-55e790a380d2.png">

</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/229#issuecomment-1263323289" expanded>

Thank you for the further testing @RezwanArefin01 @RussellDash332! It's a bit too late to fix that terminal warning, but I'll keep it in mind for the future. :)
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/323#issuecomment-1265182783" expanded>

Not sure if I've understood this perfectly here, but I believe if multiple paths result in the same exit route, then path coverage might differ from entry/exit coverage. 

```java

void doSomething() {
  ... // internal computation to obtain conditions
  if (condition1 && condition2) {
    route();
  } else if (!condition1 && !condition2) {
    route();
  } else {
    differentRoute();
  }
}
```
In the above example, two paths have the same exit route. However, this might change depending on how you structure your code.
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/335#issuecomment-1272447673" expanded>

Could you try manually [generating a coverage report](https://www.jetbrains.com/help/idea/generating-code-coverage-report.html) and see if that fixes the issue? 
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/356#issuecomment-1284438204" expanded>

Thanks prof!
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/367#issuecomment-1287829837" expanded>

I feel like you've answered your own question with:
```
assertion handles more of developer side errors while exceptions include users input errors
```

Your example should be correct. The `index` input being `null` would be a user-side error (missing index value in the CLI input) whereas `personToEdit` being null would be a developer-side error in obtaining the desired `Person` from the stored list.
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/370#issuecomment-1288053235" expanded>

Been trying to do that myself to no avail. It looks like the PlantUML [spec](https://plantuml.com/object-diagram) for object diagrams doesn't have that ability. `hide members` will hide any attributes but still leave a bounding box for the attributes field. 
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/385#issuecomment-1294445615" expanded>

Thanks prof! @damithc 
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/434#issuecomment-1308999140" expanded>

@parnikkapore Yep, similar thoughts here. My team would be sitting there re-running checks multiple times until CodeCov passed just because we didn't want to decrease its severity in the workflow.
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/464#issuecomment-1314955574" expanded>

The textbook definites navigability as:

> When two classes are linked by an association, it does not necessarily mean the two objects taking part in an instance of the association `knows about (i.e., has a reference to)` each other. The concept of which object in the association `knows about`) the other object is called navigability.

I think the key point here would be the highlighted phrase, "knows about". A does not directly know about C, and you cannot access C from A without the intermediary (B). If C was unidirectionally navigable from A, I believe there would be a separate arrowhead pointing from A to C as their association. 

Furthermore, the textbook defines the directions of navigability with the phrase "b has a reference to r". In your example, A does not directly hold a reference to C, which further makes it non-navigable.

I might be wrong here, but I believe composition/aggregation are transitive whereas navigability is not.
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/473#issuecomment-1316301712" expanded>

Sounds like it would fall under correctness as an inaccuracy.

<img width="593" alt="Screenshot 2022-11-16 at 12 10 21 PM" src="https://user-images.githubusercontent.com/73589885/202081525-d1ee3e32-44c7-4c3f-bf90-dcbf134dc368.png">

</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/476#issuecomment-1320783676" expanded>

> However, we do not know the problem domain in this case, and in that case, am I right to say that there can exist a particular problem domain in which exactly 5 elements are needed?

@zbz-lvlv That sounds true to me, however, that would be an OODM specific to that problem domain and not a general class diagram. 
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/499#issuecomment-1326431092" expanded>

![image](https://user-images.githubusercontent.com/73589885/203791946-dfc9adcc-df0b-4f7c-a2c1-27684b3624b9.png)

@damithc Hi prof, here's a screenshot with the timestamp visible.
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/499#issuecomment-1326550634" expanded>

Ah okay, thanks everyone! @damithc  @Devanshshah1309 @parth-io @nehcuy 
</panel>

</panel>


<panel type="info" header="### 7. TNG ..RREN `@DarrenCsAcc` (35 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: p1.06**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/498" expanded>

![image](https://user-images.githubusercontent.com/89026703/203781338-fdaf56b1-9f51-4319-af3b-53d7e98376a5.png)

Good day.

Can i check why option 1 is correct but option 4 is not selected? Thank you!
</panel>

<panel  header="**2. :fas-info-circle: Request for smoke test on Windows**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265" expanded>

Albeit my quality is not very good.
Hope someone can help me test.

I deleted my previous release.
Jar file is here -&gt; look for the latest release it should be version 0.2 and the file size is about 10.9mb
[](https://github.com/DarrenCsAcc/ip/releases/tag/A-Jar)

Here is my user guide.
https://github.com/DarrenCsAcc/ip/blob/master/docs/README.md

Thank you!


</panel>

<panel  header="**3. :fas-info-circle: Have a GUI that does not incorporate duke**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/258" expanded>

Hi Guys,

I have a GUI but unfortunately, it is not incorporated with the duke.
I was wondering if anyone has any advise on how to resolve this.
I followed the instructions for creating the GUI but i am not sure what went wrong
I will work on my other parts first.

https://github.com/DarrenCsAcc/ip

![image](https://user-images.githubusercontent.com/89026703/190922984-4803aa14-06c1-45f9-b8a3-f09305b69be6.png)

Thank you!
</panel>

<panel  header="**4. :fas-info-circle: Setting up my GUI**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/254" expanded>

![image](https://user-images.githubusercontent.com/89026703/190913518-6c3d6a23-b3be-45b6-bb17-e6e64ff6cc8f.png)

Hi,

 I updated my lines in the build.Gradle file but when i tied to import Javafx it does now work.
Was hopping someone could advise.

Thank you!

![image](https://user-images.githubusercontent.com/89026703/190913576-5163b056-9b3a-4878-a63f-de1e1ef0b853.png)

</panel>

<panel  header="**5. :fas-info-circle: Cannot build JAR filed**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/235" expanded>

![image](https://user-images.githubusercontent.com/89026703/190699196-ebfe99c4-60b8-45b4-95b5-919b41bdbc25.png)

Hi i am trying to build the JAR file from this video.Everything works until when i click build artifact it throws me this error.

https://se-education.org/guides/tutorials/jar.html

Was wondering if anyone knows how to solve this.

Thank you!
</panel>

<panel  header="**6. :fas-info-circle: Gradle help**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/226" expanded>

![image](https://user-images.githubusercontent.com/89026703/190649440-36bf2d2f-9455-478f-af6e-238ac26decb5.png)

Hi all,

I cannot seem to find the .idea folder and does step 2 means close the project and find the folder?
I am abit lost at this step.

Thank you!
</panel>

<panel  header="**7. :fas-info-circle: Gradle help**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/220" expanded>

Hi all,

Previously i forked my cs2103 project from the wrong directory(1 or 2 semesters ago)i cannot remember.Gradle 
I am trying to install the gradle now but i am not sure how to do it.

I am unable to perform:
Gradle support is provided as a separate branch (named add-gradle-support) in the Duke repo. Therefore, you can follow the scenario 2 in the guide below.

So i was wondering how should i go about it?

Can i do this?

https://www.jetbrains.com/help/idea/gradle.html#convert_project_to_gradle

under the 
"Convert a regular project into a Gradle project"

Thank you.

</panel>

<panel  header="**8. :fas-info-circle: Tips for doing a A-MoreOOP**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180" expanded>

Hi all,

I am currently quite behind for my IP so i am trying my best to catch up for now with the remaining time i have left. i am embarrassed to say i am currently at the stage of doing A-MoreOOP of week 3 and i am not sure how to properly organise my code for the parser part and UI part to incorporate to my main.I was wondering if anyone can give me some suggestions(example will be helpful maybe small snippets)

Thank you all for your time.
</panel>

<panel  header="**9. :fas-info-circle: Cannot seem to push my master branch with my tag**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163" expanded>

Hi all i was trying to push my commits into git and it gave me this error and i am not sure what it means.I cannot seem to push my master branch together with my tag.

I saw my current branch in the same repository but it says "This commit does not belong to any branch on this repository, and may belong to a fork outside of the repository."

Thank you!

![image](https://user-images.githubusercontent.com/89026703/189396924-1ef6cb01-da92-4c5b-a338-15ad996c88b0.png)

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163#issuecomment-1242198627" expanded>

![image](https://user-images.githubusercontent.com/89026703/189397916-13b4d106-4aae-45ca-8cb1-e4885c895100.png)
My tag is available but it shows this and my master branch is not updated for some reason.It feels like only the tag is being pushed.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163#issuecomment-1242607280" expanded>

Thanks @seelengxd and @lulucopter for the reply!

Sorry i am not super familiar with github and i am using sourcetree now.

This is what i see in sourcetree. @seelengxd 
![image](https://user-images.githubusercontent.com/89026703/189466867-7100dd6f-f3f4-42f9-a145-763e4ba9d7b0.png)

@lulucopter 
When i git-clone it will be my whole repository right?I will just do what i first did when i set up the ip?

Thank you.



</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163#issuecomment-1242608591" expanded>

I am trying to merge all the branch now. I did not do some properly so i think i have multiple merge conflict :( Will update you guys on how it goes
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163#issuecomment-1242609720" expanded>

Hi all, 

I tried merging the branch now i seem able to do it.But i don't know if i am doing it correctly..
Was wondering is there some way to check if i am doing it the right way :(
This is my current Sourcetree

![image](https://user-images.githubusercontent.com/89026703/189467348-7a910b0c-0300-441d-8a73-6a7cf744c086.png)



Thank you!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163#issuecomment-1242688151" expanded>

Thank everyone for your help and time reading, for now, i think it is fine I will let you guys know if there are any more issues.
Once again thank you!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180#issuecomment-1245487453" expanded>

Thank you all i will work on it!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180#issuecomment-1249030131" expanded>

Hi all I manage to get it done. Although it's not as good as everyone's but thank you all for your help!
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/220#issuecomment-1249237772" expanded>

Hi i ran into this error and have difficulty proceeding.I added this info into the gradle file

plugins {
    id 'java'
}

group 'org.example'
version '1.0-SNAPSHOT'

repositories {
    mavenCentral()
}
sourceSets {
    main {
        java {
            srcDirs = ['src']
        }
    }
}
dependencies {
    compile 'junit:junit:4.12'
}


![image](https://user-images.githubusercontent.com/89026703/190626725-9e73f89e-1cbb-4bd3-8b9a-158d35251526.png)

</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/220#issuecomment-1249254123" expanded>

@damithc 
Hi prof unfortunately i proceeded  with this -&gt; https://www.jetbrains.com/help/idea/gradle.html#convert_project_to_gradle
i cannot run my files for now at all.

![image](https://user-images.githubusercontent.com/89026703/190630049-27176ac8-76dd-4e44-965b-0ff8467d1bfb.png)


If i use -&gt; you need to pull the add-gradle-support branch from the upstream repo and merge it to your master branch.
Will it fix the problem i just created?

Thank you
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/220#issuecomment-1249286897" expanded>

@damithc 

Thanks prof.

This actually worked. Luckily i did not push or commit my problematic files.I will not try to be adventurous again. :(



</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/220#issuecomment-1249306108" expanded>

![image](https://user-images.githubusercontent.com/89026703/190638901-b632b0f7-dbda-4113-a273-912b177c5c14.png)

Hi all,

So what i am trying to do now is i firstly added the branch add-gradle-support from the currrent upstream repo to my own branch.Then i am trying to pull it to my own local before merging it with my master.Somehow i am running into this error.Was wondering if anyone can help.

Edit *
I found i actually had the original gradle branch now i am trying to merge it


Thank you.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/226#issuecomment-1249521442" expanded>

@damithc 
Thank you finally got it sorted out 

![image](https://user-images.githubusercontent.com/89026703/190678344-e737c7a7-6588-4df1-bb24-c745be70a4b6.png)

</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/235#issuecomment-1249623989" expanded>

I tried restarting my intelliJ IDE for now hopping it works
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/235#issuecomment-1249625819" expanded>

@RussellDash332 
For some reason when I restart my IDE somehow it works.
Thanks for the help though appreciate it!
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/254#issuecomment-1250330893" expanded>

Edit*

Ok, i like clicked some little elephant button and it works.

I needed to *initialise* it
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/258#issuecomment-1250469969" expanded>

@seelengxd 
Hi Thanks for the reply.
Can i just check am i suppose to rewrite my parser method?
Do i have to change my main method?
Is there a bit of an example ?
I am abit lost :(

Thank you!
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/258#issuecomment-1250559051" expanded>

Basically i talked to one of my group mate.
My code uses a while loop and therefore it does not fit into the entire logic of the GUI since i am not returning a string.
As such.... i need to do a major overhaul...(if its even possible)......
I am really finished....

Thanks for everyone's help still.
I just dont know...
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/258#issuecomment-1250698691" expanded>

Ok thank you i will try it now prof
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/258#issuecomment-1250725077" expanded>

![image](https://user-images.githubusercontent.com/89026703/190979133-d0c22403-6ebb-4d3b-8c34-e66dec58597a.png)

Finally managed to fix one command.Its a small step but i have to continue working towards to end goal of pivoting out of this while loop.
At least there is a glimmer of hope
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/258#issuecomment-1250911530" expanded>

I managed to rectify the bulk of it to get it to work.
The quality is nowhere near as good as most of my peers but at least I got about 90% of it to work.
I am almost done with the rest of the task hopefully I can get it done by tonight. 
I will request the smoke test in another thread.

Thanks you all for your help @damithc @seelengxd @My tp team
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251056551" expanded>

thank you for your help! 
@rui-han-crh 

and thanks for helping me check
@RussellDash332 

Here is the changes proposed by @rui-han-crh
[Ammended file ](https://github.com/DarrenCsAcc/ip/releases/tag/A-Jar)

</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251104224" expanded>

@rui-han-crh 
@RussellDash332 
[I fixed the delete here is there newest release](https://github.com/DarrenCsAcc/ip/releases/tag/A-Jar-v0.4)
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251105603" expanded>

@rui-han-crh 
Thanks for finding a bug that needs fixing .i will work on it
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251144564" expanded>

@rui-han-crh @RussellDash332 
Thanks guys for putting in so much effort in helping me i will work on it and get back to you guys.
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1279775464" expanded>

@nus-se-bot 
Sorry did not notice. Thank you for closing it has been resolved.
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/498#issuecomment-1326538164" expanded>

Thank you! If possible can i check why is option 2 correct since the diagram does not show an association between table and the door? I am guessing it can be 0 and 0 since the option is  * at both ends.
</panel>

</panel>


<panel type="info" header="### 8. CLAR..N DA `@clarence-chew` (32 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: PE - Allowed Software (Microsoft Paint)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/433" expanded>

I use Microsoft Paint to handle my screenshots, is it allowed in PE Phase 1 - part I and PE Phase 1 - part II?

If so, does this extend to other image-editing applications?
</panel>

<panel  header="**2. :fas-info-circle: CATcher did not report all the issues to the team repo**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/388" expanded>

After the CATcher issues were loaded into our team repo, it seems not all issues were added, is this intended behaviour (perhaps to reduce the load on GitHub by having to duplicate too many issues)?
</panel>

<panel  header="**3. :fas-info-circle: Test Cases video has question but no Q+ indicator**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/343" expanded>

The [W10.4] Test Cases: Equivalence Partitioning -&gt; What section of the notes has a video with a question but it doesn't have the Q+ indicator. This is to check if this is intended.
</panel>

<panel  header="**4. :fas-info-circle: Line ending issue for CI \r\n**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/336" expanded>

I'm using Windows and this is part of the ubuntu CI, and I'm not sure how to resolve this error message. There's some issue with line endings in the files, that I can tell.

Abridged error message:
```
Run ./run-checks.sh
ERROR:../src/main/java/foodwhere/storage/JsonAdaptedReview.java:1: prohibited \r\n line ending, use \n instead.
```

Full error message is here, essentially the same thing repeated across multiple files:
https://github.com/AY2223S1-CS2103-W14-2/tp/actions/runs/3213682841/jobs/5253716347

What processes can I try, to deal with the issue?
</panel>

<panel  header="**5. :fas-info-circle: Class Diagram Association: Binary Tree Node**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/331" expanded>

Context: Binary Tree Node
```
public Node {
    Node parent;
    Node leftChild; // If leftChild not null, guarantee: this.leftChild.parent = this
    Node rightChild; // If rightChild not null, guarantee: this.rightChild.parent = this

    // ...
}
```
How would one draw the association in the class diagram for this?
</panel>

<panel  header="**6. :fas-info-circle: Automated smoke test bugs in Linux and Mac involving QuantumRenderer**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/270" expanded>

Hello, I'll like to get some help with smoke tests. Here's the [JAR file](https://github.com/clarence-chew/ip/releases/tag/A-Release) and here's the [User Guide](https://clarence-chew.github.io/ip/). I got automated smoke tests with these issues and I'm not sure what causes it and how to prevent it.

On Linux, using Java 11, for the Anthea.jar uploaded on 09-15-2022 (MM-DD-YYYY) at 08:54:45:
```
Graphics Device initialization failed for : es2, sw Error initializing QuantumRenderer: no suitable pipeline found java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280) at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222) at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at java.base/java.lang.Thread.run(Thread.java:829) Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94) at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124) ... 1 more Exception in thread "main" java.lang.RuntimeException: No toolkit found at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at java.base/java.lang.Thread.run(Thread.java:829)
```

On Mac, using Java 11, for the Anthea.jar uploaded on 09-15-2022 (MM-DD-YYYY) at 08:54:45:
```
Graphics Device initialization failed for : es2, sw Error initializing QuantumRenderer: no suitable pipeline found java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280) at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222) at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at java.base/java.lang.Thread.run(Thread.java:834) Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94) at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124) ... 1 more Exception in thread "main" java.lang.RuntimeException: No toolkit found at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at java.base/java.lang.Thread.run(Thread.java:834)
```
</panel>

<panel  header="**7. :fas-info-circle: Help with smoke tests - *nix and Mac appreciated**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/192" expanded>

Hello, I'll like to get some help with smoke tests. Here's the [JAR file](https://github.com/clarence-chew/ip/releases/tag/A-Release) and here's the [User Guide](https://clarence-chew.github.io/ip/).

Console mode is highly recommended for serious usage - run `java -jar ./Anthea.jar console` or the equivalent to run it in the console.
</panel>

<panel  header="**8. :fas-info-circle: Cannot run with Gradle after adding GUI (but can still run individual main functions and build .jar)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/143" expanded>

**Setup:**
IntelliJ IDEA 2022.2 (Community Edition) - corretto-11.0.16 - Windows 10

**What seems to work:**
- individual main functions by right clicking on class, then clicking "Run ClassName.main()"
- Gradle "build" makes a .jar

**What doesn't work:**
Gradle "run" results in the below-mentioned error messages.

**Suspected issue:**
Incorrect setup of certain libraries and Gradle - also appreciate if it can be checked by seeing if the project can be built.

**Short error message:**
```
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
```
**Long error message:**
```
> Task :run FAILED
Loading library prism_d3d from resource failed: java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11\prism_d3d.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11\prism_d3d.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
	at java.base/java.lang.ClassLoader$NativeLibrary.load0(Native Method)
	at java.base/java.lang.ClassLoader$NativeLibrary.load(ClassLoader.java:2445)
	at java.base/java.lang.ClassLoader$NativeLibrary.loadLibrary(ClassLoader.java:2501)
	at java.base/java.lang.ClassLoader.loadLibrary0(ClassLoader.java:2700)
	at java.base/java.lang.ClassLoader.loadLibrary(ClassLoader.java:2630)
	at java.base/java.lang.Runtime.load0(Runtime.java:768)
	at java.base/java.lang.System.load(System.java:1837)
	at com.sun.glass.utils.NativeLibLoader.installLibraryFromResource(NativeLibLoader.java:205)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryFromResource(NativeLibLoader.java:185)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryInternal(NativeLibLoader.java:157)
	at com.sun.glass.utils.NativeLibLoader.loadLibrary(NativeLibLoader.java:52)
	at com.sun.prism.d3d.D3DPipeline.lambda$static$0(D3DPipeline.java:48)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.prism.d3d.D3DPipeline.<clinit>(D3DPipeline.java:44)
	at java.base/java.lang.Class.forName0(Native Method)
	at java.base/java.lang.Class.forName(Class.java:315)
	at com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	at java.base/java.lang.Thread.run(Thread.java:829)
Loading library prism_sw from resource failed: java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11\prism_sw.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11\prism_sw.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
	at java.base/java.lang.ClassLoader$NativeLibrary.load0(Native Method)
	at java.base/java.lang.ClassLoader$NativeLibrary.load(ClassLoader.java:2445)
	at java.base/java.lang.ClassLoader$NativeLibrary.loadLibrary(ClassLoader.java:2501)
	at java.base/java.lang.ClassLoader.loadLibrary0(ClassLoader.java:2700)
	at java.base/java.lang.ClassLoader.loadLibrary(ClassLoader.java:2630)
	at java.base/java.lang.Runtime.load0(Runtime.java:768)
	at java.base/java.lang.System.load(System.java:1837)
	at com.sun.glass.utils.NativeLibLoader.installLibraryFromResource(NativeLibLoader.java:205)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryFromResource(NativeLibLoader.java:185)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryInternal(NativeLibLoader.java:157)
	at com.sun.glass.utils.NativeLibLoader.loadLibrary(NativeLibLoader.java:52)
	at com.sun.prism.sw.SWPipeline.lambda$static$0(SWPipeline.java:42)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.prism.sw.SWPipeline.<clinit>(SWPipeline.java:41)
	at java.base/java.lang.Class.forName0(Native Method)
	at java.base/java.lang.Class.forName(Class.java:315)
	at com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	at java.base/java.lang.Thread.run(Thread.java:829)
Graphics Device initialization failed for :  d3d, sw
Error initializing QuantumRenderer: no suitable pipeline found
java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
	at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280)
	at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222)
	at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	... 1 more
Exception in thread "main" java.lang.RuntimeException: No toolkit found
	at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found

	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
```

**Version of code that has the following symptoms:**
https://github.com/clarence-chew/ip/tree/da207d2fbb3716ed2bb07b264361504b5f5e1449
</panel>

<panel  header="**9. :fas-info-circle: 💡 Why get rid of console-style output when you add your GUI?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/129" expanded>

I'm trying this out, since I have useful regression tests in my text-ui-test that I want to keep, and text-ui-test is a somewhat decent integration test.

Pros: Alternative route of testing - better chance to catch bugs.
Cons: Slightly more effort.

Step 1: Change `Ui` class into an interface with implementations `ConsoleUi` (prints to console) and `GraphicUi` (prints to GUI).
Step 2: Add some command line arguments in your program for console testing, i.e.
```java
public static void main(String[] args) {
    // allow for console tests to run
    if (args.length >= 1 && args[0].equals("console-test")) {
        ui = new ConsoleUi();
    } else {
        ui = new GraphicUi();
    }
    // more code ...
```
Step 3: Add the command line argument into your runtest.bat (example)
```bat
java -classpath ..\bin duke.Duke console-test < input.txt > ACTUAL.TXT
```
</panel>

<panel  header="**10. :fas-info-circle: Clarification on Boolean variables/methods should ... sound like booleans wrt Predicate**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/76" expanded>

Consider a Predicate<T>. Does that also need to sound like a Boolean as per our coding standard?

Example (No):
```java
private Predicate<String> check;
```

Example (Yes):
```java
private Predicate<String> isThisCommand;
```
</panel>

<panel  header="**11. :fas-info-circle: 💡 Running tests while doing A-Packages - javac command in runtest.bat needs to be changed**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/42" expanded>

I tried moving my code into packages and the runtest.bat regression tests seem to fail. Running my code in IntelliJ looks pretty fine, so my initial guess is that the runtest.bat can't deal with packages.

I had all my classes in the packages `duke` and `duke.task`. As such, what I did was to change originally:

`javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\*.java`

to:
`javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\duke\*.java ..\src\main\java\duke\task\*.java`

Windows Powershell (if you use Windows, you might get an error like this):
```
PS C:\Users\[REMOVED]\nus-cs2103-AY2223S1-ip\text-ui-test> ./runtest.bat
Exception in thread "main" java.nio.file.InvalidPathException: Illegal char <*> at index 17: ..\src\main\java\*.java
        at java.base/sun.nio.fs.WindowsPathParser.normalize(WindowsPathParser.java:182)
        at java.base/sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:153)
        at java.base/sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:77)
        at java.base/sun.nio.fs.WindowsPath.parse(WindowsPath.java:92)
        at java.base/sun.nio.fs.WindowsFileSystem.getPath(WindowsFileSystem.java:229)
        at java.base/java.nio.file.Path.of(Path.java:147)
        at java.base/java.nio.file.Paths.get(Paths.java:69)
        at jdk.compiler/com.sun.tools.javac.main.Option$37.process(Option.java:693)
        at jdk.compiler/com.sun.tools.javac.main.Option.handleOption(Option.java:1088)
        at jdk.compiler/com.sun.tools.javac.main.Arguments.doProcessArgs(Arguments.java:381)
        at jdk.compiler/com.sun.tools.javac.main.Arguments.processArgs(Arguments.java:347)
        at jdk.compiler/com.sun.tools.javac.main.Arguments.init(Arguments.java:193)
        at jdk.compiler/com.sun.tools.javac.main.Main.compile(Main.java:229)
        at jdk.compiler/com.sun.tools.javac.main.Main.compile(Main.java:170)
        at jdk.compiler/com.sun.tools.javac.Main.compile(Main.java:57)
        at jdk.compiler/com.sun.tools.javac.Main.main(Main.java:43)
********** BUILD FAILURE **********
```
</panel>

<panel  header="**12. :fas-info-circle: iP Level-7: How to run tests (A-TextUiTesting) involving file input**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/36" expanded>

This does not seem very easily testable using the method presented in A-TextUiTesting. Here are some methods I have with their pros and cons.

|Method|Pros|Cons|
|-|-|-|
|Delete the saved file manually|No extra benefits|Cannot test existing file|
|Delete and set up files manually|Comprehensive tests|Tedious|
|Have the testing script delete the file|Relatively easy|Cannot test existing file|
|Have the testing script delete and set up the file|Comprehensive tests|Need to make the testing script, need to make multiple testcases in testing script|
|Add new commands which allow loading and saving to file|Can construct tests using these features, no need to complicate testing script|More things to implement|

Any other possibilities that I haven't considered?
</panel>

<panel  header="**13. :fas-info-circle: Choosing testcases for regression testing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/32" expanded>

Which testcases are best chosen for regression testing? Share tips on being comprehensive!

1. Always test empty string
2. Familiar with another language? Test input with that language
3. Test input with a lot more spaces than normal
4. Try to test every code path you have
5. Do you assume something is a number (or some other format)? Try out a very big number, negative number, decimal, or even text.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/36#issuecomment-1221157692" expanded>

> I did it this way:
> 
> [...]
> 
> Perhaps this corresponds to the last row of the table of possible testing methods you showed.

That's a useful way of implementing it, though I would think that's quite close to the 4th (1-indexed) method. The 5th method I had in mind is reimplementing the code with extra features (perhaps adding commands "save [path]" "load [path]") such that allow for creating and removing save states.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/44#issuecomment-1221461521" expanded>

The style guide references the [Google Java style guide](https://google.github.io/styleguide/javaguide.html).

In particular, the [Exception: Overrides](https://google.github.io/styleguide/javaguide.html#s7.3.2-javadoc-exception-overrides) section says "Javadoc is not always present on a method that overrides a supertype method.". It appears to conflict with "Write descriptive header comments for all public classes/methods." in our [style guide](https://se-education.org/guides/conventions/java/index.html). Since the supertype Javadoc can be consulted, I don't think we need to write it.

That aside, there may be a need to write it if the method is different from the supertype method.

[StackOverflow](https://stackoverflow.com/questions/3109950/codestyle-put-javadoc-before-or-after-annotation) here (as @sltsheryl just mentioned)
Summary: Java annotations is part of the code so the Javadoc is placed before the annotations.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/67#issuecomment-1229030909" expanded>

Another possibility is storing it in a text file - A reason for that is so that you can see how it looks like without the \\ escape characters.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/129#issuecomment-1235630939" expanded>

Actually - Step 2 can also be changed - having one entry point for ConsoleUi and another for GraphicUi also works out.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/129#issuecomment-1236133542" expanded>

So far I managed to try it - though I'm still struggling on running it with Gradle. Currently it runs in the IDE and I can build the jar file to run, but I cannot run it with Gradle for some reason.
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/143#issuecomment-1236266314" expanded>

Running that in command prompt gives me
```
Microsoft Windows [Version 10.0.19044.1889]
(c) Microsoft Corporation. All rights reserved.

C:\Users\clare>java --version
openjdk 11.0.16.1 2022-08-12 LTS
OpenJDK Runtime Environment Microsoft-40648 (build 11.0.16.1+1-LTS)
OpenJDK 64-Bit Server VM Microsoft-40648 (build 11.0.16.1+1-LTS, mixed mode)
```
In WSL it gives me
```
default@LAPTOP-HF9OJDAE:/mnt/c/Windows/system32$ java --version
openjdk 11.0.16 2022-07-19
OpenJDK Runtime Environment (build 11.0.16+8-post-Ubuntu-0ubuntu120.04)
OpenJDK 64-Bit Server VM (build 11.0.16+8-post-Ubuntu-0ubuntu120.04, mixed mode, sharing)
```
 
New error message after doing the edits (a quick glance seems to be some path changes):
```
> Task :run FAILED
Loading library prism_d3d from resource failed: java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11.0.2\prism_d3d.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11.0.2\prism_d3d.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
	at java.base/java.lang.ClassLoader$NativeLibrary.load0(Native Method)
	at java.base/java.lang.ClassLoader$NativeLibrary.load(ClassLoader.java:2445)
	at java.base/java.lang.ClassLoader$NativeLibrary.loadLibrary(ClassLoader.java:2501)
	at java.base/java.lang.ClassLoader.loadLibrary0(ClassLoader.java:2700)
	at java.base/java.lang.ClassLoader.loadLibrary(ClassLoader.java:2630)
	at java.base/java.lang.Runtime.load0(Runtime.java:768)
	at java.base/java.lang.System.load(System.java:1837)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.installLibraryFromResource(NativeLibLoader.java:205)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.loadLibraryFromResource(NativeLibLoader.java:185)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.loadLibraryInternal(NativeLibLoader.java:157)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.loadLibrary(NativeLibLoader.java:52)
	at javafx.graphics/com.sun.prism.d3d.D3DPipeline.lambda$static$0(D3DPipeline.java:48)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at javafx.graphics/com.sun.prism.d3d.D3DPipeline.<clinit>(D3DPipeline.java:44)
	at java.base/java.lang.Class.forName0(Native Method)
	at java.base/java.lang.Class.forName(Class.java:315)
	at javafx.graphics/com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	at java.base/java.lang.Thread.run(Thread.java:829)
Loading library prism_sw from resource failed: java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11.0.2\prism_sw.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
java.lang.UnsatisfiedLinkError: C:\Users\clare\.openjfx\cache\11.0.2\prism_sw.dll: Can't load AMD 64-bit .dll on a IA 32-bit platform
	at java.base/java.lang.ClassLoader$NativeLibrary.load0(Native Method)
	at java.base/java.lang.ClassLoader$NativeLibrary.load(ClassLoader.java:2445)
	at java.base/java.lang.ClassLoader$NativeLibrary.loadLibrary(ClassLoader.java:2501)
	at java.base/java.lang.ClassLoader.loadLibrary0(ClassLoader.java:2700)
	at java.base/java.lang.ClassLoader.loadLibrary(ClassLoader.java:2630)
	at java.base/java.lang.Runtime.load0(Runtime.java:768)
	at java.base/java.lang.System.load(System.java:1837)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.installLibraryFromResource(NativeLibLoader.java:205)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.loadLibraryFromResource(NativeLibLoader.java:185)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.loadLibraryInternal(NativeLibLoader.java:157)
	at javafx.graphics/com.sun.glass.utils.NativeLibLoader.loadLibrary(NativeLibLoader.java:52)
	at javafx.graphics/com.sun.prism.sw.SWPipeline.lambda$static$0(SWPipeline.java:42)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at javafx.graphics/com.sun.prism.sw.SWPipeline.<clinit>(SWPipeline.java:41)
	at java.base/java.lang.Class.forName0(Native Method)
	at java.base/java.lang.Class.forName(Class.java:315)
	at javafx.graphics/com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	at java.base/java.lang.Thread.run(Thread.java:829)
Graphics Device initialization failed for :  d3d, sw
Error initializing QuantumRenderer: no suitable pipeline found
java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280)
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222)
	at javafx.graphics/com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found

	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94)
	at javafx.graphics/com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	... 1 more
Exception in thread "main" java.lang.RuntimeException: No toolkit found
	at javafx.graphics/com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
```
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/143#issuecomment-1236279261" expanded>

@Polygonalr That was pretty useful. I tried redownloading and setting the JDK under File > Project Structure to C:\Program Files\Amazon Corretto\jdk11.0.16_9 on my end and I think it was resolved. 

Checks:
Gradle run seems to work.
Gradle build seems to work.
Running main(...) seems to work.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/129#issuecomment-1242067749" expanded>

This thing just saved me - I realised I forgot to run the text-ui-test regression test after committing and it helped me find a bug which I patched in the next commit.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/36#issuecomment-1242746030" expanded>

As an update on this, I also have a .sh version of this I made for A-CI, if you are using something like that.

https://github.com/clarence-chew/ip/blob/master/text-ui-test/runtest.sh
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/192#issuecomment-1248037361" expanded>

Thanks for the help!
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/270#issuecomment-1252324489" expanded>

I'm going to try out the things suggested here https://github.com/nus-cs2103-AY2223S1/forum/issues/213 and release a new version.
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/270#issuecomment-1252338838" expanded>

Released a new version on https://github.com/clarence-chew/ip/releases/tag/v0.1.1 - removed the javafx block from build.gradle file.
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/272#issuecomment-1252382013" expanded>

Try #213, removing the javafx block from build.gradle?
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/323#issuecomment-1264592342" expanded>

Path coverage seems to cover entry/exit coverage. I think one distinction can happen in multithreaded operations where the order of operations may not be determined, in which there can be way more paths based on the ordering of concurrent operations, however, all of them use the same entry/exit.
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/336#issuecomment-1272557780" expanded>

Thanks, clicking the CRLF button to change it helped.
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/343#issuecomment-1279752784" expanded>

Thanks for clarifying!
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/361#issuecomment-1286316888" expanded>

One reason to prefer an immutable person is that it lessens the memory impact of the implementation of the undo command using a VersionedAddressBook. In this case, the same Person objects can be used across multiple VersionedAddressBooks.
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/388#issuecomment-1295639905" expanded>

I just read the email announcement - apparently this is an intended feature. However it would definitely be appreciated if one issue from each tester was given first instead of in strict chronological order since we can navigate to their repository to see all the other issues.
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/331#issuecomment-1295911204" expanded>

> There are two bidirectional association here:

Would that have the issue that `parent` is repeated twice?
</panel>

</panel>


<panel type="info" header="### 9. PHOO.. HAN `@xhphoong` (27 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Venue for CS2103 Final Exam**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/489" expanded>

May I ask where is the Final Exam tmr taking place at? Thank you!
</panel>

<panel  header="**2. :fas-info-circle: Enquiry about v1.4**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/381" expanded>

Hi , may I ask if 

1. I not able to add a test for the new feature, can I add the test for the new feature at v1.4? and if I find bug when writing the test code, can I fix the new feature? 
2. Can I create new class such as a manager class to manage something to reduce code duplication in different classes in v1.4 or like create new method to shorten another method length in v1.4? 

Thank you!
</panel>

<panel  header="**3. :fas-info-circle: Question about the tP workflow**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/337" expanded>

Hi, I want to check with you about the workflow. So, I have open a pull request on my team then when I am doing halfway, my teammates merge new code into the team master then when I push another commit to my branch, in the pull request it shows up sth like this: 
![Screenshot (425)](https://user-images.githubusercontent.com/92239144/194788764-eeeb0569-f290-4209-8e44-90d419da00f3.png)

Then, I try to resolve the conflicts and it merges the master branch into my own branch:
![Screenshot (426)](https://user-images.githubusercontent.com/92239144/194788827-bbc68cb3-e568-4f99-9cad-0e61f71babfb.png)

I thought I am doing it wrongly then I reopen a branch doing the same commit of my previous branch and push it again and it still shows up the need to resolve conflict issue and when resolving, it only have the option for merging master into my branch.

So I want to ask whether is it okay to **merge master into my branch and continue to add other stuff into that branch** or I have to **pull the new codes into the master and create a new branch and update my code accordingly** or is there any other way to resolve this? 

Thank you!
</panel>

<panel  header="**4. :fas-info-circle: Request for Smoke Test  (MacOS)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/282" expanded>

Hi, would appreciate if anyone can help with the smoke test for my new jar? 
Here is my [jar](https://github.com/xhphoong/ip/releases/tag/A-Release) and my [user guide](https://xhphoong.github.io/ip/). 
(Maybe can test the function ,type something random, change the format of stored data file and reopen and see how it reacts and post a ss here)
Thank You so Much! 



</panel>

<panel  header="**5. :fas-info-circle: Request smoke test for Linux/ MacOS system**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234" expanded>

Hi , would appreciate if anyone can help me test my new version of [jar](https://github.com/xhphoong/ip/releases/tag/A-Release) for linux, MacOS, windows(just in case) ? and here is my [user guide](https://xhphoong.github.io/ip/). Thanks a lot !!!

</panel>

<panel  header="**6. :fas-info-circle: Request for help to smoke test (linux,MacOS)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217" expanded>

Hi, would appreciate if anyone can help with the smoke test in linux, MacOS and Windows ? 
This is my [jar file](https://github.com/xhphoong/ip/releases/tag/v.03-A-Jar) and [user guide](https://xhphoong.github.io/ip/).
Thank you so much !!
</panel>

<panel  header="**7. :fas-info-circle: Launcher : Cannot lock Java compile cache error**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/119" expanded>

When trying to run the launcher,  this error has popped up : 
**Cannot lock Java compile cache (C:  ... \iP\.gradle\6.2\javaCompile) as it has already been locked by this process** 
and I not sure how to resolve it.  Do anyone know how to resolve it? 
Thank you!  

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/119#issuecomment-1234282885" expanded>

Thank you, it works now! 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249035676" expanded>

@parth-io Noted, thank you! 


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249041453" expanded>

@parth-io and may I ask one more thing? Is there a text difference in the error messsage (eg when randomly type sth) and the normal message? Thank you! 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249047083" expanded>

@parth-io Thank you! 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249147357" expanded>

Noted, thanks @RezwanArefin01 @parth-io @carriezhengjr. I will try fix the font and image issue. 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249153611" expanded>

I tested using windows. Everything is fine and the data folder is created. 
![Screenshot (402)](https://user-images.githubusercontent.com/92239144/190607796-bdbde77b-543a-4db3-9253-69d746d286a0.png)
![Screenshot (403)](https://user-images.githubusercontent.com/92239144/190607830-7e724c84-dfce-497a-a781-7f37c4f05835.png)

</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249257590" expanded>

Hi, this is the new [jar file](https://github.com/xhphoong/ip/releases/tag/v.04-A-Jar), would appreciate if someone could help to check it on linux and macos again to see whether this time the font type and image display out correctly? @parth-io @RezwanArefin01 @carriezhengjr  Thankss 
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249477043" expanded>

@carriezhengjr Thanks,  I reposting a new issue for the new jar file.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/229#issuecomment-1249485053" expanded>

Yes it works fine in windows and the data file is created as well. 
![Screenshot (404)](https://user-images.githubusercontent.com/92239144/190671310-f0fc7f32-e145-40a8-8480-625141d5ef7a.png)

</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1249535070" expanded>

I updated the link, can try see is it there? Thanks

</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1249694372" expanded>

@cheeheng Thanks for catching the exception. I have update a new version of it [jar](https://github.com/xhphoong/ip/releases/tag/A-Release). Can help to check again? especially because there is supposed to be other words in the ",,," section. I tried in my computer and it shows it up so I also not sure.... Thank you!!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1249757946" expanded>

@RezwanArefin01  noted, thank you! and for the data loading, I think its because i use " : " to parse instead of "|" and after that I read it without checking whether the string array produced, thus causing array out of bounds. This is my updated [jar](https://github.com/xhphoong/ip/releases/tag/A-Release), maybe can recheck? Thank you!
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1250848948" expanded>

@RezwanArefin01 @yeehaoo @johnbenedictyan Hi, I think I fix the problem alrdy, but can help me check again whether it works in linux /macs ? Thank you! The jar file is [here](https://github.com/xhphoong/ip/releases/tag/A-Release) and the [user guide](https://xhphoong.github.io/ip/). Thank you! 
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/282#issuecomment-1253184766" expanded>

@Yongbeom-Kim @RussellDash332 Thanks for testing! : )
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/282#issuecomment-1253816301" expanded>

Thank you so much ! @yuehernkang 
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/301#issuecomment-1256154266" expanded>

@damithc Hi Prof, I wan to clarify about this: does our latest version need to have A-Release tag or it can have other tag name? Because my **latest version (to be mark)** is the one with **v0.2 A-Release tag** not A-Release tag?  Thank you
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/301#issuecomment-1256178091" expanded>

> @xhphoong The two things are independent. We take the latest release for grading. The A-Release tag (like other required tags) is simply an indication that you've done that increment. It doesn't need to be attached to the latest release.

Thank you for the clarification! 
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/337#issuecomment-1273234541" expanded>

Thank you!  @damithc @Puakii @Aishwarya-Hariharan-Iyer 

</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/381#issuecomment-1293505551" expanded>

Thank you! @damithc 
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/489#issuecomment-1325892830" expanded>

Thank you ! 
</panel>

</panel>


<panel type="info" header="### 10. HUAN..CHEN `@nehcuy` (26 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: CATcher Website checkbox preview issues**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/363" expanded>

I'm not sure if this is considered a bug, but there are some slight differences in using the `Preview` tab when creating a new issue in the CATcher website, as compared to using Github. The problem is with the **display of checkboxes**. I have attached a picture below to illustrate the problem.

This is from the CATcher Website. 
![image](https://user-images.githubusercontent.com/94856691/197156681-2dd017af-4de2-4a77-b66d-0be8d86169e7.png)

and this is from Github.
![image](https://user-images.githubusercontent.com/94856691/197156925-7185f049-61b8-4eb8-ba61-4aede04d46fe.png)

As you can see, there are extra appearances of the list bullet points. In fact, the bullet points are also present in the issue after being created on the CATcher Website, when it is not supposed to show up on Github. This might be due to checkboxes using the format "- [ ]" in GFMD, and therefore the first instance of the hyphen gets detected as an unordered list instead? This is a small issue, but I think it's worth mentioning if CATcher is meant for long-term future usage for this module :>
</panel>

<panel  header="**2. :fas-info-circle: Unable to retake Week 10 in-video quizzes**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/342" expanded>

Same issue as previous weeks, in-video quizzes unable to be retaken. Instances of quizzes occur at:
- [W10.1] Design Patterns
- [W10.2] Defensive Programming
- [W10.4b] Quality Assurance → Test Case Design → Equivalence Partitions → Basic
- [W10.5b] Quality Assurance → Test Case Design → Boundary Value Analysis → How
</panel>

<panel  header="**3. :fas-info-circle: Unable to retake Week 9 in-video quizzes**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/332" expanded>

Similar to all previous cases, we are unable to retake the following 3 in-video quizzes for Week 9:
- [W9.1] OO Domain Models
- [W9.2] Activity Diagrams
- [W9.5e] Principles → Law of Demeter
</panel>

<panel  header="**4. :fas-info-circle: Request for smoke test for MacOS/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/240" expanded>

Could anyone help me run my [jar](https://github.com/nehcuy/ip/releases/tag/v1.0) file? I'm currently facing the problem of my background image not displaying on my jar file application.  
However, it works fine when I run my launcher in Intellij. I've already tried it by double-clicking the duke.jar file, and also running `java -jar duke.jar`.
Both times my background image does not show up, even though I did not edit my sourcecode. Just wanted to check if it was a Windows problem or it's shared across other OS.

**Edit:**
Background image should look like this:
![image](https://user-images.githubusercontent.com/94856691/190840630-c0ff1722-bd6f-41ab-8d71-5e06550119e8.png)

</panel>

<panel  header="**5. :fas-info-circle: Incomplete display of background image upon resizing of GUI window**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/187" expanded>

I've implemented resizing of the components to follow the corners of the page when we resize the window, but the background image does not seem to follow along. Attached below are illustrations of what I mean.
**This is the current standard starting status:**
![image](https://user-images.githubusercontent.com/94856691/189961857-347de6b1-3b37-4cdf-9e75-d09b92a35351.png)
**These are after resizing:**
![image](https://user-images.githubusercontent.com/94856691/189962085-9183e6c4-019b-4f25-a718-116ee23ef9b2.png)
![image](https://user-images.githubusercontent.com/94856691/189962099-acc3dfe4-483b-457a-bec3-219074dd5865.png)

This is my code segment for the `VBox` element in the `MainWindow.fxml` file:
```java
<content>
    <VBox fx:id="dialogContainer" prefHeight="552.0" prefWidth="388.0"
            style="-fx-background-image: url(./images/VBox-BG.png); -fx-background-size: auto;"/>
</content>
```

Here is the [link](https://github.com/nehcuy/ip/tree/branch-A-BetterGui/src/main/resources/view) to my `DialogBox.fxml` and `MainWindow.fxml` files. Any help is appreciated! 😄 

</panel>

<panel  header="**6. :fas-info-circle: Typo in Week 6 Topics notes**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/168" expanded>

Under Week 6's Topic of "Modeling: Sequence Diagrams",
`Tools → UML → Sequence Diagrams → Parallel paths`
I was just wondering if the `LocalServer#poll()` method was actually referring to the `poll()` method under `LocalData` instead?
I've attached an image to better illustrate the issue:
![image_2022-09-11_00-07-25](https://user-images.githubusercontent.com/94856691/189492034-78d157e9-fbbc-4ebb-becd-cee50b04a9e3.png)

CMIIW, but I believe `LocalServer#poll()` should have been `LocalData#poll()` instead.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/98#issuecomment-1229909928" expanded>

I was wondering if creating a class for it was a little unecessary as no objects are even created. Maybe just a private method within your `Command` class would do? But the problem is duplication of code if future new `Command` class implementations require date formatting. Not sure if making it and Interface would be better?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/137#issuecomment-1236055068" expanded>

Can you check if the tags are reflected on your forked repo? If it is not there, maybe try pushing the individual branches up to your forked repo.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/167#issuecomment-1242900280" expanded>

In particular, W6.1a and W6.1b for this week is unable to be resubmitted.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180#issuecomment-1244798847" expanded>

A little additional advice (since you only have a few days left) is to run through every minimum requirement instead of spending too much time overcustomising your bot. (Totally not what I did 🥲)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178#issuecomment-1245810527" expanded>

Instead of doing:
```java
while (myReader.hasNextLine()) {
...
}
```
on line 48 of your `Storage` class,

Try doing:
```java
String userInput = myReader.nextLine();
while (true) {
    ... 
    // Switch statements go here
    if (!myReader.hasNextLine()) {
        break;
    }
    userInput = sc.nextLine();
}
```

[Here](https://github.com/nehcuy/ip/blob/master/src/main/java/duke/storage/Storage.java) is my `Storage` class for reference :>
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/187#issuecomment-1246254025" expanded>

Thank you so much for the help. No wonder I couldn't see the background image, because the ScrollPane wasn't transparent! GUI works nicely now :>
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/187#issuecomment-1249504669" expanded>

@rui-han-crh Re-opening this because it doesn't work anymore. After i run shadowJar to build the duke.jar file, it no longer displays the background image when i run the JAR file. 🤔
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/240#issuecomment-1250002629" expanded>

@RezwanArefin01 It's due to the background image being too large. 😅 Apologies for the scare! If I were to replace it with another image of lower resolution, however, the same problem arises.
I've already updated my duke.jar to remove the high resolution image with a simpler background image.
**Edit**: Same [jar file](https://github.com/nehcuy/ip/releases/tag/v1.0) link used.

Desired output should now be like this:
![image](https://user-images.githubusercontent.com/94856691/190841657-37526c7e-3106-4d2a-8b7d-e2181efa1b77.png)

</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/240#issuecomment-1250004520" expanded>

@carriezhengjr Oh dear, thanks for checking! I think the problem arises from not being able to set the ScrollPane to be transparent, as I've already checked that the filepath to the image is correct.
Apparently there's a similar issue found [online](https://stackoverflow.com/questions/28324578/javafx-deployment-images-get-lost), but trying it does not remedy my issue. 😞 
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/326#issuecomment-1264999327" expanded>

I found a solution to this [online](https://tighten.com/blog/adding-commits-to-a-pull-request/). Basically you can add your teammate's fork as a remote repo to your local repo. However, this requires your teammate to check the "Allow edits from maintainers" checkbox on the Pull Request.

If you need to edit small things urgently, you can instead follow this [solution](https://stackoverflow.com/questions/44030176/how-to-modify-someone-elses-github-pull-request):
- Head to the PR and click "Files Changed" tab at the top. 
- Click on the blue "+" button that appears and comment out whatever changes you think needs to be done.
- Merge the branch as if there was nothing wrong.
- Make a new commit to your repository that fixes the issues (preferably mentioning the PR by issue id in your commit message so that GitHub can tell it's related and show it in the PR's Conversation page).
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/335#issuecomment-1278970155" expanded>

I've actually gotten the same error a few times and it was because I have cleared my cache and browser history, logging me out of codecov. You might want to check if you are logged into [codecov](https://about.codecov.io/).
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/342#issuecomment-1279709302" expanded>

Thanks for always fixing this problem every week prof!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/363#issuecomment-1286683150" expanded>

Apologies, I realised I should submit this feedback directly to the CATcher organisation instead.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/376#issuecomment-1291790927" expanded>

> Could I ask if there is a way around this? Thanks!

IIRC it was mentioned during my tutorial that due to restraints with PlantUML, it is fine to leave it as it is and that it is for our learning that the textbook sticks with the version where the lifeline should end where the object is deleted. This is just a vague memory, so someone please correct me if I'm wrong.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/385#issuecomment-1294487012" expanded>

Hi prof, just to clarify, if we have changes to UI that was under v1.3, is it still possible to push these changes?
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/385#issuecomment-1294504600" expanded>

@damithc Alright prof, I have sent you an email regarding this. Thanks!
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/479#issuecomment-1322010911" expanded>

My reasoning behind the answer key's construction of the partition is as such:
Since the method is asking for `isValidMonthSize`, 29 and 31 would both return a value of `true`. This is because despite 31 not being a valid date for the month of February, it is still a valid month size for other months such as January.

However, what I don't understand is why one partition is [1..31], when 2 would not be a valid month size? Shouldn't valid month sizes fall between the values of 28 (February on non-leap years) to 31 (January for eg.)? In other words, shouldn't the partition be [MIN_INT..27] [28..31] [32..MAX_INT] instead?
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/479#issuecomment-1322033097" expanded>

@damithc Ah so according to the new `isValidMonthSize` method name, both 0 and 1 are equally bad test cases to include, given that 5 was already used? In which case I think this is where @Hongyi6328 confusion stems from.
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/480#issuecomment-1324613089" expanded>

This is an issue throughout all the embedded tooltip in the online textbook. I'm experiencing the same issues as well, but after saving the textbook as PDF, all embedded tooltip do not work anymore, so I don't think its going to be much of a problem for scrollability.
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/499#issuecomment-1326426158" expanded>

@damithc That is a question from the final Lecture 13 slides if I'm not wrong.
</panel>

</panel>


<panel type="info" header="### 11. HUZA..GHAV `@huzaifa1712` (25 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request smoke test for Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/252" expanded>

Hello, I need help to test my iP on Linux. My release is [here](https://github.com/huzaifa1712/ip/releases/tag/v0.2) and my user guide is [here](https://huzaifa1712.github.io/ip/). Thanks.
</panel>

<panel  header="**2. :fas-info-circle: Library request: org.json**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/251" expanded>

## Library

[org.json](https://mvnrepository.com/artifact/org.json/json/20220320)

## Purpose

Used to implement saving and loading tasks to/from disk in Level-7. 
(I did not realise we had to request for permission to use third-party libraries for the iP, so my tutor said I should clarify before submitting)

## License

Public Domain -  see [repo](https://github.com/stleary/JSON-java/blob/master/LICENSE).

</panel>

<panel  header="**3. :fas-info-circle: Put every class in a package - should this apply to Duke.java?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/47" expanded>

I'm referring to the coding [standard](https://se-education.org/guides/conventions/java/intermediate.html#package-and-import-statements) given, under the heading **Package and Import Statements**

Just wanted to clarify as if so, the provided runtest.sh or runtest.bat would have to be changed to accommodate the new location of Duke.java.
</panel>

<panel  header="**4. :fas-info-circle: 💎 What to do if gitk command does not work on macOS**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/5" expanded>

With reference to W2.3e, Tools -&gt; Git and GitHub -&gt; commit: Saving changes to history, it says the `gitk` command can show a rudimentary version of the revision graph. 

<img width="807" alt="Screenshot 2022-08-14 at 12 58 09 AM" src="https://user-images.githubusercontent.com/20151382/184503777-df0eda31-376e-4460-863e-de7c8d1ed23f.png">

However I got a "command not found" error when typing `gitk` into my terminal. The fix from user "Clintm" in this StackOverflow link worked for me: https://stackoverflow.com/questions/30195143/gitk-command-not-found (just updating your Git version alone may not be enough). 

You do have to install a package manager called [Homebrew](https://brew.sh/) in order to install a 'git-gui' package and make gitk work. Don't know if this is something the instructors discourage, but I have found Homebrew quite useful in general and it is widely used, so I would think this is fine.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/15#issuecomment-1217991369" expanded>

Just in case you haven't seen it: does this link help?
As teoyuqi says, if Java was installed correctly it may be an issue with your PATH variable.

https://stackoverflow.com/questions/7709041/javac-is-not-recognized-as-an-internal-or-external-command-operable-program-or

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/19#issuecomment-1219011000" expanded>

Hi! I had the exact same issue and it was really annoying. When I tried comparing the files using IntelliJ itself (Select the files, right click and click 'Compare Files') I saw that it was failing due to really small, inconsequential differences I couldn't even notice when seeing the files side-by-side (see example below):

<img width="800" alt="Screenshot 2022-08-18 at 11 49 41 AM" src="https://user-images.githubusercontent.com/20151382/185289351-12a39c16-ae17-43c7-8852-b9efc3e2bf4e.png">

I am using Mac, so what worked for me was to run the `diff` command with the`-w `option, which ignores whitespace. 

**Note**: for anyone using a *nix OS it seems that -w has some nuances to it and there are other options which you may find more suitable (see this [StackOverflow](https://stackoverflow.com/questions/16423024/how-can-i-diff-2-files-while-ignoring-leading-white-space) link)

Since you are using Windows, you can try looking at the options [here](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/fc) for what I believe is the equivalent command (`FC` or File Compare, the last command in `runtest.bat`). 

I think adding the`\w` option might help? Sorry I can't test it out as I don't have access to a Windows OS or VM right now!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/27#issuecomment-1219290942" expanded>

Just in case you haven't seen it, does the fix from this issue help?: #19 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/27#issuecomment-1219300320" expanded>

@adeearyaa At the end of `text-ui-test/runtest.sh`, like this:

<img width="417" alt="Screenshot 2022-08-18 at 6 04 17 PM" src="https://user-images.githubusercontent.com/20151382/185369577-c09cf5f6-5691-4a11-978d-d576dd0c0873.png">


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/29#issuecomment-1219625959" expanded>

Hi, I tried cloning your repo and running the code. I think the reason you don't get anything in ACTUAL.TXT is because your Duke.java file does not output anything. The output from the main method in Duke.java (through `System.out`) is what is written to ACTUAL.TXT when you run `runtest.sh`.

If you try uncommenting the print statement in Duke.java and running `runtest.sh` again you might be able to see some output in ACTUAL.TXT!


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/47#issuecomment-1221565304" expanded>

Hi Prof, so to confirm would we need to put Duke.java into its own package in order to conform to the coding standard? Or can an exception be made for a file like Duke.java which is the entry point of a project? Thanks!

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/47#issuecomment-1221567843" expanded>

Thank you!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/55#issuecomment-1223883230" expanded>

You could try pulling the branch into a local branch on your repo using the answer from [here](https://stackoverflow.com/questions/5884784/how-to-pull-remote-branch-from-somebody-elses-repo) (user Antak's answer).

So you would execute this in your command line (after changing to the ip directory) to get the add-gradle-support branch from the original repo into a local branch with the same name, then merge the changes from the branch into your own branch:
`git fetch git@github.com:nus-cs2103-AY2223S1/ip.git add-gradle-support:add-gradle-support`
`git switch master`
`git merge add-gradle-support`

(assuming you want to merge the changes into your master branch - otherwise replace master with the name of the branch you want to merge into)

Just tried it and didn't seem to have any merge conflicts. Does this help?

</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/98#issuecomment-1230486807" expanded>

I think it's fine to have it in a separate class. It could make the code more extensible: if you wanted to add more commands that need similar formatting requirements you can re-use the code from that class. 

Another option could be to make a Command class that has the logic you need and have the required classes extend from there, but I'd personally prefer the method you have described.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/101#issuecomment-1230493090" expanded>

Not bad code per se, but [this repo](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) has a somewhat over-engineered implementation of FizzBuzz, perhaps taking the SWE practices we learn in this module to the extreme...
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/103#issuecomment-1231070349" expanded>

Not sure about SourceTree, but you could follow [this page](https://www.techiedelight.com/create-branch-from-previous-commit-git/) to make a branch from a previous commit and push it to the repo in the Git CLI if you want.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/105#issuecomment-1231078366" expanded>

Hi, I tried cloning your ip repo from your profile and running Duke.main() and the ip.jar from src/test/artifacts inside IntelliJ. I do encounter the error you have shown in your last screenshot. 

<img width="1391" alt="Screenshot 2022-08-30 at 10 45 30 AM" src="https://user-images.githubusercontent.com/20151382/187337389-cb906a3d-ba3a-4d77-a4e7-1b2007ac7041.png">


Perhaps you could elaborate on the behaviour you are expecting and steps you would take to reproduce it? 
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232779126" expanded>

Hi, I looked at your ip repo but I don't see the config/checkstyle folder in your root directory. Have you tried following all the steps in the [checkstyle guide](https://se-education.org/guides/tutorials/checkstyle.html)? Perhaps you can push what you have to your repo.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232955971" expanded>

I was going to say you should add the lines specified in the guide to your build.gradle file but I think you just added it to your master branch!
 
Do rename the file in /config/checkstyle to `suppressions.xml` (letter p twice) so checkstyle will run properly.
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232986005" expanded>

Odd...when I run ./gradlew build using your repo it only fails at checkstyle (as expected) without the error you mentioned.
As malwaregarry mentioned, perhaps there is an issue with the JDK settings on your system or IDE.

You might also want to check out [this SO](https://stackoverflow.com/questions/61289461/java-lang-noclassdeffounderror-could-not-initialize-class-org-codehaus-groovy-v) thread if you haven't already.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/116#issuecomment-1233762429" expanded>

For changing the java version from the terminal on Mac, try taking a look at this [link](https://stackoverflow.com/questions/21964709/how-to-set-or-change-the-default-java-jdk-version-on-macos).

Do take a look at the [advisory](https://nus-cs2103-ay2223s1.github.io/website/admin/programmingLanguages.html) on downloading the correct JDK 11 version for Mac if you still run into issues!
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/144#issuecomment-1236327089" expanded>

I think if you did it correctly, your root directory should have the build.gradle file from the [add-gradle-support](https://github.com/nus-cs2103-AY2223S1/ip/tree/add-gradle-support) branch of the original repo. 

Maybe you could delete the files you added (or [undo changes](https://www.atlassian.com/git/tutorials/undoing-changes) with Git) and try again?
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/148#issuecomment-1238109291" expanded>

Perhaps it was because some changes were made to your master branch (through the pull requests you merged?) and when you tried to update your master branch locally git suggested to pull the changes because of divergent histories, making these 'weird' merge commits.

Seems similar to the behaviour described [here](https://gist.github.com/joallard/6518431) and [here](https://stackoverflow.com/questions/7120199/github-merge-branch-master).
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/253#issuecomment-1250324136" expanded>

<img width="398" alt="Screenshot 2022-09-18 at 10 45 24 PM" src="https://user-images.githubusercontent.com/20151382/190913027-c68486e6-6d35-453a-8f53-7432d928624e.png">

Works on macOS Monterey. Loading existing tasks also works.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/308#issuecomment-1257989053" expanded>

@bryanngzh You could try looking at this [link](https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files) for pulling from the team repo by force
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/326#issuecomment-1266686022" expanded>

You can also try installing the [Github CLI](https://cli.github.com/) if you want,which makes it easier to checkout someone else's PR,.
</panel>

</panel>


<panel type="info" header="### 12. TAN ..DEON `@deeyonn` (24 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: How to approach reloading the application with a command?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/373" expanded>

Hi, I would like to explore the idea of reloading the application using a `Command`.

I would like to initialize new instances of the following classes in the reload `Command`.
* `JsonUserPrefsStorage`
* `UserPrefs`
* `JsonAddressBookStorage`
* `StorageManager`
* `ModelManager`
* `LogicManager`
* `UiManager`

and reload `MainApp` using these new instances.

Since the current `Command::execute` function only takes in `Model` as its parameter, what are some ways I can expose the current instances of the above classes for modification, and then reloading the application if needed.

</panel>

<panel  header="**2. :fas-info-circle: Requirements for clearing Use GFMD tag**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/145" expanded>

Hi all, I've noticed on the iP dashboard that my progress for the `!Use GFMD` tag has not been completed even though I have edited my `README.md`.

Is there any additional task that I have to complete i.e., create and push a tag `Use GFMD` on the commit i made to edit `README.md`?
</panel>

<panel  header="**3. :fas-info-circle: How do I correctly set up resources folder for JavaFX?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/126" expanded>

Hi, when following the tutorial for JavaFX setup, I encountered an issue with NullPointerException when I try to load my resource. Any advice on how I can resolve this?

![image](https://user-images.githubusercontent.com/41563700/188114910-512139c5-8f79-4748-bedb-801b8cea69d7.png)

The 3 things to take from the picture are:
- Resource folder structure and icon indicating that it's recognised
- The 2 lines of code copied from the tutorial
- The error message pointing to the NullPointerException

Things I've tried:
- Absolute path rather than relative path
- Restarting IntelliJ
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1217490892" expanded>

I'm not sure if I understood the requirements for method(), but why wouldn't a simple producer class fit the role for method()?

https://docs.oracle.com/javaee/7/api/javax/enterprise/inject/spi/Producer.html

https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/12#issuecomment-1217582541" expanded>

![image](https://user-images.githubusercontent.com/41563700/185060967-174c643b-0f06-4715-af47-650098843c8c.jpeg)

According to the FAQ in Week 2, this is what you should do.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/51#issuecomment-1224066004" expanded>

I thought copilot only helps by suggesting very common boilerplate code that is often reused over and over again. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/49#issuecomment-1224068242" expanded>

Thank you for the clarification! 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/123#issuecomment-1235016543" expanded>

Yes, I am experiencing the same issue as well. I will try to add the tag to the master branch after merging to see if the issue is resolved. Thanks for the suggestions!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/123#issuecomment-1235056870" expanded>

> @RichDom2185 @deeyonn is it resolved now?

Yes professor, I do see the missing tags on the dash. thank you!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/126#issuecomment-1235331677" expanded>

> Not sure if it works but I think there's a missing / before images.
> 
```
> private Image user = new Image(this.getClass().getResourceAsStream("/images/DaUser.png"));
> private Image duke = new Image(this.getClass().getResourceAsStream("/images/DaDuke.png"));
```

omg i feel so foolish! good catch! thank you so much!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/145#issuecomment-1236373193" expanded>

> Hi Deon, GFMD is meant to be used in your PR description, not your README.md. Hope this helps.

Thank you for the clarification, I will update the PR description.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/177#issuecomment-1243465396" expanded>

Perhaps you could explore using the `git reset` or `git revert` commands depending on your situation. IIRC merge commits that have not been pushed are much easier to revert.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/153#issuecomment-1243469907" expanded>

Thanks @Hongyi6328 ! It might be a little too late for myself to do any refactoring but I'll be sure to save this snippet for future use! 
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1243483072" expanded>

![image](https://user-images.githubusercontent.com/41563700/189623535-3ba7c961-db95-4033-a4fe-ef8271cb549d.png)
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178#issuecomment-1243529585" expanded>

I suspect its caused by closing myReader at the end of the function?

i.e., 
1. When you initialise your Storage object, it creates an instance of Scanner myReader and opens it, that's great.
2. When you run your readDuke function once, perhaps it works because myReader is still open.
3. At the end of the first readDuke run, myReader is closed.
4. Subsequent calls to readDuke might be using an instance of myReader that is already closed.

Perhaps you can push to a branch and post the branch here with steps stating intended outcome and actual outcome?

Edit1: I also noticed that you are using absolute file paths in your Storage class. I believe the weekly tasks recommend you to explore using relative file paths which can easily be done using `String userHome = System.getProperty("user.home");`
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178#issuecomment-1243543128" expanded>

@PokezardVGC You can try to troubleshoot by reducing the scope to the readDuke function.

i.e., Pull File and Scanner into readDuke as local variables and initialise them every function run, then closing them at the end of the run.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/177#issuecomment-1243916668" expanded>

@shawnkai delete the tag in the previous commit and add it back after you've merged worked for me
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179#issuecomment-1244884407" expanded>

I left a PR review but was unable to identify the problem. 
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/347#issuecomment-1280670037" expanded>

In this context, I would block if there are dependencies of the parameter `phone number` that requires it to be of a certain strict format. Else if the purpose of the parameter is solely for display purposes, I would warn.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/348#issuecomment-1280674286" expanded>

![image](https://user-images.githubusercontent.com/41563700/196160171-89ab1cb4-9896-4ecb-82da-c78a364c5c04.jpeg)

Seems that it would be before the next lecture.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/335#issuecomment-1280676366" expanded>

I've been experiencing the same issue from time to time. Re-running the failed task after awhile seems to work.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/352#issuecomment-1283219839" expanded>

Looking at the error and focusing on this portion,
`JsonMappingException: Can not instantiate value of type [simple type, class seedu.intrack.storage.JsonAdaptedTask] from String value ('Application submitted'); no single-String constructor/factory method`

and seeing that these are present,
`Data file not in the correct format.`
`"taskFilled" : [ "Application submitted" ],`

I'd infer that you're trying to parse an item of Task type rather than a JSON recognised type like a string.

I say this because you mentioned `only the taskName of the Task class is stored in the json file`.

You might need to explore how to "stringify" your Task onject before attempting to parse it.

I could be wrong but this is my best guess at it.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/373#issuecomment-1288677359" expanded>

> @deeyonn Out of curiosity, what's the purpose of reloading the app using a command?

Hi Prof, I would like to achieve the result of allowing the user to specify a json file to load using a command, then loading that file. Though a majority of that logic falls under `JsonAddressBookStorage`, it seems that there are many other classes listed above that are interdependent on each other.

The ideal solution would be to change the instance of as little objects as possible. The worst case would be to reload the entire application specifying all the new instances.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/373#issuecomment-1290331737" expanded>

Thank you all for the insightful feedback!! I think everyone's suggestions has its pros and cons. I have decided to modify the method signature of `Command#execute(Model model)` to `Command#execute(Model model, Storage storage)`. Though I am facing new issues regarding updating displays, I will discuss these issues with my team and see how we can move forward. Or maybe open a new issue if there is time.
</panel>

</panel>


<panel type="info" header="### 13. KIM ..BEOM `@Yongbeom-Kim` (23 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Are new error messages allowed in bug-handling?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/416" expanded>

I am asking the question with respect to this issue:

https://github.com/AY2223S1-CS2103-F13-1/tp/issues/195

Our AddressBook identifies object by an integer ID, and it seems that there is a bug where if there is an ID with value MAX_INT, and another object is added, the app adds an ID with MAX_INT+1, and on next load, the app throws away the save file (since it's overflowed to negative now).

```json
{
  "projects" : [ {
    "name" : "Individual Project",
    "repository" : "johndoe/ip",
    "deadline" : "2022-03-03",
    "client" : {
      "name" : "Alex Yeoh",
      "mobile" : "87438807",
      "email" : "alexyeoh@example.com",
      "clientId" : "1",
      "projects" : [ ],
      "pin" : "false"
    },
    "issues" : [ ],
    "projectId" : "2147483647",
    "pin" : "false"
  } ],
  "issues" : [ ]
}
```
![image](https://user-images.githubusercontent.com/63487502/199641249-20b48213-030b-4707-ab1d-c971640557fc.png)

This is definitely unintended behaviour, so I'd argue that it is a bug.

But to which extent are we allowed to fix this? I'm seeing some 'partial' fixes:
- We can simply throw an error with no feedback to user (logged to console) - in this case UG will be updated to reflect the bug
- We can throw an error with a new error message to user - but is the new error message considered 'adding' a feature?


</panel>

<panel  header="**2. :fas-info-circle: Doing later tasks first (A-Gradle before Level-7)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/58" expanded>

I'd am currently on the Level 7/8 task (halfway through 7), and I think I'd like to do the A-Gradle task first.

This is because I'd like to do read/writes on json files, and use the `org.json` dependency, and the easiest way to do this is using a tool like Maven or Gradle (and Gradle conveniently happens to be an upcoming task).

So what this means is that I'll be doing a git stash on the current branch, do the Gradle on a new branch, and then do a git fetch/merge on the level 7 branch to fetch the changes.

Can I do this?

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/282#issuecomment-1253182723" expanded>

Works on Ubuntu WSL as well.

When data file is changed:
![image](https://user-images.githubusercontent.com/63487502/191412823-17c14eba-e475-4f7d-9333-6e59dbc22631.png)

On invalid command:
![image](https://user-images.githubusercontent.com/63487502/191413027-79c4d784-f4b7-473d-9607-01f4476bd527.png)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/279#issuecomment-1253186170" expanded>

Works on Ubuntu WSL as well.

Note that I am able to resize and this breaks the UI:
![image](https://user-images.githubusercontent.com/63487502/191413287-daceffa2-e282-4737-a707-eab9f9da9825.png)

Please note that data saving **fails** to save & retrieve tasks - it creates a `task.txt`, but does not write to the file. There is no stack trace or log files produced, so I don't think this is a permissions or file IO problem.

Also, your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/277#issuecomment-1253188669" expanded>

Works on Ubuntu WSL.

Note that I am able to resize the window and this breaks the UI.
![image](https://user-images.githubusercontent.com/63487502/191414114-2ff372bc-94f1-4af1-b95d-349fa862a257.png)

Also note that I am not seeing the relevant emojis in text - but I think this might be a WSL problem.

File IO works fine

Also, your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1253190412" expanded>

Works fine on Ubuntu WSL.
![image](https://user-images.githubusercontent.com/63487502/191414531-ed144ab3-abd0-4541-a6e4-199cbd1d0d05.png)

Note that I am able to resize the window and this breaks the UI:
![image](https://user-images.githubusercontent.com/63487502/191414641-d8461f27-d1b1-4e25-8498-89be21ddf7eb.png)

File IO works fine as well

Also your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/271#issuecomment-1253206174" expanded>

Works on Ubuntu WSL. UI Looks very nice!

![image](https://user-images.githubusercontent.com/63487502/191414998-5772e3a4-402c-4174-b87d-5c580d3d3964.png)

Upon opening the app, I'm hit with a
```
Deserialization error, see below:
/root/CS2103T/DukeData/savefile.json (No such file or directory)
```
I'm not sure if this is intended, so pointing it out here.

There is a checkbox next to the TODO, but clicking it does nothing - is this meant to be interactive?
![image](https://user-images.githubusercontent.com/63487502/191415267-bf9649bd-b317-408c-8e82-93ff4513c17e.png)

Also, your file IO works, but it does _not_ save the file to the relative file path, but **instead saves the file to the `/root` directory**.  Not that this **may not work** on all machines if you don't have permission to write there (correct me if I'm wrong)

Also why are you writing `Duke.png` and `User.png` to `/root`? The other apps don't write the files there - are you copying your entire resources directory over?

Directory tree for reference:
```
root@MSI:~# tree
.
└── CS2103T
    └── DukeData
        ├── Resources
        │   └── ProfilePictures
        │       ├── Duke.png
        │       └── User.png
        └── savefile.json
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276#issuecomment-1253255209" expanded>

Testing on Ubuntu WSL:

Your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246 - please fix

When the app is resized, the text on the button is not responsive: 
![image](https://user-images.githubusercontent.com/63487502/191428445-e76702b3-765e-407a-96ee-41541a0f7661.png)

File IO works.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1255284790" expanded>

@guokweijie sflr! I added the comment because if you're not planning to support resizing, then it can be disabled with `stage.setResizable(false);`

I tried again, it doesn't work. Which linux distro is your friend on? I'm on Ubuntu 20.04.5 - seems to be a ubuntu-specific problem. Bumping JavaFX version should solve the issue

EDIT: Sorry, the resizing thing looks like a linux-specific thing? For some reason ubuntu still lets me resize apps that are set to not-resizable, my bad. ignore that part
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276#issuecomment-1255288018" expanded>

@ChongCheeKaiClarence app works now! 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/293#issuecomment-1255297210" expanded>

I am on Ubuntu 20.04.5 WSL, and i am unable to run your app.

Stack trace:
```
Graphics Device initialization failed for :  es2, sw
Error initializing QuantumRenderer: no suitable pipeline found
java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
        at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280)
        at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222)
        at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
        at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
        at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
        at java.base/java.lang.Thread.run(Thread.java:833)
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94)
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
        ... 1 more
Exception in thread "main" java.lang.RuntimeException: No toolkit found
        at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
        at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
        at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
        at java.base/java.lang.Thread.run(Thread.java:833)
```
Here is my specs:
```
dernbu@MSI:/mnt/c/users/Dernbu/Downloads/CS2103 Testing$ cat /etc/os-release
NAME="Ubuntu"
VERSION="20.04.5 LTS (Focal Fossa)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 20.04.5 LTS"
VERSION_ID="20.04"
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
VERSION_CODENAME=focal
UBUNTU_CODENAME=focal
```
Java version:
```
dernbu@MSI:/mnt/c/users/Dernbu/Downloads/CS2103 Testing$ java --version
java 18.0.2.1 2022-08-18
Java(TM) SE Runtime Environment (build 18.0.2.1+1-1)
Java HotSpot(TM) 64-Bit Server VM (build 18.0.2.1+1-1, mixed mode, sharing)
```

So [this](https://stackoverflow.com/questions/21185156/javafx-on-linux-is-showing-a-graphics-device-initialization-failed-for-es2-s) thread asks you to run with the `-Dprism.verbose=true` flag, and here it is:
```
dernbu@MSI:/mnt/c/users/Dernbu/Downloads/CS2103 Testing$ java -Dprism.verbose=true -jar doomba.jar
Prism pipeline init order: es2 sw
Using Double Precision Marlin Rasterizer
Using dirty region optimizations
Not using texture mask for primitives
Not forcing power of 2 sizes for textures
Using hardware CLAMP_TO_ZERO mode
Opting in for HiDPI pixel scaling
Prism pipeline name = com.sun.prism.es2.ES2Pipeline
GraphicsPipeline.createPipeline failed for com.sun.prism.es2.ES2Pipeline
java.lang.ClassNotFoundException: com.sun.prism.es2.ES2Pipeline
        at java.base/jdk.internal.loader.BuiltinClassLoader.loadClass(BuiltinClassLoader.java:641)
        at java.base/jdk.internal.loader.ClassLoaders$AppClassLoader.loadClass(ClassLoaders.java:188)
        at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521)
        at java.base/java.lang.Class.forName0(Native Method)
        at java.base/java.lang.Class.forName(Class.java:383)
        at java.base/java.lang.Class.forName(Class.java:376)
        at com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
        at java.base/java.lang.Thread.run(Thread.java:833)
*** Fallback to Prism SW pipeline
Prism pipeline name = com.sun.prism.sw.SWPipeline
GraphicsPipeline.createPipeline failed for com.sun.prism.sw.SWPipeline
java.lang.UnsatisfiedLinkError: no prism_sw in java.library.path: /usr/java/packages/lib:/usr/lib64:/lib64:/lib:/usr/lib
        at java.base/java.lang.ClassLoader.loadLibrary(ClassLoader.java:2434)
        at java.base/java.lang.Runtime.loadLibrary0(Runtime.java:848)
        at java.base/java.lang.System.loadLibrary(System.java:2015)
        at com.sun.glass.utils.NativeLibLoader.loadLibraryInternal(NativeLibLoader.java:150)
        at com.sun.glass.utils.NativeLibLoader.loadLibrary(NativeLibLoader.java:52)
        at com.sun.prism.sw.SWPipeline.lambda$static$0(SWPipeline.java:42)
        at java.base/java.security.AccessController.doPrivileged(AccessController.java:318)
        at com.sun.prism.sw.SWPipeline.<clinit>(SWPipeline.java:41)
        at java.base/java.lang.Class.forName0(Native Method)
        at java.base/java.lang.Class.forName(Class.java:383)
        at java.base/java.lang.Class.forName(Class.java:376)
        at com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
        at java.base/java.lang.Thread.run(Thread.java:833)
Graphics Device initialization failed for :  es2, sw
Error initializing QuantumRenderer: no suitable pipeline found
java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
        at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280)
        at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222)
        at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
        at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
        at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
        at java.base/java.lang.Thread.run(Thread.java:833)
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94)
        at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
        ... 1 more
Exception in thread "main" java.lang.RuntimeException: No toolkit found
        at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
        at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
        at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
        at java.base/java.lang.Thread.run(Thread.java:833)
```
I hope this helps in your troubleshooting, perhaps there is some dependency not captured somewhere? LMK if you need me to run anything else
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/292#issuecomment-1255303092" expanded>

I am on Ubuntu 20.04.5 WSL,

Note that your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246:
```
dernbu@MSI:/mnt/c/users/Dernbu/Downloads/CS2103 Testing$ java -jar duke.jar

(java:27939): Gdk-CRITICAL **: 00:55:51.436: gdk_x11_display_set_window_scale: assertion 'GDK_IS_X11_DISPLAY (display)' failed
#
# A fatal error has been detected by the Java Runtime Environment:
#
#  SIGSEGV (0xb) at pc=0x00007f0031eec420, pid=27939, tid=27975
#
# JRE version: Java(TM) SE Runtime Environment (18.0.2.1+1) (build 18.0.2.1+1-1)
# Java VM: Java HotSpot(TM) 64-Bit Server VM (18.0.2.1+1-1, mixed mode, sharing, tiered, compressed oops, compressed class ptrs, g1 gc, linux-amd64)
# Problematic frame:
# C  [libX11.so.6+0x29420]  XInternAtom+0x40
#
# No core dump will be written. Core dumps have been disabled. To enable core dumping, try "ulimit -c unlimited" before starting Java again
#
# An error report file with more information is saved as:
# /mnt/c/users/Dernbu/Downloads/CS2103 Testing/hs_err_pid27939.log
#
# If you would like to submit a bug report, please visit:
#   https://bugreport.java.com/bugreport/crash.jsp
# The crash happened outside the Java Virtual Machine in native code.
# See problematic frame for where to report the bug.
#
Aborted
```
I can confirm that basic task-adding and file IO works when run with `java -Djdk.gtk.version=2 -jar duke.jar`
![image](https://user-images.githubusercontent.com/63487502/191807660-57f9f217-8404-48a9-ab59-57aa08f5c0d3.png)

</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/291#issuecomment-1255306009" expanded>

I am on Ubuntu 20.04.5 WSL.

Note that your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246:
```
dernbu@MSI:/mnt/c/users/Dernbu/Downloads/CS2103 Testing$ java -jar duke.jar

(java:28121): Gdk-CRITICAL **: 01:00:23.107: gdk_x11_display_set_window_scale: assertion 'GDK_IS_X11_DISPLAY (display)' failed
#
# A fatal error has been detected by the Java Runtime Environment:
#
#  SIGSEGV (0xb) at pc=0x0000000000000002, pid=28121, tid=28156
#
# JRE version: Java(TM) SE Runtime Environment (18.0.2.1+1) (build 18.0.2.1+1-1)
# Java VM: Java HotSpot(TM) 64-Bit Server VM (18.0.2.1+1-1, mixed mode, sharing, tiered, compressed oops, compressed class ptrs, g1 gc, linux-amd64)
# Problematic frame:
# C  0x0000000000000002
#
# No core dump will be written. Core dumps have been disabled. To enable core dumping, try "ulimit -c unlimited" before starting Java again
#
# An error report file with more information is saved as:
# /mnt/c/users/Dernbu/Downloads/CS2103 Testing/hs_err_pid28121.log
#
# If you would like to submit a bug report, please visit:
#   https://bugreport.java.com/bugreport/crash.jsp
# The crash happened outside the Java Virtual Machine in native code.
# See problematic frame for where to report the bug.
#
Aborted
```

Otherwise, adding todos and file IO works well! 
![image](https://user-images.githubusercontent.com/63487502/191808383-10d9a6bd-671b-46bb-ad6d-ae7a325417f3.png)


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1255713710" expanded>

11.02
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/294#issuecomment-1255718276" expanded>

I am on Ubuntu 20.04.5 WSL,

Note that your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246:
```
dernbu@MSI:/mnt/c/Users/Dernbu/Downloads/CS2103 Testing$ java -jar  duke.jar

(java:28334): Gdk-CRITICAL **: 09:42:37.492: gdk_x11_display_set_window_scale: assertion 'GDK_IS_X11_DISPLAY (display)' failed
#
# A fatal error has been detected by the Java Runtime Environment:
#
#  SIGSEGV (0xb) at pc=0x00007f54217c9420, pid=28334, tid=28369
#
# JRE version: Java(TM) SE Runtime Environment (18.0.2.1+1) (build 18.0.2.1+1-1)
# Java VM: Java HotSpot(TM) 64-Bit Server VM (18.0.2.1+1-1, mixed mode, sharing, tiered, compressed oops, compressed class ptrs, g1 gc, linux-amd64)
# Problematic frame:
# C  [libX11.so.6+0x29420]  XInternAtom+0x40
#
# No core dump will be written. Core dumps have been disabled. To enable core dumping, try "ulimit -c unlimited" before starting Java again
#
# An error report file with more information is saved as:
# /mnt/c/Users/Dernbu/Downloads/CS2103 Testing/hs_err_pid28334.log
#
# If you would like to submit a bug report, please visit:
#   https://bugreport.java.com/bugreport/crash.jsp
# The crash happened outside the Java Virtual Machine in native code.
# See problematic frame for where to report the bug.
#
Aborted
```
Running with `java -Djdk.gtk.version=2 -jar duke.jar`, your app works fine
Same issue to resolve as above:
![image](https://user-images.githubusercontent.com/63487502/191878538-a1ae82ff-8c00-433d-8316-7fc3ce0754d4.png)
File IO works fine as well
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/295#issuecomment-1255719799" expanded>

I am on Ubuntu 20.04.5 WSL,

For some reason, your app by default has some sizing/resolution issues when I run it (I didn't resize the window):
![image](https://user-images.githubusercontent.com/63487502/191878679-83e8e079-343e-4ade-ac71-ecc5371f5a6e.png)

Everything else works well!
![image](https://user-images.githubusercontent.com/63487502/191878821-263e6f09-3dbb-4902-84e5-b42756afec30.png)

</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1255761284" expanded>

Yep, works
![image](https://user-images.githubusercontent.com/63487502/191886268-922ba105-3815-401e-ac83-12b1f9b40b0a.png)

</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/296#issuecomment-1255762689" expanded>

I am on Ubuntu 20.04.5 WSL.

App runs fine. I don't know why, your app looks like this when run:
![image](https://user-images.githubusercontent.com/63487502/191886414-488a2499-680a-46d1-8c0d-0d9f0790d126.png)

File IO and adding tasks work, but I have no idea where you're saving the tasks to:
![image](https://user-images.githubusercontent.com/63487502/191886608-c317db8c-c34c-4793-aa1a-89cc329a5be5.png)

Also console gives me this, if it is of any concern to you:
```
dernbu@MSI:/mnt/c/Users/Dernbu/Downloads/CS2103 Testing$ java -jar duke.jar
Sep 23, 2022 11:21:47 AM com.sun.javafx.application.PlatformImpl startup
WARNING: Unsupported JavaFX configuration: classes were loaded from 'unnamed module @1cf89471'
```
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/294#issuecomment-1255949828" expanded>

https://github.com/nus-cs2103-AY2223S1/forum/issues/246 is still an issue - pls bump ur javafx version to 11.0.2

Other than that, LGTM!
![image](https://user-images.githubusercontent.com/63487502/191924339-a0c31853-56a4-4725-8510-37de568c2481.png)

</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/291#issuecomment-1255950616" expanded>

New version works well! 
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/300#issuecomment-1255954092" expanded>

On ubuntu, your app suffers from https://github.com/nus-cs2103-AY2223S1/forum/issues/246, try bumping your JavaFX version to 11.0.2

Other than that, everything works well.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/373#issuecomment-1289300610" expanded>

It seems to me that you just need to empty current, and load new data into the relevant observable lists? Maybe you can expose a reload method in Model that fetches data and re-constructs relevant objects?
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/416#issuecomment-1301634072" expanded>

Ah I see, thank you for the input - I think it can definitely be considered an extreme situation, but I've written a fix for it anyways, so I guess it will be fixed 🤷
</panel>

</panel>


<panel type="info" header="### 14. ZHEN..ARUI `@carriezhengjr` (22 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: CI for build (ubuntu-latest) takes very long**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/333" expanded>

I have changed [build.gradle](https://github.com/carriezhengjr/tp/blob/gui-testing/build.gradle) to include TestFX for automated GUI testing in an attempt to solve the failing codecov/patch check #330 that appeared from my previous commit. 
However, [build (ubuntu-latest)](https://github.com/carriezhengjr/tp/actions/runs/3210434980/jobs/5248668231) is taking super long (> 1 hour) while [build (macos-latest)](https://github.com/carriezhengjr/tp/actions/runs/3210434980/jobs/5248668277) and [build (windows-latest)](https://github.com/carriezhengjr/tp/actions/runs/3210434980/jobs/5248668318) took less than 2 minutes each.
<img width="1483" alt="Screenshot 2022-10-09 at 00 36 03" src="https://user-images.githubusercontent.com/97394017/194717902-df0b8785-fd63-47e3-a23c-56bd1235e2c8.png">

Is it because I have missed out some things when adding automated GUI testing using TestFX? But why does it work with macos and windows 🤔 ?
(The [tests](https://github.com/carriezhengjr/tp/tree/gui-testing/src/test/java) that I've added are for [`HelpWindow.java`](https://github.com/carriezhengjr/tp/blob/gui-testing/src/main/java/seedu/address/ui/HelpWindow.java). They are mostly reused and adapted from the GUI tests written in [Address Book (Level 4)](https://github.com/se-edu/addressbook-level4).)

</panel>

<panel  header="**2. :fas-info-circle: Failing codecov/patch check**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/330" expanded>

My recent commit is failing a check in my repo: codecov/patch — 0.00% of diff hit (target 72.15%).
However, the pull request was already merged to our team's repo because it passes all the checks present in team's repo.

I'm not sure why the codecov/patch check fails. I have changed `HelpWindow.java` and `HelpWindow.fxml` in that commit.

Is this of a concern, and how I can resolve this?

Checks in [my repo](https://github.com/carriezhengjr/tp):
<img width="495" alt="Screenshot 2022-10-06 at 16 38 02" src="https://user-images.githubusercontent.com/97394017/194264603-8ae61dcd-f696-4390-82f7-d443e5d26a1a.png">

Checks in my [team's repo](https://github.com/AY2223S1-CS2103T-T11-4/tp):
<img width="491" alt="Screenshot 2022-10-06 at 16 44 34" src="https://user-images.githubusercontent.com/97394017/194265790-bc44d48e-fa7c-42db-931e-f598025cf2e8.png">
<img width="495" alt="Screenshot 2022-10-06 at 16 39 00" src="https://user-images.githubusercontent.com/97394017/194264704-d27509d5-50ea-4a52-9639-784dc5995505.png">


The [Codecov Report](https://codecov.io/gh/AY2223S1-CS2103T-T11-4/tp/pull/60?src=pr&el=h1&utm_medium=referral&utm_source=github&utm_content=comment&utm_campaign=pr+comments&utm_term=AY2223S1-CS2103T-T11-4) found in my [pull request](https://github.com/AY2223S1-CS2103T-T11-4/tp/pull/60):
<img width="822" alt="Screenshot 2022-10-06 at 17 40 19" src="https://user-images.githubusercontent.com/97394017/194280740-c5210b94-0146-4af4-9e0e-aa763b2cd0b1.png">


</panel>

<panel  header="**3. :fas-info-circle: Commits failing codecov checks**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/309" expanded>

My team has set up codecov already and all the checks seem to pass for my [team's repo](https://github.com/AY2223S1-CS2103T-T11-4/tp).

However, my [own fork](https://github.com/carriezhengjr/tp) is failing codecov checks and I'm not sure why is that so.
All [my branches](https://github.com/carriezhengjr/tp/branches) also show the red crosses.

<img width="1302" alt="Screenshot 2022-09-26 at 22 58 19" src="https://user-images.githubusercontent.com/97394017/192313195-514bc6bc-8e72-4554-81cf-b738e43d87f0.png">

</panel>

<panel  header="**4. :fas-info-circle: Request for smoke testing help (Windows/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219" expanded>

Hello! Could anyone help to test for Linux and Windows? Here is the [latest release](https://github.com/carriezhengjr/ip/releases/tag/A-Release). Thank you so much!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/9#issuecomment-1214963458" expanded>

I have also faced the same issue and tried the last solution provided in this link:
https://stackoverflow.com/questions/29388207/sourcetree-gui-cant-push-terminal-can-push 

Basically, you can try this method by going to GitHub —> Settings —> Developer settings —> Personal access tokens —> Generate new token. Then, you can configure the permissions (expiration, select scopes) and generate a personal access token. Copy this token.
Next, go to Sourcetree —> Accounts —> Edit… —> Auth Type: Basic. Username: your GitHub username. Password: paste your personal access token here. Protocol: HTTPS —> Save.

I am able to push after changing these settings. Hope this helps!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/11#issuecomment-1217387403" expanded>

You could try the methods here first to see if the issue persists: https://github.com/nus-cs2103-AY2223S1/forum/issues/9 
(I am also using Mac and received similar error message as you when I tried to push to remote repo too.)

Hope it helps!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249083167" expanded>

I'm using MacOS and this is what appears.
<img width="398" alt="Screenshot 2022-09-16 at 16 32 33" src="https://user-images.githubusercontent.com/97394017/190594654-f66dcf26-1700-499d-9b0b-9550078e1bf8.png">

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/204#issuecomment-1249095737" expanded>

Resizing issue is fixed now and works fine on Mac!

<img width="735" alt="Screenshot 2022-09-16 at 16 44 50" src="https://user-images.githubusercontent.com/97394017/190596708-aa4aa30a-8e90-4ed2-a9a1-4fafb4b6a0b5.png">
<img width="396" alt="Screenshot 2022-09-16 at 16 45 04" src="https://user-images.githubusercontent.com/97394017/190596742-eb0ec76b-90d3-40b9-89a2-fe032d2bcd96.png">
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249380924" expanded>

> Tested on Linux (Arch). Some images are not being loaded: ![Screenshot_20220916_172730](https://user-images.githubusercontent.com/22095441/190605552-efbcfae3-aebd-4423-8c3f-72a324f37a18.png) Read [this thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/217) for possible fix.

Thank you for helping! I have converted the images to png. Do you mind helping to test it again, especially the chatbot profile picture, user profile picture, quick start and detailed guide images? Here is the [new release](https://github.com/carriezhengjr/ip/releases/tag/A-Release). Really appreciate your help!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249384207" expanded>

Thank you @xhphoong and @RussellDash332 for helping to test on Windows! 😄 

I have uploaded a new [jar file](https://github.com/carriezhengjr/ip/releases/tag/A-Release) to fix the image issues. If you don't mind, could you help to check if the new jar can be opened and is working fine? Really appreciate your help!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249396682" expanded>

> Resizing is disabled now so that's good. The application title seems to be weird now ![image](https://user-images.githubusercontent.com/63991775/190655017-8697e629-54bd-4864-9036-b00df22ca64e.png)

Alright! I have just updated the release by removing the emoji, since it also doesn't show properly on Linux previously. Thank you so much for your help! 😄 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249420361" expanded>

Hi! I have downloaded the new jar file, but I'm not sure why I could not open it on my Mac. Seems like it's running because I have the "java" folder icon showing in the bottom bar (which always show when I run jar files), but the window is not showing up. I tried to click "Show All Windows" but I got "No Available Windows".

I have tried to delete and re-download it several times, the window to the app still does not show up.

Perhaps you could try to re-upload your jar file?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230#issuecomment-1249429528" expanded>

Hi, everything seems fine on my Mac!
<img width="400" alt="Screenshot 2022-09-16 at 22 23 23" src="https://user-images.githubusercontent.com/97394017/190661905-58073f56-deb6-4b99-96c0-714b1c43dd01.png">

</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/219#issuecomment-1249454465" expanded>

> Working as expected on Linux: ![Screenshot_20220916_223547](https://user-images.githubusercontent.com/22095441/190664471-d31c3a7c-0e91-4cba-8e77-49d96c6b2fed.png)

Thank you so much! 😄 
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/240#issuecomment-1250003521" expanded>

Hi, this is what's shown on my Mac, background image cannot be displayed:
<img width="397" alt="Screenshot 2022-09-17 at 13 21 22" src="https://user-images.githubusercontent.com/97394017/190841845-3c6d9763-5b27-4c24-bfe8-9486ff87ccf0.png">

</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/309#issuecomment-1258266156" expanded>

> I had the same issue, what I did was to refresh the token via the codecov dashboard, hope it helps.
> 
> 1. Go to https://app.codecov.io/gh
> 2. Click on your Team Repo.
> 3. Go to settings and hit regenerate.
>    ![image](https://user-images.githubusercontent.com/56034480/192319835-844a5abc-f8da-45cd-ad6c-76b5fc8f3dec.png)
> 4. Back to Github Actions and re-run all build processes.
> 
> Took reference from [stackoverflow](https://stackoverflow.com/a/67862043)

It's working now after following the steps. Thank you so much 😄 !
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/333#issuecomment-1272359270" expanded>

> @carriezhengjr did you try restarting the CI job? On a related note, GUI tests are more susceptible to OS-specific quirks.

Yes, I have cancelled the 1st attempt and tried again, but it's still not done running the check. The [1st attempt](https://github.com/carriezhengjr/tp/actions/runs/3210434980/attempts/1) took nearly 3 hours but still didn't finish running, so I cancelled it. Is there any way to solve this 🤔 ?
<img width="1482" alt="Screenshot 2022-10-09 at 00 52 11" src="https://user-images.githubusercontent.com/97394017/194718762-b93289ae-1e64-4ba7-b528-6c58faa30371.png">
<img width="1109" alt="Screenshot 2022-10-09 at 00 55 52" src="https://user-images.githubusercontent.com/97394017/194718765-d75a3bdd-f375-47d9-9658-e9b0e62bde0b.png">

Since GUI tests are susceptible to OS-specific quirks, do we need to include GUI tests in tP? 

Also, do we have to resolve the failing codecov/patch check (#330) that is included in individual forked repo, or it's fine as long as the pull request passes all checks in the team repo? (The checks seem to be different in individual forked repo and team repo.)
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/333#issuecomment-1272483055" expanded>

> If the test doesn't finish within 10 minutes or so, most likely it's stuck and best to cancel it rather than waste build minutes.
> 
> Does the test pass locally, on Linux? If yes, you can insert extra print statements to see where the test get stuck during CI. Troubleshooting GUI test errors is hard (and take many trial-and-error attempts), especially so in CI environment (which doesn't have a display for you to see how the GUI tests executes).

Ok noted.

I'm using MacOS and the test can pass locally, not sure about Linux.
Do I have to use tools like Travis CI in order for build (ubuntu-latest) to pass? 
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/330#issuecomment-1272484206" expanded>

> @carriezhengjr From the codecov [documentation](https://docs.codecov.com/docs/commit-status#patch-status), it seems to suggest that the codecov/patch check checks for any test coverage for the new lines of code you've added for that particular commit/pr. i.e. the lines of code you've added in `HelpWindow.java` were uncovered as you have not added any tests for them, therefore it fails the check.
> 
> I also faced the same situation in my individual repo and my pr, and I think the reason why it's not flagged out in the pr is because that it does not run the codecov/patch, though it still flag it under the impacted files table. I could be wrong, but that's just my interpretation of it.

Oh I see! Did you resolve the issue in the end?
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/330#issuecomment-1272506910" expanded>

> Hmm, personally, I wouldn't see it as an critical issue per se but more of a warning. I have not resolved it, but I'm guessing that in the same commit/pr you just have to write test cases which tests the lines of code that you have written.
> 
> You might not know which lines of code that you have to test before making the commit. But once you fail the check you can use codecov to see the lines that's required of you to test. For your `HelpWindow.java` file, [here](https://app.codecov.io/gh/carriezhengjr/tp/commit/332f56579f48794b5a4c9f24280cc4bf895a28fc/src/main/java/seedu/address/ui/HelpWindow.java) are the lines u have to test.
> 
> Hope this helps!

Alright thank you 😄 !
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/330#issuecomment-1272507044" expanded>

> > Hmm, personally, I wouldn't see it as an critical issue per se but more of a warning.
> 
> Yup, the module doesn't have a specific code coverage bar to meet. It is up to you to use coverage info to improve your own testing. You are free to tweak CI settings for CodeCov, or even remove it from CI.

Ok thank you prof 😃 !
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/333#issuecomment-1272559572" expanded>

> > Do I have to use tools like Travis CI in order for build (ubuntu-latest) to pass?
> 
> @carriezhengjr AB4 uses Travis because GitHub actions did not exist at the time. Otherwise Travis plays the same role as GitHub Actions i.e., they are both CI platforms. That said, the Linux environment Travis provided back then might be different from the one GitHub actions provides now, which might make a difference for the tests.
> 
> In fact, we switched the CS2103 tP from AB4 to AB3 sometime back because of this kind issues caused by GUI tests (at the time AB3 was basically AB4 minus GUI tests).
> 
> If you eventually can't get it to work on Linux, you can skip those tests on Linux (GUI tests passing on 2/3 OS'es is better than nothing). Most importantly, given the time pressure of tP, don't let this issue affect your tP progress.

Yes, I also thought they are just tools for CI, but was not sure why the build could not be run successfully. 

Ok, thank you prof 😄 !
</panel>

</panel>


<panel type="info" header="### 15. POOM..APHA `@parnikkapore` (21 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How to tag a feature request**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/447" expanded>

Assuming I got a bug report that would be resolved by adding a new feature that is not a trivial change to the design of an existing feature (example from my project: collapsing multiple whitespaces in sequence in descriptions), this should be tagged as NotInScope, FeatureFlaw, and the corresponding severity level? Am I correct here?
</panel>

<panel  header="**2. :fas-info-circle: Lots of guard clauses and activity diagrams**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/446" expanded>

What's the best practice on drawing an activity diagram for a process with lots of guard clauses? Combining them into a single diamond loses information about the order that the checks are done (important if more than one fails), while writing multiple nested diamonds leads to large diagrams that look unwieldy.
</panel>

<panel  header="**3. :fas-info-circle: Library request: Natty**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/372" expanded>

## Library

[Natty Date Parser](https://mvnrepository.com/artifact/com.joestelmach/natty/0.13)

## Purpose

Used to implement natural date/time parsing for tP (The last one has some serious limitations, notably 1/2/2022 is parsed as M/D/Y without the possibility of adjusting it)

## License

[MIT](https://github.com/joestelmach/natty)

</panel>

<panel  header="**4. :fas-info-circle: 💡PSA: Survey submissions being edited are considered to be never submitted**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/334" expanded>

Yours truly had submitted one of the iP peer evaluations and then clicked "Modify previous submission" to use my response as a reference for the other submission. I thought that the last submission would be counted even if there's an edit in progress.

Well, I received a lovely email informing me otherwise 😅

Make sure that the button that appears when you attempt to reenter the survey says "modify previous submission", *not* "continue submission" or something like that.

@\Teaching_team : I have submitted the pending edit. Hopefully the script will pick it up.
</panel>

<panel  header="**5. :fas-info-circle: Library request: JChronic**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/175" expanded>

## Library

[JChronic](https://mvnrepository.com/artifact/com.rubiconproject.oss/jchronic)

## Purpose

Use the date parser to implement C-NaturalDates

## License

MIT - See https://github.com/samtingleff/jchronic

</panel>

<panel  header="**6. :fas-info-circle: [Week 6 quiz] Is the constructors activation bar required to be connected to the entity box?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/171" expanded>

Is the constructor's activation bar required to be connected to the entity box? All diagrams in the textbook excerpts have the bar connected, but the diagrams in the quiz have them disconnected.

Neither the textbook nor the video addresses this. I've looked at a few websites, and it looks like the representation of Java-style constructors is unspecified and there is no definite consensus on this point. I've seen both connected and disconnected bars on those sites.
</panel>

<panel  header="**7. :fas-info-circle: Accidentally picked Request changes during PR review**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/99" expanded>

I accidentally picked "Request changes" instead of "Comment" for both PR reviews I've made.

What should I do now?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/9#issuecomment-1216064641" expanded>

I just checked; GH is deprecating git auth via *the account password*. SSH does not seem to be affected.

I'm not sure how this works exactly, but you might need to change the remote repo path back to the one that starts with `https://` before following Carrie's method (to clone/pull using HTTPS instead of SSH).
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1219143551" expanded>

This is a test failure. EXPECTED.TXT is the expected (correct) output -  three blank lines (??), while ACTUAL.TXT is the actual output of your program - completely empty.

[Apparently](https://www.howtogeek.com/206123/) FC will say "no differences encountered" if there are no differences, i.e. a test pass.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/80#issuecomment-1229178507" expanded>

If the branches appear on GitHub, they have been pushed and the script should pick it up on the next update.

So far, I see:
* [branch-level-8](https://github.com/zylee348/ip/tree/branch-level-8) should be picked up by the next update
* branch-A-CodingStandard showed up as [heads/branch-A-CodingStandard](https://github.com/zylee348/ip/tree/heads/branch-A-CodingStandard) - this is definitely not right. I don't use SourceTree myself so I'm not sure what the recovery procedure is here.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/80#issuecomment-1229379104" expanded>

I had a look into the commit tree; branch-level-8 seems to have been merged into master using a fast-forward merge. I'm not sure if the script is looking for a merge commit...
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/99#issuecomment-1231044625" expanded>

Alright. Thank you!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/171#issuecomment-1243001234" expanded>

The problematic bar is the red bar on question 20. Judging by jhchee18's comment, I think I lost a point for this quiz 😁

Closing as answered.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/246#issuecomment-1250198702" expanded>

It looks like JavaFX and Wayland don't get along well. (It's a new Linux GUI system that  is used by default in Ubuntu 22.04.) I can run my jar under an X11 session no problem, but not under a Wayland session.

Agreed about bumping JavaFX version.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/372#issuecomment-1288341740" expanded>

Closing as this does not support DMY. None of the other libraries I've looked at does either.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/434#issuecomment-1308813102" expanded>

Just chiming in here that I thought that coding under coverage enforcement is a goal of the module, i.e. the CodeCov checks should not be removed from the CI (as it is one thing that could fail the workflow and invalidate the PR according to module policies; removing CodeCov would be circumvention under this lens). In the end, we did make it unable to affect the passing of the CI, but it took a while before that felt justified.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/446#issuecomment-1312656881" expanded>

Say, how to diagram this?
```java
String a(int n) {
  if (a < -10) return "!a";
  if (a > 10)  return "!b";
  if (a < 0)   return "-";
  if (a == 0)  return "0";
  if (a > 0)   return "+";
  else         return "?";
}
```
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/446#issuecomment-1312659163" expanded>

I think that would be the correct way too; in the context of the tp, we would have something like [index between 1 and INT_MAX is present but is larger than highest index in list] on one of the branches
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/462#issuecomment-1314726486" expanded>

I think this counts as a FeatureFlaw, yeah
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/453#issuecomment-1314753748" expanded>

I have a feeling that this strongly undermines the "please oh please round down your severity ratings" from the official instructions...
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/453#issuecomment-1315595572" expanded>

> For the PE, you can leave it in the same level the tester reported it if you wish (you are welcome to raise it too) -- the reason not to enforce it is: it would be unrealistic to expect that all teams would raise the severity level when the tester under-reported it.

Which means that it is beneficial to round up the severity rating when you're not sure, as this gives at least some chance for the higher level to make it to Phase 3. I understand that we are able to raise the rating on Phase 3, but the more eyes the adjustment goes through the safer it is.
</panel>

</panel>


<panel type="info" header="### 16. CHEN..IHAN `@rui-han-crh` (20 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: PE - Allowed Software (Virtual Machine Players)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/439" expanded>

My main machine is Windows, is a virtual machine player (specifically VMware Workstation 16 player) running Ubuntu 22.04 allowed for PE to test for cross platform compatibility?
</panel>

<panel  header="**2. :fas-info-circle: Requesting smoke test for MacOS/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/271" expanded>

Hi, here's my [release](https://github.com/rui-han-crh/ip/releases/tag/v1.0.4).

Here's my [user guide](https://rui-han-crh.github.io/ip/). The commands are a little longer because I have `D-Loans` implemented in this program.

Thanks in advance! :> (I hope it works 🙏 )

</panel>

<panel  header="**3. :fas-info-circle: Requesting Permission to use Jackson 2.10**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/257" expanded>

## Library

[jackson-databind](https://mvnrepository.com/artifact/com.fasterxml.jackson.core)
[jackson-datatype-jsr310](https://mvnrepository.com/artifact/com.fasterxml.jackson.datatype/jackson-datatype-jsr310)

## Purpose

Intended to be used for serialising and deserialising classes (jackson-databind) and Java Date and Time API objects (jackson-datatype-jsr310). I saw these were used in the tp source code to save and load data into json files and I wanted to use them for my ip.

## License

[Apache 2.0](https://mvnrepository.com/artifact/com.fasterxml.jackson.core/jackson-databind)

</panel>

<panel  header="**4. :fas-info-circle: Usage of anonymous expression syntax raising checkstyle issues**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/92" expanded>

The use of the lambda expression may erronously trigger the checkstyle issue `SeparatorWrap` that an opening bracket must begin on the previous line. The checkstyle rules seems to think that the two brackets belong to a function name from the previous line, when there is no function name at all.

```java
 return new InternalAction(
            String.format("Alright, I'll %s task %d", isMarking ? "mark" : "unmark", index + 1),
            //CHECKSTYLE.OFF: SeparatorWrap
            () -&gt; { // On this line, the () is interpreted to be part of continuing a function declaration
                currentTaskList.get(index).markJobState(isMarking);
                Duke.exitCurrentState();
            }
    );
}
```

Besides suppressing SeparatorWrap for every line that I have a lambda expression, is there a good way that I can perhaps modify the checkstyle rules such that it no longer raises issues for all anonymous functions?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/187#issuecomment-1246118965" expanded>

Hi, instead of adding the background image to the dialog box, which only takes up a fixed size in height as per your format, add it to the AnchorPane of the MainWindow, which takes up the dimensions of the program window itself.
```xml
<AnchorPane maxHeight="-Infinity" maxWidth="-Infinity" minHeight="-Infinity" minWidth="-Infinity"
            prefHeight="600.0" prefWidth="400.0" xmlns="http://javafx.com/javafx/8.0.171"
            xmlns:fx="http://javafx.com/fxml/1" fx:controller="duke.ui.MainWindow"
            style="-fx-background-image: url(./images/VBox-BG.png)">
...
</AnchorPane>
```

However, the background will now be obstructed by the solid white ScrollPane. To make the scroll pane transparent, add a css directory under the resources folder, then add a new css file in the css directory called ScrollPane.css and format it like so
```css
.scroll-pane{
   -fx-background-color:transparent;
}

.scroll-pane .viewport {
   -fx-background-color: transparent;
}
```

Now, we can reference this css file to the ScrollPane with 
```xml
<ScrollPane fx:id="scrollPane" hbarPolicy="NEVER" hvalue="1.0"
                    prefHeight="557.0" prefWidth="400.0" vvalue="1.0" fitToWidth="true"
                    AnchorPane.leftAnchor="1.0" AnchorPane.rightAnchor="1.0"
                    AnchorPane.bottomAnchor="41.0" AnchorPane.topAnchor="1.0"
                    stylesheets="@../css/ScrollPane.css">
...
</ScrollPane>
```

This will hide the Scrollpane's opacity. So, now you can see your background

![image](https://user-images.githubusercontent.com/15359033/190039923-7415e725-2cb5-404b-8463-e7710309ef74.png)


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/189#issuecomment-1246584000" expanded>

Hi, I could launch your file with no issues (apart from the single warning related to JavaFX versions). I'm not exactly sure what is being typed into the terminal, but I'm suspecting that the input may have been typed as 

```
java duke.Launcher
```
which will throw a ClassNotFoundException
```
Error: Could not find or load main class duke.Launcher
Caused by: java.lang.ClassNotFoundException: duke.Launcher
```


Instead, in the terminal, use `cd` to navigate to the libs folder (after exporting with `gradle shadowJar`):
```
cd build/libs
```

then do:

```
java -jar duke.Launcher.jar
```

Alternatively, we can also do
```
java -jar build/libs/duke.Launcher.jar
```
from the topmost level directory. (The name of the jar file is `duke.Launcher`, if you want to change its name, it's in the `build.gradle` file under the `shadowJar` section -&gt; `archiveBaseName`)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251014745" expanded>

I've tried opening the file on two computers, but the jar file won't open. 

Using `java -jar ip.jar` gives `no main manifest attribute, in ip.jar`. Double clicking the file doesn't open the file either.

I took a look at your `build.gradle` file, you've set `mainClassName` under `application` to `seedu.duke.Duke`. Try changing this to your package names and launcher class. For example, for mine, my entry point is the Launcher class in the dukeprogram package, so my `mainClassName` is `dukeprogram.Launcher`.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/265#issuecomment-1251112304" expanded>

> It creates a text file `help.txt` right away and the application doesn't open on my end. Let me see what happens and get back to you.

@RussellDash332 
Yea I told Darren it's presently an issue with event and deadline tasks not being able to be deserialised from single word names. If we try
```
deadline abc /by 2022-12-12
```
or
```
event abc /at 2022-12-12
```
Both will stop the jar file from opening again, but names with more than two letters work properly, like

```
deadline watch lecture /by 2022-12-12
```
or
```
event eat food yum /at 2022-12-12
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/281#issuecomment-1252848176" expanded>

Hi, I'm running a Linux (Ubuntu) VM.

Currently, the images do not show on Ubuntu:
<img src="https://user-images.githubusercontent.com/15359033/191352006-71dd0829-3722-488a-95e8-6809cbf3ba59.png" width="300">

I took a look at your resources folder and this is likely because your images are in the `jpeg` format. Try converting your images into `png` format for them to appear on Linux. Reference to #217 [relevant fix](https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249137283).

For some reason, the `bye` command doesn't close the program, I have to manually close it myself.

There seems to be an issue with the vertical height of the dialog box not expanding past its fixed height. It doesn't seem to be able to display more than 4 or 5 tasks, even though the tasks exist.

<img src="https://user-images.githubusercontent.com/15359033/191355151-99617325-f55b-48b7-991c-baf567d80f51.png" width="300">

Other than that, the program works fine. The window is resizable though, but the dimensions of the scroll pane don't follow, maybe lock the screen size, or anchor the scrollpane, submit button and text field to the relevant corners of the window so they follow the window dimensions.

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/271#issuecomment-1252850882" expanded>

@sltsheryl thanks for the test and feedback!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280#issuecomment-1252872297" expanded>

HI, I'm running a Linux (Ubuntu) VM.

<img src="https://user-images.githubusercontent.com/15359033/191357441-2d81ca2b-5da7-43c7-b4c5-bd2b38f6221f.png" width="300">


All operations work fine. However, the profile picture for the responder doesn't appear. It's likely due to the image that it uses,`ManSmilingBehindWall.jpg`, being in the `jpg` format. Try converting this image to `png` for it to show on Linux machines. Reference to issue #217.

By the way. on Ubuntu 22.04.1, there's an issue with the JAR file not opening on double clicking, it can only opened upon forcing it with

```
java -Djdk.gtk.version=2 -jar jude-0.3.jar
```

It's an issue relevant to #246. Updating the `javaFxVersion` string in the `dependencies` block of the `build.gradle` file from `11` to `11.0.2` may fix this.

</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/271#issuecomment-1253282139" expanded>

@Yongbeom-Kim Thanks! 

I wrote that error message for corruption detection if the save file cannot be detected properly. It should go away if the application is opened after the initial start (since now the save file exists) and should only appear on initial start up. I'm saving to the `user.home` directory, I should have write permissions to the home directory on most machines, if I’m not wrong

Writing the images to the save file is a feature! Try changing the Duke.png or User.png images to any pictures of your choice to customise the profiles (the file names must remain the same), this feature can be read more about [here](https://rui-han-crh.github.io/ip/#setting-profile-pictures).
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/271#issuecomment-1253282942" expanded>

Thank you all for the tests!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/284#issuecomment-1253378942" expanded>

Hi, InvocationTargetException is usually caused by javafx throwing another exception on top of an exception that your program threw. In this case, it seems there is a missing check that the array of elements needed to construct a Deadline must be more than 1 when invoking the creation of a new Deadline.

On line 221 of the `TaskList` class, it is assumed that `deadlineComponents` will contain elements 0 and 1 when split by the `/by` delimiter. But with outputs that don't contain the `/by` delimiter, there is only 1 element, so index 1 doesn't exist.

This throws an ArrayIndexOutOfBoundsException in the main program. JavaFX detects this and throws another InvocationTargetException, because it is unable to finish the call with reflection. Usually InvocationTargetExceptions are wrapping exceptions that wraps around another more specific exception.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/287#issuecomment-1254424589" expanded>

I can suggest two other ways to do this, 

Firstly, we may use `Platform.exit()`, which executes as a non-blocking code. The execution passes through the line containing `Platform.exit()` as prepares to close the application but still allows following code to be executed. Then we may call `System.exit(0)` under the `Application::launch` method

```java
private String leaveProgram() {
    Platform.exit();
    return "bye"
}
```

called within some other method

```java
    String byeString = leaveProgram();
    System.out.println(byeString) // We may observe this line to be executed, despite Platform::exit being called previously
```

Then we close the program after the launch method in the `Launcher` class

```java
public static void main(String[] args) {
    Application.launch(Main.class, args);
    System.exit(0); //Exit program with status 0
    System.out.println("This line will not be printed");
}
```

Also, note that Platform.exit() will call `Main::exit`, if it exists, so we can also perform any additional cleanup right before the close in this method, if we have any.

```java
public class Main extends Application {
    public void stop() {
        System.out.println("Preparing to stop");
    }
    ...
}
```


The second way is that we use a `Timer` object to close the application after a period of time has passed. For example, if I have something to do that I know can be completed under 2 seconds, we can do

```java
    new Timer().schedule(new TimerTask() {
        @Override
        public void run() {
            Platform.exit();
            System.exit(0);
        }
    }, 2000);
    System.out.println("Closing program after 2 seconds");
```

The above will close the program after 2000 milliseconds, but will still allow any actions after to be performed up to the 2 seconds.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280#issuecomment-1254450953" expanded>

@cheeheng 

The images are working well now. I'm personally still not able to double click to open and must still use `-Djdk.gtk.version=2` but maybe this is just a thing on Ubuntu 22.04. But everything else looks and works fine now.

![image](https://user-images.githubusercontent.com/15359033/191647366-c818d1ff-672e-4dc4-9f8b-5b322976f383.png)

</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/298#issuecomment-1255811396" expanded>

Can you try `Ctrl-Shift-A` or go to the Help in the task bar on top and press the `Find Action` tab and try typing `gradle` into the help bar here

![image](https://user-images.githubusercontent.com/15359033/191896379-26f0ab65-0308-4659-a400-f8e93dcec3e4.png)

Select this elephant icon and a new tab should appear

![image](https://user-images.githubusercontent.com/15359033/191896431-46074456-0d2c-49c7-b476-8932bef468d0.png)

Press the elephant icon here for execute gradle task and try `clean shadowJar`

![image](https://user-images.githubusercontent.com/15359033/191896546-a597ee6f-2e60-4bec-a5ea-e9981ce48d70.png)

Select the first option. (Clean shadowJar will delete your existing built files and rebuild from a cleaned folder again)

EDIT:
Okay, the `./gradlew` command has to be executed from where the gradlew file is in the directory. In this care it's in your root directory, but you're currently somewhere deeper in the libs directory. Try going back up to the root directory where your gradlew file is, (I think it's ipNew, check by `ls` to see the file exists in this directory) and run `./gradlew` commands from there
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1257134688" expanded>

On Linux (Ubuntu) VM, everything works properly with reference to your user guide, no images issues. Although, I'm not sure if the font has loaded properly, it looks a bit different from the images on top.

<img src="https://user-images.githubusercontent.com/15359033/192132053-42c6e581-c7d4-47c1-baca-565ad9abfbf4.png" widht = "300">


But there is an issue with the jar file not opening properly on double clicking or using the plain `java -jar` command, it's a Wayland compatibility issue on Ubuntu 22.04 with JavaFX 11. With `java -Djdk.gtk.version=2 -jar NyanDuke.jar`, it opens normally.

![image](https://user-images.githubusercontent.com/15359033/192131915-5a4ea57e-1778-47f0-a2a0-d195d0698689.png)

Try upgrading your version by replacing `String javaFxVersion = '11'` under the `dependencies` section in your `build.gradle` file with `String javaFxVersion = '11.0.2'`. This usually fixes this error.
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1257719946" expanded>

@waynezsy 
All good now, double clicking now works and the program runs and saves as normal.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/439#issuecomment-1310124848" expanded>

Thank you!
</panel>

</panel>


<panel type="info" header="### 17. GREG..OONG `@SpecOps2016` (18 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Push keeps failing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/297" expanded>


![image](https://user-images.githubusercontent.com/76586680/191930929-1959c19a-2ae0-4455-b129-857850d01dad.png)

I keep getting this error message whenever I try to push on SourceTree.

If someone can help me with this I woudl greatly appreciate it. Thanks!
</panel>

<panel  header="**2. :fas-info-circle: Request for smoke test help (MacOS, Linux, Windows)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/294" expanded>

I would appreicate it if someone can help me test my Duke,jar file on Linux, Windows and macOS. Thank you!

The link to my jar file can be found here: https://github.com/SpecOps2016/ip/releases/tag/A-Releases
</panel>

<panel  header="**3. :fas-info-circle: JavaFX Error running JAR file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/283" expanded>

![image](https://user-images.githubusercontent.com/76586680/191409372-0717aec7-3e8c-46db-b1a4-dd06ec0cf77d.png)

Hi I am having this problem when running the JAR file.

Anyone can help on this? Thanks!
</panel>

<panel  header="**4. :fas-info-circle: Gradle Test Cases**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/100" expanded>


![image](https://user-images.githubusercontent.com/76586680/187235859-78a0f00d-7336-408a-a46b-cc8cf091f354.png)
Hi I am unable to run test cases with Gradle. Can anyone help me with this?

</panel>

<panel  header="**5. :fas-info-circle: Editing commit message after it is pushed**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/97" expanded>

How do we edit commit messages that have been pushed?
</panel>

<panel  header="**6. :fas-info-circle: A-TextUiTesting**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24" expanded>

![image](https://user-images.githubusercontent.com/76586680/185320487-1031a7d1-3a2c-4000-bf69-a0310917eecd.png)

Can someone tell me whether this indicates whether the test has passed or failed? I am running this on Windows

</panel>

<panel  header="**7. :fas-info-circle: Question on Level-2 of the project**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/10" expanded>


We are told to use Arrays to store the items. Are we permitted to use ArrayList instead for Level-2? Thank you!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/10#issuecomment-1217705942" expanded>

Thank you!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1219137466" expanded>

Yes I did
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1219293589" expanded>

![image](https://user-images.githubusercontent.com/76586680/185368142-49e1efcc-08a7-4252-a054-8db1628d2749.png)
Any reason why EXPECTED.TXT is showing up as three blank lines?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1219295231" expanded>

![image](https://user-images.githubusercontent.com/76586680/185368556-ffe59312-3e09-4554-91c7-0f80187e77f6.png)
This is my input.txt
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1221229866" expanded>

> I think the issue here is that both `diff` and `fc` are really not suited to comparing differences between the two .txt files. What I found worked for me is right clicking the file in intellij, then select `Compare With`, and compare the ACTUAL.txt to EXPECTED.txt ![image](https://user-images.githubusercontent.com/46131429/185444280-b99256df-4b1f-40db-a056-3e364b05c5a2.png)

Thank you! This helped with my issue.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/100#issuecomment-1230637980" expanded>

> try renaming `tests` folder to `test`

Thanks this helped!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/283#issuecomment-1253177382" expanded>

it worked. Thanks!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/294#issuecomment-1255775720" expanded>

Thank you guys! I have fixed some of the bugs. Would appreciate it if yall can run it again :)
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/297#issuecomment-1255985144" expanded>

My apologies. I have updated the post. Thank you!
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/294#issuecomment-1255987719" expanded>

@Yongbeom-Kim I have updated my JavaFX. I would appreciate it if you can run it again. Thank you!
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/297#issuecomment-1256115858" expanded>

Thanks! Solved
</panel>

</panel>


<panel type="info" header="### 18. GUOK.. JIE `@guokweijie` (18 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for help for smoke testing on Linux and Mac OS**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273" expanded>

need help for smoke testing on these 2 platforms, help is much appreciated!!

[here](https://github.com/guokweijie/ip/releases/tag/v0.2(fixed))

</panel>

<panel  header="**2. :fas-info-circle: Request for help with smoke test errors**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/272" expanded>

hi guys, did anyone experience these errors and possibly know how to fix them? These errors were found with the automated smoke test from the teaching team.

On Linux, using Java 11, for the duke.jar uploaded on 09-16-2022 (MM-DD-YYYY) at 23:21:45:
Sep 20, 2022 2:56:13 PM com.sun.javafx.application.PlatformImpl startup WARNING: Unsupported JavaFX configuration: classes were loaded from \'unnamed module @2b3f0ec9\' Graphics Device initialization failed for : es2, sw Error initializing QuantumRenderer: no suitable pipeline found java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:283) at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:253) at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:266) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:291) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:163) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:659) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:679) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:196) at java.base/java.lang.Thread.run(Thread.java:829) Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:95) at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:125) ... 1 more Exception in thread "main" java.lang.RuntimeException: No toolkit found at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:278) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:291) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:163) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:659) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:679) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:196) at java.base/java.lang.Thread.run(Thread.java:829)

On Mac, using Java 11, for the duke.jar uploaded on 09-16-2022 (MM-DD-YYYY) at 23:21:45:
Sep 20, 2022 2:40:53 PM com.sun.javafx.application.PlatformImpl startup WARNING: Unsupported JavaFX configuration: classes were loaded from \'unnamed module @b3b47b3\' Graphics Device initialization failed for : es2, sw Error initializing QuantumRenderer: no suitable pipeline found java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:283) at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:253) at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:266) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:291) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:163) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:659) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:679) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:196) at java.base/java.lang.Thread.run(Thread.java:834) Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:95) at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:125) ... 1 more Exception in thread "main" java.lang.RuntimeException: No toolkit found at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:278) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:291) at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:163) at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:659) at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:679) at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:196) at java.base/java.lang.Thread.run(Thread.java:834)
</panel>

<panel  header="**3. :fas-info-circle: is it ok to have 2 constructors each for event and deadline classes?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/201" expanded>

if I want to create 2 different constructors each for event and deadline class, one type for creating the task when loading the task from the text file and the other type for creating the task when the user inputs, will this break any oop principles?
</panel>

<panel  header="**4. :fas-info-circle: duke package error in intellij**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/108" expanded>

![photo_2022-08-30_01-42-03](https://user-images.githubusercontent.com/66172460/187345754-3900035c-2d8b-444e-b476-09f9aa4dd3b9.jpg)

hi, does anyone know why intellij has this red underline under the package duke when I try to put my test classes in the same package as my main classes?  it tells me to move the test classes into the same package.

does this matter as long as i can access the classes in the duke package?
</panel>

<panel  header="**5. :fas-info-circle: Unable to commit on Sourcetree on a different laptop**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/63" expanded>

hi everyone, i got this error when trying to make a commit on sourcetree and I am unable to make the commits.

git -c diff.mnemonicprefix=false -c core.quotepath=false --no-optional-locks commit -q -F C:\Users\guokw\AppData\Local\Temp\vt5wabz0.avy
fatal: cannot update the ref 'HEAD': unable to append to '.git/logs/HEAD': Invalid argument
Completed with errors, see above.

does anyone happen to know what this means? I just downloaded Sourcetree, and downloaded Git on Intellij and made changes on my iP on a new laptop today, if it affects because its not the original device.
</panel>

<panel  header="**6. :fas-info-circle: In-Video Quizzes Participation points**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/45" expanded>

Hi, can I ask if our scores in the in-video quizzes of the videos in the textbook affect the amount of participation marks that we get? Or do we get the 2 bonus points as long as we answer all of the questions in the quizzes?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/45#issuecomment-1221553879" expanded>

@damithc ok thank you Prof!

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/63#issuecomment-1226092334" expanded>

update: i cloned from my own iP repo onto my new device and copied over the changes i made and now i can commit. this is probably because of my change of device and transferring of files by onedrive?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/63#issuecomment-1227994222" expanded>

Thank you seniors! @domlimm @pyk595 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/108#issuecomment-1231117819" expanded>

> 

![image](https://user-images.githubusercontent.com/66172460/187347335-9966cbd6-39a9-4efb-b00c-ed85b7eb0131.png)

but if I create a duke package again under test directory, when i run the test, it says test no-source?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/108#issuecomment-1231124420" expanded>

> You might need to modify `build.gradle` as well as the Gradle setup in the project accordingly

oh i rebuilded the different components of the gradle project manually and now it works! thank you!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/272#issuecomment-1252384685" expanded>

> Try #213, removing the javafx block from build.gradle?

yes i just did, seems to work fine now on mac and windows, how do i know if these errors still exist tho?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/272#issuecomment-1253133516" expanded>

> > yes i just did, seems to work fine now on mac and windows, how do i know if these errors still exist tho?
> 
> 
> 
> If the JAR can work on all three OS'es, should be OK. If not sure, you can ask here for someone to help test your JAR on a specific OS.

hi prof, I tried on windows and mac os which worked fine but somehow the automated smoke test from the teaching team identified errors when opening for mac os and linux. that said, how do I know now if it would work with mac os and linux if my app still doesn't give any error messages when i test myself?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1253439961" expanded>

hi prof, can I check if the resizing of window is a requirement? @Yongbeom-Kim i checked with my friend on linux and he can run using java -jar duke.jar
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1255321928" expanded>

> @guokweijie sflr! I added the comment because if you're not planning to support resizing, then it can be disabled with `stage.setResizable(false);`
> 
> I tried again, it doesn't work. Which linux distro is your friend on? I'm on Ubuntu 20.04.5 - seems to be a ubuntu-specific problem. Bumping JavaFX version should solve the issue
> 
> EDIT: Sorry, the resizing thing looks like a linux-specific thing? For some reason ubuntu still lets me resize apps that are set to not-resizable, my bad. ignore that part

hi, do u happen to know which version of JavaFX I need to bump to to make it work?
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1255744706" expanded>

hi, i have updated my javaFx version to 11.0.2 in my build gradle, could you help to test if this works now? @Yongbeom-Kim 
[smoke testing.zip](https://github.com/nus-cs2103-AY2223S1/forum/files/9630452/smoke.testing.zip)

</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/273#issuecomment-1258915921" expanded>

thank you! @Yongbeom-Kim @damithc 
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/272#issuecomment-1258916052" expanded>

thank you prof!
</panel>

</panel>


<panel type="info" header="### 19. KANG..NHAN `@onepersonhere` (17 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: UG Draft is not captured accurately**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/397" expanded>

![image](https://user-images.githubusercontent.com/51043502/198876083-845709b3-3f7e-4cfc-82fe-eadc42b1de76.png)
This is reflected in the tP progress Dashboard even though I have added more than 3 lines to the UG in week 11.
Will I be penalised in terms of grade?
</panel>

<panel  header="**2. :fas-info-circle: Set minimum window size?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/396" expanded>

![image](https://user-images.githubusercontent.com/51043502/198872035-5ffd7ded-a4e4-4fca-96d2-646cd6e1f188.png)

Can we set a minimum window size? (Also what is the recommended minimum size)
This is to address this form of bug reports so as to prevent them from appearing in the PE. Not really sure if it is considered a feature flaw since the string is not that long (it's just the window being too small!)
</panel>

<panel  header="**3. :fas-info-circle: Clarification on Constraint-Typing-Preferred**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/386" expanded>

Is it okay to use a GUI input for the help screen? This is so that all the commands are listed and the user is able to find the commands and not refer to the User Guide.
This is how it is implemented:
![image](https://user-images.githubusercontent.com/51043502/198421076-0d7c4b61-5144-4a25-bf48-e91dd0ab518b.png)

Thank you for your feedback!
</panel>

<panel  header="**4. :fas-info-circle: IP progress dashboard updates**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/136" expanded>

I have completed the task "Use GFMD", may I know when will the dashboard be updated?
</panel>

<panel  header="**5. :fas-info-circle: Application crashed after running Launcher class**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/88" expanded>

Details:
* Intellij ver 2022.2.1 Ultimate Edition Build #IU-222.3739.54
* Using temurin-11 Eclipse version 11.0.15
* Windows 11

```java
// Under Launcher Class
public class Launcher {
    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }
}

//Under Duke Class
@Override
public void start(Stage stage) throws Exception {
    Label helloWorld = new Label("Hello World!"); // Creating a new Label control
    Scene scene = new Scene(helloWorld); // Setting the scene to be our Label

    stage.setScene(scene); // Setting the stage to show our screen
    stage.show(); // Render the stage.
}
```

Error stacktrace
```
Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class duke.Duke
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:890)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.NoSuchMethodException: duke.Duke.<init>()
	at java.base/java.lang.Class.getConstructor0(Class.java:3349)
Caused by: java.lang.NoSuchMethodException: duke.Duke.<init>()

	at java.base/java.lang.Class.getConstructor(Class.java:2151)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:801)
	at com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
	at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
	at com.sun.glass.ui.win.WinApplication._runLoop(Native Method)
	at com.sun.glass.ui.win.WinApplication.lambda$runLoop$3(WinApplication.java:174)
	... 1 more

Execution failed for task ':Launcher.main()'.
```

`Caused by: java.lang.NoSuchMethodException: duke.Duke.<init>()`

Anyone has any ideas?
I tried following past [solutions](https://github.com/nus-cs2103-AY1920S2/forum/issues/31) provided by hanming but did not resolve it.

</panel>

<panel  header="**6. :fas-info-circle: Can we amend commits but maintain the same SHA id?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/40" expanded>

I encountered this problem whereby I tagged the unamended, unpushed commit with a tag, then I amend the commit, causing it to disappear on github desktop.
 
Afterwards I tried to tag the amended commit but was unsuccessful because the tag was assigned to the original commit. 

I was able to delete the original tag and the unamended commit through Git Bash, however I felt that this is too much work for just amending a single commit and expecting the tag to be retagged on it.

Therefore, I was wondering if there is any commands/ways where we can change the title/description of the commit without changing the SHA of the commit?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/40#issuecomment-1221241299" expanded>

> The question is answered [here](https://stackoverflow.com/questions/23791999/why-does-git-commit-amend-change-the-hash-even-if-i-dont-make-any-changes).
> 
> However, you can force push the tags because they are just your own bookmarks for the project, and just add a new commit instead of overwriting the previous one.
> 
```
> git tag -f Level-x
> git push -f --tags
```
> 
> (assuming you only want to change the tag)

Hi. Does the answer suggests that the only way to change the title or description of the commit is to create a new commit with a different timestamp? 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/40#issuecomment-1221243764" expanded>

> > Hi. Does the answer suggests that the only way to change the title or description of the commit is to create a new commit with a different timestamp?
> 
> You mean the same timestamp, in order not to change the commit ID? I believe so.

Ah I see thanks. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/88#issuecomment-1229170514" expanded>

Solved it by providing a default constructor for Duke.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/136#issuecomment-1236052137" expanded>

Thanks @sikai00 , may I know if there are penalty for late submission?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/136#issuecomment-1236066956" expanded>

Thanks!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/386#issuecomment-1294525397" expanded>

Thanks prof!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/396#issuecomment-1296196938" expanded>

Thanks prof!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/397#issuecomment-1296269659" expanded>

Hi prof @damithc, I checked the RepoSense according to this [link](https://nus-cs2103-ay2223s1.github.io/tp-dashboard/?search=onepersonhere&sort=groupTitle&sortWithin=title&timeframe=day&mergegroup=&groupSelect=groupByRepos&breakdown=true&checkedFileTypes=docs&since=2022-10-22&tabOpen=true&tabType=zoom&until=2022-10-28&zFR=false&zA=onepersonhere&zR=AY2223S1-CS2103T-T10-4%2Ftp%5Bmaster%5D&zACS=4&zS=2022-10-22&zFS=onepersonhere&zU=2022-10-28&zMG=false&zFTF=day&zFGS=groupByRepos): 


![image](https://user-images.githubusercontent.com/51043502/198883002-d70a1706-3791-491f-8081-2153d145d521.png)

I think my teammate has overridden my commit according to the commit history, however the RepoSense seems to detect it but not the dashboard script? (not really sure how it works)

Is there a possible way to fix it on my side since I can't find a way to assign the @@author tag in markdown for UG?
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/397#issuecomment-1296288605" expanded>

Thanks prof! I will try it out hopefully RepoSense will detect it.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/397#issuecomment-1297105893" expanded>

Hi prof @damithc , 
I added the @@author tag and the RepoSense is able to assign the lines to me:
![image](https://user-images.githubusercontent.com/51043502/199020405-7f922403-d2c3-4d42-ad97-125d56af85b0.png)

However, I waited after the daily refresh of the tP progress dashboard but it still says the same thing unfortunately :(
![image](https://user-images.githubusercontent.com/51043502/199020943-25c3d60b-02c0-432f-b96b-c5490a9ae644.png)

Is there a way to fix the tag on the tP progress dashboard?
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/397#issuecomment-1297205632" expanded>

Thanks prof!
</panel>

</panel>


<panel type="info" header="### 20. LIN ..CHEN `@Bubbl3T` (17 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: CI unsuccessful IO redirection test due to file not found error**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/243" expanded>

My Gradle can't seem to find my Java files, anyone knows how to solve this?
[Here](https://github.com/Bubbl3T/ip) is my repository, any help is appreciated!

![image](https://user-images.githubusercontent.com/72196376/190849813-db8805a6-f7d4-4c35-8f19-9dae71a88f6b.png)


</panel>

<panel  header="**2. :fas-info-circle: Jar file not creating `data` folder on Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199" expanded>

Hi, does anyone face the same issue with your jar file running fine on Windows but not creating a `data` folder at the location on Mac? If that happens, does anyone have an idea where the problem may lie?

Also, while the data folder is not created, the data is still stored correctly and is still there when the application close and reopens. Anyone knows where the data folder went? Thank you!
</panel>

<panel  header="**3. :fas-info-circle: Unable to retake in-video quiz for W3.5b**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/41" expanded>

There seems to be a problem with trying to retake the quiz for questions in the video under the topic W3.5b. Is this intentional or just a bug?

![image](https://user-images.githubusercontent.com/72196376/185751381-7e199b6d-681d-44f5-8077-e9590067dca9.png)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1234343919" expanded>

Changes:

* Add icon to application.
* Change user and duke photos.
* Change title of application.
* Keep original UI feature of Duke greeting the user on start.

![image](https://user-images.githubusercontent.com/72196376/187936165-d091f4e9-662c-456c-8583-74b60818fde0.png)


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/129#issuecomment-1236086582" expanded>

I think this is a pretty great idea if it works! As long as you can manage your classes in a way that minimal edits are required for future updates, (e.g. add a new command or reply a with a different String), doing it this way has almost no downsides.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/138#issuecomment-1236088729" expanded>

Have you tried to build the JAR file using IntelliJ instead of Gradle?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/125#issuecomment-1236091220" expanded>

I faced the same issue and managed to resolve with Prof Damith's @damithc fix. 😄 Just remember to change the project SDK in IntelliJ to the downloaded version.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/198#issuecomment-1248026742" expanded>

You are probably still running the old java version on your terminal. I face the same issue before and you can try these few steps
1. Go to terminal and type `java -version` to check what java version you are running with
1. If the java version is not the desired version, go to `Macintosh HD > Library > Java > JavaVirtualMachines` and you should a few java versions.
1. Let's say you want to disable your jdk-11.0.13.jdk, from where you are, go to `jdk-11.0.13.jdk > Contents` and find the file called `Info.plist`, rename it to `Info.plist.disabled`

That should be enough for you to disable your that version of java and for your computer to detect the zulu version of java.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/192#issuecomment-1248037773" expanded>

Yep, works on macOS. However, I do notice that running the `list` command cause all the tasks to display in one line instead of displaying them on separate lines. Not sure if this is intended or not, but just pointing out for your information.

Also, your code running on macOS face the same issue of not creating a data file at the file location. I am facing the same issue now and still looking for solution. Do follow the other thread [here](https://github.com/nus-cs2103-AY2223S1/forum/issues/199).
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199#issuecomment-1248059480" expanded>

![image](https://user-images.githubusercontent.com/72196376/190408123-93b9a45e-6fb7-4542-b656-c27702ca0713.png)

Further investigations show that this is where the data file is. Will look into it to see if an actual fix can be found.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199#issuecomment-1248155596" expanded>

> > `private static final Path DIRECTORY_PATH = Paths.get(System.getProperty("user.dir"), "data");`
> 
> Try replacing the `System.getProperty("user.dir")` with a `"."`. The `"user.dir"` on OSX is not defined properly. With `"."` you will be getting the location from where the jar was executed. So, if you call `java -jar folder/duke.jar`, the data folder will be `./data` not `./folder/data`. There is also a way to get [the location of the jar file](https://stackoverflow.com/questions/320542/how-to-get-the-path-of-a-running-jar-file), but that is a bit more complex.

<img width="702" alt="image" src="https://user-images.githubusercontent.com/72196376/190425465-00568512-4126-4801-9a37-665287318b76.png">
Tried your suggested fix, this is what is happening now. The path kinda changed, but there is still no folder created. My program somehow still reference to the same old data file even if I move it around to other folders.

It works fine on Windows and Linux, just having some problems with Mac. I guess Mac just likes to do things differently lol.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199#issuecomment-1248156701" expanded>

@ryanlml Yeah I have already done that, but still thanks for the suggestion! \:D
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199#issuecomment-1249005089" expanded>

@damithc Thanks prof, this helped! By opening the jar file using the command `java -jar &gt;FILE_NAME>` it created a data folder and data file successfully. :)
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/213#issuecomment-1249013948" expanded>

Testing on macOS, able to open file with double click.

For your Mac, you can try to right-click your jar file and hover over the "Open With" option to see if you are opening jar files with JavaLauncher as default.

For your Windows, not exactly sure why this happens, but you might consider checking if you have javafx (not just java) properly installed and used as the default java version. Else, you can try to copy-paste the error message onto google and try your luck.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/201#issuecomment-1249018208" expanded>

Sounds undesirable to me. I feel that if you are already able to determine which of the 3 types of task to create, why not just continue to parse the remaining strings from where you are? Especially when an event and deadline have so many things in common, you might be better off with creating a method to parse the description and date-time directly from the storage and creating a task from that instead, so you do not have too many repeated code too.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/243#issuecomment-1250073515" expanded>

@RussellDash332 Yep this works! I guess this happened because I did not make changes here when I refactored duke. Thanks for the detailed help! 😄

Now I at least I know where to debug the program. Let me just fix some minor issues and I should be done :)

![image](https://user-images.githubusercontent.com/72196376/190859817-0656f3ae-6a7e-4472-858a-5e7b9edf6cd5.png)
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/243#issuecomment-1250075384" expanded>

Yeah, but because I kinda removed the text UI features, I guess I won't be able to run this without errors now :( But well, at least learnt something new, thanks! :)
</panel>

</panel>


<panel type="info" header="### 21. TAN .. WEI `@malwaregarry` (17 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Question on system testing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/494" expanded>

Hi, I would like to ask if system testing is done with access to the source code. 
As system testing is done internally, it makes sense that the testers would have access to the code. At the same time, the test cases are based on external behaviour, implying that they do not care about how the functionality is implemented.

Thanks in advance!

Excerpt on system testing from the textbook:
> System test cases are based on the specified external behavior of the system. Sometimes, system tests go beyond the bounds defined in the specification. This is useful when testing that the system fails 'gracefully' when pushed beyond its limits.


</panel>

<panel  header="**2. :fas-info-circle: Question about entry/exit coverage**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/323" expanded>

Hi, I would like seek clarification on what is meant by entry/exit coverage.

![image](https://user-images.githubusercontent.com/43949290/193392936-b44b2200-ef7e-47f8-97ef-b141291a34b8.png)

Does all _possible calls_ mean all possible values the parameter of the function can have? 
Or does it mean all control paths that can be taken? In this case what's the difference between this and path coverage?

Thanks!



</panel>

<panel  header="**3. :fas-info-circle: Question about association, composition and aggregation**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/86" expanded>

Hi, I have a question about the topics for this week: are compositions and aggregation more specific forms of associations? or are they different?

</panel>

<panel  header="**4. :fas-info-circle: JavaDoc comments**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/44" expanded>

Hi, would like to ask if JavaDoc comments for methods should be written before or after decorators:

Before
```java
/**
* Displays exit message.
*/
@Override
public void execute() {
```
After
```java
@Override
/**
* Displays exit message.
*/
public void execute() {
```

Which is correct / better? 

Thanks in advance!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/85#issuecomment-1229167650" expanded>

Hi, your diagram looks good to me. The default visibility modifier (when nothing is specific) is package private. 
Also, since ```wheels``` is a  ```List```, you can signify that it is a collection by appending square brackets to the label:
```
- wheels[]
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232597841" expanded>

This is mine. Exactly the same as the JavaFX tutorial except that the resizing issues are fixed.
![image](https://user-images.githubusercontent.com/43949290/187624778-b3a96942-c4a8-41d0-b968-7e3fca1d2910.png)

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232930653" expanded>

Hi, try building your app to ensure all dependencies are installed?

either `./gradlew build` or `gradlew build`
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232981620" expanded>

hmm, maybe try `./gradlew clean build`? Also what JDK version are you? You can check in `File > Project Structure > Project` under SDK

Update: also check the JDK you are using for gradle JVM:
![image](https://user-images.githubusercontent.com/43949290/187698168-67ffd0fb-b849-424a-aeb2-86f6f7b5218a.png)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/118#issuecomment-1233711184" expanded>

> * A common cause of  `Unable to open DISPLAY` is using an environment that doesn't support GUI applications. At least some versions of WSL don't support GUI applications.

I agree that it could be a WSL error. WSLg is currently only for Windows 11 so you might need to run the application on your Windows system. 


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/86#issuecomment-1233712753" expanded>

@damithc Thanks prof. I closed the issue as there wasn't any disagreements with @nealetham.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/120#issuecomment-1233941368" expanded>

Hi, can you upload your `build.gradle` file?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/120#issuecomment-1234069049" expanded>

Hi @JordanChua, your images are in `jpg` not `png`.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/153#issuecomment-1242739372" expanded>

Thanks @Hongyi6328! This looks great so clean. Will try to replace my `switch-case` statements with this.  
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/322#issuecomment-1264241015" expanded>

Hi, had a quick look at your website. I think the problem is that clicking on the Github logo on the top right is not linking to your team's Github repo
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/495#issuecomment-1326150238" expanded>

A similar diagram was demonstrated in the week 8 tutorial.
![image](https://user-images.githubusercontent.com/43949290/203739568-701bf132-ed26-4999-a34f-d36c7b92081b.png)

If I'm not wrong, the reason for not leaving `update()` in the abstract class is to signal that the `update()` method originated from the interface.

</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/494#issuecomment-1326153723" expanded>

@damithc Thank you prof for the explanation! I guess testing the whole system with knowledge of the code could be better considered as integration testing (of the whole system)?
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/494#issuecomment-1326398976" expanded>

I see, thank you
</panel>

</panel>


<panel type="info" header="### 22. RICH..NICK `@RichDom2185` (17 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Upgrading JavaFX version**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/428" expanded>

Are we allowed to upgrade JavaFX to the latest version (17)?

Context: There is a GUI scaling/rendering issue when testing on Linux (Wayland) that is fixed simply by updating the version of JavaFX that is packaged.

Thank you!
</panel>

<panel  header="**2. :fas-info-circle: [tP] Is Squash and merge allowed?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/209" expanded>

If our team is planning to use a branch-based workflow for our tP (i.e. all commits go to their own branches, and `master` only receives merges), can we use the "Squash and merge" option from GitHub?

The main focus of the question lies in the fact that unlike GitLab, for GitHub, we cannot have the option to both squash all commits of that branch into one commit and keep a merge commit (`--no-ff`) at the same time.

Are the merge commits necessary for the tP?
</panel>

<panel  header="**3. :fas-info-circle: iP Progress not reflected in iP Progress Dashboard**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/123" expanded>

Checked and not a duplicate of #95.

For some reason, despite having merged my [`branch-Level-7`](/RichDom2185/iP/tree/branch-Level-7), [`branch-Level-8`](/RichDom2185/iP/tree/branch-Level-8), [`branch-Level-9`](/RichDom2185/iP/tree/branch-Level-9), [`branch-A-JavaDoc`](/RichDom2185/iP/tree/branch-A-JavaDoc) and [`branch-A-CodingStandard`](/RichDom2185/iP/tree/branch-A-CodingStandard) branches, for some reason, they are still not reflected on the iP progress dashboard.

I merged using one of the following commands (varies on branch):
```bash
git pull --no-ff origin/<branch_name>
git merge --no-ff origin/<branch_name>
```

Other possibly relevant info:
```bash
$ git branch --merged master
  branch-A-CodingStandard
  branch-A-JavaDoc
  branch-Level-7
  branch-Level-8
  branch-Level-9
* master
 // ... other branches I created that are not relevant to this discussion
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1214433281" expanded>

I think it depends on what you are trying to do with `method`. Does it need to access attributes of the superclass? Maybe you can try using `CompletableFuture`. Or you could use a functional interface and pass in the method as an argument to something. Or maybe expose the `preMethod` and `postMethod` to subclasses and call them from there. I think without an example use-case, it would be hard to decide on a most appropriate implementation because it depends on what the end goal is...
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1214434000" expanded>

Either way, your proposed behaviour seems to be a good candidate for implementing the decorator design pattern. You can learn more about it [here](https://refactoring.guru/design-patterns/decorator/java/example).

```java
interface Methodable {
  void method();
}

class TestDecorator extends Methodable {
  private final Methodable wrapee;

  TestDecorator(Methodable wrapee) {
    this.wrapee = wrapee;
  }

  private void preMethod() {} 
  private void postMethod() {}

  @Override
  public void method() {
    preMethod();
    wrapee.method();
    postMethod();
  }
}
```

_PS: The website has lots of cool stuff!_
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1214437007" expanded>

Hmm it seems like you are trying to add some sort of "input validation" functionality. I would suggest using the decorators, which is an object-oriented design pattern.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/9#issuecomment-1214850386" expanded>

It seems like you are trying to use SSH authentication to GitHub. In the last screenshot you posted, it seems you have not marked GitHub's SSH fingerprint as trusted. Can you try to manually push via command line and press "y" (followed by enter) when the prompt appears? It may or may not work (if I remember correctly GitHub dropped SSH in favour of PATs a while back). But worth a try; if it doesn't work, considering googling how to set up a personal access token (PAT) on GitHub.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/123#issuecomment-1234643712" expanded>

Even if `week4` contains the same merge commits as `master`? I will try to switch to `master` for now and will update here again if it works.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/123#issuecomment-1235103500" expanded>

> hi! Did you tag your merge commits in master? <img alt="Screenshot 2022-09-02 at 2 23 56 AM" width="846" src="https://user-images.githubusercontent.com/29945147/187985942-b3b34b11-7b04-4325-98bc-1dd3c80c1b1a.png">

Hi Shenyi, yup I did, the tags on the merge commits were present on `master` (as well as my `week3` branches).
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/123#issuecomment-1235103667" expanded>

> @RichDom2185 @deeyonn is it resolved now?

Hi Prof, yes it is, thank you! Closing the issue now.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/209#issuecomment-1248844336" expanded>

Noted Prof, thank you!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/411#issuecomment-1298731341" expanded>

I think to clarify, there are 2 areas of improvement:
* UG: Make it more clear that `(` and `（` different characters, and provide a troubleshooting step to diagnose this potential source of the error message showing up, especially when copying text from external sources
* JAR file: Update the error message to also provide a troubleshooting step.

I think it's clear that the first point is a UG bug and can be addressed (but we would still like your clarification to be sure). However with regards to the second point, technically speaking, our code worked correctly and caught the unaccepted character, and displayed the correct corresponding error message. So we felt that adding additional paragraphs to the error message may constitute an "enhancement", not a bug fix, so we would like to clarify on whether this is allowed. Thank you prof!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/411#issuecomment-1298752566" expanded>

Noted, thanks Prof!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1301046837" expanded>

I cloned your branch as-is (fresh copy) and I can confirm that the tests are failing on my local environment. I'm running on Apple Silicon Mac with the following config:

```zsh
$ java -version
openjdk version "11.0.16.1" 2022-07-19 LTS
OpenJDK Runtime Environment Zulu11.58+23-CA (build 11.0.16.1+1-LTS)
OpenJDK 64-Bit Server VM Zulu11.58+23-CA (build 11.0.16.1+1-LTS, mixed mode)
```

Commands I ran:
```zsh
$ git clone --branch=nitant-test-edit https://github.com/nitant-p/tp.git nitant-p-tp
... (Output truncated for readibility)
$ cd nitant-p-tp
$ ./gradlew test
Starting a Gradle Daemon (subsequent builds will be faster)

> Task :test

EditCommandParserTest > parse_oneFieldSpecified_success() FAILED
    org.opentest4j.AssertionFailedError at EditCommandParserTest.java:275

EditCommandParserTest > parse_allFieldsSpecified_success() FAILED
    org.opentest4j.AssertionFailedError at EditCommandParserTest.java:199

EditCommandParserTest > parse_multipleRepeatedFields_acceptsLast() FAILED
    org.opentest4j.AssertionFailedError at EditCommandParserTest.java:317

EditCommandParserTest > parse_invalidValueFollowedByValidValue_success() FAILED
    org.opentest4j.AssertionFailedError at EditCommandParserTest.java:346

443 tests completed, 4 failed
... (Output truncated for readibility)
```

Are there some files in your local environment that are not pushed to that branch?
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/428#issuecomment-1304715450" expanded>

Noted Prof, thank you!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/434#issuecomment-1309241580" expanded>

Hi Prof, just chiming in, maybe you could set it so CodeCov still runs but does not fail the CI when it fails, since according to the module requirements, there's no set target on test coverage. Our team did that from this PR: https://github.com/AY2223S1-CS2103T-W16-2/tp/pull/352
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/459#issuecomment-1313520672" expanded>

Maybe the runners are just down? My projects run just fine on GitHub Actions
</panel>

</panel>


<panel type="info" header="### 23. AISH..IYER `@Aishwarya-Hariharan-Iyer` (16 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Should we rank PE-D Testers who have not submitted any bugs?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/437" expanded>

Could I request confirmation on whether we should rank PE-D testers who have not reported any bugs?
We initially did not rank a Tester in Q2 (the corresponding response for Q1 was N/A) but as we are going through the evaluation once more after bug-fixing to see if we need to change anything, we wondered if we should rank the Tester as 7/last instead.
Thanks!
</panel>

<panel  header="**2. :fas-info-circle: PPP pdf having a blank third page**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/432" expanded>

I have been trying to fix the PPP for a while now but it keeps having a blank third page though I followed the steps on https://se-education.org/guides/tutorials/savingPdf.html. Can I extract that blank page out of the PDF and use it?

I have tried adding sections, reducing content, increasing content, etc. 
</panel>

<panel  header="**3. :fas-info-circle: Requesting confirmation on whether this is an enhancement**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/419" expanded>

Good evening Prof,
In our product, a bug reported was that if `project -e p/1 m/12345678` is entered, it throws an error saying that the Project ID (`p/PROJECT_ID`) must be a positive integer (`m/` is an invalid prefix for this command). It seems that it parses `1 m/12345678` as part of the arguments for `p/`. ([Issue: #181](https://github.com/AY2223S1-CS2103-F13-1/tp/issues/181))
We documented this as part of the UG mentioning that everything after the last valid prefix (here, `p/`) shall be parsed as part of that prefix. Here, we felt that the error message is not exactly wrong as it parses all invalid flags at the tail end of the input to be a part of the arguments of the last valid prefix.
A few alternatives we came up with were:
1. Special error messages for invalid prefixes in the command that are valid in some other command for the product. (e.g. `m/` is used in client commands)
2. Parse only the first or so words for the index prefixes.

However, after reading forum post #392, we were worried that these two approaches shall be considered feature enhancements instead.
Could we please seek guidance on the same?
Thank you.
</panel>

<panel  header="**4. :fas-info-circle: Is this a case of buggy feedback message?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/415" expanded>

Good evening,
We were wondering if making the following modification to the displayed feedback message is part of bug-fixing or an enhancement: 
While the addition of exact clients as ones present on the list is not allowed, we can add a client with the same name, email, and phone as a client on the list but under a different project. (Each client has a list of projects and each project has exactly one client)
As was noticed in the PE-D, this addition still gives the success message "New client added: ---" when in fact no new item is shown on the client list but the projects shown under the specified client are changed to include the latest addition as well. 
In this case, can we change the feedback message as it is incorrect?
Thank you!
</panel>

<panel  header="**5. :fas-info-circle: Request for smoke-test help on Windows and Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/296" expanded>

Hello,
I am currently using MacOS to write and test code. My JAR release is found here:
https://github.com/Aishwarya-Hariharan-Iyer/ip/releases/tag/A-Release
If someone could please help me test it on Windows and Linux OS, I would be really grateful...
Thanks!
</panel>

<panel  header="**6. :fas-info-circle: User Input in iP**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/57" expanded>

Hi! A minor doubt:
Reg. how the user interacts with Duke, how much variation must we account for in user commands, generally? 
For example, for this week's Lvl8 task, in addition to accounting for the cases where the user types in "**deadline/2019-10-11 08:00**", should we also try to recognize commands like "**deadline/20 Nov 2020 8 P.M.**" and so on?
Thank you!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/57#issuecomment-1227393483" expanded>

Thanks, @EmilyOng! Thanks, Prof. @damithc!

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/296#issuecomment-1255784521" expanded>

Thanks a lot @Yongbeom-Kim !!! It is really kind of you to help!
Hmm...ok for the file location, if Duke.jar is in Desktop, then DukeList.txt should also be saved there. I am not sure about the UI and console parts though? Does anyone have any suggestions/faced something similar?
Thanks!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/296#issuecomment-1256904895" expanded>

Thanks a lot @RussellDash332 !!! Will change the goodbye design to perhaps close the tab ... thanks a lot for bringing that up! 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/296#issuecomment-1256905346" expanded>

Thanks, @Yongbeom-Kim @RussellDash332 really appreciate your time and suggestions/comments!!! :) 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/337#issuecomment-1272805654" expanded>

As @Puakii mentioned, that seems ok! You can also merge the upstream master to your master and then merge your master with your branch since for future PRs, you will be creating new branches from your master. So it's good to have your master synced with the upstream master. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/415#issuecomment-1300423760" expanded>

Thank you Prof @damithc!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/419#issuecomment-1302032370" expanded>

Prof @damithc, After PE-D because we were not sure if we are allowed to fix it without it being considered an enhancement. However, we can fix it using either of the alternates, whichever is allowed, if it's permitted as part of v1.4.
Moreover, it also seems to be general to other prefixes - not just index prefix - and thus seems to be a behavior. For example, `project -a n/Name t/invalid prefix` would parse everything after `n/` as part of the Name argument. Nonetheless, we are not sure if documentation is justified in this case, as re-reading this now, it seems like the documentation is explaining/justifying a behavior that is potentially buggy.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/419#issuecomment-1302125426" expanded>

Noted Prof.! Thank you so much!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/432#issuecomment-1305547748" expanded>

Thanks a lot Prof.!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/437#issuecomment-1306902476" expanded>

Thanks Prof.!
</panel>

</panel>


<panel type="info" header="### 24. POH .. JIE `@PokezardVGC` (15 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Unable to read inputs from duke.txt**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178" expanded>

Hi guys, I might need help to understand why I am not reading any files from my duke.txt files. even though there was a previosu log. Was working normally before abstracting it via OOP so not sure what happen. Currently in debugging mode as shown in the images. (extracted the boolean hasNextLine out to illisturate this, original code runs sc.hasNextLine() normally)

Used the exact same file path for both read and write so kinda puzzling why read is not detecting but write is

![image](https://user-images.githubusercontent.com/71965541/189622778-62579226-1e1e-4611-b696-9fbfa855de81.png)
![image](https://user-images.githubusercontent.com/71965541/189622805-03984af4-46d8-46a0-a147-6b26fd1c7168.png)

Would greatly appreciate if anoyone has encountered a similar problem. 

Github link: https://github.com/PokezardVGC/ip

</panel>

<panel  header="**2. :fas-info-circle: How to change our head**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/159" expanded>

![image](https://user-images.githubusercontent.com/71965541/189163492-21fbd239-6628-4be0-8159-cb017df5069a.png)
Hi guys, wondering how do we "shift" our master to where we are now in github? I think I accidnetally left master out while merging 

</panel>

<panel  header="**3. :fas-info-circle: Gradle help**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/144" expanded>

Added Gradle and having issue running my code. Works fine normally just after adding not sure what happen, in fact I am not too sure if I have install Gradle correctly
code has been pushed, refer to master branch

https://github.com/PokezardVGC/ip

Error that I gotten: 
Task 'Duke.main()' not found in root project 'Lab 2'.

</panel>

<panel  header="**4. :fas-info-circle: How to approach creation of files (Level 7)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/83" expanded>

How to go about checking if folder exists using relative paths without hardcoding filepaths? I still don't quite understand how to use the relative path, since we might be working on diffrerent directories. 
</panel>

<panel  header="**5. :fas-info-circle: [A-TextUiTesting] nothing in Actual**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/29" expanded>

![image](https://user-images.githubusercontent.com/71965541/185427885-2a3fa531-746b-44bf-981f-f36bd1793895.png)
![image](https://user-images.githubusercontent.com/71965541/185427916-d708e29f-1c03-49b3-b5ff-845a1ccd22b7.png)
![image](https://user-images.githubusercontent.com/71965541/185427933-6668f5a7-8696-4483-be51-3943ad6648b8.png)
As shown there are inputs and EXPECTED filled up but when I run rentest.sh, nothing appears in ACTUAL. Anyone encountered the same issure and happen to know why?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/29#issuecomment-1219611583" expanded>

Link here: https://github.com/PokezardVGC/ip
thanks for the tips prof
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/29#issuecomment-1219660447" expanded>

Thanks @huzaifa1712 ! Old habits of naming everything main and not noticing it's supposed to be called Duke. Really silly mistake on my part.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/83#issuecomment-1229210484" expanded>

Thanks, really helped alot. Was having trouble understanding how to create the file paths required but realised I could have created it recursively 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/144#issuecomment-1240878861" expanded>

Hi guys, I've cleared the problem. Apprently I had 2 gradles installed. Thnaks for the inputs though 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/159#issuecomment-1240906561" expanded>

![image](https://user-images.githubusercontent.com/71965541/189168040-6318c553-e03b-47cb-b599-224652620a83.png)

Attached is the remoted branches shown

Hi prof, I've actually created a branch form my current headless branch, checked out with the master branchm, deleted all the files in master branch and merged master branch to the current headless branch. Managed to get it settled but beleive this is far from the right way to do it
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/159#issuecomment-1243477813" expanded>

Thanks prof, though was a rather improvised solution managed to get it to weork. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178#issuecomment-1243534990" expanded>

Hi prof, I've actually encountered this problem since then but wanted to try it out before asking on forum gor help. Pushed my latest commits to the fork in master
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178#issuecomment-1243538894" expanded>

@deeyonn , I've only ran readDuke once though so I am not too sure if  closing at the end of the method would affect? Am I getting your point correctly? Currently readDuke is unable to read anything from duke.txt (myReader.hasNextLine() == false). Appreciate your though to help though
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178#issuecomment-1243661012" expanded>

@deeyonn , I've followed your recommendation of putting the scanners in the readDuke method. I've loaded 2 test lines in duke.txt for reference. It still says there is no nextLIne in duke.txt when there are inputs

Branch in: https://github.com/PokezardVGC/ip/tree/readDuke_not_working
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/178#issuecomment-1250653736" expanded>

Hi guys, found the error. Apprently I should only generate both Scanner and Writer when using and not as attributes. Not sure why but Writer "Overwrites" Scanner, hence all the data in duke.txt went missing
</panel>

</panel>


<panel type="info" header="### 25. SHAW.. KAI `@shawnkai` (15 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for help for smoke test for Linux and Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/264" expanded>

Hi guys,

Can I have help with testing my jar file on Mac and Linux?
The release can be reached [here](https://github.com/shawnkai/ip/releases/tag/v0.2) and my user guide can be reached [here](https://shawnkai.github.io/ip/).
Thanks so much!

</panel>

<panel  header="**2. :fas-info-circle: What to do if edit userguide**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/262" expanded>

Hi Prof @damithc , I pushed a commit with the tag A-userguide to github, but i realised there were some errors when reviewing the HTML version of the user guide and I pushed another commit to rectify the errors. Is there a need to move the tag to the later commit and if there is such a need may I know how should I be doing that? Thank you!
</panel>

<panel  header="**3. :fas-info-circle: Skipped a Step when Add Increments as PRs**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/177" expanded>

![image](https://user-images.githubusercontent.com/70712915/189605247-db9549ec-0f29-48f7-bf8b-8b473e43afbc.png)


Hi prof, I accidentally skipped the highlighted step "Pull the updated master branch from your fork to your Computer."
when I was adding increment as PR, so what I did was:

Create PR respectively for code quality and assertion
Merge the Assertion PR on GitHub
Here, instead of Pulling the updated master branch from my fork to my Computer
I directly Merged the Assertion branch and Code Quality branch on my source tree and resolved any conflicts shown.

As of here I am having difficulty pushing the master branch to github. This is a photo of my graph and the error I'm facing when I attempt to push the master branch or assertion branch to github.

![image](https://user-images.githubusercontent.com/70712915/189606066-4e639f43-c7bd-4c73-a12c-5cd96b39d363.png)
![image](https://user-images.githubusercontent.com/70712915/189606167-ebabe5e7-87c3-43ef-a875-844367173ec5.png)


May I know how do I remedy this?

Thank you in advance


</panel>

<panel  header="**4. :fas-info-circle: Minimal Requirement for Level-10**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/158" expanded>

@damithc  Hi Prof, May I check the minimal requirements for Level 10- implementing a GUI and whether it is compulsory to use FXML? Cuz it's quite easy to just keep going and not knowing where to stop so just checking. Thanks in advance!

</panel>

<panel  header="**5. :fas-info-circle: Error: A JNI error has occurred, please check your installation and try again**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/23" expanded>

I was attempting A-TextUiTesting when I ran into the error of 

cmd.exe /c runtest.bat
********** BUILD FAILURE ************
'javac' is not recognized as an internal or external command,
operable program or batch file.

I tried to follow the instructions but I'm not sure if I gave the correct location of java for JAVA_HOME. The location I gave was 
C:\Users\tanji\.jdks\corretto-11.0.16 which is the language I'm using for the project now. Now this is what I get when I try to run the  runtest.bat file: 

'cmd.exe /c runtest.bat
Error: A JNI error has occurred, please check your installation and try again
Exception in thread "main" java.lang.UnsupportedClassVersionError: Duke has been compiled by a more recent version of the Java Runtime (class file version 55.0), this version of the Java Runtime only recognizes class file versions up to 52.0
	at java.lang.ClassLoader.defineClass1(Native Method)
	at java.lang.ClassLoader.defineClass(Unknown Source)
	at java.security.SecureClassLoader.defineClass(Unknown Source)
	at java.net.URLClassLoader.defineClass(Unknown Source)
	at java.net.URLClassLoader.access$100(Unknown Source)
	at java.net.URLClassLoader$1.run(Unknown Source)
	at java.net.URLClassLoader$1.run(Unknown Source)
	at java.security.AccessController.doPrivileged(Native Method)
	at java.net.URLClassLoader.findClass(Unknown Source)
	at java.lang.ClassLoader.loadClass(Unknown Source)
	at sun.misc.Launcher$AppClassLoader.loadClass(Unknown Source)
	at java.lang.ClassLoader.loadClass(Unknown Source)
	at sun.launcher.LauncherHelper.checkAndLoadMain(Unknown Source)'


not sure if a screenshot of the environment variables page would help too 
![image](https://user-images.githubusercontent.com/70712915/185306578-1292f463-7d7d-4e2b-a95d-70d3b6560f22.png)

Thank you in advance!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/23#issuecomment-1219077208" expanded>

Not sure why the indentations didnt work when I was giving the error code. This is just to make it clearer:

cmd.exe /c runtest.bat
Error: A JNI error has occurred, please check your installation and try again
Exception in thread "main" java.lang.UnsupportedClassVersionError: Duke has been compiled by a more recent version of the Java Runtime (class file version 55.0), this version of the Java Runtime only recognizes class file versions up to 52.0
	at java.lang.ClassLoader.defineClass1(Native Method)
	at java.lang.ClassLoader.defineClass(Unknown Source)
	at java.security.SecureClassLoader.defineClass(Unknown Source)
	at java.net.URLClassLoader.defineClass(Unknown Source)
	at java.net.URLClassLoader.access$100(Unknown Source)
	at java.net.URLClassLoader$1.run(Unknown Source)
	at java.net.URLClassLoader$1.run(Unknown Source)
	at java.security.AccessController.doPrivileged(Native Method)
	at java.net.URLClassLoader.findClass(Unknown Source)
	at java.lang.ClassLoader.loadClass(Unknown Source)
	at sun.misc.Launcher$AppClassLoader.loadClass(Unknown Source)
	at java.lang.ClassLoader.loadClass(Unknown Source)
	at sun.launcher.LauncherHelper.checkAndLoadMain(Unknown Source)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/23#issuecomment-1219087829" expanded>

@damithc I have already tried restarting Intellij
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/23#issuecomment-1219141043" expanded>

Hi Prof, I keyed in java -version and got 
java version "1.8.0_311"
Java(TM) SE Runtime Environment (build 1.8.0_311-b11)
Java HotSpot(TM) 64-Bit Server VM (build 25.311-b11, mixed mode)

may i know how to change to java 11 and delete java 8? When I checked the project structure, it indicates I'm using java 11 so I'm slightly confused.

![image](https://user-images.githubusercontent.com/70712915/185337805-2392c690-fa34-42ac-a25b-e4cd65601731.png)


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/23#issuecomment-1228030220" expanded>

The issue has been resolved. Thank you!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/158#issuecomment-1241901685" expanded>

ok thanks prof!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/177#issuecomment-1243664722" expanded>

I managed to solve that part but it seems like I'm facing another problem when I'm trying to push after doing the AddAnExtension exercise. 

![image](https://user-images.githubusercontent.com/70712915/189652719-354aafa3-daa4-4ae0-bd7b-da3ff2efba62.png)

</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/177#issuecomment-1243666641" expanded>

Am I supposed to remove a tag from Github?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/177#issuecomment-1245065364" expanded>

ok thank you the problem has been resolved

</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/262#issuecomment-1250759841" expanded>

ok thanks prof!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/264#issuecomment-1250946946" expanded>

ok thanks! it wasn't intended but i think it'd be good if there was a gap haha
</panel>

</panel>


<panel type="info" header="### 26. PRAT..JAIN `@pratham31012002` (15 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: How to cite reused code now?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/477" expanded>

<img width="589" alt="image" src="https://user-images.githubusercontent.com/71367149/202898560-41c92ce3-aadb-400d-91a1-108a7a4fb673.png">

As mentioned above, we can still cite reused code, so do we create a new PR and merge it after giving the credit in the required place(s)?
</panel>

<panel  header="**2. :fas-info-circle: Recommended way to prepare for the finals?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/475" expanded>

I was wondering if there is a recommended way to prepare for the finals i.e. shall I go through the topics week by week, or shall I go through the topics as they appear in the textbook. Is there any need to go through the videos, etc. Is there any recommended flow?
</panel>

<panel  header="**3. :fas-info-circle: Is this considered a bug or an enhancement?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/403" expanded>

We allow users to create different categories (for eg. Education, Grade, Skills, etc.) for all persons in the addressbook, and the user can add information under these categories for any person.
However, currently there is no way to see the names of all categories created i.e. the only way for them to see the categories created is by going to the json file (which is not ideal or expected from the user).
This was reported as a feature flaw during the PED and we were wondering if we are allowed to display the names of the categories created in the welcome message or somewhere.
</panel>

<panel  header="**4. :fas-info-circle: Clarification regarding feature freeze**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/378" expanded>

Are the following things allowed in v1.4?

- Changing feedback messages (especially error handling messages)
- Changing implementation of a function to make it more clean and/or efficient
</panel>

<panel  header="**5. :fas-info-circle: AB3 `getImage_exitingImage()` test failing due to java.lang.UnsatisfiedLinkError**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/317" expanded>

I tried running the already written test cases for AB3. It passed all the test cases except the one for `getImage_exitingImage()` in the `AppUtilTest` class. 
<img width="1275" alt="image" src="https://user-images.githubusercontent.com/71367149/193197122-401ec49f-c1ae-4aaf-a13c-335bae97ae5d.png">
The error message continues for a few more pages.

I am running it on M1 Macbook Air.

Java version I am using:
```
openjdk 11.0.16.1 2022-07-19 LTS
OpenJDK Runtime Environment Zulu11.58+23-CA (build 11.0.16.1+1-LTS)
OpenJDK 64-Bit Server VM Zulu11.58+23-CA (build 11.0.16.1+1-LTS, mixed mode)
```

I am able to run the application and see the GUI and the commands also seem to work properly.
Kindly help me with this issue.
</panel>

<panel  header="**6. :fas-info-circle: Can we delete the readme file in the root of the repository?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/215" expanded>

Are we required to delete the readme file in the root of the repository, so that the readme file in the docs folder(user guide) appears when someone visits the repository?
</panel>

<panel  header="**7. :fas-info-circle: Name of the final release?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/210" expanded>

Is there any fixed name that we have to give for the final release of our iP? Should we name it v1.0 or v0.2/v0.3?
</panel>

<panel  header="**8. :fas-info-circle: Changing the name of the main file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/60" expanded>

I had changed the name of the main file from Duke.java to Pluto.java (Pluto being my bot), and subsequently DukeException.java to PlutoException.java. However while going through some of my peers' codes, I see that most of them haven't changed the names of the files(some have). 

Is it fine either way?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/60#issuecomment-1225776648" expanded>

Thank you prof!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1243034976" expanded>

<img width="396" alt="image" src="https://user-images.githubusercontent.com/71367149/189547052-c96aa722-3f46-42e1-bf91-566416e3d7d9.png">
 Here's my GUI for Pluto ChatBot.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/210#issuecomment-1248539885" expanded>

Okay thank you
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/215#issuecomment-1248913052" expanded>

Okay understood prof, thanks!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/378#issuecomment-1292952666" expanded>

Okay understood, thanks prof!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/403#issuecomment-1296853182" expanded>

Okay thank you prof!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/477#issuecomment-1321116750" expanded>

Okay thank you prof!
</panel>

</panel>


<panel type="info" header="### 27. KANG..HERN `@yuehernkang` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: macOS JavaFX garbled text on JavaFx version 11.**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/117" expanded>

I am currently getting this garbled text if `javaFxVersion = '11'`.
![Image](https://i.imgur.com/IDNhBRa.png)

However, if i change the version to 14, it displays as normal english characters. Is it ok to use JavaFxVersion 14? Or has anyone fixed the issue for JavaFxVersion 11
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/117#issuecomment-1233750381" expanded>

> @yuehernkang Have you followed this advisory given [here](https://nus-cs2103-ay2223s1.github.io/website/admin/programmingLanguages.html#programming-language)?

Thank you Prof. I realised apart from checking the version in the command line, we have to change the version in the project settings in intellij too!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1236092028" expanded>

Deadline Duck

![](https://i.imgur.com/F7Ur74V.png)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/144#issuecomment-1243020010" expanded>

> Hi guys, I've cleared the problem. Apprently I had 2 gradles installed. Thnaks for the inputs though

Hello Pokezard, may I know how did u check you had 2 gradles installed? I am having some issue with my gradle too. Thanks!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/191#issuecomment-1247046132" expanded>

Hello @jovitaanderson, I have just tested on macOS and it is working well!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/200#issuecomment-1248146942" expanded>

Hi @ConradLew I have just tested on my Mac and it is working fine. Cute Pepper robot picture haha
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1249531459" expanded>

Hi @xhphoong it seems like the link does not have a jar file
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/282#issuecomment-1253654686" expanded>

![](https://i.imgur.com/zHmBRxk.png)

works fine in MacOS! 

![](https://i.imgur.com/9lmJls0.png)

when data file changed 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/279#issuecomment-1253660402" expanded>

![](https://i.imgur.com/4CtCp2J.png)
works fine in macos!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276#issuecomment-1253666383" expanded>

Hello @ChongCheeKaiClarence, this is how it runs on my macos, not sure if it is just  issues with my machine.

'Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class duke.Main
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:891)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:196)
	at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.reflect.InvocationTargetException
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
	at java.base/java.lang.reflect.Constructor.newInstance(Constructor.java:490)
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:803)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:484)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:457)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:456)
	at javafx.graphics/com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
Caused by: java.lang.RuntimeException: Error! Task not given.
	at duke.Duke.&gt;init>(Duke.java:33)
	at duke.Main.&gt;init>(Main.java:16)
'
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1257178952" expanded>

![](https://i.imgur.com/g0ntXVa.png)

runs on mac. can add tasks and load tasks
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/300#issuecomment-1257179374" expanded>

Not working on MacOS. Getting this error
'Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class duke.Main
	at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:891)
'

not sure if its just me 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/295#issuecomment-1257179651" expanded>

![](https://i.imgur.com/BhHFiPX.png)

Works well on my mac when running from the terminal
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/290#issuecomment-1257180446" expanded>

![](https://i.imgur.com/9yzhAu9.png)

Works on my mac
</panel>

</panel>


<panel type="info" header="### 28. ZHAN..OKUN `@bokun2` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Does anyone meet error of codecov with this pls help sos**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/335" expanded>

![3931665286644_ pic](https://user-images.githubusercontent.com/97288772/194736738-b65b1169-ed8f-42b6-a069-32c79cab01c4.jpg)

I think I haven't deleted any related files...
</panel>

<panel  header="**2. :fas-info-circle: Request for test in ip(linux/win)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/292" expanded>

Here is my [ip!]( https://github.com/bokun2/ip/releases) Thank you in advance!
</panel>

<panel  header="**3. :fas-info-circle: Request for help of smoke test on Windows/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227" expanded>

Here is my [application](https://github.com/bokun2/ip/releases) and my [User Guide](https://bokun2.github.io/ip/) and I would appreciate some Smoke-Test on Windows/Linux. Thank you for helping!

Edit: I have updated the jar file. Thanks again for any tests >_&gt;
</panel>

<panel  header="**4. :fas-info-circle: Is it ok the input is only in GUI?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/214" expanded>

Is it ok the app is without command line input? And in this case can I just delete the text-ui-test?
</panel>

<panel  header="**5. :fas-info-circle: After merging, why my Sourcetree only showed master branch when pushing?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/52" expanded>

After merging level 7 into master, it is required that we push both master and branch-level-7 , however when I tried to push, on the "branch to push" template, the only choice is "master" and no branch-level-7. Is it because the version of the Sourcetree? Or is it because I have pushed branch-level-7 before merging?...Can I just push it like this? Also, is there someway to check whether or not my push is right? Thank you for helping
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/52#issuecomment-1223567094" expanded>

![image](https://user-images.githubusercontent.com/97288772/186077701-7b72e50b-c8f3-40f1-b592-ec0c29153120.png)
![image](https://user-images.githubusercontent.com/97288772/186077736-a7c97570-d822-4030-884c-72ab9e3f456b.png)
can this work?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/52#issuecomment-1223578296" expanded>

Oh I think I have misunderstood what the project said...Thank you for your help. I will try it
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/52#issuecomment-1223604738" expanded>

So this is the reason why I can only choose to push the master branch? Thank you for your clarification, prof.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/55#issuecomment-1224343974" expanded>

You could try to add the nus-cs2103-AY2223s1 as a remote repo and try to pull the add-cradle branch to your master branch. This can only copy add-gradle branch to your master branch.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/214#issuecomment-1248965493" expanded>

Thank you prof.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249407870" expanded>

> I would like to help but it appears that you forgot to upload the binary file on the Release section.
> 
> Update: I have tested on Windows 11 and the jar file seems to be working.

Hi I have updated the binary file. Could you pls help to see if it works? Thanks!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249418580" expanded>

> Hey, I tested with the file in your build folder and it works for Windows 10, just remember to upload the release file before the deadline.
> ![image](https://user-images.githubusercontent.com/63844743/190654273-b8ae95d3-dbe8-4620-88ce-fb30a4df199f.png)

Hi I have updated the binary file. Could you pls help to see if the file works? Thanks!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249508669" expanded>

> > > Hey, I tested with the file in your build folder and it works for Windows 10, just remember to upload the release file before the deadline.
> > > ![image](https://user-images.githubusercontent.com/63844743/190654273-b8ae95d3-dbe8-4620-88ce-fb30a4df199f.png)
> > 
> > 
> > Hi I have updated the binary file. Could you pls help to see if the file works? Thanks!
> 
> I have tested it again and yes it does work. Hope this helps :) 👍🏻

Thanks!!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249980617" expanded>

> I got a completely blank screen on Linux (Arch): ![Screenshot_20220917_013548](https://user-images.githubusercontent.com/22095441/190699369-7165236c-a99a-4ba2-b3cc-12cbf1b54d10.png) And it also gets into an infinite loop of printing exceptions:
> 
```
> Exception in thread "JavaFX Application Thread" java.lang.IllegalArgumentException: Image must be non-null
>         at com.sun.prism.paint.ImagePattern.<init>(ImagePattern.java:44)
>         at com.sun.javafx.tk.quantum.QuantumToolkit.createImagePatternPaint(QuantumToolkit.java:924)
>         at com.sun.javafx.tk.Toolkit.getPaint(Toolkit.java:661)
>         at javafx.scene.paint.ImagePattern.acc_getPlatformPaint(ImagePattern.java:292)
>         at javafx.scene.paint.Paint$1.getPlatformPaint(Paint.java:48)
>         at javafx.scene.shape.Shape.updatePGShape(Shape.java:963)
>         at javafx.scene.shape.Shape.doUpdatePeer(Shape.java:998)
>         at javafx.scene.shape.Shape.access$000(Shape.java:123)
>         at javafx.scene.shape.Shape$1.doUpdatePeer(Shape.java:131)
>         at com.sun.javafx.scene.shape.ShapeHelper.updatePeerImpl(ShapeHelper.java:74)
>         at com.sun.javafx.scene.shape.CircleHelper.updatePeerImpl(CircleHelper.java:64)
>         at com.sun.javafx.scene.NodeHelper.updatePeer(NodeHelper.java:102)
>         at javafx.scene.Node.syncPeer(Node.java:710)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2380)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
>         at javafx.scene.Scene$ScenePulseListener.syncAll(Scene.java:2389)
>         at javafx.scene.Scene$ScenePulseListener.synchronizeSceneNodes(Scene.java:2356)
>         at javafx.scene.Scene$ScenePulseListener.pulse(Scene.java:2512)
>         at com.sun.javafx.tk.Toolkit.lambda$runPulse$2(Toolkit.java:412)
>         at java.base/java.security.AccessController.doPrivileged(Native Method)
>         at com.sun.javafx.tk.Toolkit.runPulse(Toolkit.java:411)
>         at com.sun.javafx.tk.Toolkit.firePulse(Toolkit.java:438)
>         at com.sun.javafx.tk.quantum.QuantumToolkit.pulse(QuantumToolkit.java:519)
>         at com.sun.javafx.tk.quantum.QuantumToolkit.pulse(QuantumToolkit.java:499)
>         at com.sun.javafx.tk.quantum.QuantumToolkit.pulseFromQueue(QuantumToolkit.java:492)
>         at com.sun.javafx.tk.quantum.QuantumToolkit.lambda$runToolkit$11(QuantumToolkit.java:320)
>         at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
>         at com.sun.glass.ui.gtk.GtkApplication._runLoop(Native Method)
>         at com.sun.glass.ui.gtk.GtkApplication.lambda$runLoop$11(GtkApplication.java:277)
>         at java.base/java.lang.Thread.run(Thread.java:829)
```
> 
> Keeps printing this non stop. [This thread](https://github.com/nus-cs2103-AY2223S1/forum/issues/217) might be related.

Hi I have uploaded another [version](https://github.com/bokun2/ip/releases). Could you pls see if it works? Thanks
</panel>

</panel>


<panel type="info" header="### 29. KANG..QIAO `@kangqiao322` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Test cases fail for tP, preference file location error.**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/304" expanded>

Currently, my testcases for tP fails even though I have not changed anything. I feel that it might be a directory rooting problem in Intellij but I have no idea on how to fix it. Any help will be appreciated thank you!
![image](https://user-images.githubusercontent.com/93211040/192107453-fbbef0f3-0528-4621-9e42-204e5150f505.png)
![image](https://user-images.githubusercontent.com/93211040/192107486-5c69af78-9577-470e-9642-2243186577f8.png)
The main can run but I get this error too.
![image](https://user-images.githubusercontent.com/93211040/192108528-b5fcad18-9487-4853-b816-581b72864df9.png)

I think it is a file path problem but I am unsure how to fix it since the preferences.json file that is generated seems to have the wrong path.
![image](https://user-images.githubusercontent.com/93211040/192132212-88c69301-aed8-45e4-b845-e699147fb1dd.png)



</panel>

<panel  header="**2. :fas-info-circle: Request for smoke test help ( Windows, Linux or Mac)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/303" expanded>

Hi, I'm looking for help to smoke test my release [here](https://github.com/kangqiao322/ip/releases/tag/A-Release).

Thank you in advance!

</panel>

<panel  header="**3. :fas-info-circle: Gradle sync issue**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/102" expanded>

I continuously seem to have a problem with gradle, it keeps resetting my sdk settings and fail to build the module. This is the error it shows when I attempt to build the module is "Gradle sync failed: The supplied javaHome seems to be invalid. I cannot find the java executable." and I am not sure what is the reason for this.

</panel>

<panel  header="**4. :fas-info-circle: Running the Main function only returns Executing and Executing finished**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90" expanded>

After merging my master branch and the add-gradle-support branch, whenever compiling and running the code on Intellij windows, instead of displaying the usual syntax, only this is displayed  "10:44:03 PM: Executing ':Duke.main()'...

10:44:03 PM: Execution finished ':Duke.main()'.", I am unable to input anything and I am unsure what is the cause of this.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229225721" expanded>

I've tried all of them but they didn't seem to work, the build grade seems to be throwing exceptions but I'm not really sure what is the cause of them. Here is an image of the code, I apologise for the bad quality as my PC can't seem to print screen.
![20220828_003852](https://user-images.githubusercontent.com/93211040/187039901-9ece86fe-b4e3-4ed8-bfd2-bd282cbbd73f.jpg)

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229227772" expanded>

When I click on the exception, the output panel remains the same and it appears that I can only do gradlew dry run
![Uploading 20220828_005930.jpg…]()

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229244890" expanded>

Sorry for the late reply, currently I run the Duke code with the run button, I also input some command such as build file inside t
![Uploading 20220828_005930.jpg…]()
he gradle terminal
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229362580" expanded>

I firstly created a add-gradle-support branch for my remote repo, then forked it from https://github.com/nus-cs2103-AY2223S1/ip, afterwards I created a local branch following the remote add-gradle-support and has all the gradle files, then merged the gradle branch and my master branch locally before pushing it to my master branch on github
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229364615" expanded>

hmm I think I followed that but maybe I didn't close the project?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229367054" expanded>

Ok it is working now, thank you very much!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/102#issuecomment-1230740533" expanded>

Turns out the problem might've been a mismatch between the classpaths of the SDKs in Intellij, I've deleted the redundant SDKs and it seems to be fixed for now.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/303#issuecomment-1257104850" expanded>

Thank you very much! I fixed  the reply issues but I'm not sure about the messing up data file part.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/304#issuecomment-1257116548" expanded>

I have changed my directory by disabling onedrive but it still does not seem to fix the issue.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/304#issuecomment-1257195285" expanded>

Problem seems to be fixed after changing the build.gradle.
</panel>

</panel>


<panel type="info" header="### 30. HO L.. WAH `@ThomasHoooo` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Severity for similar diagrams**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/454" expanded>

May I know what is the severity for similar diagrams? The tester put as low but I think it is veryLow as it doesn't hinder the user and it is a cosmetic issue.
</panel>

<panel  header="**2. :fas-info-circle: TP progress dashboard captures the wrong release**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/344" expanded>

My group released v1.2 on our repo but the dashboard captures as v1.3.
![image](https://user-images.githubusercontent.com/78606832/195889919-626fe4dc-dd6f-4943-bbd2-4ca340a0eca5.png)
![image](https://user-images.githubusercontent.com/78606832/195889973-0e8376ce-e887-4cd1-a448-10903abd2339.png)

</panel>

<panel  header="**3. :fas-info-circle: Reporting spelling error on DevOps guide**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/185" expanded>

[
![image](https://user-images.githubusercontent.com/78606832/189887734-725aa376-0a69-496e-af36-039f61e7be14.png)
](url)

test is misspelled as testes.
</panel>

<panel  header="**4. :fas-info-circle: Need help for Java Regex**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/110" expanded>

I have a Event string `String task = "[E][ ] dancing (at: 14 Aug 2022 1200)";` and I'm trying to extract out the task `dancing` and the time `14 Aug 2022 1200`.

I have tried the following but still couldn't work.
```
Pattern timePattern = Pattern.compile("at: (.*?)\\)"); // Pattern to match time 14 Aug 2022 1200
Matcher timeMatcher = timePattern.matcher(task);
```

Can someone enlighten me?

</panel>

<panel  header="**5. :fas-info-circle: java.nio.file.InvalidPathException when I run runtest.bat**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/28" expanded>

Hi guys I'm using a windows laptop and I came across this issue when I try to run runtest.bat. It throws me: 
'Exception in thread "main" java.nio.file.InvalidPathException: Illegal char &gt;*> at index 17: ..\src\main\java\*.java
        at java.base/sun.nio.fs.WindowsPathParser.normalize(WindowsPathParser.java:182)
        at java.base/sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:153)
        at java.base/sun.nio.fs.WindowsPathParser.parse(WindowsPathParser.java:77)
        at java.base/sun.nio.fs.WindowsPath.parse(WindowsPath.java:92)
        at java.base/sun.nio.fs.WindowsFileSystem.getPath(WindowsFileSystem.java:229)
        at java.base/java.nio.file.Path.of(Path.java:147)
        at java.base/java.nio.file.Paths.get(Paths.java:69)
        at jdk.compiler/com.sun.tools.javac.main.Option$37.process(Option.java:693)
        at jdk.compiler/com.sun.tools.javac.main.Option.handleOption(Option.java:1088)
        at jdk.compiler/com.sun.tools.javac.main.Arguments.doProcessArgs(Arguments.java:381)
        at jdk.compiler/com.sun.tools.javac.main.Arguments.processArgs(Arguments.java:347)
        at jdk.compiler/com.sun.tools.javac.main.Arguments.init(Arguments.java:193)
        at jdk.compiler/com.sun.tools.javac.main.Main.compile(Main.java:229)
        at jdk.compiler/com.sun.tools.javac.main.Main.compile(Main.java:170)
        at jdk.compiler/com.sun.tools.javac.Main.compile(Main.java:57)
        at jdk.compiler/com.sun.tools.javac.Main.main(Main.java:43)
********** BUILD FAILURE **********
'
I am not sure why this is the case as when i run 'javac .\src\main\java\*.java' it works perfectly.

My runtest.bat is as follow: 
'''
@ECHO OFF

REM create bin directory if it doesn't exist
if not exist ..\bin mkdir ..\bin

REM delete output from previous run
if exist ACTUAL.TXT del ACTUAL.TXT

REM compile the code into the bin folder
javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\*.java
IF ERRORLEVEL 1 (
    echo ********** BUILD FAILURE **********
    exit /b 1
)
REM no error here, errorlevel == 0

REM run the program, feed commands from input.txt file and redirect the output to the ACTUAL.TXT
java -classpath ..\bin Duke &gt; input.txt > ACTUAL.TXT

REM compare the output to the expected output
FC ACTUAL.TXT EXPECTED.TXT
'''
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/42#issuecomment-1221382154" expanded>

Hi I visited your github and seems like your .java files in `\src\main\java\duke\` is dependent on the files in `\src\main\java\duke\task\`. Your situation is slightly different from mine but I can see how I can help.

Can you try `javac -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\duke\task\*.java ..\src\main\java\duke\*.java`?

If not, maybe try to separate into two lines?
```
javac -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\duke\task\*.java
javac -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\duke\*.java
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/110#issuecomment-1231914041" expanded>

> Looking at [Parser.java here](https://github.com/se-edu/addressbook-level2/blob/master/src/seedu/addressbook/parser/Parser.java), you can see that giving names to the capturing group helps you to capture the respective keywords. I guess you can make use of that and hopefully will make it easier to extract.

Thanks for replying even though it's not really applicable in my context.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/110#issuecomment-1231925738" expanded>

> An example of this would be something like this.
> 
```java
> String task = "[E][ ] dancing (at: 14 Aug 2022 1200)";
> Pattern pattern = Pattern.compile("\\] (?<description>[&hat;\\(]*)\\(at: (?<time>.*)\\)"); // might not work
> Matcher matcher = pattern.matcher(task);
> String description = matcher.group("description");
> String time = matcher.group("time");
```

Hey my bad I just realised there were some mistakes in my previous comment. I tested out and everything seems to be working fine. Thank you very much.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/110#issuecomment-1231927365" expanded>

Yup I realised my mistake. Nonetheless u will still need `matcher.find()` in order for it to work.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/121#issuecomment-1235101343" expanded>

You have to first close your project in Intellij, then reopen your project again so that it will download all the necessary packages.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/185#issuecomment-1246222567" expanded>

Sure Prof!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/344#issuecomment-1279213511" expanded>

@damithc I see. Thanks for the clarification!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/454#issuecomment-1313209272" expanded>

There are only 1-2 similar diagrams and what they perform are quite similar as well.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/454#issuecomment-1313225967" expanded>

Thanks Prof!
</panel>

</panel>


<panel type="info" header="### 31. HUAN..NGYI `@Hongyi6328` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Where can we check our answers to follow-up questions?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/484" expanded>

Prof Damith said that the teaching team can help with this. Where can we find the responses?
</panel>

<panel  header="**2. :fas-info-circle: [Spoiler Alert] Not sure about a question in the Practice Exam**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/479" expanded>

![image](https://user-images.githubusercontent.com/58073006/203022441-9fc60267-fcae-4552-abb9-540e1d0f71e6.png)

The options are 0, 1, 29, 31, and 32.
I think both 0 and 1 are in the same equivalence class as 5. How do we determine the least suitable value then?
</panel>

<panel  header="**3. :fas-info-circle: Will the solutions to the mock exam and practice exam be released?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/478" expanded>

n/a
</panel>

<panel  header="**4. :fas-info-circle: Week 8 Quiz Part 1 Questions and Answer Key do not Match**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/325" expanded>

Question 11 appears different in the original quiz and in the answer key.
![image](https://user-images.githubusercontent.com/58073006/193510613-4bc8785d-7dcd-4e9f-9ca3-49fb4c99823e.png)
![image](https://user-images.githubusercontent.com/58073006/193510634-98d5983e-5892-46a5-ad7e-25c68dc18df7.png)

</panel>

<panel  header="**5. :fas-info-circle: A grammar mistake**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/267" expanded>

![image](https://user-images.githubusercontent.com/58073006/191017699-d3f3a2cb-f45c-4930-becf-7ec0d953d157.png)
https://nus-cs2103-ay2223s1.github.io/website/schedule/week7/project.html
</panel>

<panel  header="**6. :fas-info-circle: 💡[Tips] Some functional programming applicable for iP**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/153" expanded>

You can create command suppliers using the `Function` class like this:
```Java
    private static final Function<? super String, ? extends Command> DELETE_COMMAND_SUPPLIER = commandArgument -&gt; {
        int taskIndex = getTaskIndexFromCommand(commandArgument);
        return new DeleteCommand(taskIndex);
    };
```
So that you have a static instance of a function that specifies how to get a command. Now you can put it in a hash map! Given the first word of command, you can now easily find its corresponding command.
```Java
    public Command parse(String input) {
        String instruction = // ...
        String argument = // ...
        Function<? super String, ? extends Command> supplier = commandMap.get(instruction);
        return supplier.apply(argument);
    }
```
</panel>

<panel  header="**7. :fas-info-circle: JUnit test on private methods**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/73" expanded>

To follow Gradle testing conventions, I need to save JUnit tests at a different location. For example if I want to test a method in root/main/java/util/Duke.java, I need to save the "mirrored" test classes in root/**test**/java/util/Duke.java. So is there a workaround for me to test internal private methods from outside without changing their access modifier? I also do not want to maintain a public copy of the methods, because I might update the original methods and it would be very troublesome to sync the two versions.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/73#issuecomment-1229115908" expanded>

Thank you Chee Heng!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1251009293" expanded>

That's mine. A little bit late to the party.
![image](https://user-images.githubusercontent.com/58073006/191026326-6779e209-77dc-4509-9fd4-17cca8b5ce76.png)

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/325#issuecomment-1264978280" expanded>

Actually many questions got shuffled in the answer key.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1298229326" expanded>

You can try invalidate cache rebuild the project.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/479#issuecomment-1321940910" expanded>

> > Rationale: 29 is a non boundary value but the question says 5 (also a non-boundary value from the same partition) is already being used as a test case. (examiner note: the partitions are [-MAX..0][1..31][32..MAX])
> 
> The answer is 29 according to the answer report on Examsoft.

But why is this so? Feb in leap years has exactly 29 days, so 29 should be a boundary value too.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/478#issuecomment-1321941190" expanded>

> The results and explanations for the MCQ and follow-up questions can be viewed on the Examsoft website (assuming you have already submitted):
> 
> https://apac.examsoft.com/GKWeb/login/NUS

Thank you so much!!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/479#issuecomment-1322132092" expanded>

Thank you prof!! Now I get it.
</panel>

</panel>


<panel type="info" header="### 32. LEE ..NIEL `@lulucopter` (13 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Bug in printable friendly version of the textbook?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/480" expanded>

Link to the printer friendly textbook page: https://nus-cs2103-ay2223s1.github.io/website/se-book-adapted/print.html

Not sure is it due to my machine or is it a bug, but just to bring to attention that when the reader clicks on an embedded tooltip (?) in the page eg. 
![image](https://user-images.githubusercontent.com/76448538/203088186-0e238ac4-c3c9-4a51-bc42-06b740d93b31.png)

After the reader exits the tooltip, they will no longer be able to scroll up and down the page unless they refresh the page

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/49#issuecomment-1222261133" expanded>

I had the same issue for some of the in video questions as well. Don't think we are allowed to resubmit it
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163#issuecomment-1242506456" expanded>

A quick fix/hack you can consider doing is doing a `git clone` to sync your local repo with your online repo. May not be the best method or address the problem at its root but it does fix the problem if you are desperate
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/155#issuecomment-1242511788" expanded>

Hello, I took a look at your repo, and I suspect it is because of how your packages are structured, and gradle is unable to find your files. 
Perhaps you can consider nesting your non-main packages such as `commands` and `exceptions` into your main `duke` package? That might fix the issue
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/35#issuecomment-1242518699" expanded>

Just wanted to add on that I faced a similar issue, where the checkstyle file could not load with an exception along the lines of 

`The Checkstyle rules file could not be parsed. cannot initialize module TreeWalker - cannot initialize module JavadocMethod - Property 'scope' does not exist, please check the documentation` 

After some debugging, I realised the issue came from the addressbook file being outdated, since using the checkstyle version 8.32 rectifies the issue. If you face a similar issue, because you used the AB3-0.2.1.ea RAR file (Which was downloaded from the tP [releases page](https://github.com/se-edu/addressbook-level3/releases)), you may want to instead pull the files from the given repo (they should be the most updated at 10.2)


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/297#issuecomment-1255998397" expanded>

Perhaps you want to explore more into the bottom 3 rows which source tree indicated they already exist
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/201#issuecomment-1256004857" expanded>

I don't think having multiple constructor classes break any OOP principles, but I agree with the above. Design wise, it would be better to let the parser/loader handle the logic, and guarantee the appropriate inputs are put into the constructor classes. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/305#issuecomment-1257053553" expanded>

Try #213, perhaps removing the JavaFx block from `build.gradle` might help
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/305#issuecomment-1259700487" expanded>

Sounds like a possible dependency issue. Are your project SDKs updated and correct ?  (Can be found in `file > project structure` )
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/311#issuecomment-1262745218" expanded>

Most obviously, requireNonNull is more explicit and enhances the readability of the code compared to the latter. 
But more than that, the method actually throws an explicit NP exception compared to a generic assertion error

```java
public static <T> T requireNonNull(T obj) {
    if (obj == null)
        throw new NullPointerException();
    return obj;
}
```
This allows us to control the behaviour better, and guarantee that the object created is definitely not null, compared to having to assert the non null checks throughout the code (at least all the paths where the object passes through).

Actually did some research on this cause of your qn and you can read more on it in [this S/O forum](https://stackoverflow.com/questions/45632920/why-should-one-use-objects-requirenonnull)


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/464#issuecomment-1315783813" expanded>

Agree with @kxrt here. If an intermediary is required for A to 'navigate' to C, then A does not actually have a reference to C, but rather, a reference to an intermediate that has a reference to C.

This touches a bit on coding practices as well, and if good coding practices are done by the coder, A should not be able to directly navigate to C within its' code (I believe this should be the law of demeter)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/476#issuecomment-1320460682" expanded>

As you suggested, you are right to say that the array can hold up to 5 elements. But do that note the difference between *up* to 5 and *exactly* 5. 

In this case, the UML diagram should be `0..5` to represent the "up to 5" idea. However, in the diagram, having the multiplicity be `5` suggests that there **MUST** be exactly 5 bots, which is wrong.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/475#issuecomment-1320462084" expanded>

I think revising the quizzes and tutorials are quite useful! Similarly, participating in forum discussions can strengthen your understanding imo as well 👍 

</panel>

</panel>


<panel type="info" header="### 33. REUB.. ZHE `@ReubenChay` (13 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: storage and opening message issue with GUI**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/172" expanded>

Hi! I'm facing some issues when using the GUI. Firstly, when the window opens, no opening message eg. "Hi, I'm Duke!" appears until I type in some command. Secondly, it keeps loading new storage files for the lists ie. doesn't re-load the old task lists stored in a file to use. 

These work when I run it normally in my CLI, but it doesn't work with the GUI. Anyone knows how to fix this? 
Your help is greatly appreciated :) 

Link to github: https://github.com/ReubenChay/ip
</panel>

<panel  header="**2. :fas-info-circle: Error when using FXML**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/166" expanded>

Hi! I followed the guide and everything seems to be in place. However, when I try to run Launcher, I get this error: 

`javafx.fxml.LoadException: `
(followed by a huge list of failure to load all the required variables) 
`Caused by: java.lang.reflect.InvocationTargetException`
`Caused by: java.lang.NullPointerException: Input stream must not be null`

I pushed my commit to my fork found here: https://github.com/ReubenChay/ip
Any help would be greatly appreciated! 
</panel>

<panel  header="**3. :fas-info-circle: gradlew commands failing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/116" expanded>

Hi! When I run any command using gradlew (tried clean/build/checkstyle/shadowJar) it all fails with this error: 

FAILURE: Build failed with an exception.
* What went wrong:
Could not initialize class org.codehaus.groovy.runtime.InvokerHelper
* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.
* Get more help at https://help.gradle.org
BUILD FAILED in 764ms

I read through a previous thread with this exact same issue and tried the solutions but it still doesn't work. Any help would be appreciated!

Link to repo: https://github.com/ReubenChay/ip.git


</panel>

<panel  header="**4. :fas-info-circle: Clarification on level-8 date and time**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/81" expanded>

Hi! Can I check that for the input, should it accept both formats of:
1. just the date eg. yyyy-mm-dd, and/or 
2. both date and time eg. yyyy-mm-dd HHmm 

</panel>

<panel  header="**5. :fas-info-circle: Unable to push to github**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/34" expanded>

Hi! I can't seem to push my commits to github, this is the error that I receive. I've tried googling and using all the suggested methods that I found but they all don't seem to work. 

Pushing to https://github.com/ReubenChay/ip.git
remote: Permission to ReubenChay/ip.git denied to ReubenChay.
fatal: unable to access 'https://github.com/ReubenChay/ip.git/': The requested URL returned error: 403
Completed with errors, see above


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/34#issuecomment-1221238017" expanded>

@damithc @kxrt thanks for the help! I realised I was using my password for authentication instead of a PAT which resulted in the denied permission. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/116#issuecomment-1233727471" expanded>

Thanks prof! Just added the link to my repo. I tried the above solutions one by one but I still get the same error
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/116#issuecomment-1233758157" expanded>

@xzzz3 Hi! Yea I am using java 11 for IntelliJ. 
@damithc Hi prof, I'm using my CLI on mac os. My machine java version is 16.

Could this be the issue? If i use CLI to run it will it use java 16 instead? If so, how can I force it to use 11 instead?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/116#issuecomment-1233869568" expanded>

@huzaifa1712 @damithc  thank you for the help! Managed to work on both my cli and gradle tools on intellij now. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/166#issuecomment-1242973772" expanded>

oh i see, thanks for spotting this! @cliftonfelix 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/172#issuecomment-1242989932" expanded>

@jhchee18 thanks! i managed to fix the first issue. The 2nd issue is a bit trickier, guess I didnt explain it well. 

When i load up the GUI and type "list" it will say there are no tasks in the list. When i add some tasks, and then type list, these tasks will appear. At the same time, if i look at my tasks.txt file, these tasks are actually being added to the file. If i reload the GUI again, it will start off with a new list that is empty, but adding further tasks will still modify this original tasks.txt file properly. It's like everytime i load the GUI it starts off with a new list but any actions will still modify tasks.txt 

For eg, if tasks.txt has 3 tasks in it and i run the GUI and type list, it will say no tasks in the list. If i add another 2 tasks to it and type list, on the GUI it will show i have these 2 tasks. But in the tasks.txt file there are now 5 tasks. If i re-load the GUI and start again it says no tasks. 

If i run it in intellij, all the tasks appear as per normal when reading from tasks.txt 
Not sure if this is related but if i input "bye" in intellij the program ends as intended. If i input "bye" in the GUI it will send the goodbye message but the GUI will not close 

Hope this doesn't sound too confusing..
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/172#issuecomment-1242991140" expanded>

for reference, here it is working fine if i run it in intellij, loading up the tasks already stored in my file, and then when i load it using my GUI, it shows no tasks: 
<img width="426" alt="Screenshot 2022-09-11 at 11 44 08 PM" src="https://user-images.githubusercontent.com/77574488/189536520-f824bfd3-0289-48a8-97d8-18d96adf78aa.png">

<img width="399" alt="Screenshot 2022-09-11 at 11 44 48 PM" src="https://user-images.githubusercontent.com/77574488/189536556-6c77a36b-77c8-4611-9b05-3fe1d126420e.png">



</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/172#issuecomment-1243303501" expanded>

@teekaytai hi! i was under the impression that when Launcher launches, it actually calls the main method which will call run(), so I thought I didn't need to add it there. Thanks for clearing up this misconception. It's fixed now, thanks for the help! 
</panel>

</panel>


<panel type="info" header="### 34. JOHN..AWAN `@johnrhimawan` (13 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Error in Reading/Writing from Json File**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/352" expanded>

```
Oct 19, 2022 12:16:43 AM seedu.intrack.MainApp init
INFO: =============================[ Initializing InTrack ]===========================
Oct 19, 2022 12:16:44 AM seedu.intrack.MainApp initConfig
INFO: Using config file : config.json
Oct 19, 2022 12:16:44 AM seedu.intrack.MainApp initPrefs
INFO: Using prefs file : preferences.json
Oct 19, 2022 12:16:44 AM seedu.intrack.commons.core.LogsCenter init
INFO: currentLogLevel: INFO
Oct 19, 2022 12:16:44 AM seedu.intrack.commons.util.JsonUtil readJsonFile
WARNING: Error reading from jsonFile file data\intrack.json: com.fasterxml.jackson.databind.JsonMappingException: Can not instantiate value of type [simple type, class seedu.intrack.storage.JsonAdaptedTask] from String value ('Application submitted'); no single-String constructor/factory method
 at [Source: {
  "internships" : [ {
    "name" : "Test",
    "position" : "Software Engineer",
    "phone" : "324789",
    "email" : "test@test.com",
    "status" : "Progress",
    "address" : "hahaha",
    "taskFilled" : [ "Application submitted" ],
    "tagged" : [ ]
  } ]
}; line: 9, column: 22] (through reference chain: seedu.intrack.storage.JsonSerializableInTrack["internships"]->java.util.ArrayList[0]->seedu.intrack.storage.JsonAdaptedInternship["taskFilled"]->java.util.ArrayList[0])
Oct 19, 2022 12:16:44 AM seedu.intrack.MainApp initModelManager
WARNING: Data file not in the correct format. Will be starting with an empty InTrack
Oct 19, 2022 12:16:44 AM seedu.intrack.MainApp start
INFO: Starting InTrack V1.2.0ea
Oct 19, 2022 12:16:44 AM seedu.intrack.ui.UiManager start
INFO: Starting UI...
```

I encountered this error when launching my application. After going through the code, a ```DataConversionException``` is thrown. I think that there might be a problem with the reading/writing of the json file since after I enter the input, only the taskName of the ```Task``` class is stored in the json file (the ```Task``` class encapsulates both the taskName which is the description of the task and the taskTime which is the time the task is due).

</panel>

<panel  header="**2. :fas-info-circle: Request for Smoke Test Help on Mac/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/224" expanded>

Hi, can I ask for help to run smoke tests on Mac and Linux? I updated my previous release.

The JAR file can be found [here](https://github.com/johnrhimawan/ip/releases/tag/A-Release).

Thanks!


</panel>

<panel  header="**3. :fas-info-circle: Request for Smoke Test Help (Mac/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/223" expanded>

Hi, can I ask for help to run smoke tests on Mac and Linux? I updated my previous submission.

The JAR file can be found [here](https://github.com/johnrhimawan/ip/releases/tag/A-Release).

Thanks!


</panel>

<panel  header="**4. :fas-info-circle: Request for Smoke Test Help on Mac and Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/206" expanded>

Hi, can I ask for help to run smoke tests on Mac and Linux?

The JAR file can be found [here](https://github.com/johnrhimawan/ip/releases/tag/A-Release).

Thanks!

</panel>

<panel  header="**5. :fas-info-circle: Skipped the Practice using parallel git branches and PRs In Week 5**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/181" expanded>

Hi prof, I already finished the tasks up to Week 5; however, I accidentally skipped through the instruction that explains that we should practice using parallel git branches and PRs since I was trying to complete the iP tasks quickly. Thus, my progress for Week 5 was submitted the same way as previous weeks (merge from other branch to master without PR). The "Merging PRs" tag is still active in the dashboard because I merged a PR for gradle support. May I please ask how I can resolve this issue?

This is the part I skipped:

![image](https://user-images.githubusercontent.com/65337049/189795603-c23e86ea-e62b-440e-8bf0-52fac632837a.png)

</panel>

<panel  header="**6. :fas-info-circle: Unable To Login GitHub Account from SourceTree**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/84" expanded>


![Screenshot 2022-08-27 181613](https://user-images.githubusercontent.com/65337049/187025870-6a29c615-0aed-4fc0-830d-2135c629af8f.jpg)
I tried to push some of the changes I committed to GitHub, but I saw that I suddenly had to login GitHub and it rejected my username and password. I would like to confirm if the fix for this issue is to generate a personal access token on GitHub for my ip repo?


</panel>

<panel  header="**7. :fas-info-circle: Question about A-TextUiTesting**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/26" expanded>

How comprehensive should the testing be? How many test cases are we recommended to use?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/26#issuecomment-1219280261" expanded>

Ok, thanks for the clarification Prof!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/84#issuecomment-1229206406" expanded>

Hi, thanks for the help. I generated a PAT, and when the same login page prompts I enter my GitHub username as username and PAT as password. However, the same error message still pops up.

![image](https://user-images.githubusercontent.com/65337049/187035299-97e6f5cf-1f34-4d6f-bb5d-3e79c69d4175.png)

Did anyone experience the same issue?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/84#issuecomment-1229208795" expanded>

@damithc @riccqi Thanks for the help! My issue has been resolved.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/181#issuecomment-1244924122" expanded>

Ok thanks for the information Prof!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/352#issuecomment-1283376485" expanded>

Thanks, already managed to solve this issue. My issue was that I override the toString() and getTask() methods in my ```JsonAdaptedTask``` class. This made the json file saved not in the manner it was supposed to.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/374#issuecomment-1290641328" expanded>

From reading the documentation at https://docs.oracle.com/javase/7/docs/api/java/awt/HeadlessException.html, maybe you can try see first if the code works if you remove the ```mail()``` method? The ```HeadlessException``` might be result of the pop-up after the method ```mail()``` is called since it might not be supported.
</panel>

</panel>


<panel type="info" header="### 35. TIMO..KOEI `@t1mzzz` (13 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: JUnit Test Issues**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/374" expanded>

I'm having issues with JUnit tests. The code is basically a pop-up for the user's email client. The tests were all successful in Intellij, but the CI has some errors (as seen below). I think it's because of the libraries I'm using ([`java.awt.Desktop`](https://docs.oracle.com/javase/7/docs/api/java/awt/Desktop.html) and [ `java.net.URI`](https://docs.oracle.com/javase/7/docs/api/java/net/URI.html)). Does anyone have any ideas regarding this? Is this a UI issue and is similar to #328?

<img width="374" alt="image" src="https://user-images.githubusercontent.com/97350034/197788954-904f27ca-8d60-4cba-b073-4b43c0a68747.png">

</panel>

<panel  header="**2. :fas-info-circle: Request for smoke test help (Windows/Mac/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/279" expanded>

Hi, can I ask for help to run smoke tests? My release can be found [here](https://github.com/t1mzzz/ip/releases/tag/A-Release).

Thanks in advance!
</panel>

<panel  header="**3. :fas-info-circle: Request for smoke testing help**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/278" expanded>

Hi, can I ask for help to run smoke tests? My release can be found [here](https://github.com/t1mzzz/ip/releases/tag/A-Release)

Thanks in advance!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1233784194" expanded>

Here's my GUI with the Chatbot and User images changed.
<img width="297" alt="image" src="https://user-images.githubusercontent.com/97350034/187843325-155258ae-0bc4-4903-8995-e92da3efd93a.png">

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/145#issuecomment-1236372283" expanded>

Hi Deon, GFMD is meant to be used in your PR description, not your README.md. Hope this helps.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276#issuecomment-1252678185" expanded>

Works okay for me. However, resizing doesn't work properly. You can disable it by using `stage.setResizable(false)`.
<img width="297" alt="image" src="https://user-images.githubusercontent.com/97350034/191324325-60c7706c-15d4-4447-9353-8782d969cbc0.png">

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/280#issuecomment-1252803518" expanded>

Hi!

I'm on Windows 11 and your JAR file works fine. 👍 

<img width="296" alt="image" src="https://user-images.githubusercontent.com/97350034/191345722-f3e74d56-960d-46a2-b089-59cf984016f5.png">

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/279#issuecomment-1254867317" expanded>

Thanks for the help! @RussellDash332 @Yongbeom-Kim @yuehernkang 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/374#issuecomment-1290660114" expanded>

Thanks @johnrhimawan for the reply I'll try it out.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/374#issuecomment-1290660984" expanded>

Thanks for reply prof @damithc. So what is the best course of action?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/374#issuecomment-1291423510" expanded>

> > Thanks for reply prof @damithc. So what is the best course of action?
> 
> Options;
> 
> 1. Omit GUI related actions from tests run by CI. This is the reason why AB3 omits any automated GUI tests.
> 2. IIRC, we used TestFX library in [AB4](https://github.com/se-edu/addressbook-level4) to do GUI testing in headless mode, but this was sometime back

How do I delete the GUI related actions from tests run by CI? By that do you mean completely deleting the below in the .yml file?

<img width="185" alt="image" src="https://user-images.githubusercontent.com/97350034/197922447-c1cb921e-b752-4ff5-88c2-5c27647a1190.png">


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/374#issuecomment-1291855179" expanded>

> The simplest way is to not write such JUnit tests that involve the GUI (i.e., test such behavior manually instead).

Alright prof, but how should that means the method and line coverage may not be 100%. That's still okay right?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/374#issuecomment-1291905289" expanded>


> @t1mzzz 100% coverage was never a requirement https://nus-cs2103-ay2223s1.github.io/website/admin/tp-expectations.html#individual-expectations-on-testing

Okay, prof! Thanks so much for the help and clarification!
</panel>

</panel>


<panel type="info" header="### 36. TAI .. KIN `@teekaytai` (12 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Incorrect hyperlink in Week 7 topics**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/268" expanded>

Under Week 7's Topics, W7.7b, Step 3.4 of the forking workflow, one of the hyperlinks appears to be incorrect. The hyperlink labelled "this GitHub help page" links to the [Week 7 Topics page](https://nus-cs2103-ay2223s1.github.io/website/schedule/week7/topics.html). 

The same link in the full textbook correctly goes to the page about [Git and GitHub](https://nus-cs2103-ay2223s1.github.io/website/se-book-adapted/chapters/gitAndGithub.html). Other nearby hyperlinks in the topics page appear to be correct too.

![image](https://user-images.githubusercontent.com/90845551/191077061-f49bcddf-2cb4-46d8-80f3-9e2c5e18ab8d.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/50#issuecomment-1222283204" expanded>

I think one way you could test the main Duke method is to separate out the part that reads the keyboard input from the rest of Duke. Then your JUnit test can directly feed in a string to Duke to test it.

Normal operation:
```
 UI
  |
  | sends input from keyboard to
  v
Duke
```

Testing:
```
JUnit
  |
  | directly sends some hardcoded string to
  v
Duke
```

Hope this helps.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/69#issuecomment-1227604247" expanded>

To add on, if you edit an old commit using rebase, be forewarned that every commit after that one will actually become new commit objects as well. In particular, any tags those commits may have had would need to be replaced.

If you do choose to go ahead with rebasing, GitHub has a pretty clear [guide](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/changing-a-commit-message#amending-older-or-multiple-commit-messages) on how to amend the subjects of past commits (refer to the section "Changing the message of older or multiple commit messages").

After you are done with the rebasing, notice that you will also need to _force push_ the changes to override what's on GitHub. I suggest doing it with the force-with-lease flag:

```
git push --force-with-lease origin master
```

The with-lease part helps check that you don't accidentally overwrite someone else's work when you force push. Not too relevant now but may save you from an angry teammate one day.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/70#issuecomment-1227628817" expanded>

I don't see why not. It makes sense that the data file should not be committed.

Side note, regarding this part

> redundant commit before checking out to other branches

If I understand correctly you are making temporary commits so that you can clear the current changes and allow yourself to move to another branch?  
If so you could benefit from using the `git stash` command to temporarily shelve changes and move to something else. Here's the entry in the [textbook](https://nus-cs2103-ay2223s1.github.io/website/se-book-adapted/chapters/gitAndGithub.html#stash-shelving-changes-temporarily).
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/89#issuecomment-1229199169" expanded>

@xiaobill8 I took a peek at your repo, and it looks like your master branch only has commits up till Level 6. Your level 7 and 8 branches have your latest work though. You'll need to merge your level 7 and 8 branches into master and then also be sure to push your master branch to github. After that the dashboard should hopefully update.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/112#issuecomment-1232696756" expanded>

Normally when you input your whole command in one shot the flow goes like this

1. JavaFX receives input from user and passes it over to Duke
2. Duke comes up with a response and passes it back to JavaFX
3. JavaFX shows the response to the user

If instead you would like to break the command into multiple steps, the flow might look something like this

1. JavaFX receives input from user and passes it over to Duke
2. Duke informs JavaFX that this particular command needs more inputs, maybe also informing JavaFX of what piece(s) of info it needs next. In the meantime this partial command has to be stored away somewhere
3. JavaFX relays Duke's 'response' to the user, asking the user for the next part of the command
4. Repeat as necessary
5. Once the full command is completed Duke can process it and return the response as before

Note that for the tP it is not recommended to do this one-input-at-a-time idea. To quote from the [website](https://nus-cs2103-ay2223s1.github.io/website/admin/tp-constraints.html#recommendation-cli-first):

> One-shot commands are faster over multi-step commands.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/122#issuecomment-1234494033" expanded>

Do you mean the ones for CheckStyle? If so we can use the ones from [addressbook-level3](https://github.com/se-edu/addressbook-level3/tree/master/config/checkstyle)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/131#issuecomment-1235656393" expanded>

Sounds like this file has tabs in it instead of spaces so it's confusing CheckStyle. Replace the whitespace with spaces instead of tabs and everything should return to normal!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/172#issuecomment-1242997909" expanded>

Looks like you simply forgot to call `storage.openFile()` and `storage.listInit(taskList.getList())`. You only call it in your `run` method which is why it works for your CLI app. Meanwhile, `getResponse` doesn't call `run`.

Perhaps this is a sign that these methods should be called inside Duke's constructor instead?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/341#issuecomment-1275933594" expanded>

Hi! I don't really know what's causing the inconsistent behaviour, but I did notice one thing weird. Regarding this assertion in your `FoodComparatorTest`:

```java
// lunch after breakfast
assertEquals(1, foodComparator.compare(BREAD, APPLE));
```
Seems you intended `BREAD` to be a lunch item and `APPLE` to be a breakfast item. However, when I checked your `TypicalFoods`, they are both tagged `breakfast`. Looks like this was changed in the latest commit to the branch titled [Merge pull request #61 from nicolelim02/update-tag](https://github.com/AY2223S1-CS2103T-T17-2/tp/commit/fa8793e23d1057f85e79ef1da9698181a82b44ff#diff-10489c775072bd082d050446399ed6f49d55cbd3256745fefbfc1e19981dacde).

There were plenty of other changes in that commit too, maybe something there can explain what's happening?

Good luck debugging!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/373#issuecomment-1289359664" expanded>

I think you can add a separate flag to the `CommandResult` class that signals whether a reload is required (similar to the flags for opening the help window or for exiting the app). Then as the `CommandResult` is passed back up the "chain of command", the relevant classes can perform the necessary actions. So for example, when the command is executed and the `CommandResult` is returned to the `LogicManager`, the `LogicManager` can do a check for this flag. `LogicManager` has access to the `Storage`, so `LogicManager` can ask the `Storage` to do a reload.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/446#issuecomment-1312658272" expanded>

I don't think capturing the order of checks is a focus of activity diagrams. Instead, activity diagrams require that **exactly one** condition is true. So for the example above, you cannot copy the conditions verbatim. You would need to separate it out into [a &gt; -10], [-10&gt;=a&gt;0], [a==0], [0&gt;a&gt;=10] and [10>a]. This way, we don't need to be concerned about the actual order the checks are being done in the code

![image](https://user-images.githubusercontent.com/90845551/201510610-c300a946-a2e7-4fed-b688-96835644859f.png)

</panel>

</panel>


<panel type="info" header="### 37. NGUY.. ANH `@april-anh` (12 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: How to export colorful version of activity diagram (Plant UML)?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/430" expanded>

The color scheme in my `.pulm` is gray when I use `save diagram` I get the same picture in `png` format. I wonder how I can expert it to the colorful scheme `.png` file (red, yellow same as the one given in AB3)

Current:
![image](https://user-images.githubusercontent.com/88279850/200242743-d6832414-ca9b-4c10-ab52-929f8ea14b80.png)

What I need:
![image](https://user-images.githubusercontent.com/88279850/200242839-f9b35b20-c866-4e75-b775-618a484064fe.png)

</panel>

<panel  header="**2. :fas-info-circle: Do reducing or adding more constraints on user input allowed in v1.4?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/383" expanded>

Right now, our command `edit` requires the user to input 2 parameters, for example, `edit a/A b/B`.
Are we allowed to change the `edit` commands to require only 1 parameter, for example, `edit a/A` or `edit b/B` in v1.4?
I'm not sure if this change violates the feature-freeze requirement or not.

Thank you!
</panel>

<panel  header="**3. :fas-info-circle: Unable to retake in-video quiz for Week 8.**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/327" expanded>

Similar to #139 and many other issues.
In particular, quiz in section 
>Drawing class/object diagrams (basic) - Box, Item, Lid
</panel>

<panel  header="**4. :fas-info-circle: WARNING: Loading FXML document with JavaFX API of version 18**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/193" expanded>

After changing the background color of the GUI using Scene Builder, I got the following warning:
```
Sep 15, 2022 1:16:55 PM javafx.fxml.FXMLLoader$ValueElement processValue
WARNING: Loading FXML document with JavaFX API of version 18 by JavaFX runtime of version 11
```
FYI, I simply changed the default color (white) to "#05445E".
</panel>

<panel  header="**5. :fas-info-circle: Wrong branch name for Level-10**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/149" expanded>

I accidentally named the branch `Level-10` instead of `branch-Level-10`. Hence, the merged branch was not detected in the IP dashboard. I just realized that but now it is already marked as overdue. Are there any things I can do to fix it?
</panel>

<panel  header="**6. :fas-info-circle: Unable to run gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/56" expanded>

Although I successfully build the project using gradle. When I try to run it under `application\run`. The following error occurs. 
`Could not find or load main class seedu.duke.Duke` but there is no `seedu` folder in the repo. How can I fix this?
</panel>

<panel  header="**7. :fas-info-circle: javac is not recognized error while running text-ui-test**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/15" expanded>

I'm using Windows and when I try to run the ```runtest.bat``` file in the ```text-ui-test``` folder I get the following error message.

```
cmd.exe /c runtest.bat
********** BUILD FAILURE ************
'javac' is not recognized as an internal or external command,
operable program or batch file.

```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/15#issuecomment-1219004523" expanded>

Thanks @teoyuqi and @huzaifa1712 ! The problem is solved. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/56#issuecomment-1225480147" expanded>

Solved! Thank you!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/149#issuecomment-1239242547" expanded>

Thanks, @RussellDash332  But if I rename it now, the dashboard still reflects as overdue, is it?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/149#issuecomment-1240189099" expanded>

Thank Prof @damithc  and @RussellDash332. The problem is resolved.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/430#issuecomment-1305284040" expanded>

Thanks, Prof!
</panel>

</panel>


<panel type="info" header="### 38. CHUA..HING `@rylzxc` (12 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Product logo**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/423" expanded>

Are we allowed to add our product logo at this stage?
</panel>

<panel  header="**2. :fas-info-circle: Taking input by input in JavaFX**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/112" expanded>

Has anyone tried implementing the chatbot to take in one input at a time? 

Something like: first input: event, second input: work, third input: 2022-10-10

In code, it'll be the scanner reading the next line on pressing enter, but I'm not sure how to make it work in JavaFX.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/6#issuecomment-1214274716" expanded>

I think the reason why we have a try-catch block in the first place is because we **expect** the program to throw errors, and we perform exception handling. So, what if we can't expect/predict an exception being thrown? As @e1010101 mentioned, the finally block contains code that runs **regardless of any exceptions thrown**, in this case it is useful if to have cleanup code in your finally block to do whatever cleanup required. Therefore, it is encouraged for a try block should have either at least one catch or finally to cover all bases.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229105004" expanded>

Are there any prompters/error messages when you hover over 'Assertions' and 'Test' which are highlighted in red?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229107055" expanded>

Have you tried syncing? You can try this by going to `View -&gt; Tool windows -&gt; Gradle -&gt; Sync (an icon beside the '+')`
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229135251" expanded>

Have you tried these 2 options: 
1. File -&gt; Invalidate caches
2. Delete the .idea folder -&gt; Close and re import the project
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/82#issuecomment-1229135626" expanded>

You can follow the date format as you did to store deadline dates, and that's the minimal requirement if I'm not wrong.

Customisability of Duke is allowed hence addition of extra flags is permitted. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/112#issuecomment-1233915278" expanded>

@teekaytai Thanks, I have implemented it. :)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180#issuecomment-1244974030" expanded>

I referred to [this](https://github.com/se-edu/addressbook-level2/tree/master/src/seedu/addressbook) while organising my code. It points to the code base of addressbook-level2 and it is quite similar to what we're doing for iP.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/184#issuecomment-1245221650" expanded>

I think in your build.gradle file the mainClassName should be duke.Launcher (i.e. pointing to the launcher instead of your main class)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/112#issuecomment-1250532320" expanded>

@damithc Hi Prof, I was wondering how the iP is graded, like is it okay (won't penalize score) to do it this way or must I stick to the format that was proposed?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/112#issuecomment-1250658519" expanded>

> @rylzxc either approach is fine for the iP, but as @teekaytai mentioned, the multi-step approach is not recommended for the tP.

Mine is implemented in a way such that a DialogBox pops up to request for further information after a command, this would be okay right just for the iP.
</panel>

</panel>


<panel type="info" header="### 39. CLIF..ELIX `@cliftonfelix` (11 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: LocalDate Parse Invalid Dates**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/62" expanded>

I'm not sure why but for some of the invalid dates, LocalDate.parse doesn't return an error
1. 29, 30, 31 Feb 2022 -&gt; 28 Feb 2022
2. 31 June 2022 -&gt; 30 June 2022

![image](https://user-images.githubusercontent.com/88199596/186452020-46bb71d8-a419-4cb8-a0b8-16e0e2cbfc33.png)

Am I using it incorrectly? Is there any solution?
</panel>

<panel  header="**2. :fas-info-circle: Line Limit in runtest.bat Output**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/48" expanded>

It seems like there is a limit for the output of the difference. Is there a way to remove/increase the limit?
</panel>

<panel  header="**3. :fas-info-circle: [A-TextUiTesting] What should happen if ACTUAL.TXT is different from EXPECTED.TXT**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14" expanded>

https://se-education.org/guides/tutorials/textUiTesting.html#:~:text=If%20the%20actual%20output%20differs%20from%20the%20EXPECTED.TXT%2C%20the%20script%20will%20report%20a%20failure.

On the page above it says:
If the actual output differs from the EXPECTED.TXT, the script will report a failure.

I tried to make the EXPECTED.TXT different from the actual output but the script doesn't report any failure, ACTUAL.TXT was created (or recreated).
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217915215" expanded>

@RussellDash332 but the thing is on the website it says the script will report a failure when EXPECTED.TXT is different from ACTUAL.TXT but I don't see any failure produced by the script
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217924440" expanded>

@RezwanArefin01 Yes, I also tried to put an empty EXPECTED.TXT and after running runtest.bat ACTUAL.TXT was replaced with a new one and no error reported
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217937446" expanded>

@RezwanArefin01 I figured out why. 
It's because I double-clicked on runtest.bat file directly on the folder, so cmd opened and closed directly. 
Just now I tried to open cmd and run the .bat on cmd and I can see the output.

Thanks @RezwanArefin01 @RussellDash332 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/14#issuecomment-1217945107" expanded>

@RezwanArefin01 Oh yea it works. Thanks haha
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/48#issuecomment-1225884748" expanded>

Thanks @kxrt I'll try it
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/62#issuecomment-1225910780" expanded>

Ah okay.. thanks @lesterong! Will try it
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1235871880" expanded>

Some improvements:

- Adding background image
- Setting the dialog box to not be truncated
- Prompt text in TextField

![image](https://user-images.githubusercontent.com/88199596/188230848-6bd5c878-6991-4800-bd7f-a8fbb72b3062.png)

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/166#issuecomment-1242743799" expanded>

Hi @ReubenChay, it seems like your dukeImage name is meseeks.png but inside your MainWindow.java, you put an extra "e" after "me" (meeseeks.png).

I tried to remove the extra e and it works fine

![image](https://user-images.githubusercontent.com/88199596/189488224-b3a273e9-db3d-4f81-a089-f567b00c99f6.png)

</panel>

</panel>


<panel type="info" header="### 40. CHAN..OONG `@Hikoya` (11 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Are editing comments of code allowed for v1.4?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/429" expanded>

Hi prof, are we allowed to edit code comments? eg. javadocs etc
</panel>

<panel  header="**2. :fas-info-circle: Typo in Using GitHub Actions @SE-EDU/guides?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/142" expanded>

In the guide on setting up Github Actions, it was mentioned that the .yml file should be placed in the `[root]\.workflows` folder. However, shouldn't it be in the `[root]\.github\workflows` folder instead?

![image](https://user-images.githubusercontent.com/13346668/188284332-4d3ae819-7f36-4422-8ed8-0cdb29d4d1b1.png)

![image](https://user-images.githubusercontent.com/13346668/188284368-e3ec18e3-fce0-4eca-afd3-59fa7112aa66.png)

</panel>

<panel  header="**3. :fas-info-circle: Localization of IP and TP**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/113" expanded>

Hi Prof

For the iP as well as the tP, do we assume that the input by the user will be in English eg. task name is written in English, addresses for tP written in English

or do we have to handle international languages eg. Mandarin separately.

Asking on behalf of tP members, tutor suggested to post on forum for everyone.
</panel>

<panel  header="**4. :fas-info-circle: Cannot write to text file while running JAR file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/54" expanded>

Hello everyone, while running my main code in IntelliJ, I was able to read from text file, and write to the text file as well.

However, after compiling into JAR file and running, I notice some issues:
1. If the file does not exist, it automatically creates (intended) and can write to file just fine.
2. If I quit the application, and try to run it again, it reads from the file just fine, but now shows an error whenever I try to save the file.

![image](https://user-images.githubusercontent.com/13346668/186118248-98d44ce9-da26-44f3-989d-ccd9f8f2e36f.png)

Thank you for the help.

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/22#issuecomment-1219083390" expanded>

To respond to Prof's answer, here is how to rename a GitHub repository 

First, go to your repository, and click on the settings button

![image](https://user-images.githubusercontent.com/13346668/185308299-aaece240-ab34-4b1c-ab22-b93104e07c94.png)

Then, you will be able to rename your repository to 'ip' . Make sure to click the rename button!

![image](https://user-images.githubusercontent.com/13346668/185308444-6e758ab7-cbbc-41ca-a9f8-d83683beb0a9.png)


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/22#issuecomment-1219206000" expanded>

For me, I simply dragged and dropped the image into the input box directly. Github would automatically generate the markdown and upload the image to their server. 

For instance, the images uploaded in my previous comment were of :
https://user-images.githubusercontent.com/13346668/185308444-6e758ab7-cbbc-41ca-a9f8-d83683beb0a9.png
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/54#issuecomment-1223907219" expanded>

Hello Prof, thanks for the comment. 

I tried to run it somewhere else eg. C:\CS2103-test and it worked as intended (able to write to file)

To my fellow peers who may be facing the same issue: try running it on a different folder and not spend time figuring out what has happened!

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/55#issuecomment-1224023747" expanded>

Either that or you can simply do a 

`git merge --no-ff upstream/add-gradle-support`

See if it helps you merge the gradle branch to your master.

EDIT: Check whether you have the upstream repo set by running `git remote -v`

![image](https://user-images.githubusercontent.com/13346668/186162018-dadcb123-614e-4e90-89b6-cecee7c6e730.png)

Else simply do a `git remote add upstream git@github.com:nus-cs2103-AY2021S1/ip.git` and run the merge command again


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/49#issuecomment-1229215507" expanded>

Hello prof, for W4.2 and W4.3, the videos do not allow resubmission as well!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232483895" expanded>

![image](https://user-images.githubusercontent.com/13346668/187599919-d8cafd26-0d39-4758-ada0-8955ad85f4cb.png)

Here's my UI close to the one given in the JavaFX tutorial, with a slight twist in terms of choice of picture :) 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111#issuecomment-1232484970" expanded>

Side note here: the tutorial mentioned to use JavaFX version 11 instead

```
repositories {
    mavenCentral()
}

dependencies {
    String javaFxVersion = '11'

    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'
}
```

https://se-education.org/guides/tutorials/javaFxPart1.html

You are currently using 17.0.1

EDIT: My bad for not noticing your next comment, do try the link sent by deepimpactmir!
</panel>

</panel>


<panel type="info" header="### 41. TANG..HONG `@hauchongtang` (11 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/52#issuecomment-1223575690" expanded>

Looks like you have merged L-7 branch with master. To update the remote repo, you just need to push &hat; to your fork. After which, your fork should have the commit "Merge branch-Level-7 ... ... ". (Check ur fork repo on github)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/53#issuecomment-1223582164" expanded>

In your `build.gradle` file, the `shadowJar`'s `archiveBaseName` is still named duke. That might be the issue.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/56#issuecomment-1225438244" expanded>

The problem might be in build.gradle file:

'
application {
    mainClassName = "seedu.duke.Duke" // change this to your package name for instance duke.Duke
}
'
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/71#issuecomment-1228099187" expanded>

>

@Dilysss I was able to build it successfully, maybe can try deleting the iP folder and `git clone` your repo again to your device.

![image](https://user-images.githubusercontent.com/56034480/186835072-59ac3c0b-8954-411e-af7d-4da6e8169b15.png)

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/80#issuecomment-1229111196" expanded>

Hi, your branch name is wrong for Level-8, it should be `branch-Level-8` with Capital L for level. Try to check your branch naming, whether it corresponds to the name stated in the CS2103 website as your branch name needs follow the exact name given in the task page else it will not be detected.

You can refer to this article on how to [rename your local and remote branches](https://stackoverflow.com/questions/6591213/how-do-i-rename-a-local-git-branch)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232513081" expanded>

Here is my GUI, similar components to the one given. However, I added `padding, borderRadius` as well as `spacing` to `DialogBox` as well as adjusted background color in `MainWindow`. I also made the image smaller. Can make use of scene builder or just edit the `.fxml` files directly.

![image](https://user-images.githubusercontent.com/56034480/187607396-d41ef292-c510-4d89-b6ec-6a44904b2564.png)

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/162#issuecomment-1242090374" expanded>

There is no Main class in your master branch, have u pushed it ?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/190#issuecomment-1246838556" expanded>

It seems like in your `Sally.java` line 25, your image route is missing a slash, hence giving u the error. 
I have highlighted where u can find the stack trace.
![image](https://user-images.githubusercontent.com/56034480/190180313-d27dd00a-b945-430c-acfb-ceec2cb5d5c0.png)

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/202#issuecomment-1248183090" expanded>

I think your `build.gradle` is missing `checkstyleMain`.

```
checkstyleMain {
    source = 'src/main/java'
}
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/202#issuecomment-1248217799" expanded>

You are missing a directory for ur `config` folder. It should be --> `config/checkstyle`

![image](https://user-images.githubusercontent.com/56034480/190436494-d460db7b-bc83-4a8f-86e4-94d55ff2c718.png)

Here is the checkstyle results after a run.

![image](https://user-images.githubusercontent.com/56034480/190436815-706750b2-9dc2-4afc-ba3a-3a94b0d85f83.png)


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/309#issuecomment-1258231359" expanded>

I had the same issue, what I did was to refresh the token via the codecov dashboard, hope it helps.

1. Go to [https://app.codecov.io/gh](https://app.codecov.io/gh)
2. Click on your Team Repo.
3. Go to settings and hit regenerate.
![image](https://user-images.githubusercontent.com/56034480/192319835-844a5abc-f8da-45cd-ad6c-76b5fc8f3dec.png)

5. Back to Github Actions and re-run all build processes.

Took reference from [stackoverflow](https://stackoverflow.com/a/67862043)
</panel>

</panel>


<panel type="info" header="### 42. LINU.. KIN `@linuschui` (11 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to run junit tests**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/188" expanded>

Hello I am using i5 Mac

I was attempting to add more tests for my new commands but I am running into this error 
 
<img width="1369" alt="Screenshot 2022-09-14 at 1 26 12 AM" src="https://user-images.githubusercontent.com/97402389/189968374-a5ff0ff3-fa90-41ac-baad-8039c5feada0.png">

I have added junit4 as a dependency to the test module but it is unable to solve the issue 😢 
<img width="1010" alt="Screenshot 2022-09-14 at 1 26 26 AM" src="https://user-images.githubusercontent.com/97402389/189968436-5bf5803b-cdca-4b1f-90b6-577b4d278e81.png">

Will appreciate any help, thank you!
</panel>

<panel  header="**2. :fas-info-circle: class file for javafx.event.EventTarget not found**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140" expanded>

I followed the guide [given](https://se-education.org/guides/tutorials/javaFxPart1.html) but am running into this error when i run `Launcher`.
Will appreciate any help, thank you ! 😸 

(using i5 Mac)

<img width="938" alt="Screenshot 2022-09-03 at 6 43 20 PM" src="https://user-images.githubusercontent.com/97402389/188266911-efed18d6-64a8-4308-9cd4-a23b608400b6.png">

</panel>

<panel  header="**3. :fas-info-circle: Unable to configure javafxm**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/121" expanded>

## Hi I am using i5 mac and but am unable to configure javafxm (not using Gradle) 

Taken from this [website](https://se-education.org/guides/tutorials/javaFxPart1.html) :

2. Import the libs folder from the SDK into your project (note: `JAVAFX_HOME` is the directory in which you have unzipped the JavaFX SDK). `File` > `Project Structure` > `Libraries` > `+` > `Java` > `{JAVAFX_HOME}/lib`

3. From `Run` > `Edit Configurations`, add the following line into your VM options for each of the main classes.
`--module-path {JAVAFX_HOME}/lib --add-modules javafx.controls,javafx.fxml`
e.g., `--module-path C:/javafx-sdk-11.0.2/lib --add-modules javafx.controls,javafx.fxml`

Here's what I have done :

2. `File` > `Project Structure` > `Libraries` > `+` > `Java` > `{JAVAFX_HOME}/lib`

<img width="1016" alt="Screenshot 2022-09-01 at 11 09 10 PM" src="https://user-images.githubusercontent.com/97402389/187948777-04491853-5132-4197-942c-7455972e162d.png">

3. `Run` > `Edit Configurations`
<img width="1033" alt="Screenshot 2022-09-01 at 11 09 49 PM" src="https://user-images.githubusercontent.com/97402389/187948988-d4e9c7b3-6f96-42f2-9017-d026d03a949c.png">

Could I get some help with fixing this issue, thank you!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/121#issuecomment-1234514273" expanded>

Thank you for the suggestion prof, I have copied the code into `build.gradle` but it is unable to fix this issue 😢 
<img width="359" alt="Screenshot 2022-09-02 at 12 30 55 AM" src="https://user-images.githubusercontent.com/97402389/187965887-f15a0423-202e-4707-a9dc-fd56483e9205.png">

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/121#issuecomment-1235292984" expanded>

thanks @ThomasHoooo I've got it to work using your advice but I'm facing a different error now, will open up another issue for it. 👍 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1237666340" expanded>

Thank you all for you help !! @maryjess @Donovan9617 @YH-15 @lfrostbytee 
However, I am still encountering the same error 😢 

<img width="1133" alt="Screenshot 2022-09-06 at 1 11 58 PM" src="https://user-images.githubusercontent.com/97402389/188551882-a25cba73-e5f3-47b2-a657-81a06212464a.png">

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1237667598" expanded>

@jetlfj Thank you for your help too ! The default constructor did not help either 😢 

<img width="924" alt="Screenshot 2022-09-06 at 1 14 07 PM" src="https://user-images.githubusercontent.com/97402389/188552146-34a0e3c1-22b4-4512-ae58-5c6f19be8013.png">

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1237670261" expanded>

@damithc Thank you Prof for the suggestion. I have pushed it here! https://github.com/linuschui/ip/tree/A-Debug
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1237695340" expanded>

Hi @sikai00 thank you for the recommendation. I deleted my modules following the website and i got classnotfound exception
<img width="1429" alt="Screenshot 2022-09-06 at 2 02 26 PM" src="https://user-images.githubusercontent.com/97402389/188558409-f1656ba3-f69a-435a-9534-6464906dbf95.png">

my project structure looks like this now
<img width="1440" alt="Screenshot 2022-09-06 at 2 03 15 PM" src="https://user-images.githubusercontent.com/97402389/188558526-73d1acfb-7d2c-459b-a8e7-769f2c8118c7.png">

thank you for all your help I am getting very stressed out as my friends have not encountered this problem.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/157#issuecomment-1240673631" expanded>

I have not reached that stage yet but you can try changing your SDK to the Zulu one recommended by the module [here](https://nus-cs2103-ay2223s1.github.io/website/admin/programmingLanguages.html) then go to File -&gt; Project Structure and change it to zulu !! 😸 
<img width="839" alt="Screenshot 2022-09-08 at 8 45 09 PM" src="https://user-images.githubusercontent.com/97402389/189125051-2c31834e-0265-4026-9c77-285e0b768a9f.png">
<img width="549" alt="Screenshot 2022-09-08 at 8 49 02 PM" src="https://user-images.githubusercontent.com/97402389/189125845-fd9eb343-ccfe-4137-bb28-006953222191.png">


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1240676537" expanded>

Thank you prof @damithc and fellow batchies for helping with this ! I have finally resolved it after 10 days 😸 
</panel>

</panel>


<panel type="info" header="### 43. LI Z..AOQI `@Eclipse-Dominator` (11 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/16#issuecomment-1218237596" expanded>

Hello, if you are using wsl, you should be running the `runtest.sh` file instead of the `runtest.bat` file. 
Are you coding in wsl environment but executing the `runtest.bat` file in windows?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/16#issuecomment-1218277428" expanded>

Actually, I realised FC is file compare on windows. So you are definitely running the bat file.
I have a friend who had similar problems, the sudden denial of access could be due to anti-virus blocking access permissions of the batch file. So you can disable your anti-virus temporarily to see if it resolves the permissions issue.

Once again, if you are using a linux environment for the iP project, I would recommend doing the testing using the provided `runtest.sh` file. It might not run as the original file contains carriage returns `\r`. But if you encounter that, you can install `dos2unix` from apt or whatever package manager your WSL system is using and pass the file through `dos2unix` to remove the carriage return (`dos2unix runtest.sh runtest.sh`). 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/8#issuecomment-1218287224" expanded>

Hello, regarding the original post 

> However this approach doesn't prevent anyone from calling `method()` directly, which will be a problem. Making it `private` isn't an option, since abstract method cannot be `private`. With this approach, a proper access modifier would be one that only sub-classes can access and inherit, but other package classes cannot. But I don't think any of the access modifier does that. So my current option is to ensure that I don't call `method()` directly from other classes myself.
> 
> Any thoughts on how to improve this?

I think you can always just use `protected` access modifier to achieve that level of access you have mentioned

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/18#issuecomment-1218308114" expanded>

Hello, looks like you are authenticating using passwords. 
Github no longer supports password authentication options. Hence, you need to set up a personal access token (PAT) in order to authenticate git operations.
You can follow the guide [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). That being said, the more detailed steps is already posted here: #9 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/89#issuecomment-1229195856" expanded>

On renaming a branch,
I renamed mine on the website itself but I didn't really change the 'internal' name (It still displays as origin/branch-level-7 on vscode). In the end, I did it locally, deleted the upstream branch, and pushed the renamed branch to the fork.
`git branch -m branch-level-7 branch-Level-7` (rename branch-level-7 to branch-Level-7 locally (similar to `mov` command))
`git push origin -d branch-level-7` (deletes `branch-level-7` from the upstream repo)
`git push origin -u branch-Level-7` (pushes the newly renamed branch to upstream)
As it's only a rename, all your commits done on the branch locally will not change

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/144#issuecomment-1236392800" expanded>

Hello, not sure if the issue has been resolved but I took a look at your `build.gradle`, reminder to update the `mainClassName` to point to the correct path based on your current pathing which should be `duke.Duke`
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/249#issuecomment-1250329516" expanded>

Hello, you can open GUI with WSLg if you are on windows 11. 
But you need to updated your javafx dependency to the latest version. If not you will encounter `gdk_x11_display_set_window_scale: assertion 'GDK_IS_X11_DISPLAY (display)' failed` error when trying to open it. A work around is to add the `-Djdk.gtk.version=2` flag when running the jar file.
![image](https://user-images.githubusercontent.com/4567895/190913030-47bff9d2-6f83-4a36-811d-16a69dd12187.png)

You can probably open the the jar file with intellij because your intellij is running a jdk installation located on windows (which means that you are likely running it on windows). For the screenshot above, `/mnt/c/` is a sign that you are running on WSL which is running on your ubuntu distro (not your windows). Since it looks like you are using windows 10, it is unlikely you will be able to get gui to work (maybe you can try using win-kex but doing that is not really worth imo
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1250332158" expanded>

A bit late to the party but wtv
<img width="472" alt="image" src="https://user-images.githubusercontent.com/4567895/190915151-89d037c8-054a-4566-9d64-5512ed0c42e8.png">
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/261#issuecomment-1250733535" expanded>

GUI works fine on Windows and WSL for me. 
However there is a bug when the save file is corrupted and the program tries to save an entry.
i.e. 
Content of save file:
```
T|0|hello
T|0test 123
```
____
When running with the above corrupted save file, you are now unable to add any new task to the save file.
Attempting to add a new task will throw the error below
<img width="1479" alt="image" src="https://user-images.githubusercontent.com/4567895/190980622-73dcb84a-20fb-4dad-8e2e-d275bfdb9bfe.png">

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/186#issuecomment-1250746456" expanded>

I know this issue is closed but you can actually package the jar with the font that you want to include. 
(though just make sure the font you choose have the appropriate liscence so that you can actually use them)
For example, if I wanted to use UbuntuMono font type
```
resources/
├── fonts
│   └── UbuntuMono-Regular.ttf
├── images
│   ├── DaDuke.png
│   └── DaUser.png
└── ...
```
I can then access these fonts via 
```java
Font font = Font.loadFont(DialogBox.class.getResource("/fonts/UbuntuMono-Regular.ttf").toString(), 15);
```
and I can now apply the font to the dialog box with
```java
dialog.setFont(font);
```
shadowJar will package this font together inside the jar so you no longer need to depend on the end user to have the corresponding font.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/129#issuecomment-1250761216" expanded>

Well, my solution to this is to have an interface for input and output and have a CLI IO and GUI IO that implements that interface.
```
inputoutput/
├── DukeAbstractIo.java
├── DukeCliIo.java
├── DukeCliSettings.java
├── DukeGuiIo.java
└── DukeIo.java
```
I abstracted out the IO component of the application so I only need to ensure that the CLI IO and the GUI IO are functional as I only need to call stuff like `printTask` , `printError` ... from it.
___
I can then access the CLI and other options via launch flags 
```
Duke

Usage: duke.jar [options] [paths...]

Options
--help -h               Displays this message
-g --gui                Lauches Duke without a GUI
--use-save -s <path>    Specifies a custom save path
-ng --no-gui            Launches Duke with a GUI
```
</panel>

</panel>


<panel type="info" header="### 44. BRYA.. HAO `@bryanngzh` (11 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: How to undo old merge commit**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/308" expanded>

Hi guys, while doing `tutorial-adding-command`, I accidentally merged the 'tutorial-adding-command' branch with my master branch and I'm unsure how to undo it. 

This was what I did:
1. Create branch 'tutorial-adding-command'
2. Add code stuff into that branch
3. git add -u on 'tutorial-adding-command' branch
4. git commit -m  on 'tutorial-adding-command' branch 
5. git checkout master
6. git merge --no-ff tutorial-adding-command
7. git push origin master 

So what I essentially did was to merge my master branch with 'tutorial-adding-command' branch and pushed my master branch to my tP fork. 

Now my master branch on both github and local has the remark functionality and I can't do any new branches since new branches would have the remark functionality as well. 

How should I go about reverting back my master branch back to the way it was?

Thanks!

--------
Edit: I was thinking maybe I could replace the source folder on my master branch locally and then push it onto github again?
</panel>

<panel  header="**2. :fas-info-circle: Request for smoke testing help (Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/228" expanded>

Hi! Would appreciate it if anybody could help me test my JAR file on Linux.
My jar file can be found [here](https://github.com/bryanngzh/ip/releases/tag/A-Release) and my UG [here](https://bryanngzh.github.io/ip/).

Thanks!
</panel>

<panel  header="**3. :fas-info-circle: JavaFX tutorial part 1 - Launcher error**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/107" expanded>

I was following the JavaFX tutorial but I got stuck at part 1.
When I try running the launcher, i get this error code.
![image](https://user-images.githubusercontent.com/50972999/187345469-ebd15535-9314-4eca-80f4-e5f1cae43f04.png)
How do I go about fixing this?

Thanks!
</panel>

<panel  header="**4. :fas-info-circle: Unable to refactor duke.java into duke package**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/66" expanded>

I'm currently doing A-Packages and I can't seem to refactor duke.java into the duke package.
I've created a package called duke under src/main/java. When i try to drag my duke.java from src/main/java to src/main/java/duke, this error message pops up.
<img width="967" alt="image" src="https://user-images.githubusercontent.com/50972999/186604620-9cb283d2-f220-4c32-bb7a-0cd0e44d019a.png">
Furthermore, I'm not able to run the code as I'm given this error. (If I try to force refactor duke.java into src/main/java/duke.)
<img width="483" alt="image" src="https://user-images.githubusercontent.com/50972999/186607142-06d98853-c1c8-457b-8e5c-51c76546beed.png">
I'm only able to run Duke.java if I move it back to src/main/java.
How do I make it such that I can move my duke.java into src/main/java/duke and make it still be able to run? 
Edit: I'm running this on MacOS Intel. 
Would appreciate any help, thanks!

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/66#issuecomment-1227026291" expanded>

@Echomo-Xinyu thank you! It works.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/107#issuecomment-1231112664" expanded>

Thanks!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/104#issuecomment-1231117076" expanded>

Hi, I'm having this issue as well.

I followed the advisory @dexter-sim mentioned above previously and it fixed my address book.

![image](https://user-images.githubusercontent.com/50972999/187346846-15f91ecc-e7fd-4f42-93fc-5165fc9adefd.png)

However, when I try doing the JavaFX tutorial part 1 running the print hello world, I get the same pop-up as @boredcoco.
I'm using a MacBook w/ Intel processor.

![image](https://user-images.githubusercontent.com/50972999/187346991-23c47f5b-6f0a-46f3-a676-7e62f4249f3f.png)

I also get this error message when I try running the Launcher from the JavaFX tutorial.  

```
> Task :Launcher.main()
2022-08-30 12:03:42.229 java[6672:371084] CoreText note: Client requested name ".SFNS-Regular", it will get Times-Roman rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[NSFont systemFontOfSize:].
2022-08-30 12:03:42.229 java[6672:371084] CoreText note: Set a breakpoint on CTFontLogSystemFontNameRequest to debug.
2022-08-30 12:03:42.239 java[6672:371084] CoreText note: Client requested name ".SFNS-Regular", it will get Times-Roman rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[NSFont systemFontOfSize:].
2022-08-30 12:03:42.511 java[6672:371126] CoreText note: Client requested name ".SFNS-Regular", it will get Times-Roman rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[NSFont systemFontOfSize:].
```

Don't know why the advisory doesn't work for the JavaFX code. Need help on this as well.

For reference, my java --version gives this.
![image](https://user-images.githubusercontent.com/50972999/187347199-d70a666a-a104-47ff-8cbb-80a721894e71.png)

Thanks!

Edit: Nevermind, I fixed this by changing the SDK in Project Structure in IntelliJ. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/160#issuecomment-1241545327" expanded>

Hi @drkkjh, I think you can try merging the above 3 branches to your master branch. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/228#issuecomment-1253188874" expanded>

Hi, I've changed the image type from jpeg to png, hopefully, that fixes the issue!
I would appreciate it if anyone could help me retest this on Linux.
I've updated the jar file above.
(Also, if anyone has any insights on how to fix the above do let me know)

Thanks! 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/308#issuecomment-1257981947" expanded>

Hi @RussellDash332, thanks for the suggestion! How do you pull the master branch from the team repo (by force)? 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/308#issuecomment-1258016351" expanded>

Thank you all for your help! Managed to resolve this by the `git fetch upstream` method.
</panel>

</panel>


<panel type="info" header="### 45. LI Z..EKAI `@lizekai-richard` (11 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Junit Test Problem**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/307" expanded>

Hi, I'm here to ask for help with Junit test.

Currently, this is my file structure. I created a test folder and a java folder within it. However, I'm unable to create any packages inside the java folder, only other directories instead. I thought it's because I didn't set the java folder as the root of test so I did it. But after that, errors occurred as below
<img width="348" alt="Screenshot 2022-09-26 at 3 50 07 PM" src="https://user-images.githubusercontent.com/88566387/192223199-ffd293b6-101a-45ae-94b1-f924225d23b5.png">
<img width="486" alt="Screenshot 2022-09-26 at 3 50 12 PM" src="https://user-images.githubusercontent.com/88566387/192223212-8118eac6-222c-4bc7-b0d7-a1eda0726f68.png">
In the gradle.build, I already added the dependencies 
<img width="792" alt="Screenshot 2022-09-26 at 3 50 19 PM" src="https://user-images.githubusercontent.com/88566387/192223373-c143623f-a046-47d6-a432-836b7af6f881.png">
After I unmarked the java as the test source root and added test files in the corresponding directories, the gradle can run all the tests.
<img width="331" alt="Screenshot 2022-09-26 at 3 49 26 PM" src="https://user-images.githubusercontent.com/88566387/192224020-ed73eb06-faee-4ded-8e0f-5b3ee8ba99f3.png">

<img width="487" alt="Screenshot 2022-09-26 at 3 49 30 PM" src="https://user-images.githubusercontent.com/88566387/192223723-6f8c9739-3070-4866-aac4-0b8e64c334f5.png">
However, I think there shouldn't be an issue if I mark the java as the source root of test (and I think it should be done). Can anyone help with this?
</panel>

<panel  header="**2. :fas-info-circle: Unable to use JUnit with Gradle on IntelliJ**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79" expanded>

Hi, I'm having difficulties building JUnit tests on my IP. The problem is I can't import

`org.junit.jupiter.api.Assertions.assertEquals;`

`org.junit.jupiter.api.Test;`

Although they are in my Gradle dependencies.

<img width="762" alt="Screenshot 2022-08-27 at 10 25 07 AM" src="https://user-images.githubusercontent.com/88566387/187010745-a2d84f42-e03f-4a4e-aefe-e3a5fea0d7fb.png">
<img width="278" alt="Screenshot 2022-08-27 at 10 25 21 AM" src="https://user-images.githubusercontent.com/88566387/187010749-d6c055cc-6b35-4ca2-8dbc-2b6466489340.png">
<img width="845" alt="Screenshot 2022-08-27 at 10 25 40 AM" src="https://user-images.githubusercontent.com/88566387/187010753-2695ae04-c8a7-42e5-ae22-5b1788eb97cc.png">

Does anyone encounter the same issue? I'm using Mac OS.

</panel>

<panel  header="**3. :fas-info-circle: Unable to Push**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/11" expanded>

I'm trying to push my commits of ip to the remote repo. However, the error below keeps prompting. It seems that there is an authentication problem. What should I do to fix this? I'm using Mac as my development environment.

<img width="642" alt="Screenshot 2022-08-17 at 10 17 46 AM" src="https://user-images.githubusercontent.com/88566387/185020433-b1abf191-b663-4447-a7bc-60796b47db54.png">


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/11#issuecomment-1217409706" expanded>

It works! Thanks a lot for your help.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229105618" expanded>

It says "Can't resolve symbol Test", and IntelliJ suggests that I should add this library to the Gradle classpath, which I think I have already included in the dependency.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229107563" expanded>

I have just tried, but still not working.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229129208" expanded>

Here is the branch I create

https://github.com/lizekai-richard/ip/tree/branch-JUnit-Error
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229135905" expanded>

@rylzxc Thanks a lot! Your second option works.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/307#issuecomment-1259035647" expanded>

Some updates:

I tried invalidating caches and re import. And below is what I got:
<img width="337" alt="Screenshot 2022-09-27 at 2 20 06 PM" src="https://user-images.githubusercontent.com/88566387/192448419-f9f363e6-5a35-4595-889e-4669014b55b6.png">
<img width="601" alt="Screenshot 2022-09-27 at 2 20 15 PM" src="https://user-images.githubusercontent.com/88566387/192448440-f39cc296-e601-4fa8-a35a-0367b3142cb4.png">
I still cannot import Junit test package. However, I used Gradle to run test and got this:
<img width="1232" alt="Screenshot 2022-09-27 at 2 20 35 PM" src="https://user-images.githubusercontent.com/88566387/192448616-a43c4dd2-dcd6-40e5-96d3-aaba4c63b971.png">
Seems these test are unable. How could this happen?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/307#issuecomment-1259040803" expanded>

So can I just leave this and push it to my remote repo?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/307#issuecomment-1259045577" expanded>

Okay, thank you prof.
</panel>

</panel>


<panel type="info" header="### 46. LEE ..HAWN `@XenonShawn` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Q6 of Practice Paper Part 1**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/486" expanded>

Unfortunately, we can't see the correct or wrong solutions in Examsoft since they don't display pictures, but I assume that the diagram does not comply with (just two classes with no association line between them):

```
Chair               Table
```

Can I check why isn't the given object diagram compliant with that? I thought that it's not necessary to provide an association in a class if the diagram does not require it?
</panel>

<panel  header="**2. :fas-info-circle: PE Readiness Quiz**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/438" expanded>

According to the module website, the PE Readiness Quiz is due before the PE.

![image](https://user-images.githubusercontent.com/57314121/201039979-2b62338f-be54-4b06-bf96-f3e114907af7.png)

However, the quiz has already closed, 24h earlier than indicated.

![image](https://user-images.githubusercontent.com/57314121/201040034-97c9d5b1-a92f-440e-a1f5-90088bf5fc19.png)

Is this intentional?
</panel>

<panel  header="**3. :fas-info-circle: RepoSense with Morphing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/412" expanded>

My team decided to morph AB3 rather than evolve it, and I changed a lot of the names, models, test cases, etc. However, because I changed the names of the files/modules, even if I barely touched the contents of the file, the whole file is attributed to me in the RepoSense. Do I need to do anything for this? What about those files which I edited half of it but also renamed it?
</panel>

<panel  header="**4. :fas-info-circle: Clarification on Feature Flaw vs Functionality Bug**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/392" expanded>

The boundary is a little unclear, and this puts us in a difficult position considering that we get penalized for correcting a feature flaw.

For example, this FAQ says that we cannot add extra validation if its omission does not lead to unexpected functionality,

![image](https://user-images.githubusercontent.com/57314121/198842087-8bd4a18b-2009-437f-868d-23351beb578f.png)

But this FAQ says that we can if it goes against what we expect:

![image](https://user-images.githubusercontent.com/57314121/198842107-e80e37b9-5158-476a-a529-d02b0af1e4b5.png)

If we, say, have a command to list all `Person`s. But we didn't check for if there was additional text, eg `list asjfhksdjfahkl`, and this still lists all people. This is definitely not expected, but it does not cause the software to mis-behave. Is there a clearer boundary on this?
</panel>

<panel  header="**5. :fas-info-circle: Long startup times with Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/312" expanded>

## Development Environment

* IntelliJ IDEA 2021.3.2 
* Windows 10 Pro
* AMD Ryzen 7 PRO 5850U

## Issue

I have noticed that gradle frequently takes a long time to start running the application. This issue has been occuring since gradle was introduced in the iP, but I just ignored it as I thought it was normal. It turns out it wasn't, so I've tried finding out a bit more about it.

Gradle does not always take a long time to run, but it frequently does.

Running `gradle run --profile` produces this

![image](https://user-images.githubusercontent.com/57314121/192861049-ffbbc67a-9657-4674-817c-9906c28fb150.png)

As we can see, Gradle spent 21s starting up for seemingly no reason. Does anyone have an idea on how I can resolve this?
</panel>

<panel  header="**6. :fas-info-circle: `Objects.requireNonNull` vs `assert obj != null`**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/311" expanded>

Hey there,

I was wondering if there was a difference between the two, since I see `requireNonNull` being used often in AB3. Is there a reason why we would prefer one or another?

Thanks!
</panel>

<panel  header="**7. :fas-info-circle: Unable to retake in-video quiz for W3.7**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/49" expanded>

As per the title, I put in the wrong answer the the test cases per method question, am I allowed to resubmit it?

Side question, the bonus marks only require answered in-video quizzes in at least 7 weeks, which mean the result of the quizzes are inconsequential, only the attempt matters?
</panel>

<panel  header="**8. :fas-info-circle: Confirming Assessment Breakdown**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/7" expanded>

I've noticed that the actual result of the quizzes aren't part of the assessment criteria, as long as you score at least 70% it'll be counted under participation marks.

Can I confirm that there is no need to redo the quizzes until we get 100%?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/312#issuecomment-1261352502" expanded>

Upon further investigation, it seems like my issue is with a mapped network drive being unavailable. 

## Premise

I use a VPN to access a network drive. I don't usually turn on the VPN, so the network drive isn't normally available. This actually causes IntelliJ to freeze when clicking `File > Open`, as can be seen in [this post](https://intellij-support.jetbrains.com/hc/en-us/community/posts/360003304839-Open-File-or-Project-is-really-slow) on JetBrains' IDE support forum.

It seems like Gradle is trying to access some files too, but I have no idea why an unavailable mapped network drive would cause it to hang as well. Having the VPN on seems to result in a more acceptable 3s of startup time, but I'll have to continue using gradle to see if the network drive is really the issue. 

![image](https://user-images.githubusercontent.com/57314121/192867136-bb1638a4-a507-44ae-b352-6177cd3f4de8.png)

## Resolution

Turning off the VPN and trying to run gradle seems to result in a long startup time again (just got a painful 1min startup time 😢), so that seems to be the problem. Unfortunately, this _decade old_ problem [doesn't seem to be fixed yet](https://youtrack.jetbrains.com/issue/IDEA-101218), even upgrading to the latest IntelliJ 2022.2.2 does not help, so I'll just need to deal with it.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/412#issuecomment-1299865200" expanded>

> @XenonShawn if some code is attributed to you incorrectly, you can override that using RepoSense's `@@author` tags mechanism. More details https://nus-cs2103-ay2223s1.github.io/website/admin/tools.html#tool-reposense-for-authorship-tracking

Hi Prof, I'm aware of this. I'm just wondering about the extent - am I supposed to `@@author` everything except for the exact lines I changed? That's easily dozens of files, is there a better way than this?
</panel>

</panel>


<panel type="info" header="### 47. ZHAN..HENG `@zbz-lvlv` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Quiz Week 8A, Question 19**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/476" expanded>

![image](https://user-images.githubusercontent.com/9377433/202719229-77217202-3a82-4c7e-a7ce-8d641d817f3a.png)

Why is Mat having exactly 5 helpers wrong? The array can hold up to 5 elements, but shouldn't the diagram be modelling the problem (which there can be one which requires exactly 5 helpers) instead of modelling the implementation?
</panel>

<panel  header="**2. :fas-info-circle: How does CS2103T get priority for GitHub CI workflow?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/459" expanded>

Hi guys, I'm building my own project in Python and have just set up a CI pipeline with GitHub actions. However, the check is extremely slow (queueing for more than 1 hour already), so I was wondering if there is a way to speed it up? Do CS2103T projects get priority when it comes to the GitHub CI side, and if so, is there any way for me to configure it for my own project?
</panel>

<panel  header="**3. :fas-info-circle: Class diagram question about multiple instances for 2 variables.**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/417" expanded>

How to indicate in a class diagram a scenario like this?
`C` can have `0..*` of `A`, `0..*` of `B`, but must have at least one of either `A` or `B` present?

So the only illegal scenario is having 0 `A` and 0 `B`.
</panel>

<panel  header="**4. :fas-info-circle: Reusing Minecraft assets in AB3?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/395" expanded>

Hi guys, are we allowed to reuse 3rd party assets when they have been mentioned to be available for non-commercial reuse? Our program is not a independently created mod.

From [Mojang's website](https://www.minecraft.net/en-us/terms), under the `Brand and Asset Guidelines section`:
> We are also quite relaxed about other non-commercial things so feel free to create and share videos, screen shots, independently created mods (that don't use any of our Assets), fan art, machinima, etc.

We have used some of Minecraft's textures, fonts and a computer graphic of a creeper in our program.



</panel>

<panel  header="**5. :fas-info-circle: 💡LPT: What to do if the jar file youve exported wont run**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/169" expanded>

Here are the possible reasons that I have experienced myself:

1. JavaFX dependencies are not properly configured. You should add all these under "dependency" in your Gradle build file.
```
    String javaFxVersion = '18.0.2'

    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'
```

2. The main class of your program inherits from `Application`.
There is a known issue with JavaFX and Gradle that if your main class extends `Application`, the jar file won't run properly. The solution here, is to make a main class wrapper, such that you have a `Main` class that calls a method in a `Launcher` class. `Launcher` extends `Application`, and the `main` method in the `Main` class can call a `launch` method in the `Launcher` class to execute `Application.launch()`.
</panel>

<panel  header="**6. :fas-info-circle: Use of external Java libraries in iP?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/39" expanded>

Are we allowed to use external Java libraries in the iP? For example, I want to include something to process csv files.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/459#issuecomment-1313525615" expanded>

![image](https://user-images.githubusercontent.com/9377433/201647295-a639ebc4-d60c-4290-aa05-3b9b016254d6.png)

I only added a `requirements.txt` with some Python modules to be installed. Could that be the issue?

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/459#issuecomment-1314754620" expanded>

It's a private project for my freelance work, so I won't be able to share the details here. Thanks for your help anyways!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/476#issuecomment-1320733630" expanded>

Thank you for your response. I understand that according to the code, it is such that 0..5 is the more sensible answer. However, we do not know the problem domain in this case, and in that case, am I right to say that there can exist a particular problem domain in which exactly 5 elements are needed?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/476#issuecomment-1321006235" expanded>

okay i see, thank you!!
</panel>

</panel>


<panel type="info" header="### 48. SUN ..INYU `@Echomo-Xinyu` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: 💡 Fix for unable to find `dot` executable and cant render component diagram with PlantUML in IntelliJ**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/355" expanded>

Hi there,
for those who are using Mac and `brew` command to install `GraphViz` (for `plantUML`) and cannot render the component diagram in Intellij, the error prompt being `Dot executable null ...`, you may find this [StackOverflow post](https://stackoverflow.com/a/71052034/7604626) useful. Note that please refer to the highlighted answer when opening the link. (ie the answer starting with *"On a mac using Intellij, if Intellij cannot find graphviz, ...."*) This post has fixed the issue for mine and I hope it helps for yall as well.

For those with similar issues but different OS, you may consider viewing other answers for reference.
</panel>

<panel  header="**2. :fas-info-circle: Clarification on Overzealous input validation**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/347" expanded>

Hi Prof! Our team is a bit unsure about what it means by "Overzealous input validation". (section screenshot as below) In the example of input `1234 5678 (HP) 1111-3333 (Office)` for a single phone field, what is the expected action we should be taking against input? How is warning different from a block in terms of the behaviour in this case?

<img width="722" alt="MicrosoftTeams-image" src="https://user-images.githubusercontent.com/25452497/196139316-473fc774-c657-4446-b06f-a00fc73e8f92.png">
</panel>

<panel  header="**3. :fas-info-circle: 💡 how to set Intellij not using wildcard import**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/339" expanded>

For those who suffered from Intellij automatically replacing multiple import statements with a wildcard import like me, I think this article can be useful!

https://stackoverflow.com/questions/3348816/intellij-never-use-wildcard-imports
</panel>

<panel  header="**4. :fas-info-circle: 💡Tip for those who cannot run .jar file after shadowJar successful build**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/152" expanded>

Hi there,

I encountered the issue `"Java Application Launch Failed — Check Console for Possible Error Message"` after clicking my jar file. If you have encountered a similar issue as me, you need to ensure **you can run your application through the Gradle `.run` command**.

For my case, I have earlier simply copied the `Launcher.java` and `Main.java` files from the JavaFX tutorial into my repository and this results in the Gradle being unable to identify my application, hence unable to launch the Java application as the error message.

As there are very few posts on such an issue (as I tried to search earlier), hope this can help clarify the issue for those who need.

Cheers!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/66#issuecomment-1226927839" expanded>

In this case, the default running command is still to run the `Duke.java` at the previous location and hence it cannot find the main class `Duke` as the file is no longer there. You need to edit the configuration by updating the path of `Duke.java` in order to accommodate the refactor.

Another simple way to fix is to click the green run button beside your current `Duke.java` `main` class and it will automatically form a new `Duke(1)` configuration to execute the file.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/79#issuecomment-1229133628" expanded>

Hi @lizekai-richard, I have cloned the branch you have created and imported the two lines you mentioned above successfully without encountering any error. Hence, I suspect the issue is pertaining to your environment setup instead of the project itself.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/164#issuecomment-1242653679" expanded>

You may consider checking whether you can run your application via Gradle as mentioned in my earlier post #152 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/152#issuecomment-1248830149" expanded>

> Hi im having the same problems that I cant run my application using the gradle .run , how did you solve that problem?

The issue was due to Grable unable to identify the main class position. Hence, I have updated the `mainClassName` in the `application` section of`build.gradle` file to the correct class.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/413#issuecomment-1304556188" expanded>

> the first one is the default RepoSense behavior but you can override it with `@@author` tags

Hi prof, could you give an example of how this tag can be used? For example, if ABC wants to claim the authorship of this method band, should ABC be our real name or GitHub name? how this JavaDoc should be written exactly?

```java
/**
 * Returns 1 all the time.
 * @@author: ABC
 */

```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/413#issuecomment-1304556516" expanded>

> > the first one is the default RepoSense behavior but you can override it with `@@author` tags

> Hi prof, could you give an example of how this tag can be used? For example, if ABC wants to claim the authorship of this
> method, should ABC be our real name or GitHub name? how this JavaDoc should be written exactly?

I have realised a link to the question I asked has been given in an earlier post. For those who want an answer like me, you can find the relevant information here: https://nus-cs2103-ay2223s1.github.io/website/admin/tools.html#tool-reposense-for-authorship-tracking
</panel>

</panel>


<panel type="info" header="### 49. SHAR..ZHEN `@sharmaine1028` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Question regarding navigability**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/464" expanded>

Consider that Class A has a field Class B, then there is navigability between Class A and Class B.

Class A -&gt; Class B

Class B has a field Class C, there there is navigability between Class B and C.
Class B -&gt; Class C

My question is whether this means Class A has navigability to Class C? (Class A can only access Class C through a getter in Class B)

Can the class diagram be drawn as such
Class A -&gt; Class C ?


</panel>

<panel  header="**2. :fas-info-circle: Query about whether Functionality Bug: Data not saved when more than one window is open #4146 is valid**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/442" expanded>

# Bug reported
![image](https://user-images.githubusercontent.com/54767477/201458494-3a582b81-8ffb-4837-892a-7b951c78a3b1.png)
![image](https://user-images.githubusercontent.com/54767477/201458503-06e65a2f-1bf0-49b7-a50d-f1b403a50886.png)

# Why we think this bug is not in scope
We feel that the behaviour of our app is very reasonable. For instance, when we open multiple documents, it is true and expected that the app will take the latest one as the final changes. In addition, it is very rare for users to open the app twice.

Also, we feel that this bug would apply to almost all tP projects and getting penalised for a bug like this would be a little unfair. 

# Conclusion
Hence, we feel that this bug should not be not in scope.

Yet, we would like to check with the teaching team if our conclusion is valid. 

</panel>

<panel  header="**3. :fas-info-circle: Is UI update considered a feature? (Will it be affected by feature freeze?)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/360" expanded>

My group was wondering if updating the UI is considered a feature? We were thinking it isn't since it's not part of the user stories or give any added functionality. But just in case, we wanted to confirm that it will not be affected by the feature freeze.
</panel>

<panel  header="**4. :fas-info-circle: Are class names also part of association?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/87" expanded>

As I was reading through the notes, I came across this question and I was wondering if this is an error or are class names part of association?
![image](https://user-images.githubusercontent.com/54767477/187026301-2e4a7d1d-bd36-40f4-8cad-ee2db4cdb815.png)

</panel>

<panel  header="**5. :fas-info-circle: Checking understanding of UML class diagram**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/85" expanded>

For the code below, could someone help me check that the diagram I have drawn is correct for the `Car` class please ? Particularly, if no modifier is present, is it right that we use package-private modifer?

```java
class Car {

    Engine engine;
    private List<Wheel> wheels = null;
    public String model;

    public void drive(int speed) {
        move(speed);
    }

    private void move(int speed) {
        ...
    }
}
```

![image](https://user-images.githubusercontent.com/54767477/187025872-0a2aa61e-289b-4e86-acbb-9d0d839a1fe7.png)


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/87#issuecomment-1229167549" expanded>

Sorry saw that someone asked this already
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232847728" expanded>

Here is my GUI, same as the JavaFX Tutorial except that
* Made the icons circle and smaller
* Add padding between each dialog
* Add spacing so that image does not block the words
![image](https://user-images.githubusercontent.com/54767477/187674115-764817b1-2caa-4896-9cac-6d04475acdd3.png)

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/442#issuecomment-1312377975" expanded>

Hi Prof Damith, I have just tested it, and AB3 behaves the same way in that it takes the changes from the latest closed window. 

For instance 
1. Open two windows of AB3
2. In first window, enter `add n/John p/123 e/john@gmail.com a/NUS`
3. In second window, enter `add n/Ken p/123 e/ken@gmail.com a/NUS`
4. Exit both windows
5. AB3 takes changes from latest changed window
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/442#issuecomment-1312381576" expanded>

Okay thank you so much Prof Damith!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/464#issuecomment-1317904647" expanded>

I think the above responses makes sense, thank you!
</panel>

</panel>


<panel type="info" header="### 50. PANI..TANT `@nitant-p` (10 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Bug Report may be correct but for a different reason**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/452" expanded>

I got a bug report stating that the UG is too long for a certain command, because there are too many things to take note of.

I disagree with the reason the tester stated, but there are a few repeated examples which does make it longer than it needs to be.

In this case, would the bug report be considered valid even though the reasoning is incorrect?
</panel>

<panel  header="**2. :fas-info-circle: Does code quality (length) matter for test cases?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/409" expanded>

I have some test cases that perform a general test on each field.

This test was already present in AB3, but there were only 3 to 4 fields. Now we have over 10 fields and the test method is quite long.

Will test cases be considered when marking code quality?
</panel>

<panel  header="**3. :fas-info-circle: Test cases failing Java CI build checks but passes on IntelliJ**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404" expanded>

I made a PR adding test cases for a command, and they all pass on my PC on IntelliJ (Using Windows 10, Java version: 11.0.13 IntelliJ version: 2022.2.3)

However, all but four test cases pass on the build check for ubuntu. 

I reran the job multiple times and the build report even states 100% of test cases pass.

Does anyone know what the issue could be?

PR is [here](https://github.com/AY2223S1-CS2103T-W08-3/tp/pull/196)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/409#issuecomment-1298246430" expanded>

@damithc Thank you prof!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1299911939" expanded>

@Hongyi6328 How do I do that?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1300761901" expanded>

@damithc I'll ask my teammates to try run the tests locally. I also reran the failing tests individually on my computer, and they pass as well.


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1300835313" expanded>

@damithc I tried it a few times before and it still did not work. 

Currently, a new pull request was just merged into our `main` branch and many other test cases (ones that were previously passing) are no longer passing on my local computer. This is now a different problem, working on it now!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1300879279" expanded>

@pyk595 @damithc I pulled the latest copy from our `master` branch and merged with the PR branch and tried again. 

Unfortunately, the same tests are failing on the CI check, but everything passes on my local machine.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1301607306" expanded>

@damithc @RichDom2185 @mjgui Thank you all for the help! I am still not sure exactly why the test cases pass on my local machine despite being synced with my team repo's master branch. There are no local files used in the failing test cases.

@mjgui When I stepped through the debugger "pm" is fine and the `assertEquals` returns true. Anyway, I just changed everything to be upper case by default and it now works on the CI check. Thank you for your help!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/452#issuecomment-1313204348" expanded>

Okay thanks prof!
</panel>

</panel>


<panel type="info" header="### 51. SHAH..ORVA `@DevanshShah1309` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Result of Issues Reported During PE**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/502" expanded>

Can I check whether we will be able to know the final outcome of the issues that we had reported in the PE but both the tester and the dev team disagreed with (as decided by the tutors/Prof)?

(Just curious to see which side's reasoning was more reasonable)
</panel>

<panel  header="**2. :fas-info-circle: Follow-up questions not being submitted**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/492" expanded>

Hi Prof, I followed the instructions on how to submit the follow-up questions on Examplify and even checked the Request Feedback option before moving to the next question for the practice exam. 

However, I got an email saying that those answers were not submitted.

Could you please clarify if there's anything I missed out?

(Is anyone else facing the same issue?)
</panel>

<panel  header="**3. :fas-info-circle: Gradle Wrapper issue causing CI to Fail**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/310" expanded>

After making changes to some .md file and creating a PR (can be found [here](https://github.com/AY2223S1-CS2103T-W13-4/tp/pull/5)), the CI is failing because of the following issue:

<img width="1044" alt="Screenshot 2022-09-27 at 9 03 46 PM" src="https://user-images.githubusercontent.com/59191109/192534837-def303a0-88ea-4111-9625-e99e840fe326.png">

I built gradle again but there was no change to the .jar file and the CI still fails. Here's the [link to the CI job](https://github.com/AY2223S1-CS2103T-W13-4/tp/actions/runs/3135646944/jobs/5091574695).

Any help is appreciated.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/310#issuecomment-1259678105" expanded>

Thanks @RussellDash332 👍 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/458#issuecomment-1313429642" expanded>

Thanks for the prompt response Prof :)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/453#issuecomment-1313662709" expanded>

Hi Prof @damithc, can I follow-up on this with a more specific example? 

Say there are 2 bug reports regarding the same bug (i.e., duplicate bug reports) but each has a different severity (say one has `veryLow` and the other has `medium`). If we keep the original one as the bug report with `veryLow` severity and mark the bug report with `medium` severity as a duplicate, does the tester who marked it as `medium` have a right to say it is not a duplicate or change the severity?

In other words, if the bug is actually roughly `medium`, is it okay for the dev team to use the `veryLow` bug report as the original copy and assign all other higher severity copies as duplicates?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/484#issuecomment-1324858721" expanded>

I think you can find the model answers given by the teaching team on ExamSoft (under courses -&gt; view results)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/483#issuecomment-1324865489" expanded>

Hmm interesting interpretation. 

In my opinion, a "sub-activity" is a direct **part** of a bigger activity. The examples you mentioned make sense from a use-case POV but they aren't exactly "sub-activities" (e.g playing piano isn't a sub-activity of "having fun"). 

So, I think it is composition because of the hint given by the naming of the association itself (i.e., **sub-activity**). It's quite similar to: tasks and sub-tasks

An example of an activity and its sub-activity can be something like: 
Activity: Prepare for CS2103T Finals
Sub-activities:
1. Read textbook
2. Practice quizzes

Then, it becomes that there is a whole-part relationship between the activity and sub-activities right?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/492#issuecomment-1325998044" expanded>

Yeah same but the top one disappears after a second or so right? Seems like a glitch to me
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/499#issuecomment-1326456576" expanded>

Though (just to clarify) I don't think we're expected to know terms which are not in the textbook or under the optional sections right?
</panel>

</panel>


<panel type="info" header="### 52. LEW ..NRAD `@ConradLew` (9 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Clarification on disagreement criteria**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/468" expanded>

In the following scenarios, are there sufficient grounds for disagreement?

1. The team downgrades the severity but does not provide any explanation. Does the FAQ mentioned in the website apply to the downgrading of severity as well instead of only outright rejections?

![image](https://user-images.githubusercontent.com/97608304/201881435-53abb8fa-2731-45b9-bb26-ba7d0d3a604e.png)

2. The team has claimed that the proposed feature flaw is not in scope, however, I am unsure about whether the feature flaw meets the criteria for "without much additional effort" as claimed by the website as fixing the flaw involves only about one or two lines of change for about 2 to 3 files. My concern is that there is no given benchmark to gauge this additional effort, and what can seem trivial and easy to implement for some might differ between people.

![image](https://user-images.githubusercontent.com/97608304/201884503-2c741b55-15ef-47a6-bea4-382336a41953.png)


</panel>

<panel  header="**2. :fas-info-circle: Are we allowed to change the format of the data file?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/426" expanded>

Is it allowed under the feature freeze to modify the data file into a more suitable format, since it does not change the external behaviour of the application?
</panel>

<panel  header="**3. :fas-info-circle: Request for smoke testing help (Mac/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/200" expanded>

Hi, would appreciate if any Mac/Linux users can help me test my JAR file. The release can be found [here](https://github.com/ConradLew/ip/releases/tag/A-Release). Thanks!

</panel>

<panel  header="**4. :fas-info-circle: Adding local storage text file to gitignore**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/70" expanded>

Am I allowed to add the file used to store tasks locally to .gitignore? Doing on-the-fly manual testing causes changes in the file that in turn sometimes forces me to make a redundant commit before checking out to other branches to do other levels/deliverables.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1233749424" expanded>

Here's my GUI with only the Duke profile picture changed.

![Screenshot 2022-09-01 131041](https://user-images.githubusercontent.com/97608304/187836165-28f742cf-9604-4121-93f8-6288e4414a65.jpg)

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/200#issuecomment-1249458994" expanded>

> Some pictures are not being loaded on Linux (ArchLinux with KDE). ![Screenshot_20220915_223508](https://user-images.githubusercontent.com/22095441/190432193-3bd7a36e-01ef-454f-ae46-af808fe88bcb.png)

Hi @RezwanArefin01 I've reuploaded the bot image in my latest jar file [here](https://github.com/ConradLew/ip/releases/tag/A-Release). Could you try it again to see if the image is fixed? Thanks!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/200#issuecomment-1249994429" expanded>

Re-tested on Linux (Ubuntu), problem fixed after redownloading image. Thanks for earlier help @yuehernkang @RezwanArefin01. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/426#issuecomment-1304576893" expanded>

Noted, thanks prof!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/468#issuecomment-1315309053" expanded>

Noted, thanks prof!
</panel>

</panel>


<panel type="info" header="### 53. CHON..ENCE `@ChongCheeKaiClarence` (9 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Bug in JAR file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/284" expanded>


I tried the input `deadline deadline`, and I got this error message in my JAR file.

But this error does not occur when I run the launcher from the launcher class.

![image](https://user-images.githubusercontent.com/97396452/191438937-1c22b98b-b1ac-4747-a338-c213b2a54582.png)

</panel>

<panel  header="**2. :fas-info-circle: Request for smoke test on Linux and Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276" expanded>

Need help with testing. Thanks, Here is my [release](https://github.com/ChongCheeKaiClarence/ip/releases/tag/A-Release)
</panel>

<panel  header="**3. :fas-info-circle: JAR file too big**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/269" expanded>

Hi, my JAR file is around 34MB, which is very large.
Here is my [release](https://github.com/ChongCheeKaiClarence/ip/releases/tag/A-Release).

I have checked my library/resource files, but I am unsure if there are any unnecessary ones.



</panel>

<panel  header="**4. :fas-info-circle: CheckStyle detecting wrong indentation level**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/131" expanded>

CheckStyle detected an indentation of level 8 even though my indentation is level 4. I accidentally followed both instructions and installed both Gradle and CheckStyle plugin. I am not sure if this might have accidentally caused a bug. Please help.

![image](https://user-images.githubusercontent.com/97396452/188174772-a36a01f7-342d-41d5-b98d-fc23f9d9d1c0.png)

IntelliJ version 2021.3.1.
Java 11.0.13
WinOS.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/269#issuecomment-1252700028" expanded>

It works! Thanks alot!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276#issuecomment-1253526860" expanded>

@Yongbeom-Kim Thanks for the help! I disabled resizing, not sure if that is causing the bug. I tried fixing the issue from the link you sent. Could you help me to check? 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/284#issuecomment-1253528714" expanded>

@rui-han-crh @RussellDash332 Thanks for the help! It's working.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276#issuecomment-1253756869" expanded>

@yuehernkang I realized I made the mistake of not putting the JavaFX block above the dependencies block.
Could you try it again? Thanks for the help! 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/276#issuecomment-1253759327" expanded>

@t1mzzz Thanks for the help! I disabled the resizing.


</panel>

</panel>


<panel type="info" header="### 54. LEE .. JET `@jetlfj` (9 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for Smoke Test (MacOS/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230" expanded>

Hi all, would greatly appreciate some help testing my app on MacOS and Linux.
The jar file is attached [here](https://github.com/jetlfj/ip/releases/tag/A-Release) and the user guide can be found [here](https://jetlfj.github.io/ip/).
Thank you!
</panel>

<panel  header="**2. :fas-info-circle: Failing build (ubuntu-latest) for CI**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/135" expanded>

I am unable to complete **Build and check with Gradle** in **build (ubuntu-latest)** due to the following error, which then causes build (macos-latest) and build (windows-latest) to be cancelled as well.

Any idea what's causing this to happen?

[Here](https://github.com/jetlfj/ip) is my repository and I am on Windows if that matters.

Any help is greatly appreciated!

![image](https://user-images.githubusercontent.com/97273951/188211723-aa395d61-c067-4685-8ef7-07b369414c26.png)
</panel>

<panel  header="**3. :fas-info-circle: 💡 [Guide] Checkstyle with Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/35" expanded>

In case you are having difficulty adding Checkstyle to Gradle (like I did for quite a while), here is a quick guide:

After setting up Gradle in `A-Gradle`,
1. Create a directory `/config/checkstyle` within `ip`.
2. Copy and paste the files `checkstyle.xml` and `suppressions.xml` from [this repository](https://github.com/se-edu/addressbook-level3/tree/master/config/checkstyle) into this directory.
3. Within the `build.gradle` file, add the following:
```java
plugins {
    // other existing plugins
    id 'checkstyle'
}

checkstyle {
    // NOT '8.29'
    toolVersion = '10.2'
}
```
4. `gradlew checkstyleMain` or `./gradlew checkstyleMain` should work now.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/114#issuecomment-1232906176" expanded>

Consider checking this guide out if you are still having trouble: #35 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/135#issuecomment-1236061716" expanded>

Thank you all for the help!

![image](https://user-images.githubusercontent.com/97273951/188259111-8ff4a182-6bf0-438e-9844-183432e9047c.png)

Here's what I did:

1. Open the terminal in IntelliJ (Alt + F12).
2. Enter `git update-index --chmod=+x gradlew`.
3. Commit the changes in Sourcetree (It will say "No changes in this file have been detected, or it is a binary file or it is configured to be ignored by the File patterns").
4. Push the commit.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1236124904" expanded>

Can you try adding a default constructor for Duke? One that does not take in any parameters.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230#issuecomment-1249667146" expanded>

> Hi, everything seems fine on my Mac! 

Thanks for testing it!

> Could not get it working on Linux (Arch)
I'm getting a ~0 width/height window, which is also not resizeable. Maybe setting a minimum size of the window will help?

Thanks for catching this, I've released a new jar file [here](https://github.com/jetlfj/ip/releases/tag/A-Release) to try to remedy it. Could you please help me test it again? Thanks!


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230#issuecomment-1250048491" expanded>

@Nephelite 
I've converted the images to .png and released the new jar file [here](https://github.com/jetlfj/ip/releases/tag/A-Release). Do you mind testing it again? Thanks!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/230#issuecomment-1250313841" expanded>

Thank you all for the help!

Here are the changes I made:
1. Put `stage.setResizable(false);` after `stage.setScene(scene);` in `Main.java`.
2. Replaced the images after converting them again.
3. In `build.gradle`, add the following: 
```
plugins {
    // other existing plugins
    id 'org.openjfx.javafxplugin' version '0.0.10'
}

javafx {
    version = "11.0.2"
    modules = [ 'javafx.controls', 'javafx.fxml' ]
}
```
</panel>

</panel>


<panel type="info" header="### 55. LEON..LENG `@seelengxd` (9 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke testing help [Windows/Linux]**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/212" expanded>

Hello! Here is my [jar](https://github.com/seelengxd/ip/releases/tag/A-Release) and [user guide](https://seelengxd.github.io/ip/)! would appreciate help to test if the jar works on windows & linux. thank you!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/90#issuecomment-1229209705" expanded>

Hmm... I tried to clone your repo and I can't seem to replicate only displaying that message...

- When I run Duke.java directly it seems to work
![image](https://user-images.githubusercontent.com/34371483/187035865-09aec0c8-a94b-48dd-85d0-1b4aabd87158.png)
- When I try to run with gradle I get the `Could not find or load main class seedu.duke.Duke` message (probably need to remove `seedu` in your `build.gradle` -&gt; `application` -&gt; `mainClassName`)

I think you can try recloning the repo`git clone git@github.com:kangqiao322/ip.git directory_name_of_new_clone` and see if it works. :P



</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/100#issuecomment-1230471129" expanded>

try renaming `tests` folder to `test`
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232536980" expanded>

Here is my GUI - changed icons and different colour if it is an error message.

<img width="398" alt="image" src="https://user-images.githubusercontent.com/34371483/187613117-79fe5daf-f8f8-4661-affc-4003742ef292.png">

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/163#issuecomment-1242213388" expanded>

i was looking at this [commit](https://github.com/DarrenCsAcc/ip/commit/76bee7a8d4d81f6bd22961a8230489896e4c18a8) and can't find it on both `master` and `branch-level-7`

hmm

1. is the commit on your branch and not pushed / is branch-level-7 updated?
2. is this branch merged yet?

might be relevant but when i try to clone this repo and look at the graph i see this

<img width="710" alt="image" src="https://user-images.githubusercontent.com/34371483/189399666-67bb3fe9-4298-47f8-9b38-07dabd4b9183.png">

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/212#issuecomment-1249305033" expanded>

Thanks for the help! :D
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/239#issuecomment-1249991866" expanded>

This is kinda a guess (i might be wrong)

https://codecov.io/gh/AY2223S1-CS2103T-T11-4/team-repo

so the name is `team-repo` on code-cov

but your team repo name is `tp`...

```
Pinging Codecov: https://codecov.io/upload/v4?package=github-action-2.1.0-uploader-0.3.1&token=*******&branch=tutorial-adding-command&build=3071873273&build_url=https%3A%2F%2Fgithub.com%2FAY2223S1-CS2103T-T11-4%2Ftp%2Factions%2Fruns%2F3071873273&commit=c355cf412815532ec32ef29d9bf3b05517bdf2db&job=Java+CI&pr=4&service=github-actions&slug=AY2223S1-CS2103T-T11-4%2Ftp&name=&tag=&flags=&parent=
[2022-09-17T03:01:18.215Z] ['error'] There was an error running the uploader: Error uploading to [https://codecov.io:](https://codecov.io/) Error: There was an error fetching the storage URL during POST: 404 - {'detail': ErrorDetail(string='Could not find a repository, try using repo upload token', code='not_found')}
```

and the error is it cannot find the repo and it is trying to find `tp`

i think this is a codecov repo name wrong problem and not really your code 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/258#issuecomment-1250442082" expanded>

Hm... went to peek at your code.

So firstly, based on these 2 extracts, we know one way is we want `Duke.getResponse(input)` to return your duke output to be "incorporated with the duke"

`MainWindow.java`
```
@FXML
private void handleUserInput() {
    String input = userInput.getText();
    String response = duke.getResponse(input);
    dialogContainer.getChildren().addAll(
            DialogBox.getUserDialog(input, userImage),
            DialogBox.getDukeDialog(response, dukeImage)
    );
    userInput.clear();
}
```

`Duke.java`
```
public String getResponse(String input) {
    return "Duke heard: " + input;
}
```

Currently, your duke logic is... in one method in the while loop of `Parser.java`. (I would recommend breaking it up if you have time)

I think the most direct method (**tho prob not the cleanest way**) is to extract out just the logic inside this while loop into a new method first in Parser.java so it takes in a String input and returns the message you want the GUI to send.

Then, inside `getResponse` of `Duke.java`, return the result of calling this new method with the input.

Hope this helps :D
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1263044263" expanded>

https://github.com/AY2223S1-CS2103T-W16-3/tp/pull/9/files

![image](https://user-images.githubusercontent.com/34371483/193179468-484a1b2c-3ddd-47aa-936b-7848bbb94e8e.png)

This looks kinda suspicious.

Jekyll seems to want a [front matter](https://jekyllrb.com/docs/front-matter/) for markdown - [stated here](https://jekyllrb.com/tutorials/orderofinterpretation/#:~:text=Files%20must%20have%20a%20Markdown%20file%20extension%20and%20front%20matter%20in%20order%20for%20Jekyll%20to%20convert%20them.) 

maybe try to add that part back and see if it fixes 🤔 

</panel>

</panel>


<panel type="info" header="### 56. EMIL..I QI `@EmilyOng` (9 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Clarification on bug fixes VS enhancement**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/431" expanded>

# Issue

Currently, in our application, issuing a successful `view` command displays the `Show graphically all expenditure by category` in the command result display.

![Screenshot 2022-11-07 at 6 05 24 PM](https://user-images.githubusercontent.com/21200681/200283063-6f804a0b-6388-4f78-9174-82d27cc82a2f.png)

As users are able to toggle to another tab by means of clicking as well, the command result display is not refreshed and remains at `Show graphically all expenditure by category`.

![Screenshot 2022-11-07 at 6 06 01 PM](https://user-images.githubusercontent.com/21200681/200283224-68eba8fc-6268-4ba5-b49e-db9de9572bdc.png)

# What we think

1. This is a hindrance to the user because they can be confused by the wrong visual feedback provided in the command result box. Thus, we want to update the text in the command box to `Show graphically all income by category` (which is an existing message for `view` command if viewing income entries). Is this considered a violation of feature freeze?
2. When there is no entry found in the application, the size for the list panel enlarges, which is an inconvenience to the user. Can we resize the list panel back to its supposed size?

![Screenshot 2022-11-07 at 6 16 46 PM](https://user-images.githubusercontent.com/21200681/200285788-a3d9bce3-4f26-4990-939d-03a57bd78bc5.png)

</panel>

<panel  header="**2. :fas-info-circle: Request for Smoke-Test on Windows/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/225" expanded>

Hi! Here is my [application jar](https://github.com/EmilyOng/ip/releases/tag/A-Release) and [User Guide](https://emilyong.github.io/ip/), and I would appreciate any Smoke-Test help on Windows/Linux. Thanks!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/57#issuecomment-1225512329" expanded>

https://github.com/nus-cs2103-AY2223S1/forum/issues/46 I think Duke should minimally recognise one date format, and other date formats are optional if you want.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232561360" expanded>

| Duke| |
|---|---|
|![Screenshot 2022-08-31 at 3 18 57 PM](https://user-images.githubusercontent.com/21200681/187617484-54ebdf36-c07a-4a74-9f33-e2c05155d45f.png)|![Screenshot 2022-08-31 at 3 19 06 PM](https://user-images.githubusercontent.com/21200681/187617491-5b6d7a7a-170e-438c-b367-90bd71b7a030.png)|

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/225#issuecomment-1249379524" expanded>

Thanks!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/225#issuecomment-1250010912" expanded>

Thanks everyone!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/431#issuecomment-1305406844" expanded>

Thanks Prof :)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/397#issuecomment-1305848053" expanded>

Hi Prof @damithc, could I check with you about the detection of PPP draft?

> However, RepoSense assigns a line to whoever edited it last. So, if someone else edited those lines after your edited them, that person will be assigned as the author of those lines.

I have added a commit which contains >5 lines at https://github.com/AY2223S1-CS2103T-W17-2/tp/commit/f7e957c1d90f3ae5defb9ab8ee6e1e79c1ddb61f on last Thursday, but the result is not captured on the TP dashboard. There were no others who override my lines too. Thanks!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/397#issuecomment-1306584234" expanded>

I see, thanks!

</panel>

</panel>


<panel type="info" header="### 57. GUJA..LESH `@parth-io` (8 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Penalties for medium to high severity bug**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/435" expanded>

Hi guys, does anybody know what the penalties for bugs of `severity.High` and `severity.Medium` are? We discovered a bug of medium to high severity and are considering updating the JAR release despite the late penalty of -2 per team member. We understand the exact penalties are not released to the students, but if anybody has a rough estimation, it would help us make a decision.

An additional consideration is that the effort marks are likely to be impacted, if testers for the PE are unable to test the feature fully due to the bug (thus affecting the peer tester's evaluation of effort).

If this issue is not ok to be maintained on the forum, we will close it and we can directly email you @damithc .
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179#issuecomment-1244117101" expanded>

Hmm, I cloned your repo to figure out why this is happening.

I got rid of the deprecation warning by changing line 3 of `/gradle/wrapper/gradle-wrapper.properties` to `distributionUrl=https\://services.gradle.org/distributions/gradle-6.2-bin.zip` - basically you need to downgrade your Gradle version.

Also, lines 25-26 in `MainWindow.java` has incorrect file names. They should be:
```
private Image userImage = new Image(Objects.requireNonNull(this.getClass().getResourceAsStream("/images/User.png")));
private Image dukeImage = new Image(Objects.requireNonNull(this.getClass().getResourceAsStream("/images/Duke.png")));
```

Also, I tried commenting out code - a blank stage does show up if you comment out the preceding code in `Main.java`.

I'm not sure what could be causing this issue.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249031907" expanded>

![image](https://user-images.githubusercontent.com/67057645/190584337-46ca454c-3e05-4be6-b0ba-27f906da591c.png)

Tested the commands on Linux (Kubuntu) with Java 11 - the images do not load, but all the commands work well and the file `./data/duke.txt` is loaded on subsequent launches properly
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249045744" expanded>

It's strange, the code you wrote is pretty much identical to mine in terms of the structure and method calls, so I'm not sure why the images are not loading - I'll try cloning the repo and building the jar locally

Yep, there's a difference

![image](https://user-images.githubusercontent.com/67057645/190587575-390c886e-98d2-465d-bfee-15fad876252b.png)
![image](https://user-images.githubusercontent.com/67057645/190587637-24426dc8-299e-4b73-99f8-5a2e6c98f64b.png)

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249086809" expanded>

I think I figured out why the images are not loading (for me at least): 

Try adding the two print lines to `MainWindow::setAnya`. 
```
    public void setAnya(Anya a) {
        System.out.println("Image loading error? " + userImage.exceptionProperty());
        System.out.println("Image loading error? " + userImage.getException());
        anya = a;
        String greet = a.start();
        dialogContainer.getChildren().addAll(
            DialogBox.getAnyaDialog(greet, anyaWelcomeImage)
        );
    }
```

The output I get is:
```
Image loading error? ReadOnlyObjectProperty [bean: javafx.scene.image.Image@36927683, name: exception, value: java.io.IOException: Wrong JPEG library version: library is 80, caller expects 70]
Image loading error? java.io.IOException: Wrong JPEG library version: library is 80, caller expects 70
```

Apparently this has to do with the `libjpeg` library version that's being called by the jar file. @RezwanArefin01 do you have the same issue?

Dependency versions in `build.gradle` are as expected. I can't figure out how to force Java to bundle this specific version of `libjpeg` (also this issue doesn't happen for my own repo)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/217#issuecomment-1249136473" expanded>

Wow, this is a tricky problem. Just curious, where did you change the version for the `.fxml` files? In `build.gradle`?

Is it still unresolved for the other students?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/435#issuecomment-1306681308" expanded>

Ok thank you for the reply Prof!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/499#issuecomment-1326449381" expanded>

'Padding' is a term specific to project management as well.

> The padding refers to extra time added to a schedule that isn’t really needed but that is added just to feel confident in the estimate. The impact of padding could be significant on project schedule. The quality of the estimates directly affects whether or not the project can meet scope, cost and schedule commitments. The accumulation of padding all the tasks can result in overly cautious project schedules and uncertainties across the project schedule.

from [here](https://svprojectmanagement.com/avoiding-problem-of-padding)

I think the question meant to contrast the idea of having a buffer after a realistic estimate for the project's completion schedule, instead of including the buffer as 'padding' in the project's completion time, which would then make the completion time an unrealistic estimate.

Edit: grammar correction
</panel>

</panel>


<panel type="info" header="### 58. SIM ..AMIN `@Benjamin-Sim` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Naming Convention for JAR Files**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/357" expanded>

Hi does this module require us to follow a specific naming convention for JAR filenames? E.g. UpperCamelCase, camelCase, all lowercase, etc.
</panel>

<panel  header="**2. :fas-info-circle: Sourcetree cannot push gradle.yml to fork**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165" expanded>

When trying out A-CI, I created the gradle.yml file on my Master branch on my local machine (I'm using Windows). However, Sourcetree gave me this error when I tried to push the changes to my fork.

![Capture](https://user-images.githubusercontent.com/92283593/189474496-bac4cbcf-d238-4db4-8343-fa005d77cd12.PNG)

It seems that GitHub recognizes that the path `.github/workflows` contains workflow files and hence denies my Sourcetree client from pushing files to that directory since my Sourcetree client doesn't have the required 'workflow' scope permissions.

I tried looking in my GitHub settings to see if I can give Sourcetree 'workflow' scope permissions but I couldn't find anything.

Any help would be appreciated, thanks!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165#issuecomment-1242680208" expanded>

> @Benjamin-Sim Something related: When you create a GitHub personal access token (PAT), you can specify which actions it can be used for.

Hi Prof @damithc, yes I've also tried creating a PAT with the 'workflow' permissions. But I couldn't find a place to enter it when linking my Sourcetree client with my GitHub account.

I followed Option 1 at [this guide](https://se-education.org/guides/tutorials/sourcetree.html#on-windows) to link Sourcetree with my GitHub account, and I was only prompted to enter my GitHub email and password to login. After that, my Sourcetree client was automatically linked and I wasn't asked to input any PAT.

Is there another way to link Sourcetree with GitHub that allows me to specify what PAT to use?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165#issuecomment-1242695320" expanded>

> [This](https://community.atlassian.com/t5/Sourcetree-questions/How-do-I-use-a-personal-access-token-PAT/qaq-p/1263836) and [this](https://community.atlassian.com/t5/Sourcetree-questions/Adding-a-github-personal-access-token-to-sourcetree/qaq-p/1755393) post from the Atlassian forums mention placing the PAT in your password field when using basic auth. Perhaps try that?
> 
> Alternatively, if all else fails, you could manually add the file from the GitHub website and pull to refresh changes.

Hi @kxrt, I tried using basic auth using my PAT as the password and it works! Thanks for your help!

Although, I wonder how other students who use the regular OAuth push workflow files. I'm guessing there is a cleaner way of granting 'workflow' permissions?

The awkward thing I notice about PATs is that GitHub recommends that you create them with an expiry date. So it looks like I have to generate a new PAT and relink Sourcetree with GitHub everytime the PAT expires. In contrast, the regular OAuth doesn't seem to have this expiry date issue.

So I'm curious if there are any other solutions to this problem.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165#issuecomment-1242724295" expanded>

> Glad to see it worked!
> 
> One way to get past the PAT expiry issue is using Git CLI and connecting over SSH.

I see, but does that use OAuth? And does it give 'workflow' permissions too?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/165#issuecomment-1242912205" expanded>

> > > Glad to see it worked!
> > > One way to get past the PAT expiry issue is using Git CLI and connecting over SSH.
> > 
> > 
> > I see, but does that use OAuth? And does it give 'workflow' permissions too?
> 
> OAuth is a separate authentication system from SSH. SSH keys are generated on a different page from OAuth tokens in your Settings. And yep, it does give the `workflow` permission - I use it myself. I recommend reading up on [this](https://stackoverflow.com/questions/67077837/in-what-ways-is-an-ssh-key-different-from-tokens-for-git-authentication) post for a quick description of the differences in the two. PAT is probably safer since it's limited in comparison.

Ah I see, thanks for explaining!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/212#issuecomment-1248856180" expanded>

Hi @seelengxd, your jar works fine on Windows 👍.

Only issue is that these warnings are printed to the console every time I enter a command:

![Capture](https://user-images.githubusercontent.com/92283593/190546461-73fac860-4f4b-4790-88a1-d6ee9c721b38.PNG)

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/357#issuecomment-1284079788" expanded>

Ok thanks prof!
</panel>

</panel>


<panel type="info" header="### 59. TAN ..RYAN `@ketamethane` (8 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke testing help (Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/216" expanded>

Hi, I need smoke testing help on the Linux OS. The [jar](https://github.com/ketamethane/ip/releases/tag/A-Release) file and [UG](https://ketamethane.github.io/ip/) are here. Will appreciate any help, thank you!
</panel>

<panel  header="**2. :fas-info-circle: Screenshot appears on README preview, but not on deployed page**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/205" expanded>

As the title goes.
Here is the code for my README editing page.

![edit](https://user-images.githubusercontent.com/88729540/190452199-05ffbf21-8df6-436d-9af1-805204197b52.jpg)

This is the preview page with the directory of docs included.

![preview](https://user-images.githubusercontent.com/88729540/190452490-9b1c88f2-37c2-4a35-8d3f-259d0227860b.jpg)

And this is the deployed website.

![deployed page](https://user-images.githubusercontent.com/88729540/190449612-e9458767-c56f-4fb5-b228-95d4be892363.jpg)

I've tried looking through the past issues and googling it, but to no avail. Changing the image file path to become relative (`/docs/Ui.png`) did not work either. Would appreciate any help, thank you!
</panel>

<panel  header="**3. :fas-info-circle: Checkstyle test failed (Unable to create root module)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/202" expanded>

I'm using Windows 10 and the latest version of Intellij.
I've followed the instructions in the issue #35 and I have fetched the external resources as well.
Yet, my code failed the checkstyle section of the Java CI.


This is what is shown in the command prompt.
![cmd](https://user-images.githubusercontent.com/88729540/190425771-61e84db3-4912-4406-b4b2-b28760153011.jpg)

Any help is appreciated, thank you,

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/202#issuecomment-1248191691" expanded>

I added it in as well, but I still faced the same error in the command prompt. When I ran `checkstyleMain` in the `build.gradle` file, this is what I saw
![ss](https://user-images.githubusercontent.com/88729540/190431803-16913165-b5cb-4e94-99b4-a0cef7ea31c0.jpg)

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/202#issuecomment-1248231893" expanded>

Hmm... It was strange. I had the same directory as you. However, after some refactoring and undoing those refactoring, the issue sort of resolved by itself. I can see all my checkstyle issues now. Thank you @hauchongtang 😄 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/205#issuecomment-1248452368" expanded>

Issue solved, thank you so much! @RezwanArefin01 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/216#issuecomment-1249038168" expanded>

Noted, thanks for helping with the check! @RezwanArefin01 😃 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/336#issuecomment-1272533797" expanded>

For some reason, Window line endings are in \r\n . 
Could you try going into IntelliJ `File` > `Settings` > `Code Style` > `Line Separator` and set it to \n ?
![image](https://user-images.githubusercontent.com/88729540/194757205-78aa6370-3833-4993-ab56-eeb3276a1330.png)

Then highlight all the lines with the issue flagged out by the CI.
Click on `CRLF` or whatever is showing and change it to \n format
![image](https://user-images.githubusercontent.com/88729540/194757273-7b732f70-fc08-422a-bd0b-ecf95dcebbcb.png)

</panel>

</panel>


<panel type="info" header="### 60. TEE ..TENG `@Puakii` (8 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: UG bugs in PE**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/440" expanded>

Should you report UG bugs in phase 1 or 2? It seems like both phase can report UG bugs?
</panel>

<panel  header="**2. :fas-info-circle: Sending pull request to the wrong team repo**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/362" expanded>

Is there any issues if I send a pull request to another team's repo by accident and immediately closing it?
</panel>

<panel  header="**3. :fas-info-circle: Should you change commit message if you break git conventions**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/69" expanded>

Should I update the commit message if I have accidentally break git conventions, i.e. adding a full stop after my commit?

If yes, how should I go about it?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/69#issuecomment-1227390358" expanded>

@xiaobill8 what if its an older commit and it has already being pushed?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/69#issuecomment-1227671914" expanded>

okay thanks guys for the input!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/337#issuecomment-1272782455" expanded>

Yes, you can merge master into your branch and continue to add things into that branch. Pulling from the upstream master into your branch allows you to fix any merge conflicts and be updated with the latest code as well as keep whatever you are doing in that branch
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/362#issuecomment-1286616397" expanded>

Thanks @damithc 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/440#issuecomment-1311319761" expanded>

okay thanks prof!
</panel>

</panel>


<panel type="info" header="### 61. ARYA..DEEP `@adeearyaa` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Azulu JDK download**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/198" expanded>


![Screenshot 2022-09-15 at 8 01 09 PM](https://user-images.githubusercontent.com/87979157/190398564-85635f6c-289e-4d15-9bf1-7a8730baf728.png)
Hi my Mac is not M1 but im stil facing the gibberish issues when running my project from gradle but not when i run from intellij can anyone help me with this
</panel>

<panel  header="**2. :fas-info-circle: A-Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/55" expanded>

Hi I just wanted to check how do we merge the gradle branch with our main branch because even after I have forked the ip repo it only copied over the original branch not the add-gradle branch or is there something else we have to do?

</panel>

<panel  header="**3. :fas-info-circle: text-ui testing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/27" expanded>

Hi i used the dosunix command to fix the possible line error even though my expected and actual files look the same , however its still saying test case failed?
![Screenshot 2022-08-18 at 5 45 23 PM](https://user-images.githubusercontent.com/87979157/185365503-0006f6c4-ded4-4504-9b4b-dc6ab1bdf54c.png)


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/27#issuecomment-1219295482" expanded>

oh where do i need to add the -w?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/27#issuecomment-1219304687" expanded>

Ah okay , actually in my case i used diff -B to help it pass the test case diff -w did not seem to resolve my issue. Thanks for the help!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/152#issuecomment-1247963096" expanded>

Hi im having the same problems that I cant run my application using the gradle .run , how did you solve that problem?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/125#issuecomment-1248003659" expanded>

Hi I installed azul jdk but my java version has not changed on my mac?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/198#issuecomment-1248038292" expanded>

Hi it works now thanks!
</panel>

</panel>


<panel type="info" header="### 62. QIU ..ASON `@jasonqiu212` (8 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Git conventions for tp**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/320" expanded>

Hello everyone! I was wondering if there's a strict guideline for the commit messages in our `tp`.

In the [Git conventions](https://se-education.org/guides/conventions/git.html) site, it provides a format of `{Optional scope}: {description of change}`. However, the site also mentioned about the usage of [Conventional Commits Format](https://www.conventionalcommits.org/en/v1.0.0/), which looks like `commit type(optional scope): description of change`.

Our group wants to use the conventional commit format. Thus, we were wondering if there is a strict requirements on the commit message format for the `tp` (i.e. There's a script that's marking the format).

Thank you!

</panel>

<panel  header="**2. :fas-info-circle: Typo in Tutorial: Adding a command**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/288" expanded>

Hello! I believe I found a typo in [Tutorial: Adding a command](https://nus-cs2103-ay2223s1.github.io/tp/tutorials/AddRemark.html) under the section **Parse user input**.

In the code snippet for `RemarkCommandParser.java`, the website displays the following:
```java
public RemarkCommand parse(String args) throws ParseException {
    requireNonNull(args);
    //...
}
```

However, `requireNonNull` is not defined in the `tp` codebase. Is this a typo? Does it refer to the `requireAllNonNull` method instead?

Thank you!
</panel>

<panel  header="**3. :fas-info-circle: Storing start and end date time in `Event`**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/82" expanded>

Hi everyone, 

For `Level-8`, I noticed that the instructions only mentioned to store **deadline** dates as a `java.time.LocalDateTime`. 

Should we implement the same feature to store date time for `Event` as well? And if so, would it be better to store both a start and end date time to indicate an interval? Could we add additional flags to the `event` command to input the start and end date times (eg. `/start` and `/end`)? 

Thanks!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/82#issuecomment-1229216817" expanded>

Thank you everyone for your advice! Will consider adding an additional flag :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/288#issuecomment-1254568243" expanded>

Ah yes, I just realized too, after referring from the sample code. Thanks for the reply!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/320#issuecomment-1264208466" expanded>

Okay, thank you for clarifying prof!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/317#issuecomment-1264598672" expanded>

Hi @pratham31012002,

I cloned your [repository](https://github.com/pratham31012002/tp) onto my machine and all tests seem to work fine. 

For the `getImage_exitingImage()` in the `AppUtilTest` class, it also passes.

![Screen Shot 2022-10-02 at 5 46 36 PM](https://user-images.githubusercontent.com/25262042/193448058-d52c1b9a-7e28-48c6-a354-309ce567c28e.png)

Perhaps you would want to try cloning your repo again and try running the tests on a fresh build?

My computer specs:
- M1 Pro MacBook Pro
- Same Java version
```
openjdk version "11.0.16" 2022-07-19 LTS
OpenJDK Runtime Environment Zulu11.58+15-CA (build 11.0.16+8-LTS)
OpenJDK 64-Bit Server VM Zulu11.58+15-CA (build 11.0.16+8-LTS, mixed mode)
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/500#issuecomment-1327976758" expanded>

Hi @zsiggg, To be absolutely safe, I think after the release of the finals grades is a good time.
</panel>

</panel>


<panel type="info" header="### 63. FARR..ALIM `@sugiyem` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Library request: TestFX**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/382" expanded>

## Library

[TestFX](https://github.com/TestFX/TestFX)

## Purpose

Testing the UI of the application

## License

[EUPL](https://github.com/TestFX/TestFX/blob/master/LICENSE.txt)

</panel>

<panel  header="**2. :fas-info-circle: Request smoke test for MacOS**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/253" expanded>

Hi all, would really appreciate if anyone can help me test my [app](https://github.com/sugiyem/ip/releases) on MacOS. You can view my User Guide [here](https://sugiyem.github.io/ip).

Thank you!

</panel>

<panel  header="**3. :fas-info-circle: Request smoke test for MacOS/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242" expanded>

Hi all, would really appreciate if anyone can help me test my [app](https://github.com/sugiyem/ip/releases) on MacOS and Linus. You can view my User Guide [here](https://sugiyem.github.io/ip).

Thank you!

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232623245" expanded>

Here is my GUI. Modified the profile pictures and dialog box.

<img src="https://user-images.githubusercontent.com/90848662/187629448-0cb88355-9204-4142-948e-6baa57df7c16.png" height=75% width=75%/>

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250054552" expanded>

@Nephelite thank you for the suggestion. I've updated the jar file.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250268639" expanded>

@Nephelite Thanks for the input. Could you help me check my updated [jar](https://github.com/sugiyem/ip/releases) file?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250317832" expanded>

Thanks all!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/253#issuecomment-1250326042" expanded>

@huzaifa1712 thanks!!
</panel>

</panel>


<panel type="info" header="### 64. JANE..TENG `@janelleljt` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request help for smoke testing mac and linux OS**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/277" expanded>

You can find the latest version [here](https://github.com/janelleljt/ip/releases/tag/v.02) and the user guide [here](https://janelleljt.github.io/ip/). Thanks in advance!
</panel>

<panel  header="**2. :fas-info-circle: Getting Warning of Unsupported JavaFX configuration**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111" expanded>

Hi all, I'm having this issue where I cannot run `./gradlew run` via CLI due to a warning: 
> `WARNING: Unsupported JavaFX configuration: classes were loaded from 'unnamed module @7d59e741'`

When running the ip using the gradle toolbar, a `Hello World` window does pop up in spite of the same warning received. 

Any help appreciated thanks!

![image](https://user-images.githubusercontent.com/75255420/187578878-490fa1d9-e3f7-4e5d-82b1-c47276d54f06.png)
</panel>

<panel  header="**3. :fas-info-circle: Unable to start addressbook.jar**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/94" expanded>

I downloaded addressbook.jar from [this link](https://github.com/se-edu/addressbook-level3/releases), but unable to get it running on my computer. I have tried:
1. Clicking the file, but (I am on Windows) it prompts me to select an application to run it on. 
2. Typing `java -jar addressbook.jar` into my command line when in the same directory as addressbook.jar file, but gives me the following error: 
![image](https://user-images.githubusercontent.com/75255420/187077574-946f82b3-59b3-4c21-a107-ffc1932d742a.png)

Any help appreciated thanks!

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/94#issuecomment-1229469559" expanded>

Hi prof, this is the output. 
![image](https://user-images.githubusercontent.com/75255420/187078605-861520b5-e338-4e4d-aa9d-e2282eed327c.png)

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/94#issuecomment-1229806473" expanded>

@damithc Hi prof, it worked when on Windows. Thanks a lot! I will now close the issue. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111#issuecomment-1232467880" expanded>

@deepimpactmir Hi, here's my build.gradle

```
plugins {
    id 'java'
    id 'application'
    id 'com.github.johnrengelman.shadow' version '5.1.0'
    // id 'checkstyle'
}


repositories {
    mavenCentral()
}

dependencies {
    testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
    testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'
    String javaFxVersion = '17.0.1'

    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'

}

test {
    useJUnitPlatform()

    testLogging {
        events "passed", "skipped", "failed"

        showExceptions true
        exceptionFormat "full"
        showCauses true
        showStackTraces true
        showStandardStreams = false
    }
}

application {
    mainClassName = "bobthebot.utils.Launcher";
}

shadowJar {
    archiveBaseName = "bob"
    archiveClassifier = null
}

run{
    standardInput = System.in
}

//checkstyle {
//    toolVersion = '10.2'
//}
```

I followed the tutorial [here](https://se-education.org/guides/tutorials/javaFxPart1.html) but changed 
> `String javaFxVersion = '11'`
to 
> `String javaFxVersion = '17.0.1'`
because version 11 was not working initially for me as well.

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111#issuecomment-1232487014" expanded>

@Hikoya when I used 11 I got this haha :"
![image](https://user-images.githubusercontent.com/75255420/187600825-fad7d092-e56f-4e86-86a1-ba7d8428f86d.png)

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111#issuecomment-1232489362" expanded>

@kxrt I am running from `Launcher.java` hahaha :" It's ok I tried using @deepimpactmir 's reccomendation and it doesn't give me a warning when I use the Gradle toolbar, but I still cannot use CLI :". I'll just use the toolbar for now, thanks everyone!
</panel>

</panel>


<panel type="info" header="### 65. LIM ..O EN `@qiaoen17` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to open jar file on windows using Java SE binary but able to open jar file on IntelliJ**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/249" expanded>

Hello, I went to try to fix my Storage.java and Duke.java as it was not generating text files on other computers, basically an issue with the save function in my latest commit. Before, I was able to run the jar file generated via Java SE binary without the changes, but now I am unable to and the jar file generated only runs in IntelliJ when I run duke.jar.

I tried running it in ubuntu via java -jar duke.jar but got the error below:
![Screenshot (235)](https://user-images.githubusercontent.com/92434807/190889322-015e0d1e-f29d-490f-bd28-4ee82ab47e3e.png)

Not very sure how to solve this error and I can't really find solutions online either.

</panel>

<panel  header="**2. :fas-info-circle: Unable to open jar file on my own computer**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/236" expanded>

I built my jar file using shadowJar and tried opening it using Java(TM) Platform Binary, but it does not open. So I tried launching it through intelliJ and it gives me the following error: 

![Screenshot (232)](https://user-images.githubusercontent.com/92434807/190697800-490af049-2bab-4f2c-958e-de36acc3b955.png)

I went to check for the suggested fix from another post but I already fixed it:

![Screenshot (233)](https://user-images.githubusercontent.com/92434807/190698150-b3e7bfff-e588-4213-ab7a-c0f3c662cd6c.png)

The error says it was caused by `NullPointerException` so I tried looking into the line where it says it has an error.

![Screenshot (231)](https://user-images.githubusercontent.com/92434807/190698804-3627de9a-e10e-4c79-b409-e686c04a145b.png)

I tried removing line 20, but it still gives me the same error message` NullPointerException` occurred at line 20, so I'm not sure what to do now. I have tried searching online and found the following website:
[Stackoverflow link](https://stackoverflow.com/questions/55123711/javafx-error-exception-in-application-start-method)

But I'm not sure how to follow the fix there. If anyone has encountered this issue and solved it, please help.

</panel>

<panel  header="**3. :fas-info-circle: A-CodingStandard tag cannot be detected in iP progress dashboard**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/137" expanded>

I have tagged A-CodingStandard as shown below, and merged all branches to master, but I'm still not sure why the tag isn't detected. Any help would be appreciated.


![Screenshot (218)](https://user-images.githubusercontent.com/92434807/188257450-fe7e0b31-4884-4095-aa45-59220626c266.png)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/137#issuecomment-1236062912" expanded>

Ah okay, thank you for the help!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/236#issuecomment-1250037421" expanded>

It works now 👍 Thank you so much!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/249#issuecomment-1250217541" expanded>

Hello, I saw the issue #118 and I concluded ubuntu most likely does not support GUI. To clarify, I tried running the jar file on ubuntu as I was unable to run jar files on my command prompt and I wanted to see why **duke.jar is able to open and run on IntelliJ** but **not on Java SE binary** . I thought the error was related to why duke.jar would not open on Java SE Binary, but I see that is not the case. 

I'm not sure how to debug why it does not run on Java SE binary but it is able to run in IntelliJ, so I think that would be my main issue now :(

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/249#issuecomment-1250316430" expanded>

@damithc Nope, I'm using windows. 

![Screenshot (236)](https://user-images.githubusercontent.com/92434807/190906190-4195aede-9147-47fd-b53b-94d2ffe3b651.png)

Unable to run using Java SE Binary 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/249#issuecomment-1250345932" expanded>

Ah thank you, I'll close this issue then.
</panel>

</panel>


<panel type="info" header="### 66. SNG ..OREN `@misterpuffin` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Unable to open DISPLAY on WSL2 after adding Gui**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/150" expanded>

Hi everyone, I was trying to add JavaFX to my Duke application. However, after following the tutorial I was unable to run my app with ```./gradlew clean run``` I suspect it might be an issue with my WSL2 installation, as I am using the jdk stored in my WSL2.

Here is the error message I got.

```
> Task :run FAILED
Authorization required, but no authorization protocol specified
Exception in thread "main" java.lang.UnsupportedOperationException: Unable to open DISPLAY
        at com.sun.glass.ui.gtk.GtkApplication.lambda$new$6(GtkApplication.java:173)
        at java.base/java.security.AccessController.doPrivileged(Native Method)
        at com.sun.glass.ui.gtk.GtkApplication.<init>(GtkApplication.java:171)
        at com.sun.glass.ui.gtk.GtkPlatformFactory.createApplication(GtkPlatformFactory.java:41)
        at com.sun.glass.ui.Application.run(Application.java:144)
        at com.sun.javafx.tk.quantum.QuantumToolkit.startup(QuantumToolkit.java:258)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:269)
        at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
        at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
        at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
        at java.base/java.lang.Thread.run(Thread.java:829)

FAILURE: Build failed with an exception.

```

* Your development environment (IntelliJ version, Java version, OS, ...)
```
openjdk 11.0.16 2022-07-19
OpenJDK Runtime Environment (build 11.0.16+8-post-Ubuntu-0ubuntu120.04)
OpenJDK 64-Bit Server VM (build 11.0.16+8-post-Ubuntu-0ubuntu120.04, mixed mode, sharing)
```


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/97#issuecomment-1229889608" expanded>

If you're trying to edit the last commit message, you can do `git commit --amend -m "Your message"`. However, when you try to push it to a remote repository you'll need to force push to override the changes. `git push --force-with-lease origin master` is recommended to prevent override someone else's work on the remote repository.

Actually there seem's to be a previous discussion here https://github.com/nus-cs2103-AY2223S1/forum/issues/69 which might be of more help.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/150#issuecomment-1239125957" expanded>

thanks everyone for the help! I ended up follow @zupey's advice and managed to get it working :)

closing the thread for now!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/255#issuecomment-1250789592" expanded>

hello i just took a look at your repo! and it seems like you're putting your resource folder in main/java/Duke instead of main/resources.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/299#issuecomment-1255823878" expanded>

hey! from your ip repo, it seems like the `MainWindow.fxml` in `src/main/resources/view` folder has JavaFX version set to 18. 

You can see this in `xmlns="http://javafx.com/javafx/18"`. Instead, you can try changing it to  `xmlns="http://javafx.com/javafx/8.0.171"` , which is the same version used in your `DialogBox.fxml`

hope this helps!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/297#issuecomment-1256892250" expanded>

It seems as though it is failing because you're trying to push tags already in your remote repository. Glad you managed to solve the issue, reminder to close the issue if everything is okay!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/308#issuecomment-1257990895" expanded>

I think it might be more convenient and safer to `git reset` to the last commit before the merge. You can use `git log` to find the hash of the commit. 

As to how to pull the master branch, assuming you've added your team repo as a remote repo named 'upstream', you can `git fetch upstream` and then `git reset --hard upstream/master`. I don't really recommend this though in case you lose work that's on your master branch.
</panel>

</panel>


<panel type="info" header="### 67. CHEN.. YEE `@PeiYee88` (7 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Physical venue of final exam**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/493" expanded>

Hi! I would like to ask where is the venue of tomorrow's final exam and has the seating arrangement plan released yet? Thank you!
</panel>

<panel  header="**2. :fas-info-circle: Answers for practice papers**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/482" expanded>

Hi! I would like to ask if there are any answer keys provided to the practice papers on Examplify. If there is, where can I find them?
</panel>

<panel  header="**3. :fas-info-circle: Unable to merge pull requests into teams repo**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315" expanded>

<img width="686" alt="image_2022-09-29_23-35-04" src="https://user-images.githubusercontent.com/77477618/193075921-1ac60c88-d760-48c2-9bd9-e7fa480ebcab.png">

Attached is a screenshot while I try merging pull requests into the master branch of my team's repo. Anyone has any idea what the issue is here? Thanks in advance!

Here's the link to the page: https://github.com/AY2223S1-CS2103T-W16-3/tp/pull/9
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1249603225" expanded>

<img width="301" alt="Ui" src="https://user-images.githubusercontent.com/77477618/190694375-09681f1c-3049-406f-bc2a-013be9d6c889.png">

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1262487158" expanded>

@RussellDash332 yep it failed when i try running ci tests.
<img width="733" alt="image_2022-09-29_23-57-06" src="https://user-images.githubusercontent.com/77477618/193080935-9e38d297-7246-4e48-ad43-2efd904610c2.png">

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/315#issuecomment-1262528065" expanded>

@RussellDash332 Thanks for the help! My CI passes but now the PR request page still shows unable to merge due to missing deployment page. I have already configured it under Settings > Page and set it to master /doc, and there is a Github page for my repo.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/482#issuecomment-1324620602" expanded>

Thank you so much!
</panel>

</panel>


<panel type="info" header="### 68. SIM ..XTER `@dexter-sim` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Is it ok to reject severity downgrade if I accept the bug rejection?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/466" expanded>

The developer team rejected the bug report and lowered the severity of the bug report. 

However, only justification for rejection is given and not for lowering severity.

Is it ok to reject the lowering severity but accept that the bug report is rejected?
</panel>

<panel  header="**2. :fas-info-circle: Does notInScope count towards accuracy?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/465" expanded>

If the type.* and severity.* match, does not in scope count towards accuracy?

<img width="752" alt="image" src="https://user-images.githubusercontent.com/95021334/201850944-cc706e71-effd-46ea-98ca-b4b8ad39b77f.png">

</panel>

<panel  header="**3. :fas-info-circle: Request smoke test for Linux system**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/241" expanded>

Hi, I would really appreciate it if anyone can help me run some smoke tests on Linux.

https://github.com/dexter-sim/ip/releases/tag/v0.3

Thank you!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/104#issuecomment-1231072749" expanded>

I had this problem on my Mac as well. 
Following this [advisory](https://nus-cs2103-ay2223s1.github.io/website/admin/programmingLanguages.html) in the textbook solved the issue for me.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/241#issuecomment-1257219828" expanded>

Thank you for testing.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/466#issuecomment-1314887181" expanded>

Thank you for the clarification.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/465#issuecomment-1314888000" expanded>

Thank you for the clarification. 
</panel>

</panel>


<panel type="info" header="### 69. TIO ..EZRA `@e1010101` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Policy regarding reuse of your own code**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/349" expanded>

I was wondering what the necessary steps were to use my code in the TP. I have a code snippet from one of my other projects that I would like to use, but I could not find any information regarding this on the module website (or I missed it). 

What is the policy regarding this?
</panel>

<panel  header="**2. :fas-info-circle: website-adapted Increment describes nonexistent problems**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/322" expanded>

Under the tP dashboard (team view), the tracker describes issues regarding my team's (CS2103T-T08-1) website-adapted increment, despite them already being fixed. For example, one issue mentioned was `[README.md] CI banners not pointing to own project;`. 

However, this has already been amended.

Is this error due to syncing issues, or is there some other reason?
</panel>

<panel  header="**3. :fas-info-circle: Request to use AIML-related libraries for better user interaction**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/183" expanded>

## Library

Project AB, an ALICE chatbot implementation [(Library URL)](https://mvnrepository.com/artifact/org.goldrenard/ab)
Sanmoku, dependency for Project AB [(Library URL)](https://mvnrepository.com/artifact/net.reduls.sanmoku/sanmoku)
Sanmoku-feature-ex, dependency for Project AB [(Library URL)](https://mvnrepository.com/artifact/net.reduls.sanmoku/sanmoku-feature-ex)
SLF4J, dependency for Project AB [(Library URL)](https://mvnrepository.com/artifact/org.slf4j/slf4j-api)
Log4J over SLF4J, dependency for Project AB [(Library URL)](https://mvnrepository.com/artifact/org.slf4j/log4j-over-slf4j)

## Purpose

AIML (Artificial Intelligence Markup Language) is an XML language for specifying chatbot content. By using AIML files, I can customize my chatbot's responses to various questions easily. AIML also allows for other functionalities such as remembering/teaching certain words to my chatbot.

## License

Project AB is covered by the [GNU Lesser GPL license](http://www.gnu.org/licenses/lgpl.html), as outlined in the website [here](https://code.google.com/archive/p/program-ab/).

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/6#issuecomment-1214272840" expanded>

From my understanding, a "finally" block always runs regardless of whether an exception occurs. Quoting from [this post](https://stackoverflow.com/questions/1158667/why-use-finally-in-try-catch) on StackOverflow: 

_"...Finally will always run (barring program crash). If the function exits inside of the try catch block, or another error is thrown in either the try or the catch, the finally will still execute. You won't get that functionality not using the finally statement."_

Here's an example from [Oracle Docs](https://docs.oracle.com/javase/tutorial/essential/exceptions/finally.html) where "finally" is used to perform cleanup (which you want to do regardless of an exception occurring or not):

```
finally {
    if (out != null) { 
        System.out.println("Closing PrintWriter");
        out.close(); 
    } else { 
        System.out.println("PrintWriter not open");
    } 
    if (f != null) {
	    System.out.println("Closing FileWriter");
	    f.close();
	}	
} 
```

So "catch" and "finally" have different purposes as code inside "catch" blocks are only executed when an exception occurs, while "finally" contains code that runs regardless of any exceptions. Note that putting the cleanup code outside a "finally" in the above example would result in the cleanup code not being executed since the program would terminate before.

Hope this helps!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/183#issuecomment-1245284894" expanded>

Thank you prof, I will update in the future!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/322#issuecomment-1264277317" expanded>

Thanks all, closed as the issue is resolved.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/349#issuecomment-1281787006" expanded>

Ok, will do! Closed as this is answered.
</panel>

</panel>


<panel type="info" header="### 70. NEAL..CHEN `@nealetham` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: PE Phase 3 Deadline confusion**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/461" expanded>

In the module website, it states that the deadline for PE phase 3 is on Fri, Nov 18th 2359.

![image](https://user-images.githubusercontent.com/49066882/201819469-2a00002b-6420-4b64-b63d-b627e47b8e64.png)


However, in the email sent by prof, it's by Thu, Nov 17th 2359.

![image](https://user-images.githubusercontent.com/49066882/201819529-9d3a2cbd-20bb-4553-9ad1-2985e976628d.png)

It could possibly be a typo?

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/86#issuecomment-1229400456" expanded>

Hi, I believe it to be the case too. If I'm not wrong, associations simply defines a relationship/connection between any two classes (IS-A or HAS-A). For the case of composition and aggregation, it models a HAS-A relationship.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/330#issuecomment-1272450295" expanded>

@carriezhengjr From the codecov [documentation](https://docs.codecov.com/docs/commit-status#patch-status), it seems to suggest that the codecov/patch check checks for any test coverage for the new lines of code you've added for that particular commit/pr. 
i.e. the lines of code you've added in `HelpWindow.java` were uncovered as you have not added any tests for them, therefore it fails the check.

I also faced the same situation in my individual repo and my pr, and I think the reason why it's not flagged out in the pr is because that it does not run the codecov/patch, though it still flag it under the impacted files table. I could be wrong, but that's just my interpretation of it.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/330#issuecomment-1272494611" expanded>

Hmm, personally, I wouldn't see it as an critical issue per se but more of a warning. I have not resolved it, but I'm guessing that in the same commit/pr you just have to write test cases which tests the lines of code that you have written.

You might not know which lines of code that you have to test before making the commit. But once you fail the check you can use codecov to see the lines that's required of you to test. For your `HelpWindow.java` file, [here](https://app.codecov.io/gh/carriezhengjr/tp/commit/332f56579f48794b5a4c9f24280cc4bf895a28fc/src/main/java/seedu/address/ui/HelpWindow.java) are the lines u have to test.

Hope this helps!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/338#issuecomment-1273258711" expanded>

I think the diagram serves to remind students what an activity diagram is. If I'm not wrong, this question will be discussed during tutorial. You can check your answer then.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/401#issuecomment-1296471741" expanded>

Hi all, I'm from the same group as @nseah21. To provide more context, `Command A` was implemented prior to `Command B` i.e. they were not done in parallel.

It was only after the implementation of `Command A`, did we see the value in implementing `Command B`, which was similar to `Command A` in functionality, but provided much better convenience and use cases for the user. As such, we could argue that `Command A` was the precursor to `Command B`.

Though they are not exactly the same feature, both achieve similar outcomes, with only minor differences as mentioned by @nseah21. We initially kept both of them as we felt that users could benefit from having both commands. However, seeing as it has caused confusion among our PE testers, we are now unsure if giving the user the option of having both commands, outweigh the value-add of having only a single "more powerful" `Command B`.

This brings in another interesting topic that is, in software design, is giving the user more options to perform the same tasks better? Or is it better to limit them to prevent confusion.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/461#issuecomment-1314727623" expanded>

Whoops my bad. Thank you prof!
</panel>

</panel>


<panel type="info" header="### 71. XIAO..BILL `@xiaobill8` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: [PE] Documentation for a feature missing completely**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/460" expanded>

If the documentation for a feature is missing completely, would it be considered a Documentation bug or a Feature flaw?
From the tester's perspective, there is no information in the User Guide whatsover regarding the feature, so it would seem as a Feature Flaw.

For context, a parameter for a command was missing in both the error message and documentation, so a feature in the UI could not be changed at all without prior knowledge of the parameter.
Would it also be considered a high severity? (Since in the PE readiness quiz, even a slight misspelling of a parameter was considered an Medium)
<img width="1353" alt="image" src="https://user-images.githubusercontent.com/58042582/201738431-a4f50e26-04fd-4a6a-a6f9-6fa3b57183f3.png">

</panel>

<panel  header="**2. :fas-info-circle: Unable to rename Git branch due to case differences**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/89" expanded>

I accidentally named my branches branch-level-7 and branch-level-8, and it seems like the dashboard isn't picking them up due to 'level' vs 'Level'. However, I'm unable to rename them to branch-Level-7 and 8 as Git branch names are case insensitive apparently. How should I go about resolving this?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/69#issuecomment-1227331154" expanded>

If the commit was your latest commit in your local repository, and not pushed to origin (github), you can use `git commit --amend` which should bring up vim to let you edit the commit message, after which you can `:wq` to save and quit.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/69#issuecomment-1227419809" expanded>

In that case, you may need to use the rebase function to "re-do" all the commits from a point in the branch history (the earliest commit that you want to change). You can refer to section 2 of https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History for details.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/314#issuecomment-1264639238" expanded>

@junlee1991 Hi Junlee, I'm getting `no module-info.java found` too. Is this breaking anything in your ip? Otherwise, I don't think that this is an issue.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/460#issuecomment-1316804268" expanded>

@damithc To clarify, would this be considered a Documentation Bug or Feature Flaw? Since the tester has no information regarding this feature whatsover from the UG.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/460#issuecomment-1318099524" expanded>

@damithc Thank you for the clarification!
</panel>

</panel>


<panel type="info" header="### 72. TINA..RWAL `@Thing1Thing2` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: To fix or not? Bug that is also a UI issue**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/402" expanded>

We have some confusion if a bug we have can be addressed in v1.4 since it falls under being a UI issue as well.

In our user guide, we stated that a client's **address** should be shown after executing a command.
However, our implementation does not show a client's **address** after executing that command.
Fixing this issue will cause a minor change to UI, which is not allowed.

Should we continue with the fix or drop it?
</panel>

<panel  header="**2. :fas-info-circle: Read for fun: really bad code💎**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/101" expanded>

Found a nice [website](https://shitcode.net/) to gaze upon bad code. Example:
![image](https://user-images.githubusercontent.com/93027319/187238790-7c2db9a3-d8b6-4ad8-b9a6-38d74631048c.png)

If you know of any more of these kinds of fun websites to check out, pls add them below! :laughing:
</panel>

<panel  header="**3. :fas-info-circle: PPP meaning**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/38" expanded>

Minor issue, what does PPP mean here: 
![image](https://user-images.githubusercontent.com/93027319/185729960-86e931ff-c08d-41ad-9746-93bd267388c6.png)
Thank you
</panel>

<panel  header="**4. :fas-info-circle: Cannot scroll after opening embedded page**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/1" expanded>

At [this page](https://nus-cs2103-ay2223s1.github.io/website/schedule/week2/topics.html) after opening and closing the embedded link " a Git repo can work with remote repos other than the one it was cloned from.", I am unable to scroll the page. It only works after refreshing the page. Here is a screenshot of the page concerned before and after the issue:
## before

![image](https://user-images.githubusercontent.com/93027319/184385600-cf62e450-af86-4020-a9c2-abee824f5b6a.png)

## after

![image](https://user-images.githubusercontent.com/93027319/184386470-4d5732c9-1ad8-46d4-a00a-33a9410bf1b4.png)


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/36#issuecomment-1220831319" expanded>

I did it this way:
1. Create as many input.txt files as you like with different names 
2. Feed each of these to the program using the batch script runtest.bat
3. The batch script appends the output of running each  input.txt to ACTUAL.TXT
runtest.bat looked like this:
```
@ECHO OFF

 REM create bin directory if it doesn't exist
 if not exist ..\bin mkdir ..\bin

 REM delete output from previous run
 del ACTUAL.TXT

 REM compile the code into the bin folder
 javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\*.java
 IF ERRORLEVEL 1 (
     echo ********** BUILD FAILURE **********
         exit /b 1
         )
REM no error here, errorLevel == 0
REM run the program, feed command from inputn.txt file and redirect the output to the ACTUAL.txt
         java -classpath ..\bin Duke < input.txt > ACTUAL.TXT
         java -classpath ..\bin Duke < input1.txt >> ACTUAL.TXT
         java -classpath ..\bin Duke < input2.txt >> ACTUAL.TXT
         java -classpath ..\bin Duke < input3.txt >> ACTUAL.TXT
         java -classpath ..\bin Duke < input4.txt >> ACTUAL.TXT
         java -classpath ..\bin Duke < input5.txt >> ACTUAL.TXT

         REM compare the output to the expected output
         FC ACTUAL.TXT EXPECTED.TXT
```
Perhaps this corresponds to the last row of the table of possible testing methods you showed.

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/36#issuecomment-1221233669" expanded>

@clarence-chew 
Oh, I understand what you mean now about "Add new commands". Yes, 4th one seems more fitting because we are deleting the ACTUAL.txt file before running the script again. Thank you for the clarification :D
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/402#issuecomment-1296554839" expanded>

Yes, that would work ... thank you for the clarification!
</panel>

</panel>


<panel type="info" header="### 73. FU Z..NWEN `@Fuzanwenn` (7 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Cannot push after changing personal access token**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/222" expanded>

My personal token expired recently and I had to renew it. Then such error occurs when I try to push. Could someone please help me? Thanks!
![10a46d1b2549918206a36eb962a8204](https://user-images.githubusercontent.com/97226948/190626792-6e219728-7bf5-433d-b34d-c28da15569f4.jpg)
![8526aafdea0654d34f8f6d722ec9f5d](https://user-images.githubusercontent.com/97226948/190626801-f15296b6-0c00-4e18-bcaa-44a89c52fdb1.jpg)

</panel>

<panel  header="**2. :fas-info-circle: Cannot push on SourceTree**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/18" expanded>

The error attached pops up when I push on SourceTree. Anyone please helps me. Thank you.
![cd5453a29c99dacb9add9a158e60313](https://user-images.githubusercontent.com/97226948/185201006-9f3e339b-1cc1-4859-86fa-3636294a596a.png)


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/18#issuecomment-1218762826" expanded>

I followed the guide and created a PAT. But I couldn't configure and anthorize it. There is no such "Configure SSO" button for me to click.
![image](https://user-images.githubusercontent.com/97226948/185265733-5aa6bc8a-e53d-4dbb-9631-2bb5948aee09.png)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/18#issuecomment-1218841234" expanded>

Hi thank you for the link! I solved it using method 1. Really appreciate your help!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/18#issuecomment-1229453733" expanded>

Thank you.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/222#issuecomment-1249256103" expanded>

It works! Thanks a lot!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/222#issuecomment-1257221231" expanded>

Thank you.
</panel>

</panel>


<panel type="info" header="### 74. CRYS..PHUA `@crvstalphua` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Optional parameters not displayed in Command Error Message**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/418" expanded>

For my groups application, when there is an invalid command format error, we display an error message which shows the correct format of the command (e.g. project -a n/NAME d/DEADLINE). However, for some of the commands, some of the parameters are optional and we have displayed that in our ug (e.g. project -a n/NAME [d/DEADLINE]), but missed that out in the error message.

Since the parameter should be optional and not putting the brackets [] would be considered providing incorrect information, is this considered an error and can thus be edited and fixed? 


</panel>

<panel  header="**2. :fas-info-circle: Is adding extra input checks considered a change to the feature?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/414" expanded>

In the recent PE-D, there was a bug reported for my group where our application would not take in an ID input that is beyond our list index. The command simply wont run (you cannot click enter). For example, something like the case below.
I was wondering if adding checks within the classes, to check for invalid id and throw an exception, was allowed? or whether it's considered changing the feature. 

![image](https://user-images.githubusercontent.com/89404671/199492805-7b828c3c-3c2f-437e-ad0c-be8fe8b37780.png)

</panel>

<panel  header="**3. :fas-info-circle: Requesting for smoketest for windows**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/259" expanded>

Hi, need help testing my iP on windows!

Here's my [release](https://github.com/crvstalphua/ip/releases/tag/A-Release), any help would be great! Thanks!
</panel>

<panel  header="**4. :fas-info-circle: intellij shows errors with accessing other classes of the same package**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/93" expanded>

After installing gradle, my intellij code suddenly shows errors everywhere. The major error being that my main class Bob cannot access the other classes Parser or Storage despite all being in the same package. When I run and build the code with gradle it all still runs fine, so I'm not sure why all these errors are being displayed on intellij.

<img width="1440" alt="Screenshot 2022-08-28 at 9 31 53 PM" src="https://user-images.githubusercontent.com/89404671/187076584-6316a694-a1a3-47f0-aeed-47694dca1597.png">

Anyone know how I can fix this? :") Even though my code still runs, I wouldn't want it becoming an issue in future.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/93#issuecomment-1229547431" expanded>

didn't manage to try any methods listed because not sure why but after working with my code for a few hours, it corrected itself and stopped displaying the errors! thank you though!!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/418#issuecomment-1301860939" expanded>

Okay thank you!
</panel>

</panel>


<panel type="info" header="### 75. JONA..YANG `@jontmy` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Is it ok to accept severity downgrade if I reject the bug rejection?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/469" expanded>

Inverse of #466.

I have to justify the severity I chose (which got downgraded), but...:

If I accept the downgraded severity but the dev team's rejection is overruled, will it end up as a lose-lose? (I lose accuracy, dev team gets penalized for the bug). Or does the original severity get applied?

If I disagree with the downgraded severity, will both the downgrade and my rejection to the dev team's rejection need to be accepted by the TA for the rejection to be accepted? (in which case I can avoid risking my disagreement with the rejection getting overruled because I should have accepted the severity downgrade)
</panel>

<panel  header="**2. :fas-info-circle: Library request: `JCommander` for command parsing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/340" expanded>

## Library

[JCommander](https://jcommander.org)

## Purpose

A CLI command parsing library instead of using AB3's argument tokenizer, as it has better support for optional and required arguments. While `commons-cli` has already been approved in #319, we prefer JCommander as it has support for parameter validation, converters into complex objects, and nicer syntax with annotations and such.

## License

[Apache License 2.0](https://github.com/cbeust/jcommander/blob/master/license.txt)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/469#issuecomment-1315178482" expanded>

Yep it does, thanks prof!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/478#issuecomment-1321884140" expanded>

The results and explanations for the MCQ and follow-up questions can be viewed on the Examsoft website (assuming you have already submitted):

[https://apac.examsoft.com/GKWeb/login/NUS](https://apac.examsoft.com/GKWeb/login/NUS)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/479#issuecomment-1321886868" expanded>

> Rationale: 29 is a non boundary value but the question says 5 (also a non-boundary value from the same partition) is already being used as a test case. (examiner note: the partitions are [-MAX..0][1..31][32..MAX])

The answer is 29 according to the answer report on Examsoft.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/490#issuecomment-1325926957" expanded>

Using the Textbook.pdf downloaded from LumiNUS as an alternative seems to search fine (macOS Ventura):
<img width="1132" alt="Screenshot 2022-11-24 at 11 59 20" src="https://user-images.githubusercontent.com/50949210/203690983-03896bbc-11a2-41c5-a657-1057987cc373.png">

Also worth double checking whether exact match search is on:
<img width="385" alt="Screenshot 2022-11-24 at 12 00 10" src="https://user-images.githubusercontent.com/50949210/203691080-86b15bb9-324c-4756-b9fb-9d3e9c0e7bb0.png">

---

The table of contents gets completely garbled in Preview though, not sure why:
<img width="1293" alt="Screenshot 2022-11-24 at 12 03 07" src="https://user-images.githubusercontent.com/50949210/203691471-91fde1e8-0895-4369-8180-8863c1442395.png">

</panel>

</panel>


<panel type="info" header="### 76. ELGI..HENG `@ElginL` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Calculating percentage of bugs accepted by triage**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/451" expanded>

Hi, I would like to ask how the percentage of bugs accepted by triage is calculated.

For example (not factual data):
If I have 4 bugs accepted, 2 bugs rejected, 2 not in scope, and 1 duplicate (duplicated myself), how do I calculate the percentage accepted?
</panel>

<panel  header="**2. :fas-info-circle: Queries about `PRODUCT_NAME`**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/424" expanded>

I have just seen the required files name format for submission. However, does the `PRODUCT_NAME` refer to the exact name within **tP Teams List**?

Because our team have changed the product name to deviate away from what is listed in the tp Teams List. Furthermore, how do we change the product name, target user, and value proposition in tp Teams List? I can't seem to find it anywhere.
</panel>

<panel  header="**3. :fas-info-circle: UI Testing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/328" expanded>

Hi, I'm in the process of updating my tp's application UI, but I can't pass the code coverage CI.

The code coverage report states that I have certain lines not covered by tests, such a snippet from `MainWindow.java`:

```java
StatusBarFooter statusBarFooter = new StatusBarFooter(logic.getJeeqTrackerFilePath());
statusbarPlaceholder.getChildren().add(statusBarFooter.getRoot());
```

However, I have no idea how I can create test cases for these cryptic lines, and from what I observe, most of the pre-built UI that is given at the start aren't covered by test cases as well (such as the classes in UI folder). So, I'm quite confused as to what is required.

Can anyone give me an approach to solve this? Thanks

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/328#issuecomment-1268135246" expanded>

Okay, thank you prof 👍 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/424#issuecomment-1304429657" expanded>

> @ElginL It should be a close match, if not an exact match. Please send me the new product name (and other details) so that I can update the team list.

Hi prof, should I send it to you through email? Or which platform should I use to send the updated details?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/451#issuecomment-1312790071" expanded>

Okay, thank you prof
</panel>

</panel>


<panel type="info" header="### 77. WAYN..YUAN `@waynezsy` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke test help (Windows, MacOS, Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302" expanded>

Hi, I'm looking for help to smoke test my latest release [here](https://github.com/waynezsy/ip/releases/tag/v1.0).

Would greatly appreciate any help, thank you!😄

- [X] Windows
- [X] MacOS
- [X] Linux

</panel>

<panel  header="**2. :fas-info-circle: iP Level-8 Duke behaviour clarification**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/46" expanded>

Hi, I have 2 questions related to clarifying the minimal expected behaviour of Duke at Level-8.

1. Currently, my Duke is able to recognise a specific input format i.e. `2/12/2019 1800` as a date/time (stored using LocalDateTime) but not another input format e.g. `2-12-2019 1800` as a date/time. Is this the expected minimal behaviour of the level-8 increment, or am I supposed to have Duke be able to recognise multiple types of date/time input?

![image](https://user-images.githubusercontent.com/97035005/185791454-163229c7-956c-418d-97f9-15a0a0d8e4a2.png)

2. The requirements for Level-8 are somewhat ambiguous. In the minimal version, we are told to store dates as a LocalDate. Are we also (concurrently) required to detect and store date/times as LocalDateTime?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1256526265" expanded>

Thanks Russell! Checked off Windows in the task list.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1257213531" expanded>

Thanks everyone!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1257296982" expanded>

@rui-han-crh I've updated my build.gradle, could I please trouble you to test my latest release to see if it runs on double-click now? Thank you so much!
Unfortunately the font problem stems from Linux not having Courier New and I'm not aware of a suitable monotype font available on all platforms, so the Nyan will remain misaligned 😞 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/302#issuecomment-1258167565" expanded>

Thanks for your help!
</panel>

</panel>


<panel type="info" header="### 78. ER W.. HAN `@seanflyyy` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: making edits to older commits and marking criteria**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/12" expanded>

Hello! I was working on the IP and I realised that I could have written some code better in level 2. However, I have already made commits until level 5, so may I know how I can go about making the improvements to level 2? 

Additionally, in this case, if I had fixed the bad coding decisions in level 5 which I noted in level 2, would I be penalised? Just wondering what the marking criteria would be? Would it be based on the individual commits or the final output?

Thank you!!
</panel>

<panel  header="**2. :fas-info-circle: Clarification on Week 1 Quiz Question 45**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/6" expanded>

Hello all! I was attempting the quiz and for this question, 

"It is redundant for a ‘try’ block to have a ‘finally’ block if you already have a ‘catch’ block."

I had selected true since according to the Week 1 Syllabus, "The try statement should contain at least one catch block or a finally block and may have multiple catch blocks." But the solution provided was True since "They have different purposes." 

Just wanted to clarify on this because it was a bit confusing for me, because technically, it is redundant for a ‘try’ block to have a ‘finally’ block if you already have a ‘catch’ block since you should have either at least one catch block or a finally block, just that they have different purposes so in practice, they are not exclusive(?)




</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/6#issuecomment-1214273580" expanded>

Thanks for the clarification! That does make sense haha. Perhaps the question could have been phrased better because it contradicts what it says in the textbook that a try block should have either at least one catch statement or a finally statement haha
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/6#issuecomment-1214278760" expanded>

@damithc Thank you for your clarification prof! It is much clearer now. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/12#issuecomment-1217599835" expanded>

@deeyonn Ahh, I must have missed that. Thank you for pointing it out!
@peppapighs Understood, thanks for the help!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/347#issuecomment-1281129363" expanded>

Hi prof @damithc, if we are encouraged to warn rather than block, would we not need to take into account the different possibilities of inputs and handle them accordingly. Moreover, if we are accepting anything as input, would that not defeat the purpose of validation. It seems like we are being penalised for adding validation?

Would be great if you could clarify this! Thank you!
</panel>

</panel>


<panel type="info" header="### 79. IZZ..ALIL `@izzahaj` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Errors with jacocoTestReport when adding a remark command in the tutorial**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/285" expanded>

Hello, I was following the tutorial to add a remark command to AB3, but ran into these errors when writing one of the tests in the `RemarkCommandTest` class.

```
> Task :compileTestJava
> Task :processTestResources UP-TO-DATE
> Task :testClasses
> Task :test
> Task :jacocoTestReport FAILED
FAILURE: Build failed with an exception.
* What went wrong:
Execution failed for task ':jacocoTestReport'.
> Error while creating report
* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
* Get more help at https://help.gradle.org
BUILD FAILED in 7s
6 actionable tasks: 3 executed, 3 up-to-date
```

Another error after running `RemarkCommandTest`:
```
Can't add different class with same name: seedu/address/logic/parser/CliSyntax
```

My RemarkCommandTestClass:
```
package seedu.address.logic.commands;

import static seedu.address.logic.commands.CommandTestUtil.assertCommandSuccess;
import static seedu.address.testutil.TypicalIndexes.INDEX_FIRST_PERSON;
import static seedu.address.testutil.TypicalPersons.getTypicalAddressBook;

import org.junit.jupiter.api.Test;

import seedu.address.model.AddressBook;
import seedu.address.model.Model;
import seedu.address.model.ModelManager;
import seedu.address.model.UserPrefs;
import seedu.address.model.person.Person;
import seedu.address.model.person.Remark;
import seedu.address.testutil.PersonBuilder;

/**
 * Contains integration tests (interaction with the Model) and unit tests for RemarkCommand.
 */
class RemarkCommandTest {
    private static final String REMARK_STUB = "Some remark";
    private Model model = new ModelManager(getTypicalAddressBook(), new UserPrefs());

    @Test
    public void execute_addRemarkUnfilteredList_success() {
        Person firstPerson = model.getFilteredPersonList().get(INDEX_FIRST_PERSON.getZeroBased());
        Person editedPerson = new PersonBuilder(firstPerson).withRemark(REMARK_STUB).build();

        RemarkCommand remarkCommand =
                new RemarkCommand(INDEX_FIRST_PERSON, new Remark(editedPerson.getRemark().value));

        String expectedMessage = String.format(RemarkCommand.MESSAGE_ADD_REMARK_SUCCESS, editedPerson);

        Model expectedModel = new ModelManager(new AddressBook(model.getAddressBook()), new UserPrefs());
        expectedModel.setPerson(firstPerson, editedPerson);

        assertCommandSuccess(remarkCommand, model, expectedMessage, expectedModel);
    }
}
```

Code in `seedu/address/logic/parser/CliSyntax`:
```
package seedu.address.logic.parser;

/**
 * Contains Command Line Interface (CLI) syntax definitions common to multiple commands
 */
public class CliSyntax {

    /* Prefix definitions */
    public static final Prefix PREFIX_NAME = new Prefix("n/");
    public static final Prefix PREFIX_PHONE = new Prefix("p/");
    public static final Prefix PREFIX_EMAIL = new Prefix("e/");
    public static final Prefix PREFIX_ADDRESS = new Prefix("a/");
    public static final Prefix PREFIX_REMARK = new Prefix("r/");
    public static final Prefix PREFIX_TAG = new Prefix("t/");

}
```
I lifted the code from [here](https://github.com/se-edu/addressbook-level3/commit/fac8f3fd855d55831ca0cc73313b5943d49d4d6e#diff-ff58f7c10338b34f76645df49b71ecb2bafaf7611b20e7ff59ebc98475538a01R36-R49), as shown in the tutorial. Any help would be greatly appreciated!

</panel>

<panel  header="**2. :fas-info-circle: help with setting up codecov**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/147" expanded>

I followed the DevOps [guide](https://nus-cs2103-ay2223s1.github.io/tp/DevOps.html) given to set up codecov for the tp repo but so far all the CI runs shown in GitHub actions have failed after pushing dummy commits:
<img width="1292" alt="Screenshot 2022-09-05 at 8 47 46 PM" src="https://user-images.githubusercontent.com/88933129/188453605-8f5a2f17-ba71-48d7-b8d9-9d6b858c0fbc.png">

On the Codecov website, it says that my tp repo has not been set up yet despite following the instructions given in both the DevOps guide and [here](https://app.codecov.io/gh/AY2223S1-CS2103T-T12-4/tp/new).

Any help would be greatly appreciated!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/147#issuecomment-1237558101" expanded>

Thank you for the replies! @RussellDash332 I've added a newline and it works now.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/285#issuecomment-1253508050" expanded>

Hi @RussellDash332 I just pushed to the branch in my fork
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/285#issuecomment-1253665511" expanded>

Thank you for the effort. I ran `./gradlew clean` before running the tests and it worked as per normal.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/291#issuecomment-1255151631" expanded>

<img width="714" alt="Screenshot 2022-09-22 at 10 56 15 PM" src="https://user-images.githubusercontent.com/88933129/191781633-99bbfa15-6ad4-4384-b225-4da8e900b506.png">

Hi, it works well on Mac!
</panel>

</panel>


<panel type="info" header="### 80. CHLO..YING `@chloeelim` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Clarification on applying `NotInScope` criteria on `DocumentationBug`**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/471" expanded>

Hi,

I was wondering how the criteria for bugs classified as `NotInScope` should apply to a `DocumentationBug`.

Here's the relevant snippet in question from the module website:

<img width="692" alt="Screenshot 2022-11-15 at 4 57 56 PM" src="https://user-images.githubusercontent.com/79991214/201910441-d2187e65-1102-47e2-b517-414cbda53ec8.png">

As you can see, it appears that the set of criteria provided would most suitably apply to a `FeatureFlaw` or `FunctionalityBug` since the two requirements don't really apply to a `DocumentationBug`.

So I'm quite confused how we should determine whether a `DocumentationBug` (eg: image mismatch between UG and product) we've reported really qualifies for `NotInScope` as claimed by the developers' response.

Thanks!

</panel>

<panel  header="**2. :fas-info-circle: Request for Smoke-Test on Windows/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/244" expanded>

Hello! Here is my [JAR file](https://github.com/chloeelim/ip/releases/tag/A-Release) and [User Guide](https://chloeelim.github.io/ip/), any help in doing a smoke test on the JAR file on Windows/ Linux would be greatly appreciated. Thank you! : )
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1236297786" expanded>

changes made:
- dark mode theme
- sticky top bar
- styled the scroll bar
- added a list view for task/ tasklist

<div style="display: flex">
<img width="396" alt="Screenshot 2022-09-04 at 5 25 51 PM" src="https://user-images.githubusercontent.com/79991214/188306873-caff43b1-f907-440f-bd7a-2cdbaa7303bb.png">
<img width="397" alt="Screenshot 2022-09-04 at 5 26 12 PM" src="https://user-images.githubusercontent.com/79991214/188306881-2a1c5ed4-fcd1-4829-9a03-3e3e57ba6215.png">
</div>

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/242#issuecomment-1250045812" expanded>

Hi, tested on MacOS and seems to be working fine. Not sure if this was intended, but there's a weird character (see below) that appears when you input an invalid command.

<div display = "flex">
  <img width="397" alt="Screenshot 2022-09-17 at 6 20 23 PM" src="https://user-images.githubusercontent.com/79991214/190852143-9638bc83-393c-4d3f-8dae-726795a7c2f3.png">
  <img width="389" alt="Screenshot 2022-09-17 at 6 21 43 PM" src="https://user-images.githubusercontent.com/79991214/190852154-92247c82-d753-482d-b4fb-56fd41a32a5a.png">
</div>
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/244#issuecomment-1250089312" expanded>

Thanks for the help! (Have a great recess week &hat;&hat;)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/471#issuecomment-1315219886" expanded>

Got it, thanks Prof!
</panel>

</panel>


<panel type="info" header="### 81. TAN ..TING `@ytingtan` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Cause: zip END header not found**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/313" expanded>

Details:
* IntelliJ version: Community Ediiton 2021.3.1
* OS: Windows
* Tried to run Main, but `Cause: zip END header not found` error is shown 

I have referred to this stackoverflow post such as https://stackoverflow.com/questions/52411697/intellij-compilation-error-zip-end-header-not-found, but when i run `./gradlew --version` I do not get any errors. In fact, I can still see that my Gradle version 7.4.2. 

I have also tried to Unlike Gradle project and Link again, but it still does not work. 

Attached is my project structure: 
![image](https://user-images.githubusercontent.com/95749518/192929126-0d4929fe-c69d-43e8-bba5-0022df2b9b30.png)

Appreciate any help! 🙏 


</panel>

<panel  header="**2. :fas-info-circle: Unable to run jar file due to java.lang.ClassNotFoundException**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/189" expanded>

Details: 
* IntelliJ version: Community Ediiton 2021.3.1, OS: Windows 
* Issue: Created jar file and ran `java -jar ip.jar`, but error message shown: 
```
Error: Could not find or load main class duke.Launcher
Caused by: java.lang.ClassNotFoundException: duke.Launcher
```

Attached below is my file structure.
![image](https://user-images.githubusercontent.com/95749518/190103342-f63ee9da-2f65-45d2-9f8a-6fa2da726a31.png)

I set `Launcher.java` as the main point of entry of the code, and `Launcher.java` launches `Duke.java` which extends `Application`. 

I have followed the LPT at #169 but it shows the same error. Appreciate any help! 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/189#issuecomment-1247483813" expanded>

It works now, thank you so much! 😸 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/313#issuecomment-1263168978" expanded>

Thanks Prof! I have tried all 3 actions above. However, the error still persists. The code can be found in my fork [here ](https://github.com/ytingtan/tp/tree/update-UserGuide)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/313#issuecomment-1263186770" expanded>

Update: I tried to run `./gradlew wrapper --gradle-version=7.4.2` to reinstall gradle 7.4.2 but instead I got a 
```
FAILURE: Build failed with an exception.

* What went wrong:
Could not create service of type ClassLoaderRegistry using GlobalScopeServices.createClassLoaderRegistry().
```

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/313#issuecomment-1263196978" expanded>

YOOOOO I GOT IT 

Solution: 
1. Go to C:\Users\yourname\.gradle\wrapper\dists and delete the folder labelled gradle 7.4.2 
2. Go to [gradle website](https://services.gradle.org/distributions/) to download the distribution (7.4.2 used for tp) into the same place as Step 1 
3. Unzip folder 
4. Restart IntelliJ 
5. DONE!!!!! 

😸 
</panel>

</panel>


<panel type="info" header="### 82. CHEN..G-YU `@jchilling` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: FXML loading error**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/124" expanded>

Hi, I have followed the JavaFX tutorial and have faced this error when implementing FXML. Does anyone know how to fix it?

![issue6](https://user-images.githubusercontent.com/83859498/187976317-be211bb5-94da-4a09-8a21-77495943a232.png)

</panel>

<panel  header="**2. :fas-info-circle: Unable to run Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/75" expanded>

Hi, I have merged 'add-gradle-support' branch and followed the steps for Scenario 2. However, when I run gradle the display is like the images below. Here is my code's link: https://github.com/jchilling/ip. Can anyone help me to solve this issue? Thanks!

![issue4](https://user-images.githubusercontent.com/83859498/186900511-5f9b6988-993f-46f8-a39d-77e7c495c812.png)
![issue5](https://user-images.githubusercontent.com/83859498/186900517-ad0410f2-4d05-4b8b-b810-60fd7c99970e.png)


</panel>

<panel  header="**3. :fas-info-circle: Unable to push via SourceTree or command line**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/9" expanded>

I followed all the setups on the course website. I can commit, tag, and pull. However, I cannot push via Sourcetree or the command line. My application just doesn't terminate. 
![issue1](https://user-images.githubusercontent.com/83859498/184610880-9aed0258-88a8-4550-bed1-a33319bae931.png)

I tried the advice online and changed my remote repo path, but it resulted in another error. Could anyone kindly advise how to make the push function work? 
 
![issue2](https://user-images.githubusercontent.com/83859498/184611206-0fa678a6-1ce0-4146-b0bf-570ab2d4fd10.png)
![issue3](https://user-images.githubusercontent.com/83859498/184611637-dd370a49-890f-4d18-a006-0cba4314074e.png)




</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/9#issuecomment-1216890022" expanded>

Thank yall!! I am able to push after following Carrie's method :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/75#issuecomment-1229127388" expanded>

Hi sorry for the late reply. My gradle functions as normal now, thanks prof!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/124#issuecomment-1235193075" expanded>

My controller's location is correct. After testing around a bit, I realized that fxml probably doesn't support .jpg files. My launcher works after I convert my image files into .png. Thanks for the help! 
</panel>

</panel>


<panel type="info" header="### 83. ZHAN..GJUN `@albertZhangTJ` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoketest on Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/260" expanded>

Hi guys!

Can anyone help test out the [jar for my ip](https://github.com/albertZhangTJ/ip/releases/tag/A-Release-updated) on Mac? Thanks in advance!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/256#issuecomment-1250446651" expanded>

Works on Ubuntu 20.04:
![Kazam_screenshot_00025](https://user-images.githubusercontent.com/72067599/190936854-ce885ef1-795e-4c24-98fc-9896532e95d7.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/260#issuecomment-1250598161" expanded>

For any questions related to command syntax, please type `help` in the application. A help message will be displayed. Thank you!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/261#issuecomment-1250680819" expanded>

Seems to work fine on Ubuntu 20.04 (other than the previously mentioned problem with resizing).
![Kazam_screenshot_00026](https://user-images.githubusercontent.com/72067599/190971571-7f020774-5ebd-4211-9aa8-7ff82319909b.png)

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/260#issuecomment-1250687927" expanded>

@optionalemon Noted with thanks, it is indeed a small mismatch in width setting. Already corrected.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/260#issuecomment-1250688245" expanded>

@WuHaohui1231 Thank you for your help!
</panel>

</panel>


<panel type="info" header="### 84. OU J.. BIN `@kelvinou01` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: When should we use association roles vs labels?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/497" expanded>

For example if `A` uses `B`, how do we decide to use an association role or label for `uses`?
</panel>

<panel  header="**2. :fas-info-circle: jar file works on mac but not on windows**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/176" expanded>

- Issue: [jar file](https://github.com/kelvinou01/ip/releases/tag/A-Release) works fine on mac, even if the jar file is run in a new empty directory. However, it throws the following error on windows:
  
  ```bash
  Error: JavaFX runtime components are missing, and are required to run this application
  ```
  
- Jar file is ~8mb in size, so it likely contains all the dependencies. 

- Jar file was built using `bash ./gradlew shadowJar` on mac
  
- Using OpenJDK 11 JDK FX version
  
- `java --version` prints the following:
  
  ```bash
  openjdk 11.0.16 2022-07-19 LTS
  OpenJDK Runtime Environment Zulu11.58+15-CA (build 11.0.16+8-LTS)
  OpenJDK 64-Bit Server VM Zulu11.58+15-CA (build 11.0.16+8-LTS, mixed mode)
  ```
  
- `build.gradle` file is as follows:
  
  ```java
  plugins {
      id 'java'
      id 'application'
      id 'com.github.johnrengelman.shadow' version '5.1.0'
      id 'checkstyle'
  }
  
  repositories {
      mavenCentral()
  }
  
  dependencies {
      testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
      testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'
  
      String javaFxVersion = '11'
  
      implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
      implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
      implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
      implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
      implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
      implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
      implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
      implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
      implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
      implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
      implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
      implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'
  }
  
  test {
      useJUnitPlatform()
  
      testLogging {
          events "passed", "skipped", "failed"
  
          showExceptions true
          exceptionFormat "full"
          showCauses true
          showStackTraces true
          showStandardStreams = false
      }
  }
  
  application {
      mainClassName = "duke.Launcher"
  }
  
  shadowJar {
      archiveBaseName = "duke"
      archiveClassifier = null
  }
  
  checkstyle {
      toolVersion = "10.2"
      sourceSets = []  // Only run checkstyle when we explicitly call it
  }
  
  run{
      standardInput = System.in
  }
  ```
  
- Tried the following alternative `build.gradle` file corresponding to the [alternative JavaFX installation method](https://openjfx.io/openjfx-docs/#gradle) provided in [SE-Edu](https://se-education.org/guides/tutorials/javaFxPart1.html). It doesn't work as well.
  
  ```java
  plugins {
      id 'java'
      id 'application'
      id 'com.github.johnrengelman.shadow' version '5.1.0'
      id 'checkstyle'
      id 'org.openjfx.javafxplugin' version '0.0.10'
  }
  
  repositories {
      mavenCentral()
  }
  
  dependencies {
      testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
      testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'
  }
  
  test {
      useJUnitPlatform()
  
      testLogging {
          events "passed", "skipped", "failed"
  
          showExceptions true
          exceptionFormat "full"
          showCauses true
          showStackTraces true
          showStandardStreams = false
      }
  }
  
  application {
      mainClassName = "duke.Launcher"
  }
  
  shadowJar {
      archiveBaseName = "duke"
      archiveClassifier = null
  }
  
  checkstyle {
      toolVersion = "10.2"
      sourceSets = []  // Only run checkstyle when we explicitly call it
  }
  
  javafx {
      version = "18.0.2"
      modules = [ 'javafx.controls', 'javafx.fxml' ]
  }
  
  run{
      standardInput = System.in
  }
  ```
  
- Tried [this fix](https://github.com/nus-cs2103-AY2223S1/forum/issues/169) provided on the forum. Jar file still doesn't work on windows.


- Any help is appreciated 🥲
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/176#issuecomment-1243448830" expanded>

Jar file runs on my friend's mac too.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/176#issuecomment-1245143054" expanded>

Hi @VimuthM, thank you for taking a look into my problem. I've double checked which JDK my Gradle wrapper is using. 

`./gradlew -version` returns the following:
```
Revision:     61d3320259a1a0d31519bf208eb13741679a742f

Kotlin:       1.3.61
Groovy:       2.5.8
Ant:          Apache Ant(TM) version 1.10.7 compiled on September 1 2019
JVM:          11.0.16.1 (Azul Systems, Inc. 11.0.16.1+1-LTS)
OS:           Mac OS X 12.1 aarch64
```

Also, I've set `JAVA_HOME` to the azul/zulu jdk:
```
export JAVA_HOME=/Library/Java/JavaVirtualMachines/zulu-11.jdk/Contents/Home
```

Unfortunately, my jar files are still not working on windows. I'm still trying and I'd be very grateful for any more suggestions :) 

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/176#issuecomment-1245147728" expanded>

I've also tried adding these lines to my build.gradle as per [this SO post](https://stackoverflow.com/a/21212790), to no avail.
```
compileJava.options.fork = true
compileJava.options.forkOptions.executable = '/Library/Java/JavaVirtualMachines/zulu-11.jdk/Contents/Home/bin/javac'
```

I've also tried executing my gradle wrapper as follows:
```
 ./gradlew shadowJar -Dorg.gradle.java.home=/Library/Java/JavaVirtualMachines/zulu-11.jdk/Contents/Home/  
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/176#issuecomment-1246495431" expanded>

I have it fixed now. Basically, I changed the class I start the program with from Launcher to Main.

My Launcher essentially acted as a main class before I made this fix.

Thank you everyone who stopped by to look into my problem, really appreciate it :)
</panel>

</panel>


<panel type="info" header="### 85. TIN .. HAO `@tinenhao` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Cant seem to execute JAR file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/164" expanded>

I have successfully generated a jar file using Gradle shadowJar, however, the generated jar file can't seem to run (when I try to open it nothing happens). Not sure what I should do as I have included the relevant commands as instructed in the website,
</panel>

<panel  header="**2. :fas-info-circle: Unable to import from java after installing gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/31" expanded>

![image](https://user-images.githubusercontent.com/88677292/185468818-05335a58-e0a4-4be6-94ae-5e81cdca6502.png)
![image](https://user-images.githubusercontent.com/88677292/185468873-39dffcb4-2bca-457e-9fae-c21a13c7b2de.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/31#issuecomment-1220197247" expanded>

I did the following steps
1. pull from the gradle branch
2. delete the IDEA file
3. restart project in IDEA
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/31#issuecomment-1220214931" expanded>

The problem was resolved after I recloned from the repo. Thank you for your help
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/164#issuecomment-1242654334" expanded>

This was exactly my problem. Thank you!
</panel>

</panel>


<panel type="info" header="### 86. YANG..YANG `@myangat0343` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Encounter Bugs When Running JAR**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/105" expanded>

When I run the JAR in the terminal, it encounters a bug. But there is no bug when running in Intellij. Can anyone figure out the reason?
I think it may the path of JAR file ?


<img width="233" alt="path" src="https://user-images.githubusercontent.com/70734965/187335824-158732c5-f6e9-4d97-b724-42c93354fe57.png">

<img width="384" alt="Correct result by IJ" src="https://user-images.githubusercontent.com/70734965/187335441-1528bd43-e4c6-4b3d-9201-8290a72882dd.png">
<img width="393" alt="Exception by JAR" src="https://user-images.githubusercontent.com/70734965/187335446-25029b68-6e49-4f88-837e-fa5e23a809ae.png">

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/34#issuecomment-1221491964" expanded>

With great thanks for @damithc @kxrt @ReubenChay. I also encountered the same problem. And for me(Mac user), the SourceTree user account must be login with Auth Type(Basic) and PAT. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/105#issuecomment-1231114421" expanded>

> I took a quick peek at your code for `Storage.java`. Looks like you're not creating a directory if the filepath for your storage file doesn't exist, and the "IOException e" print comes from there. The Level-7 task description specifies this needs to be handled.
> 
> A possible reason for this could be the hardcoded path in `Duke.java` - it might be worth reconsidering the implementation here!

Thank you so much!

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/105#issuecomment-1231114899" expanded>

I rewrite the path of data and solve the problem. Thank you : )
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/213#issuecomment-1248936392" expanded>

I am using my mac, and I download your .jar file, I can double-clicking and open it.
</panel>

</panel>


<panel type="info" header="### 87. LOH .. WYE `@nopehax` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke test help (MacOS, Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/293" expanded>

Hi guys, I've received an email from the teaching team stating that the following errors has been found during their automated smoke test:
```
On Linux, using Java 11, for the doomba.jar uploaded on 09-16-2022 (MM-DD-YYYY) at 14:58:52:
Graphics Device initialization failed for : es2, sw Error initializing QuantumRenderer: no suitable pipeline found 
java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at 
com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280) at 
com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222) at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at 
com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at 
com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at 
com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at 
java.base/java.lang.Thread.run(Thread.java:829) Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no 
suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94) at 
com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124) ... 1 more Exception in thread "main"
 java.lang.RuntimeException: No toolkit found at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at 
com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at 
com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at 
com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at 
java.base/java.lang.Thread.run(Thread.java:829) 


On Mac, using Java 11, for the doomba.jar uploaded on 09-16-2022 (MM-DD-YYYY) at 14:58:52:
Graphics Device initialization failed for : es2, sw Error initializing QuantumRenderer: no suitable pipeline found 
java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found at 
com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280) at 
com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222) at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at 
com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at 
com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at 
com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at 
java.base/java.lang.Thread.run(Thread.java:834) Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no 
suitable pipeline found at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94) at 
com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124) ... 1 more Exception in thread "main" 
java.lang.RuntimeException: No toolkit found at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267) at 
com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158) at 
com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658) at 
com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678) at 
com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195) at 
java.base/java.lang.Thread.run(Thread.java:834)

```

For my previous build, I followed the guide that was linked [here](https://openjfx.io/openjfx-docs/#gradle) instead of doing the copy and pasting way. It passed the Java CI checks with no errors, as shown in the screenshot below and I have also asked my friend who is using MacOS to test the jar file and it works. So I am not sure why it didn't pass the smoke test.
![image](https://user-images.githubusercontent.com/57407346/191348797-12dcbd50-26d0-4888-8771-588570edeccc.png)

But I've modified the code such that it uses the copy and paste way so could someone help me test out both of my code?
The original jar file can be found [here](https://github.com/nopehax/ip/releases/tag/Bug-Fix) and the one with the fix [here](https://github.com/nopehax/ip/releases/tag/A-BetterGui)


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179#issuecomment-1246409614" expanded>

Hi @gabyang, the GUI is not popping up because in Main.java when creating a new instance of Duke, that instance will be run i.e. the old CLI duke. Since the CLI doesn't show, you're not able to exit it and that instance will always be running and so, your program is forever stuck at line 15 of Main.java.

Thus the solution is to remove the line `run();` in line 46 of Duke.java
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/153#issuecomment-1247063346" expanded>

Thanks @Hongyi6328, that's really cool! Wished I'd seen this earlier
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/293#issuecomment-1256987121" expanded>

Ok, thanks for testing it out!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/293#issuecomment-1264426274" expanded>

Ah, I see thank you!
I found the problem, which was the circle component for JavaFX. Not sure why it was working for windows but not for macos and linux. I have removed the component and went back to using ImageView.
</panel>

</panel>


<panel type="info" header="### 88. KHOO..RICK `@drkkjh` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke test help (Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/266" expanded>

Hi! I need help to test my iP on Linux. My user guide is [here](https://drkkjh.github.io/ip/) and the release can be found [here](https://github.com/drkkjh/ip/releases/tag/A-Release).

Thanks!

</panel>

<panel  header="**2. :fas-info-circle: iP branches not detected in iP dashboard**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/160" expanded>

Hi, I have merged via PR on my own fork and pushed the branches `branch-A-Assertions` and `branch-A-CodeQuality`. The tags on my main branches are detected but somehow the branches `branch-A-Assertions` and `branch-A-CodeQuality` are not detected. I have cloned my own repo and verified that I have pushed.

The screenshots below show that I have pushed my branches:
<img width="1014" alt="image" src="https://user-images.githubusercontent.com/61372278/189279664-7162c981-ec15-416e-acb2-24124b8c015d.png">

However, for every pull request, I have also accidentally merged the branches `branch-A-Assertions` and `branch-A-CodeQuality` with main resulting in the following sourcetree graph:
<img width="725" alt="image" src="https://user-images.githubusercontent.com/61372278/189280897-2115e76d-f37f-40b6-b7be-afe9dd603ac0.png">

Any help would be greatly appreciated! 🥲 

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/160#issuecomment-1241548690" expanded>

Thanks prof and @bryanngzh for the help! I have merged and will wait for the next dashboard update to verify again.

<img width="729" alt="image" src="https://user-images.githubusercontent.com/61372278/189284423-3d20016a-4d29-45a5-a1aa-58616ab609ae.png">


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/264#issuecomment-1250922100" expanded>

<img width="401" alt="image" src="https://user-images.githubusercontent.com/61372278/191011823-8db77208-71b7-455d-b2e6-aa7ee0cf3e4e.png">

Seems to work fine for me on macOS, however, not sure if the gap between the send and the user input is intended?

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/266#issuecomment-1257964815" expanded>

Thanks @RezwanArefin01! I'll try to fix it
</panel>

</panel>


<panel type="info" header="### 89. CHUA..LTON `@notle1706` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Number of bugs allowed as a group**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/450" expanded>

Hi, according to the email sent out by prof, 
> you can likely accept 5+ minor bugs before even it starts affecting your marks (because a certain amount of bugs are forgiven) 

Does this also mean that a group can accept 25+ minor bugs before it starts to affect our marks or 5 minor bugs as a whole? Our team is planning to split all the bugs found
</panel>

<panel  header="**2. :fas-info-circle: Error when running checkstyle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/64" expanded>

Whenever I try to run `./gradlew checkstyleMain` I get the following error.
`ERROR: JAVA_HOME is not set and no 'java' command could be found in your PATH.`
Thanks in advance!

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/64#issuecomment-1226987025" expanded>

update: I added the JAVA_HOME path in my enviroment settings and it's working now.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/450#issuecomment-1312781098" expanded>

Thank you prof for the reply. Also, would the penalty be evenly distributed among all group members should we decide to leave all accepted bug reports unassigned?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/450#issuecomment-1312783052" expanded>

Thank you!
</panel>

</panel>


<panel type="info" header="### 90. CHAN.. KAI `@sikai00` (5 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/25#issuecomment-1219853196" expanded>

Can confirm @ngshijun is right. Managed to replicate the same exact error with Oracle Java 18.0.2. 

Try running `where java` in your terminal (I'm assuming you are using zsh). It should output something like this:
<img width="534" alt="image" src="https://user-images.githubusercontent.com/63795894/185473540-6863fdd1-230a-4118-b487-bdaf7a48004c.png">

The 2nd line refers to the Azul Java folder in my computer's directory (yours may be different depending on where you put your Azul Java folder). zsh will prefer to use the 1st Java it can find (in this case /usr/bin/java) which is Oracle Java, so the fix is simply to let zsh "see" your Azul Java installation first. 

Simply go to your root directory (perform a `cd`), then do `vim .zshrc` which opens the config file for zsh.
Then, add this line into your .zshrc:
`export PATH='<your Azul Java folder>':$PATH`
Note that your directory should include 'bin' per my screenshot.

It should look like this now (might vary on your machine):
<img width="529" alt="image" src="https://user-images.githubusercontent.com/63795894/185741763-2f5ec860-6711-4518-9e53-8e716370bef0.png">
_(Edit: Make sure JAVA_HOME leads to the installation folder of Azul rather than bin for Gradle to identify the correct JVM to use, otherwise it will say that it is an invalid Java installation.)_
Save it, restart your terminal, then verify that Azul Java comes first by performing `where java` again (`java --version` can also verify your Java version).
<img width="538" alt="image" src="https://user-images.githubusercontent.com/63795894/185475037-75f03b44-d186-48a3-a807-25c867dac638.png">

If you don't see 2 lines (referring to the two different Java installation), it means that you probably haven't set the installation of Azul Java to your path. You can perform the same steps as above (to add Azul Java to your PATH) and it should still work.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/136#issuecomment-1236051575" expanded>

According to the [progress dashboard description](https://nus-cs2103-ay2223s1.github.io/dashboards/contents/ip-progress.html), the dashboard should be updated in a script run that occurs once per day.  
For today,  
<img width="506" alt="image" src="https://user-images.githubusercontent.com/63795894/188256979-4b23608d-19fa-48e2-af7b-c45efabe31fb.png">    
script was ran at 1039. So you probably have to wait for tomorrow for the next script run.

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/136#issuecomment-1236052816" expanded>

Here's a [page](https://nus-cs2103-ay2223s1.github.io/website/admin/weeklySchedule.html#deadline-for-weekly-tasks  ) from the admin info where you can look up more information if you need.
I believe there shouldn't be any since the GFMD hard deadline was just yesterday.  

<img width="823" alt="image" src="https://user-images.githubusercontent.com/63795894/188257253-95e7695b-8a36-48d4-8b4a-4df02664f7f6.png">

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1237684533" expanded>

@linuschui I was able to successfully run your program.  

<img width="808" alt="image" src="https://user-images.githubusercontent.com/63795894/188556041-328443c1-e565-4225-aee4-0eec34c4b7d7.png">  

Apologies as I don't have a solution for you, but you might want to check if your project structure and gradle settings in IntelliJ are configured properly.

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1237686712" expanded>

@linuschui I was also able to google a [past student's user guide](https://russell-loh-nus.github.io/duke/#faq) who faced the exact same issue. You might also want to give this a try
</panel>

</panel>


<panel type="info" header="### 91. YEO ..DRIC `@edricyeo` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to open JAR file on Windows. Unable to open jar file by double-clicking on Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/213" expanded>

Details: MacOS Monterey 12.1
Code: Download my release [here](https://github.com/edricyeo/ip/releases/tag/A-Release)
Issue: Only able to open JAR file on mac. Unable to double-click to run the jar file on my mac, but able to open jar file using:
```java
java -jar duke.jar
```
When double-clicking the jar file on my mac, the jar file does not open but does not show any error.
When running the jar file using `java -jar duke.jar` on Windows OS, gets this error:

![IMAGE 2022-09-16 10:26:45](https://user-images.githubusercontent.com/80802319/190543333-14409289-630f-49b1-b2e0-60f85abeceb3.jpg)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/204#issuecomment-1248289871" expanded>

Works fine for mac! 👍🏻
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/213#issuecomment-1248955249" expanded>

@myangat0343 Oh thank you! Is there any setting you need to enable to get it to do so? I'm able to open some jar files by double clicking it on my mac but i cant open my own duke.jar file. Was wondering if there was something I was missing out, appreciate any help!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/213#issuecomment-1249097614" expanded>

@Bubbl3T Thank you! I am using JavaLauncher as default but can't seem to open it. Thanks for your help though!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/213#issuecomment-1249100932" expanded>

@RezwanArefin01 Thank you for your help! You get the pipeline error on Linux as well? Not sure how to test the issue about the images not being loaded though... Please let me know if you find out how though! Appreciate it :)
</panel>

</panel>


<panel type="info" header="### 92. EDBE..NATA `@Berted` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: A-Jar: Changing the command to run the JAR file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/61" expanded>

In the Duke A-Jar section, it's stated that: 
> You can assume the user will run the jar file in the following way only:
> - Copy the jar file into an empty folder
> - Open a command window in that folder
> - Run the command `java -jar {filename}.jar` e.g., `java -jar Duke.jar` (i.e., run the command in the same folder as the jar file)

However, as my application is using UTF-8 in its outputs, running `java -jar Duke.jar` will usually result in the UTF-8 strings to not be properly rendered. As such, would it be okay if I slightly change the command to `java -Dfile.encoding=UTF-8 -jar Duke.jar`? 

I've also added the appropriate information and runner scripts in the [release body text](https://github.com/Berted/ip/releases/tag/A-Jar) to indicate this change. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/30#issuecomment-1219623467" expanded>

Hi Jason, to my knowledge it seems that script was made with it being run from the `text-ui-test` directory in mind.

Try changing directories to `text-ui-test` by performing `cd text-ui-test`, then run the `runtest.bat` script. Hopefully this works.

GL!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/61#issuecomment-1225863181" expanded>

Understood, thanks for the suggestion prof!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/68#issuecomment-1227359357" expanded>

Hi, I'm not sure if this is the issue, but it's worth a shot since I can't see your repository directly:

In the build.gradle file, try changing:
```
application {
    mainClassName = "seedu.duke.Duke"
}
```

to
```
application {
    mainClassName = "duke.Duke"
}
```

I believe that's your package naming scheme based on the screenshot? But basically, change it to the correct package specifier for the Duke class. Hope this helps, GL!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/68#issuecomment-1227416234" expanded>

I think the issue is due to conflicting JDK versions, i.e. in the Terminal the one that is running seems to be Version 17, whilst this project uses Version 11. 

I had a similar issue in my set-up and I wasn't able to resolve the issue. Albeit, I found an alternative to avoid dealing with the version conflict using IntelliJ's run configuration feature.

Say you want to run JUnit tests with `gradlew testClasses test`, what you can do is:
1. Click on the dropdown menu next to the Run button.
![image](https://user-images.githubusercontent.com/46164341/186705753-fe52c076-8394-4e2d-9a3c-c583f815670c.png)
1. Click on Edit Configurations
1. Click the Add New Configuration button (That's the + button)
1. Name the new Configuration to your preference, and add `testClasses test` to the "Run" textbox field.
1. Click Apply, now you should be able run the configuration by selecting it in the dropdown menu.

Hope this can help achieve what you want to do.

If anyone has a better solution to resolve this issue, i.e. dealing with conflicting JDK versions, feel free to chime in!
</panel>

</panel>


<panel type="info" header="### 93. NAM ..QUAN `@quannam0124` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: run .\gradlew checkstyleMain fails with could not initialize class error**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115" expanded>

#My Checkstyle with Gradle build is failing 
I have reused the checkstyle.xml and supressions.xml files. However, when i run gradlew checkstyleMain, the build fails with the following error:
> Could not initialize class org.codehaus.groovy.runtime.InvokerHelper

If anyone encountered a similar problem and have solved it, I would greatly appreciate the assistance. Thank you! 👍 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232939950" expanded>

> Hi, I looked at your ip repo but I don't see the config/checkstyle folder in your root directory. Have you tried following all the steps in the [checkstyle guide](https://se-education.org/guides/tutorials/checkstyle.html)? Perhaps you can push what you have to your repo.

Hello! I just pushed the checkstyle folder to the repo
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232940737" expanded>

> Hi, try building your app to ensure all dependencies are installed?
> 
> either `./gradlew build` or `gradlew build`

I tried doing that and the build failed with this error 😢 I ran it using the terminal on Intellij

> Could not initialize class org.codehaus.groovy.reflection.ReflectionCache


![image](https://user-images.githubusercontent.com/77949597/187690516-39c97218-f918-482f-809f-48f29e9cb2cb.png)


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1232965956" expanded>

Oh thank you! I have added to build.gradle file and renamed suppressions.xml. So far Im still running into this error when i run ```./gradlew build``` and ```./gradlew checkstyleMain```

> Could not initialize class org.codehaus.groovy.reflection.ReflectionCache

When I run main method in Duke it builds and runs normally, so I'm not sure why this error is popping up
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/115#issuecomment-1233129204" expanded>

My JDK Settings is JDK 11 for my project settings and GRADLE JVM. I deleted my .idea folder, .gradle folder, and build folder. Then I ran ./gradlew build again and the error doesn't show up anymore! Thank you everyone for your help!!
</panel>

</panel>


<panel type="info" header="### 94. YANG..NYAN `@TheSoggy` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Are we allowed to trim unnecessary parts of command usage message for commands?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/421" expanded>

Is it okay in v1.4 to trim and remove the unnecessary parts of our usage message to standardize it across similar commands?

E.g. Trimming from `Marks a specific debt of the person identified by the index number used in the displayed person list as paid. The debt is specified by the index number of the debt displayed in the person's debt field. Multiple debts may be specified.` to `Marks a debt of a person as paid. Multiple debts may be specified.`

Our delete debt command has the same command format as mark debt command and its usage message follows the latter's format `Deletes a debt from a person. Multiple debts may be specified.`
</panel>

<panel  header="**2. :fas-info-circle: Are we allowed to make changes to components that could potentially have a bug?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/410" expanded>

1. When we merged the pull request that changed the GUI, we intended for the GUI to keep track of the user's expanded tab. All our commands are currently implemented such that after execution, the previous list is kept so we thought that the the list (including expansions) will continue to be kept. &gt;br>
We did not expect that when a command is entered, it would reset the tabs and close all of them. We had a pull request to fix this at 28 Oct 12pm, which was after the v1.3 jar deadline. Can this be considered a bug even though we did not explicitly state what the intended behavior of the component would be? &gt;br>
![image](https://user-images.githubusercontent.com/8470009/199199389-01b56b5f-071f-4dfb-a82e-7f9f39e41ce6.png)

1. Before we updated the GUI in the pull request, there was a "No Debts" placeholder in our simple text UI. But after we updated the UI, the placeholder was no longer available. Would this be considered as a bugfix to fix the functionality that was available in our v1.3 demo and unintentionally missing in v1.3.2 after we updated the GUI?
![image](https://user-images.githubusercontent.com/8470009/199201708-abe2ceb8-9fe0-4dbc-ab93-71516e38d986.png)
![image](https://user-images.githubusercontent.com/8470009/199203151-54d10472-e4da-4f6a-bceb-1f8eec82b08d.png)

1. Is updating a error message when the error message is being used on a wrong error counted as correcting a misbehaviour? Currently when we catch a invalid date it says "Dates should be in yyyy-mm-dd" instead of "That's not a valid date".  &gt;br>
![image](https://user-images.githubusercontent.com/8470009/199200634-cb361116-8eaa-4070-b8f0-274c712cea57.png)


</panel>

<panel  header="**3. :fas-info-circle: Requesting for help in smoke testing (Windows, Mac, and Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/291" expanded>

You can find the latest version [here](https://github.com/TheSoggy/ip/releases/tag/A-Release) and the user guide [here](https://thesoggy.github.io/ip/). Thanks in advance!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/291#issuecomment-1255916682" expanded>

Thanks for the help guys! @Yongbeom-Kim I have fixed the bug mentioned in your comment, would you mind helping me test again? The release is [here](https://github.com/TheSoggy/ip/releases/tag/A-Release). Thank you so much!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/410#issuecomment-1298298241" expanded>

@damithc Here you go: https://github.com/AY2223S1-CS2103T-W13-3/tp/pull/206. We had already merged a fix but are now worried if it violates anything so we will revert the merge if its not allowed.
</panel>

</panel>


<panel type="info" header="### 95. RACH..AWAN `@Rachel-AG` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for Smoke Test Help (Mac/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/232" expanded>

Hi, I've just updated my previous release and I would really appreciate it if anyone can help me run some smoke tests on Mac/Linux. 

The JAR file can be found [here](https://github.com/Rachel-AG/ip/releases/tag/A-Release).

Thanks you!
</panel>

<panel  header="**2. :fas-info-circle: Request for smoke testing help (Mac/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/207" expanded>

Hi! Would appreciate it if anyone can help me test my JAR file on Mac/Linux. 
The release can be found [here](https://github.com/Rachel-AG/ip/releases/tag/v0.2). 
Thanks!

UPDATE: Most recent release can be found [here](https://github.com/Rachel-AG/ip/releases/tag/v0.3).
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/207#issuecomment-1248514360" expanded>

I see! Thank you for your help @RezwanArefin01
Here is my updated [release](https://github.com/Rachel-AG/ip/releases/tag/v0.3).
Would really appreciate it if anyone can test it again. Thanks!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/207#issuecomment-1249036581" expanded>

I see! Thank you everyone @RezwanArefin01 @zlimez 😄 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/232#issuecomment-1250050208" expanded>

Thank you!! @RezwanArefin01 @sltsheryl 
</panel>

</panel>


<panel type="info" header="### 96. FLOR..WONO `@florentianayuwono` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Cannot build or run after using Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/68" expanded>

In IntelliJ, in the beginning I cannot run the file Duke.java after merging the Gradle branch to master.
![Screenshot (471)](https://user-images.githubusercontent.com/76247368/186678048-8c1ff2ad-8596-4dde-9da7-31eea94a2bdf.png)

So, I tried running specifically from the Duke.main() and it shows successful run.
![Screenshot (473)](https://user-images.githubusercontent.com/76247368/186677802-f2ab9990-eebe-49a8-9f63-819a3c592a44.png)

But then when I tried `gradlew clean test` in my terminal, it shows something like this.
![Screenshot (474)](https://user-images.githubusercontent.com/76247368/186678443-fa5ef241-d490-4423-a1d6-07caa148665b.png)

So I tried `.\gradlew clean test`, but then it shows error like this.
![Screenshot (475)](https://user-images.githubusercontent.com/76247368/186678612-03c245e2-0eaf-4ff8-a159-cc0da795070e.png)

I have tried googling the error type:
```
* What went wrong:
Could not initialize class org.codehaus.groovy.runtime.InvokerHelper
```

But according to this [article](https://youtrack.jetbrains.com/issue/IDEA-253061/Could-not-initialize-class-orgcodehausgroovyruntimeInvokerHelper), it said that:
Looks the Gradle version is not incompatible with your Project JDK version.
Please try to use the Gradle version 6.3 or later. If it doesn't help, also try to update the JDK version to JDK8/11/14.

But I have make sure that my Gradle version and JDK is as specified. Here are the references for my Project Setting:

![Screenshot (476)](https://user-images.githubusercontent.com/76247368/186679439-de31aa42-cb2e-41c1-92f9-a380bf8114ea.png)
![Screenshot (477)](https://user-images.githubusercontent.com/76247368/186679456-42eb519b-95e7-4469-b697-1bd370da3e3e.png)
![Screenshot (478)](https://user-images.githubusercontent.com/76247368/186679458-eda1fa97-24cb-49af-ae6f-55f8b5b7379b.png)
![Screenshot (479)](https://user-images.githubusercontent.com/76247368/186679463-f0bc6fe6-9437-436a-857a-37aefc943490.png)

I have an assumption that the Gradle error is connected to the issue that I cannot run from Duke but have to go to Duke.main(), but I don't know what went wrong that caused that issue.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/68#issuecomment-1227393852" expanded>

Thank you! Yes, I have tried doing that. Update on my case:

In Intellij, after deleting some file with heavy string content, I can run the Duke.java directly. I have tried build and running from the Gradle toolbar and it seems successful. I have also tried clicking on other type of tasks also.
![Screenshot (480)](https://user-images.githubusercontent.com/76247368/186699848-7165a0d3-7005-487b-adaf-4d166c24fb0e.png)


But somehow when I tried to type in the terminal, the error still persists. Here is the full info on the error. I am wondering on what went wrong with the terminal way? It said something about `Java home is different.`
```
PS C:\Users\HEWLETT PACKARD\ip> .\gradlew --info clean test                                                                                             
Initialized native services in: C:\Users\HEWLETT PACKARD\.gradle\native                                                                                 
Found daemon DaemonInfo{pid=3156, address=[e6f39c89-cbf1-432e-b507-58a1456f57d2 port:64887, addresses:[/127.0.0.1]], state=Idle, lastBusy=1661438419670,
 context=DefaultDaemonContext[uid=b1414354-1abd-438c-a414-2526f4d8c732,javaHome=C:\Program Files\Java\jdk-11.0.13,daemonRegistryDir=C:\Users\HEWLETT PAC
KARD\.gradle\daemon,pid=3156,idleTimeout=10800000,priority=NORMAL,daemonOpts=--add-opens,java.base/java.util=ALL-UNNAMED,--add-opens,java.base/java.lang
=ALL-UNNAMED,--add-opens,java.base/java.lang.invoke=ALL-UNNAMED,--add-opens,java.prefs/java.util.prefs=ALL-UNNAMED,-XX:MaxMetaspaceSize=256m,-XX:+HeapDu
mpOnOutOfMemoryError,-Xms256m,-Xmx512m,-Dfile.encoding=utf8,-Duser.country=ID,-Duser.language=en,-Duser.variant]} however its context does not match the desired criteria.
Java home is different.
Wanted: DefaultDaemonContext[uid=null,javaHome=C:\Program Files\Java\jdk-17.0.1,daemonRegistryDir=C:\Users\HEWLETT PACKARD\.gradle\daemon,pid=32472,idle
Timeout=null,priority=NORMAL,daemonOpts=--add-opens,java.base/java.util=ALL-UNNAMED,--add-opens,java.base/java.lang=ALL-UNNAMED,--add-opens,java.base/ja
va.lang.invoke=ALL-UNNAMED,--add-opens,java.prefs/java.util.prefs=ALL-UNNAMED,-XX:MaxMetaspaceSize=256m,-XX:+HeapDumpOnOutOfMemoryError,-Xms256m,-Xmx512m,-Dfile.encoding=windows-1252,-Duser.country=ID,-Duser.language=en,-Duser.variant]
Actual: DefaultDaemonContext[uid=b1414354-1abd-438c-a414-2526f4d8c732,javaHome=C:\Program Files\Java\jdk-11.0.13,daemonRegistryDir=C:\Users\HEWLETT PACK
ARD\.gradle\daemon,pid=3156,idleTimeout=10800000,priority=NORMAL,daemonOpts=--add-opens,java.base/java.util=ALL-UNNAMED,--add-opens,java.base/java.lang=
ALL-UNNAMED,--add-opens,java.base/java.lang.invoke=ALL-UNNAMED,--add-opens,java.prefs/java.util.prefs=ALL-UNNAMED,-XX:MaxMetaspaceSize=256m,-XX:+HeapDumpOnOutOfMemoryError,-Xms256m,-Xmx512m,-Dfile.encoding=utf8,-Duser.country=ID,-Duser.language=en,-Duser.variant]

  Looking for a different daemon...
Found daemon DaemonInfo{pid=27056, address=[ac2d7e8e-87d6-4ddf-9b39-e0b8f774c479 port:65067, addresses:[/127.0.0.1]], state=Idle, lastBusy=1661439351975
, context=DefaultDaemonContext[uid=6a0bfc11-7cf4-4c39-8a66-a76402321890,javaHome=C:\Program Files\Java\jdk-11.0.13,daemonRegistryDir=C:\Users\HEWLETT PA
CKARD\.gradle\daemon,pid=27056,idleTimeout=10800000,priority=NORMAL,daemonOpts=--add-opens,java.base/java.util=ALL-UNNAMED,--add-opens,java.base/java.la
ng=ALL-UNNAMED,--add-opens,java.base/java.lang.invoke=ALL-UNNAMED,--add-opens,java.prefs/java.util.prefs=ALL-UNNAMED,-XX:MaxMetaspaceSize=256m,-XX:+Heap
DumpOnOutOfMemoryError,-Xms256m,-Xmx512m,-Dfile.encoding=windows-1252,-Duser.country=ID,-Duser.language=en,-Duser.variant]} however its context does not match the desired criteria.
Java home is different.
Wanted: DefaultDaemonContext[uid=null,javaHome=C:\Program Files\Java\jdk-17.0.1,daemonRegistryDir=C:\Users\HEWLETT PACKARD\.gradle\daemon,pid=32472,idle
Timeout=null,priority=NORMAL,daemonOpts=--add-opens,java.base/java.util=ALL-UNNAMED,--add-opens,java.base/java.lang=ALL-UNNAMED,--add-opens,java.base/ja
va.lang.invoke=ALL-UNNAMED,--add-opens,java.prefs/java.util.prefs=ALL-UNNAMED,-XX:MaxMetaspaceSize=256m,-XX:+HeapDumpOnOutOfMemoryError,-Xms256m,-Xmx512m,-Dfile.encoding=windows-1252,-Duser.country=ID,-Duser.language=en,-Duser.variant]
Actual: DefaultDaemonContext[uid=6a0bfc11-7cf4-4c39-8a66-a76402321890,javaHome=C:\Program Files\Java\jdk-11.0.13,daemonRegistryDir=C:\Users\HEWLETT PACK
ARD\.gradle\daemon,pid=27056,idleTimeout=10800000,priority=NORMAL,daemonOpts=--add-opens,java.base/java.util=ALL-UNNAMED,--add-opens,java.base/java.lang
=ALL-UNNAMED,--add-opens,java.base/java.lang.invoke=ALL-UNNAMED,--add-opens,java.prefs/java.util.prefs=ALL-UNNAMED,-XX:MaxMetaspaceSize=256m,-XX:+HeapDumpOnOutOfMemoryError,-Xms256m,-Xmx512m,-Dfile.encoding=windows-1252,-Duser.country=ID,-Duser.language=en,-Duser.variant]

* Try:
Run with --stacktrace option to get the stack trace. Run with --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 650ms

```
Here are few articles I have found regarding this error, but none seems to solve my problem.
[java home is different](https://stackoverflow.com/questions/37960949/intellij-idea-says-java-home-is-different)
[build error](https://stackoverflow.com/questions/35536013/intellij-build-error-context-mismatch/41053289#41053289)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/68#issuecomment-1227440774" expanded>

Thank you for the help!

Update:
- I have restarted the IDE and terminal, but seems like now it isn't the cause.
- For @Berted, yes now that I remember, my terminal is indeed the Java 17. I have tried your Edit Configurations and it showed successful build even though I haven't tried with the real JUnit tests. I will update again later after adding JUnit tests. Once again, thank you!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/68#issuecomment-1227551359" expanded>

Update: it works! Thank you everyone!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/485#issuecomment-1324984739" expanded>

In the website, it is said that for Object UML Diagram multiplicity is omitted because it is always 1. So I also wonder whether the case for omitted multiplicity in Class Diagram translates to `1`, `0...1` or `*` multiplicity.
</panel>

</panel>


<panel type="info" header="### 97. ANJA..RWAL `@agarwal-anjali` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Is it still a good design if all attributes of a person are not immutable?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/361" expanded>

Initially the edit command was only to edit an attribute of a single person at a time and when the execute method of the edit command was called a new instance of  a Person was created with the edited attributes and the person list in the address book was updated.

But now, if I have a feature in which I am editing an attribute of all persons (say attribute X) in the address book, is it better to have attribute X mutable so that when the execute method of the edit command for this attribute is called we can modify the value for this attribute for all the persons in the address book or should we maintain the immutability of the attributes of a person and create a new instance of each person for the edited attribute X (equivalent to replicating the address book in the memory with the updated attribute) every time attribute X  is being edited?
</panel>

<panel  header="**2. :fas-info-circle: A-OOP: Can we call TaskList functions within Parser class?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/91" expanded>

As per the guidelines Parser class must interpret the user input. So after interpreting the user input can we perform the required actions on the list of tasks (using the functions of the TaskList class) within the Parser class itself or do we need to return the interpreted user input back to the Duke class and call TaskList functions there?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1243340862" expanded>

Here's the GUI for my Alpha Bot!

![GUI snippet](https://user-images.githubusercontent.com/97397344/189599079-c5e13006-f877-4d03-bc43-b1e17cbc26ae.png)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/361#issuecomment-1286450372" expanded>

> @agarwal-anjali This is a good question for a discussion. Have you already tried either of the options yet?

Yes, in my current implementation the attribute X is mutable for a person!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/361#issuecomment-1286451075" expanded>

> One reason to prefer an immutable person is that it lessens the memory impact of the implementation of the undo command using a VersionedAddressBook. In this case, the same Person objects can be used across multiple VersionedAddressBooks.

Yeah thank you, it makes sense!
I shall consider making all the attributes of a person immutable.
</panel>

</panel>


<panel type="info" header="### 98. ONG ..STER `@lesterong` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Can the following issues be counted as not in scope?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/443" expanded>

1. <img width="1317" alt="image" src="https://user-images.githubusercontent.com/84223259/201468645-28e8daaf-d3a9-4088-9a9b-dbb4e0d60b61.png">

nus-cs2103-AY2223S1/pe-dev-response#4848: The bug reported did not mention how it was reproduced. However after investigating, we realised that it might be due to the way the user opened the program. Opening the program by double clicking and opening it by `java -jar` command saves to a different data json file. The respective json files are updated correctly, depending on how the application was launched. Since the tester used two different methods of launching the jar file, it appeared to the tester that the json file was not being updated correctly. We also found that AB3 has the same behaviour as this. Hence, we feel that this might be 'not in scope' as you didn't break something that worked already. 


2. <img width="1228" alt="image" src="https://user-images.githubusercontent.com/84223259/201468672-a74c1623-bff0-4703-9ae8-6dbae780eec4.png">

nus-cs2103-AY2223S1/pe-dev-response#4847: We find that it may be not in scope, as the instructions for PE specify:
> Launch the jar file using the java -jar command rather than double-clicking (reason: to ensure the jar file is using the same java version that you verified above). Use double-clicking as a last resort.

However, if it is not considered out of scope, since we did mention it in our UG, we were wondering if we could lower the severity as we don't think this is a major issue, as it only happens on the first initial launch, and only for MacOS users. The subsequent launches will not cause the same prompt to the user. 

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/62#issuecomment-1225893806" expanded>

Hey @cliftonfelix, you're using the `LocalDate` correctly, and that is the behaviour of the `LocalDate` class in Java. In fact, you do not even need to use the `inputformatter`, and you can run `LocalDate.parse("2022-08-24")` directly.

A workaround according to this [question on Stack Overflow](https://stackoverflow.com/questions/66587606/i-want-to-check-if-date-is-correct-like-2021-02-31-is-not-correct) is to use the `ResolverStyle` enum in Java.

```java
import java.time.LocalDate;
import java.time.format.DateTimeFormatter;
import java.time.format.ResolverStyle;

DateTimeFormatter inputFormatter = DateTimeFormatter.ofPattern("uuuu-M-d").withResolverStyle(ResolverStyle.STRICT);

// No Exception
LocalDate.parse("2022-02-28", inputFormatter)
// Throws an Exception
LocalDate.parse("2022-02-31", inputFormatter)
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/288#issuecomment-1254567278" expanded>

In this case, it refers to the `requireNonNull(T obj)` method found in `java.util.Objects`. All you need to do is import it.
```java
import static java.util.Objects.requireNonNull;
```

That said, you can use `requireAllNonNull(Object... items)` as well, since it takes in a variable number of arguments.


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/360#issuecomment-1285165227" expanded>

Yes, UI updates are affected by the feature freeze in v1.4. You can find more information [here](https://nus-cs2103-ay2223s1.github.io/website/admin/tp-w12.html#2-start-fixing-ped-bugs-before-the-tutorial).

<img width="762" alt="image" src="https://user-images.githubusercontent.com/84223259/196902339-1e290fb9-04e5-4e75-8689-97c42c96f4a6.png">

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/443#issuecomment-1312501268" expanded>

Thanks Prof! 
</panel>

</panel>


<panel type="info" header="### 99. TOH ..REMY `@deepimpactmir` (4 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111#issuecomment-1232461771" expanded>

Can we see your build.gradle? Seems like `javafx` is not loaded.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/111#issuecomment-1232475815" expanded>

Can you try following [this](https://openjfx.io/openjfx-docs/#gradle) instead? This seems to work fine for me.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/222#issuecomment-1249253008" expanded>

I think you'll have to pull first before pushing. If you can't pull due to the commit, you can reset using `git reset --soft HEAD~1`


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/246#issuecomment-1250198627" expanded>

You probably should bump your version of JavaFX to 11.0.2. Look at this for [more details](https://bugs.openjdk.org/browse/JDK-8210411). The issue is the version you're using does not support Wayland which is the default compositor on Ubuntu.
</panel>

</panel>


<panel type="info" header="### 100. JESS..TIJO `@maryjess` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: [Code Dashboard] iP code not shown in code dashboard**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/33" expanded>

My iP code is not shown in the code dashboard, however its progress is shown in the progress dashboard. 
To my understanding, the dashboards are updated daily, and my last update to the code was yesterday afternoon. 
For this case, should I just wait for the code dashboard to be updated, or is there anything I should do?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/33#issuecomment-1221213258" expanded>

Yes, by update I meant pushing to GitHub. I checked again just now and the code is still not updated. The dashboard shows that the last updated time was this morning though.
![image](https://user-images.githubusercontent.com/88389105/185725827-3305a670-9f02-492b-9a93-a775dac9e54e.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/33#issuecomment-1221241159" expanded>

I see. Thank you Prof!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1236125154" expanded>

I tried moving the `start` method to another class `Main`.
Then I simply changed the parameter of `launch()` in `Launcher` to be `Main.class`.

Works on my side!
</panel>

</panel>


<panel type="info" header="### 101. CHUA..RDAN `@JordanChua` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: JavaFX java.lang.NullPointerException: Input stream must not be null**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/120" expanded>

Hi I have been following the steps as stated in implementing the GUI but when running my launcher class I get a nullPointer Exception, which i suspect may be due to some problem in the directory I have input in the specific lines: 

As per the error message it appears that in this particular part of MainWindow.fxml: 
'
xmlns="http://javafx.com/javafx/8.0.171" xmlns:fx="http://javafx.com/fxml/1"
'
Intellij gives the warning that these 2 URL are not supported.

Any help or ideas on what could be wrong would be appreciated :) Here is the link to my current branch if its easier to see: 
[branch-level-10](https://github.com/JordanChua/ip/tree/branch-Level-10)


'''java
javafx.fxml.LoadException: 
/C:/Users/jcyx1/OneDrive/Documents/GitHub/ip/build/resources/main/view/MainWindow.fxml:9

	at javafx.fxml.FXMLLoader.constructLoadException(FXMLLoader.java:2625)
	at javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:2603)
	at javafx.fxml.FXMLLoader.loadImpl(FXMLLoader.java:2466)
	at javafx.fxml.FXMLLoader.load(FXMLLoader.java:2435)
	at duke.Main.start(Main.java:26)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$9(LauncherImpl.java:846)
	at com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
	at java.base/java.security.AccessController.doPrivileged(AccessController.java:391)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
	at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
	at com.sun.glass.ui.win.WinApplication._runLoop(Native Method)
	at com.sun.glass.ui.win.WinApplication.lambda$runLoop$3(WinApplication.java:174)
	at java.base/java.lang.Thread.run(Thread.java:830)
Caused by: java.lang.NullPointerException: Input stream must not be null
	at javafx.scene.image.Image.validateInputStream(Image.java:1117)
	at javafx.scene.image.Image.&gt;init>(Image.java:701)
	at duke.MainWindow.&gt;init>(MainWindow.java:27)
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
Caused by: java.lang.NullPointerException: Input stream must not be null
'''

:bulb: You can use [Markdown](https://guides.github.com/features/mastering-markdown/) to format your text

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/120#issuecomment-1233986295" expanded>

Sure this is the code for my build.gradle file: 
[build.gradle.txt](https://github.com/nus-cs2103-AY2223S1/forum/files/9468485/build.gradle.txt)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/120#issuecomment-1234045678" expanded>

Sure I have pushed my current changes to my branch and I have attached the link to it in my orginal post as well :)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/120#issuecomment-1234076425" expanded>

I changed my images to png format and it worked! Thank you for the help! 👍 
</panel>

</panel>


<panel type="info" header="### 102. YANG..IANG `@Shawn532` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Workflow of tp**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/329" expanded>

I am a bit confused about the workflow of the tp. I want to add two commands. The first is adding students, and the second is deleting students. Should I do these on two separate branches, or is one okay?

Also, if I do it on two separate branches,  the second command depends on the first. Do I create another branch from the first branch?
</panel>

<panel  header="**2. :fas-info-circle: CI checks unsuccessful**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/162" expanded>


<img width="1728" alt="first" src="https://user-images.githubusercontent.com/77186068/189378338-9a9a577e-389a-4c11-9032-367241d73def.png">
<img width="1630" alt="first 2" src="https://user-images.githubusercontent.com/77186068/189378396-71b0854c-feac-4ffc-b27f-f8680f52ff1e.png">

I couldn't pass the CI checks for the ip. It shows an error cannot find symbol Main.class, but I have class Main in my code, and when I run 
`./gradlew check`
in intellij it doesn't show an error message. I am very confused. Can someone please kindly help?


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/162#issuecomment-1242593603" expanded>

> There is no Main class in your master branch, have u pushed it ?

I realized I somehow accidentally added the Main class in .gitignore file earlier. After fixing that, I passed the CI. Thank you very much!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/329#issuecomment-1268482345" expanded>

> @Shawn532 Adding and deleting go together, so it should be fine to do as one PR, providing you aim to merge the PR within the span of one iteration.

Okay thank you prof! Let's say I want to add another command which is not so related, like adding a question, then I need to create a separate branch and do two PRs right?
</panel>

</panel>


<panel type="info" header="### 103. WAH ..RREN `@Darren12345677` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Very odd commits reflected in version history**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/148" expanded>

![image](https://user-images.githubusercontent.com/63776243/188636834-b569d158-de34-41d1-ad65-39821f401686.png)

Hi friends, I have 2 commits labeled "Merge branch 'master' of https://github.com/Darren12345677/ip" after I merged 2 pull requests from 2 branches and I do not know what that commit is or how it came about. Why is there no destination branch? 
</panel>

<panel  header="**2. :fas-info-circle: Formatting suggestions for line exceeding 120 characters**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/67" expanded>

For the design of ROOFUS's greeting, I want to display this design. However, it does not conform to the hard limit of 120 characters per line. Is it possible for me to exceed the limit for this case? Otherwise, does anyone have any other suggestions? 

![image](https://user-images.githubusercontent.com/63776243/186678063-849ba801-2fae-44f8-9dbc-d8b93d12feca.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/67#issuecomment-1229122949" expanded>

Thank you all! I think the next file is a great idea! @damithc @clarence-chew. 
Yes I will follow your suggestion in the future, thanks @lfrostbytee 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/148#issuecomment-1242931955" expanded>

Thank you so much! @huzaifa1712 
The links were very helpful. I realized that when I pull from remote Master to local Master, I tick the option to "Create a new merge commit even if fast-forward is possible" which created that merge commit message. This is unnecessary because I already merged the branch via pull request and I am only pulling the remote Master to update my local repository.  
</panel>

</panel>


<panel type="info" header="### 104. SEE .. WEI `@seetohjinwei` (4 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/93#issuecomment-1229466916" expanded>

Have you tried some of the solutions from here?

```
File -&gt; Invalidate Caches / Restart... -&gt; Invalidate and Restart
```

https://stackoverflow.com/questions/39952303/intellij-idea-doesnt-see-classes-but-building-via-gradle-works
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232498017" expanded>

![image](https://user-images.githubusercontent.com/47915290/187604955-478a5bc1-e98b-48b7-b8d0-90bee23b4af0.png)

Here's my GUI, which is very similar to the one in the tutorial, but I changed the image size slightly and changed the user image.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/224#issuecomment-1249302240" expanded>

![image](https://user-images.githubusercontent.com/47915290/190638436-7a6c92a7-592a-42b4-89a4-e06867d75626.png)

Seems to work fine for me on macos!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/245#issuecomment-1250075594" expanded>

![image](https://user-images.githubusercontent.com/47915290/190860425-09a49cab-6314-4902-abeb-744f395d1618.png)


Hi! Seems to work fine on macos (except resizing the window).
</panel>

</panel>


<panel type="info" header="### 105. TAN ..XIAN `@yixiann` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Are input validations catching visually similar symbols with a different unicode a bug? And if so can we modify the error message to include more details?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/411" expanded>

This is with reference to : https://github.com/AY2223S1-CS2103T-W16-2/tp/issues/397

In a more extreme case

<img width="1073" alt="image" src="https://user-images.githubusercontent.com/78332456/199273149-af36e57b-aaf6-45e2-9d26-eed816a5810f.png">


V.S.

<img width="1091" alt="image" src="https://user-images.githubusercontent.com/78332456/199272297-973f61b8-6303-4a8f-9f9e-79e68685fbdb.png">

Our application current is able to differentiate both symbols but it looks like a bug. 

<img width="923" alt="image" src="https://user-images.githubusercontent.com/78332456/199273238-e1879ca9-d9b9-4a89-a863-7238b6198da4.png">

Are we then allowed to modify the error message as such:

<img width="463" alt="image" src="https://user-images.githubusercontent.com/78332456/199273399-bc2aa749-a7e9-4b5b-8d30-29afbd24f29b.png">


</panel>

<panel  header="**2. :fas-info-circle: Evaluation of effort for modification of AB3**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/275" expanded>

We are morphing our AB3's. May we know how effort is quantified?

In the case of the new feature, we believe it will be more straightforward as we can count lines of code or count features of equivalent work.

However, in the case of modifications, how are these modifications measured since a portion of this code has been written before or our functionalities are similar to what AB3 is currently doing?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/109#issuecomment-1235406199" expanded>

I am facing the same issue at:

https://nus-cs2103-ay2223s1.github.io/website/schedule/week5/topics.html#supplementary-requirements

In the sentence:
A supplementary requirements section can be used to capture requirements that do not fit elsewhere. Typically, this is where most Non-Functional Requirements will be listed.

After clicking 
"Non-Functional Requirements"

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/411#issuecomment-1298754182" expanded>

Thank you prof!
</panel>

</panel>


<panel type="info" header="### 106. LEE ..YANG `@zylee348` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: jar file returns javafx.fxml.LoadException**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/184" expanded>

running on windows 10; gradlew run works perfectly fine but after building the shadowJar, it returns exceptions

![image](https://user-images.githubusercontent.com/90611909/189877576-1502cdb5-3fdd-4876-b60c-25b88a90a067.png)

</panel>

<panel  header="**2. :fas-info-circle: branches not showing up in ip progress dashboard**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/80" expanded>

My branch-level-8 and A-CodingStandard aren't showing up on the iP progress dashboard. For branch-level-8, after 3hrs of continual screw ups with sourcetree, I redownloaded my repo and continued work from there for wk3 tasks. However, the branch-level-8 still failed to show up and now the A-CodingStandard. This is the current state of the master branch
![image](https://user-images.githubusercontent.com/90611909/187011971-58f5f482-bae6-4925-813c-33016bff184d.png)

![image](https://user-images.githubusercontent.com/90611909/187011959-e298cf63-8277-423a-91d4-87f94a820895.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/184#issuecomment-1245245418" expanded>

I actually changed that at already after a first round of debugging but this my gradle file that led to this error

```
plugins {
    id 'java'
    id 'application'
    id 'checkstyle'
    id 'com.github.johnrengelman.shadow' version '5.1.0'
    id 'org.openjfx.javafxplugin' version '0.0.10'

}

repositories {
    mavenCentral()
}

checkstyle {
    toolVersion = '10.2'
}

dependencies {
    String javaFxVersion = '11.0.2'

    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'
    testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
    testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'
}

test {
    useJUnitPlatform()

    testLogging {
        events "passed", "skipped", "failed"

        showExceptions true
        exceptionFormat "full"
        showCauses true
        showStackTraces true
        showStandardStreams = false
    }
}

javafx {
    version = "11.0.2"
    modules = [ 'javafx.controls', 'javafx.fxml' ]
}

application {
    mainClassName = "duke.Launcher"
}


shadowJar {
    archiveBaseName = "duke"
    archiveClassifier = null
}

run{
    standardInput = System.in
}
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/184#issuecomment-1245273478" expanded>

Solved: naming errors in fxml images
</panel>

</panel>


<panel type="info" header="### 107. ISAA..YANG `@Isaaclhy00` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to run jar file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/305" expanded>

Able to run the jar file inside IntelliJ, however unable to run it from the terminal.
* Ran using java 11 inside IntelliJ

Error message when running from terminal as follows
* WARNING: Unsupported JavaFX configuration: classes were loaded from \'unnamed module @4b4d0112\' 
* Graphics Device initialization failed for : d3d, sw 
* Error initializing QuantumRenderer: no suitable pipeline found 
* Loading library prism_es2 from resource failed: java.lang.UnsatisfiedLinkError: /Users/iz/.openjfx/cache/11/libprism_es2.dylib: dlopen(/Users/iz/.openjfx/cache/11/libprism_es2.dylib, 0x0001): tried: '/Users/iz/.openjfx/cache/11/libprism_es2.dylib' (mach-o file, but is an incompatible architecture (have 'x86_64', need 'arm64e'))



</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/305#issuecomment-1257237569" expanded>

The same issue used to appear when I run it in IntelliJ, however I have already removed it and rebuilt the jar file, now it runs fine in IntelliJ. But I can't get it to run after uploading the jar file to GitHub, or from the terminal.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/305#issuecomment-1259821110" expanded>

Hi I've attempted to fix it, any kind soul would help with a simple smoke test [here](https://github.com/Isaaclhy00/ip/releases) ?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/305#issuecomment-1261252832" expanded>

Thank you so much @RussellDash332 :)
</panel>

</panel>


<panel type="info" header="### 108. CHEW..KENG `@rgonslayer` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: tP Task - v1.1 PR**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/321" expanded>

I noticed in week 7, my v1.1 PR is marked as overdue although I have created PRs and it was successfully merged by my teammates. It was also tagged as milestone v1.1. I was wondering if there was anything I may have missed out which caused it to be marked as overdue?
</panel>

<panel  header="**2. :fas-info-circle: cloning with SourceTree produces an error**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/17" expanded>

While cloning my repo using SourceTree after forking, I ran into this error and I am not sure how to resolve it even after googling the issue. 

'hg clone git@github.com:rgonslayer/jarvis.git /Users/dylenchew/jarvis 
Couldn't posix_spawn: error 2
Completed with errors, see above'

From what I can find, it has to do with my Python version being changed from an update on MacOS. For further diagnostic information, I am running an Intel Mac on version 12.5. 


Would appreciate any help as it is preventing me from starting on my ip!


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/17#issuecomment-1220444689" expanded>

im not sure how to change from mercurial to git in sourcetree, it seems to default to mercurial as I clone
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/321#issuecomment-1264267071" expanded>

@damithc I managed to resolve the issue! thank you!
</panel>

</panel>


<panel type="info" header="### 109. GABR..UANG `@gabyang` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to set up JavaFXML in step 4 of GUI**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179" expanded>

As stated in the title I am unable to get my Program to run JavaFXML even though I followed the tutorial. Attached is a picture of the current error message when I run the Launcher program. 
![image](https://user-images.githubusercontent.com/88603547/189692928-c85a91a1-8751-4395-b795-74c14ac22e96.png)

Running it with stacktrace leads me to this error: 
![image](https://user-images.githubusercontent.com/88603547/189693372-a700130f-fac3-43cf-b1da-afd101c368d1.png)


Some things I have tried for debugging include:
1) Ensuring that build.gradle is accurate
2) Ensuring that my run configurations are running Java-11
3) Ensuring that my project configurations are set at the latest Java-11
4) Asking my groupmates to help me debug the error 
5) Taking a look at issue #111 

Any help on this matter will be appreciated!

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179#issuecomment-1243976436" expanded>

hi @damithc thanks for taking a look! 

This is the link to my ip, I have opened a PR to merge the JavaFXML changes with the rest of my code. I didn't immediately merge it with the rest of my code because I didn't want to screw up my current ip
https://github.com/gabyang/ip

If you would like me to merge it, let me know!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179#issuecomment-1245665868" expanded>

Hi all, thanks very much for your time and efforts in helping me! I really appreciate it! @sarrrdin @parth-io @deeyonn @domlimm 

Regarding the changes I have made/tried for my JavaFXML integration, I have tried all of your suggestions, namely:
1) Running stacktrace debugging option - error is still the same as before, there is no more elaboration on that
2) Commenting out the main function of Duke.java - unlikely the issue of multiple main methods
3) Downgrade my gradle version and changed the path for the jpg files for Duke and User
4) Resolved the conflict in build.gradle file and also tried commenting out the code for explicit config for JavaFX

And yes, a GUI window is supposed to pop up once the code is running, but there is nothing as of now. Once again thanks to all who took the time to look at my code! 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179#issuecomment-1246570851" expanded>

Thanks! That managed to solve it! Appreciate all of your help! 
</panel>

</panel>


<panel type="info" header="### 110. SAMU..ERNG `@Sampy147` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Can this bug be considered as Response.NotInScope**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/455" expanded>

Our app is a task, exam and module manager, and currently one task is linked to one exam. One tester reflected that one task should be able to link to more than one exam, as some tasks might be in preparation for more than one exam. This appears to be like a extension of a feature but we did not mention this in the UG as a future extension. 

We feel that this can be considered as Response.NotInScope as per the definition below, as the app is reasonably useful and rectifying the feature is less important than the work that has been done already.

<img width="540" alt="image" src="https://user-images.githubusercontent.com/87646810/201607632-c41c5c9a-fbb3-4d3d-ae79-54647f31ab61.png">

Implementing tasks that can be linked to more than 1 exam would require a lot more work and is non-trivial, as the completion bars for tasks and modules would have to change accordingly to account for this. The completion bars being referred to are the ones in the exam panel below.

<img width="548" alt="image" src="https://user-images.githubusercontent.com/87646810/201598024-5e1662ba-83f2-4d87-bd24-4901a25abd87.png">

Furthermore, the deletion and editing of tasks and exams would have to take this into account, given that tasks are linked to exams. For example, when an exam is deleted/edited, all the tasks with this exam should be deleted/edited as well. This implementation is non-trivial and requires comprehensive redesigning of multiple other crucial features for this purpose. In this case, we were wondering if this comment to implement tasks linked to multiple exams can be considered Response.NotInScope. 

The link to the bug report is here:
https://github.com/nus-cs2103-AY2223S1/pe-dev-response/issues/1607
</panel>

<panel  header="**2. :fas-info-circle: Are we allowed to make changes to these components that could potentially be bugs?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/407" expanded>

We have 3 questions to ask regarding whether a feature is considered a functionality bug or feature flaw.

1) We have tasks linked to exams and they each contain a module. Modules with a certain module code are related to tasks and exams with the same module code. When we call edit module method and the module code is edited, the corresponding module code in the exam and in the task is changed, however the links between tasks and exams are dropped too (what we intended to happen is that there should not be a drop in the link between tasks and exams, but we mistakenly did not make this happen). A reviewing team pointed out that we dropped this link between the tasks and their exams when edit module is called and labelled it as a feature flaw. 

A possible scenario can be:

Assuming this is the starting stage, where some modules, exams and tasks are added:

![image](https://user-images.githubusercontent.com/87646810/199163274-05d07084-1ecd-4c90-a3d2-e680147f610c.png)

After calling `m edit 1 c/cs1101`, it should change all the module codes of exams and tasks with `gess1033`  to `cs1101`, with the links between tasks and exams of the same module code to not have dropped. They are dropped as shown:

![image](https://user-images.githubusercontent.com/87646810/199163292-e66d9677-88ea-4772-b4d4-d1df0b7b06f5.png)

We clarified with our TA and he does agree that it could be a functionality bug. Given normal user input, the expected behaviour is that the links between tasks and exams should be preserved, as these links should not be affected when both their module codes change to the same module code when edit module is called. It would cause great inconvenience to the user if editing a module automatically removes links between tasks and exams. 

In the UG, we mentioned `If the module code of the module is edited, and the module is linked to some tasks and exams, the module of these tasks and exams will be changed to this edited module.` It did not mention anything about what happens to the links between task and exam when edit module is called, thus it is implied that these links should not be changed as that is the expected behaviour 


2) Would it be possible to change the name of the placeholder in the command? For example, changing e unlink INDEX to e unlink TASK_INDEX. This won't change the format that the user inputs the command as INDEX and TASK_INDEX both accept numbers and it is just a renaming of the placeholder in the UG.

3) For the display of the module code among the different columns (exams,tasks,modules) , it was pointed out by few groups as a functionality bug that there is some inconsistency in the display of the module code casing in the UI. For example, as shown in the screenshot below, the module code can be displayed in lowercase for the module panel while it can be shown as FULLCAPS for the task panel. Given that we handle module code in all commands as case insensitive, is it possible to standardise the display of the module code such as in all caps to address this functionality bug.

![image](https://user-images.githubusercontent.com/87646810/199164348-55759707-805c-449a-b397-87a091de2626.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/407#issuecomment-1298418709" expanded>

Thanks Prof! This helps! Would like to clarify for point 2 and 3:

2. Would it be allowed if we changed the error message when the user types the command wrongly? For example, we currently have an error message saying showing e unlink INDEX. Would it be allowed to change the message to e unlink TASK_INDEX to reflect the changes we made for the placeholder in the UG

3. Currently our program treats module code name as case insensitive, but we received reviews that mention leaving module codes as inputted by the user might be inconsistent visually as even though for eg both cs2103t and CS2103T are recognised the same by the program, the user might prefer for the module code to all be the same. Another reviewer mentioned that they thought they could edit module with the same letters but different casing, a problem which might have occurred due to inconsistent casing, as shown in thew picture below. Hence, we think that displaying our module codes as FULLCAPS would greatly help the user and resolve these issues. Would this change (taking all user inputs of module codes and just changing the display to the FULLCAPS equivalent(Not changing any underlying code or logic of module code)) be allowed?

![image](https://user-images.githubusercontent.com/87646810/199217805-d2b13cd5-32f4-4cad-a1a6-23e746a00875.png)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/455#issuecomment-1313333740" expanded>

Okay thanks Prof! Appreciate the help!
</panel>

</panel>


<panel type="info" header="### 111. YAP ..ASON `@JasonYapzx` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/212#issuecomment-1248864789" expanded>

Hey seeleng, works fine on Windows 10 for me as well.
For the warnings mentioned by @Benjamin-Sim, it might be because in your `.fxml` files the `xmlns` tag is of JavaFX version 18. But otherwise nice UI and great  visual feedback for erroneous commands :)
![image](https://user-images.githubusercontent.com/63844743/190547625-91182de9-53cb-4109-8c73-9d361d3628f2.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249389582" expanded>

Hey, I tested with the file in your build folder and it works for Windows 10, just remember to upload the release file before the deadline.
![image](https://user-images.githubusercontent.com/63844743/190654273-b8ae95d3-dbe8-4620-88ce-fb30a4df199f.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/227#issuecomment-1249471935" expanded>

> > Hey, I tested with the file in your build folder and it works for Windows 10, just remember to upload the release file before the deadline.
> > ![image](https://user-images.githubusercontent.com/63844743/190654273-b8ae95d3-dbe8-4620-88ce-fb30a4df199f.png)
> 
> Hi I have updated the binary file. Could you pls help to see if the file works? Thanks!

I have tested it again and yes it does work. Hope this helps :) 👍🏻 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/261#issuecomment-1250679217" expanded>

Hey, everything seems to be working fine on my windows 10 machine (reading and writing of save files, commands, and erroneous commands), just the resizing of the application does not follow for the main chat itself. Only the input text field adjusts accordingly. Hope this helps!

![image](https://user-images.githubusercontent.com/63844743/190971453-da8570c8-624b-4a35-8c58-45f90647b6a1.png)

</panel>

</panel>


<panel type="info" header="### 112. HONG..BETH `@elizabethhky` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Cannot cmd f on Module Website pdf**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/490" expanded>

Hi, I created a pdf version of the Software Engineering textbook on the module website and when I open the pdf file using Preview on Macbook, cmd f does not work for certain keywords like "OODM" and "Software Engineering". Is there a way to fix this issue? Thanks!

</panel>

<panel  header="**2. :fas-info-circle: JAR file getting weird characters**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/157" expanded>

Context: 
Mac M1 chip, Project SDK: OpenJDK version 11.0.2

When I run the new JAR file created for my GUI, my text field gets weird characters but the rest of the other components (the dialogbox) shows the text normally and an error pops up in the terminal.
The MainWindow run by java -jar:
<img width="401" alt="Screenshot 2022-09-08 at 6 21 32 PM" src="https://user-images.githubusercontent.com/97357632/189098528-a14b117a-8fa7-428a-9eb8-0d5ebef08883.png">
The Error:
<img width="1461" alt="Screenshot 2022-09-08 at 6 22 23 PM" src="https://user-images.githubusercontent.com/97357632/189098674-43b58236-6190-4b8e-bb81-bc8155c2d15b.png">

I suspected that it was my SDK version but I have already set it to be OpenJDK version 11.0.2. However, when I run `java -version` in my ip terminal, it says that my version is version 11.0.16.1
<img width="658" alt="Screenshot 2022-09-08 at 6 20 08 PM" src="https://user-images.githubusercontent.com/97357632/189098234-0187ebdf-dd6f-4b17-9b07-ae98197dd012.png">

I am quite confused because when I run my Launcher.main() normally, without java -jar, the weird characters do not appear.
The MainWindow ran by running Launcher.main():
<img width="400" alt="Screenshot 2022-09-08 at 6 24 04 PM" src="https://user-images.githubusercontent.com/97357632/189099014-db44a88e-645b-4259-a112-b566d512a2cd.png">

I also tried changing my fxml file to have the font Arial instead of Lucida Grande but it does not seem to work. Any help would be much appreciated! 

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/157#issuecomment-1241501612" expanded>

Thank you so much for the suggestions! It worked 😊 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/490#issuecomment-1325930732" expanded>

Oh I see, thank you so much for your help! 😊 The table of contents page also appears garbled on my computer, not too sure why either.
</panel>

</panel>


<panel type="info" header="### 113. LEE ..GENE `@leecaregene` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Library request: zxcvbn4j**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/375" expanded>

## Library

[zxcvbn4j](https://github.com/nulab/zxcvbn4j)

## Purpose

For estimating the strength of passwords.

This is a java port of [zxcvbn](https://github.com/dropbox/zxcvbn), which is a password strength estimator inspired by password crackers written on JavaScript.

## License

[MIT](https://github.com/nulab/zxcvbn4j/blob/master/LICENSE.txt)

</panel>

<panel  header="**2. :fas-info-circle: Library request: Password4j**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/358" expanded>

## Library

[Password4j](https://password4j.com/)

## Purpose

For easier handling of passwords.

Password4j is a Java fluent cryptographic library for encrypting and checking passwords with different [Key derivation functions](https://en.wikipedia.org/wiki/Key_derivation_function) (KDFs) and [Cryptographic hash functions](https://en.wikipedia.org/wiki/Cryptographic_hash_function) (CHFs).

## License

[Apache 2](https://github.com/Password4j/password4j/blob/master/LICENSE)

</panel>

<panel  header="**3. :fas-info-circle: Library request: OpenCSV**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/351" expanded>

## Library

[OpenCSV](https://opencsv.sourceforge.net/)

## Purpose

For easier reading and writing of CSV files.

OpenCSV is an easy-to-use CSV (comma-separated values) parser library for Java.

## License

[Apache 2](https://opencsv.sourceforge.net/licenses.html)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1233335495" expanded>

Here's my GUI, changes made to the JavaFX tutorial:
* Label resizes to fit text
* Monospace font

![Capture](https://user-images.githubusercontent.com/110937351/187764013-37659662-3311-495f-9c5f-10f3b7cece73.PNG)
</panel>

</panel>


<panel type="info" header="### 114. PANG..ILYS `@Dilysss` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: iP Progress not reflected in iP Progress Dashboard**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/95" expanded>

I have merged and pushed the branches 'branch-Level-9', 'branch-A-JavaDoc' and 'branch-A-CodingStandard', as well as the A-Jar tag but I don't know why they are not being reflected in the iP progress dashboard. 
These screenshots show that my branches and tags have been pushed into git:

![Screenshot 2022-08-28 at 11 12 18 PM](https://user-images.githubusercontent.com/97424532/187081146-b846fb37-7b26-4b95-a356-7f0f66243583.png)
![Screenshot 2022-08-28 at 11 13 00 PM](https://user-images.githubusercontent.com/97424532/187081178-abf2c287-d6dd-4c79-ba44-9b0b0b025601.png)
<img width="534" alt="Screenshot 2022-08-28 at 11 14 45 PM" src="https://user-images.githubusercontent.com/97424532/187081251-8b8448cc-6c2d-4e91-af9f-336bd455f091.png">

Any help would be appreciated!
</panel>

<panel  header="**2. :fas-info-circle: Unable to build and run Duke using Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/71" expanded>

I have merged the 'add-gradle-support' branch and followed the steps for Scenario 2, however the following exceptions occur every time I open my IP.  I can't run my java files as well. May I know how to solve this issue? Thanks!

<img width="1438" alt="Screenshot 2022-08-26 at 1 41 25 PM" src="https://user-images.githubusercontent.com/97424532/186830353-36ed4eac-46b4-411d-8a6a-cba3fcdae512.png">


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/71#issuecomment-1228090974" expanded>

> @Dilysss perhaps push your current code to a branch in your fork and give the link here. That'll allow others to check if they can reproduce the error.

Here is the link: https://github.com/Dilysss/ip/tree/branch-Temp
Thanks!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/95#issuecomment-1229491254" expanded>

Hi prof, I tried merging again but it says 'Already up to date' for all the branches? Also, I did all the merging and pushing the tags and branches this morning so I believe it should have been updated?

<img width="570" alt="Screenshot 2022-08-28 at 11 47 17 PM" src="https://user-images.githubusercontent.com/97424532/187082783-f7c0df99-4254-4387-a807-98ef94bfbedd.png">


</panel>

</panel>


<panel type="info" header="### 115. KANG..XIAN `@kangzongxian` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Gibberish GUI Output (M1 Mac)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/125" expanded>

Hello everyone,

I am a Mac User (M1 Mac) and am trying to do the GUI, but it produces Gibberish like this (https://ibb.co/zHngY2z), along with this error
```
2022-09-02 17:06:18.415 java[8910:271820] CoreText note: Client requested name ".SFNS-Regular", it will get Times-Roman rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[NSFont systemFontOfSize:].
2022-09-02 17:06:18.415 java[8910:271820] CoreText note: Set a breakpoint on CTFontLogSystemFontNameRequest to debug.
2022-09-02 17:06:18.419 java[8910:271820] CoreText note: Client requested name ".SFNS-Regular", it will get Times-Roman rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[NSFont systemFontOfSize:].
2022-09-02 17:06:18.548 java[8910:271858] CoreText note: Client requested name ".SFNS-Regular", it will get Times-Roman rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[NSFont systemFontOfSize:].
```

I have already done up the Week 1 Programming Language Requirements for Mac to use the Java Zulu JDK, may I know if anyone has a solution for this?

Thank you!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/125#issuecomment-1235271249" expanded>

Okay I have resolved it by using another jdk from openadoptjdk

This link helped me: https://github.com/Szaki/XiaomiADBFastbootTools/issues/289
Scroll below to read about the openadoptjdk part in the link above

I already had brew installed, so I did brew install adoptopenjdk

After that I went to Intellij --> File --> Dependencies and I used AdoptOpenJdk as my Dependencies and applied.

That fixed my output and I can now see Hello World!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/125#issuecomment-1235370041" expanded>

Thank you Professor Damith @damithc for the reply!

Ahh I see I will try to see if I can fix it using that method, thank you!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/125#issuecomment-1236101862" expanded>

@Bubbl3T thank you so much for the reply! I went to change it as well and got it fixed, thank you!
</panel>

</panel>


<panel type="info" header="### 116. ZICO..ZICO `@zicotjia` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Requesting help for smoke testing Linux and Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/290" expanded>

Can someone check if there is an issue with my current release in Linux and Mac? The current release is [here](https://github.com/zicotjia/ip/releases/download/v0.2/Duke.jar) and user guide is [here](https://zicotjia.github.io/ip/)
</panel>

<panel  header="**2. :fas-info-circle: Clarification regarding the extent of customization of iP**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/13" expanded>

The instruction said that we are allowed to customize the behavior of Duke such as name and command format. May I ask for clarification on how much we can customize. For example, am I allowed to change the way duke will take in input. For Example, instead of a single line with multiple commands such as `deadline do homework /by 31 Aug`, can I make it that Duke will take one command per line and gives the user instruction after each command.

I.e: 
input: `deadline`
output: `What Is the description of the deadline: `
input:  `do homework`
output: `Please specify the date of the deadline: `
...

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/13#issuecomment-1217836658" expanded>

Thank you for the clarification Prof.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/290#issuecomment-1254959516" expanded>

Thanks for the help. Do you mind doing one more smoke test? Just to check if the image will load or not. The newest release is [here](https://github.com/zicotjia/ip/releases/download/v0.2/Duke.jar).
</panel>

</panel>


<panel type="info" header="### 117. MELI..ANTO `@melissaharijanto` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Interpreting class diagrams with omitted multiplicity**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/485" expanded>

<img width="1225" alt="Screen Shot 2022-11-23 at 19 14 36" src="https://user-images.githubusercontent.com/97304787/203533140-b3c01625-21c5-4a7e-a9ad-2681bdeafe47.png">

Hello, I would like to ask regarding this question in Week 4's weekly quiz in LumiNUS. 

In the class diagram, the multiplicity between the `Admin` class and the `Student` class is omitted. Are we allowed to assume that there is a `0...1` multiplicity between an `Admin` and a `Student` (i.e. an admin can have `0...1` student(s))? 

I am confused as the solution only says that the object diagram is not compliant with the class diagram only because of the professor to professor association. Is an `Admin` object allowed to have no associations to a `Student` object?

</panel>

<panel  header="**2. :fas-info-circle: Are these issues considered UI bugs, and will fixing them be considered as enhancements?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/394" expanded>

Hello Prof, I would like to ask whether we are allowed to modify a few UI issues we received in our bug report:

1. There are extra panels (lines) when there is only one or two items in the list. They seem to appear after a user deletes the data in the `Orders` list. Are we allowed to modify the UI to remove this?
Link to issue: https://github.com/AY2223S1-CS2103T-W15-3/tp/issues/153

**With two items**
![image](https://user-images.githubusercontent.com/97304787/198868275-b7aedc9b-bb6b-4a7a-9757-5c6c6d3f0e3b.png)

**With one item**
![image](https://user-images.githubusercontent.com/97304787/198868283-27a712d5-a944-429e-964d-defdf52a070d.png)

2. Including many item tags will lead to less readability of the items. I believe this is not a test of extreme inputs, and can be changed by setting `HBox` to `FlowPane` instead. Will this modification be allowed?
Link to issue: https://github.com/AY2223S1-CS2103T-W15-3/tp/issues/164
![image](https://user-images.githubusercontent.com/97304787/198868707-57a1baef-080a-43f2-b513-338a3e7aa09d.png)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/394#issuecomment-1296173255" expanded>

Thank you for the confirmation, prof!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/485#issuecomment-1325047126" expanded>

Ah I see, thank you prof! I understand now 👍 
</panel>

</panel>


<panel type="info" header="### 118. LIVI.. LEO `@liviamil` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to run application due to missing JavaFX runtime components**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/190" expanded>

EDIT: current [code](https://github.com/liviamil/ip/tree/branch-Level-10)
Hello, I am trying to implement the GUI, but I have been getting these errors when I attempt to run the program:
```
* What went wrong:
Executing ':Launcher.main() --stacktrace'...

> Task :compileJava UP-TO-DATE
> Task :processResources UP-TO-DATE
> Task :classes UP-TO-DATE

> Task :Launcher.main() FAILED

Deprecated Gradle features were used in this build, making it incompatible with Gradle 8.0.

You can use '--warning-mode all' to show the individual deprecation warnings and determine if they come from your own scripts or plugins.

See https://docs.gradle.org/7.1/userguide/command_line_interface.html#sec:command_line_warnings
3 actionable tasks: 1 executed, 2 up-to-date
Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class sally.main.Main
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:890)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:834)
Caused by: java.lang.reflect.InvocationTargetException
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
	at java.base/java.lang.reflect.Constructor.newInstance(Constructor.java:490)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:802)
	at com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
	at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
	at com.sun.glass.ui.win.WinApplication._runLoop(Native Method)
	at com.sun.glass.ui.win.WinApplication.lambda$runLoop$3(WinApplication.java:174)
	... 1 more
Caused by: java.lang.NullPointerException: Input stream must not be null
	at javafx.scene.image.Image.validateInputStream(Image.java:1117)
	at javafx.scene.image.Image.<init>(Image.java:701)
	at sally.main.Sally.<init>(Sally.java:25)
	at sally.main.Main.<init>(Main.java:17)
	... 13 more

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':Launcher.main()'.
> Process 'command 'C:/Program Files/Java/jdk-11.0.13/bin/java.exe'' finished with non-zero exit value 1

* Try:
Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Exception is:
org.gradle.api.tasks.TaskExecutionException: Execution failed for task ':Launcher.main()'.
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.lambda$executeIfValid$1(ExecuteActionsTaskExecuter.java:188)
	at org.gradle.internal.Try$Failure.ifSuccessfulOrElse(Try.java:263)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:186)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:174)
	at org.gradle.api.internal.tasks.execution.CleanupStaleOutputsExecuter.execute(CleanupStaleOutputsExecuter.java:109)
	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:56)
	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:200)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:195)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:75)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:153)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:62)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.lambda$call$2(DefaultBuildOperationExecutor.java:79)
	at org.gradle.internal.operations.UnmanagedBuildOperationWrapper.callWithUnmanagedSupport(UnmanagedBuildOperationWrapper.java:54)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:79)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:74)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:408)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:395)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:388)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:374)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.lambda$run$0(DefaultPlanExecutor.java:127)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:191)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.executeNextNode(DefaultPlanExecutor.java:182)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:124)
	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
	at org.gradle.internal.concurrent.ManagedExecutorImpl$1.run(ManagedExecutorImpl.java:48)
	at org.gradle.internal.concurrent.ThreadFactoryImpl$ManagedThreadRunnable.run(ThreadFactoryImpl.java:56)
Caused by: org.gradle.process.internal.ExecException: Process 'command 'C:/Program Files/Java/jdk-11.0.13/bin/java.exe'' finished with non-zero exit value 1
	at org.gradle.process.internal.DefaultExecHandle$ExecResultImpl.assertNormalExitValue(DefaultExecHandle.java:414)
	at org.gradle.process.internal.DefaultJavaExecAction.execute(DefaultJavaExecAction.java:52)
	at org.gradle.api.tasks.JavaExec.exec(JavaExec.java:156)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at org.gradle.internal.reflect.JavaMethod.invoke(JavaMethod.java:104)
	at org.gradle.api.internal.project.taskfactory.StandardTaskAction.doExecute(StandardTaskAction.java:58)
	at org.gradle.api.internal.project.taskfactory.StandardTaskAction.execute(StandardTaskAction.java:51)
	at org.gradle.api.internal.project.taskfactory.StandardTaskAction.execute(StandardTaskAction.java:29)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter$2.run(ExecuteActionsTaskExecuter.java:506)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:29)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:26)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:75)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:153)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.run(DefaultBuildOperationRunner.java:56)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.lambda$run$1(DefaultBuildOperationExecutor.java:74)
	at org.gradle.internal.operations.UnmanagedBuildOperationWrapper.runWithUnmanagedSupport(UnmanagedBuildOperationWrapper.java:45)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.run(DefaultBuildOperationExecutor.java:74)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeAction(ExecuteActionsTaskExecuter.java:491)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeActions(ExecuteActionsTaskExecuter.java:474)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.access$300(ExecuteActionsTaskExecuter.java:106)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter$TaskExecution.executeWithPreviousOutputFiles(ExecuteActionsTaskExecuter.java:271)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter$TaskExecution.execute(ExecuteActionsTaskExecuter.java:249)
	at org.gradle.internal.execution.steps.ExecuteStep.executeInternal(ExecuteStep.java:83)
	at org.gradle.internal.execution.steps.ExecuteStep.access$000(ExecuteStep.java:37)
	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:50)
	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:47)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:200)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:195)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:75)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:153)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:62)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.lambda$call$2(DefaultBuildOperationExecutor.java:79)
	at org.gradle.internal.operations.UnmanagedBuildOperationWrapper.callWithUnmanagedSupport(UnmanagedBuildOperationWrapper.java:54)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:79)
	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:47)
	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:37)
	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:68)
	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:38)
	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:50)
	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:36)
	at org.gradle.internal.execution.steps.CancelExecutionStep.execute(CancelExecutionStep.java:41)
	at org.gradle.internal.execution.steps.TimeoutStep.executeWithoutTimeout(TimeoutStep.java:74)
	at org.gradle.internal.execution.steps.TimeoutStep.execute(TimeoutStep.java:55)
	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:51)
	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:29)
	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:54)
	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:35)
	at org.gradle.internal.execution.steps.BroadcastChangingOutputsStep.execute(BroadcastChangingOutputsStep.java:60)
	at org.gradle.internal.execution.steps.BroadcastChangingOutputsStep.execute(BroadcastChangingOutputsStep.java:27)
	at org.gradle.internal.execution.steps.BuildCacheStep.executeWithoutCache(BuildCacheStep.java:174)
	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:74)
	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:45)
	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:40)
	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:29)
	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:36)
	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:22)
	at org.gradle.internal.execution.steps.SkipUpToDateStep.executeBecause(SkipUpToDateStep.java:99)
	at org.gradle.internal.execution.steps.SkipUpToDateStep.lambda$execute$0(SkipUpToDateStep.java:92)
	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:52)
	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:36)
	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:85)
	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:42)
	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:37)
	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:27)
	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:91)
	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:49)
	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:106)
	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:51)
	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:72)
	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:46)
	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.lambda$execute$2(SkipEmptyWorkStep.java:86)
	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:86)
	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:32)
	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsStartedStep.execute(MarkSnapshottingInputsStartedStep.java:38)
	at org.gradle.internal.execution.steps.LoadExecutionStateStep.execute(LoadExecutionStateStep.java:43)
	at org.gradle.internal.execution.steps.LoadExecutionStateStep.execute(LoadExecutionStateStep.java:31)
	at org.gradle.internal.execution.steps.AssignWorkspaceStep.lambda$execute$0(AssignWorkspaceStep.java:40)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter$TaskExecution$2.withWorkspace(ExecuteActionsTaskExecuter.java:284)
	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:40)
	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:30)
	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:37)
	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:27)
	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:44)
	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:33)
	at org.gradle.internal.execution.impl.DefaultExecutionEngine$1.execute(DefaultExecutionEngine.java:76)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:185)
	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:174)
	at org.gradle.api.internal.tasks.execution.CleanupStaleOutputsExecuter.execute(CleanupStaleOutputsExecuter.java:109)
	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:56)
	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:200)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:195)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:75)
	at org.gradle.internal.operations.DefaultBuildOperationRunner$3.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:153)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:68)
	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:62)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.lambda$call$2(DefaultBuildOperationExecutor.java:79)
	at org.gradle.internal.operations.UnmanagedBuildOperationWrapper.callWithUnmanagedSupport(UnmanagedBuildOperationWrapper.java:54)
	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:79)
	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:74)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:408)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:395)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:388)
	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:374)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.lambda$run$0(DefaultPlanExecutor.java:127)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:191)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.executeNextNode(DefaultPlanExecutor.java:182)
	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:124)
	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
	at org.gradle.internal.concurrent.ManagedExecutorImpl$1.run(ManagedExecutorImpl.java:48)
	at org.gradle.internal.concurrent.ThreadFactoryImpl$ManagedThreadRunnable.run(ThreadFactoryImpl.java:56)


* Get more help at https://help.gradle.org

BUILD FAILED in 1s
8:05:28 PM: Execution finished ':Launcher.main() --stacktrace'.
```

I tried to fix this error
```
Caused by: org.gradle.process.internal.ExecException: Process 'command 'C:/Program Files/Java/jdk-11.0.13/bin/java.exe'' finished with non-zero exit value 1
```
by doing 'Invalidate Cache & Restart' as I saw online, but it didn't make any differences.

I am unsure of which part of the code I should look into to fix this problem. Would it have something to do with the incompatible Gradle version? But the previous iteration worked fine despite the incompatible versions. 

Any help would be appreciated, thank you!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/190#issuecomment-1246686173" expanded>

Hi Prof, I have edited my comment and include the link there, alternatively, it can also be found [here](https://github.com/liviamil/ip/tree/branch-Level-10)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/190#issuecomment-1246804236" expanded>

Hello, thanks for pointing that out and the suggestion, I have set the `mainClassName` to `sally.main.Launcher` as suggested. 
<img width="323" alt="image" src="https://user-images.githubusercontent.com/96341083/190172754-35cc909d-1d7e-4f40-95f6-b6185770dea6.png">

Unfortunately it still doesn't fix the problem, the exact same set of errors show up once I try to run Launcher
```
Executing ':Launcher.main()'...

Starting Gradle Daemon...
Gradle Daemon started in 5 s 276 ms
> Task :compileJava UP-TO-DATE
> Task :processResources UP-TO-DATE
> Task :classes UP-TO-DATE

> Task :Launcher.main() FAILED

Deprecated Gradle features were used in this build, making it incompatible with Gradle 8.0.

You can use '--warning-mode all' to show the individual deprecation warnings and determine if they come from your own scripts or plugins.

See https://docs.gradle.org/7.1/userguide/command_line_interface.html#sec:command_line_warnings
3 actionable tasks: 1 executed, 2 up-to-date
Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class sally.main.Main
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:890)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:834)
Caused by: java.lang.reflect.InvocationTargetException
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
	at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
	at java.base/java.lang.reflect.Constructor.newInstance(Constructor.java:490)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:802)
	at com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
	at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
	at com.sun.glass.ui.win.WinApplication._runLoop(Native Method)
	at com.sun.glass.ui.win.WinApplication.lambda$runLoop$3(WinApplication.java:174)
	... 1 more
Caused by: java.lang.NullPointerException: Input stream must not be null
	at javafx.scene.image.Image.validateInputStream(Image.java:1117)
	at javafx.scene.image.Image.<init>(Image.java:701)
	at sally.main.Sally.<init>(Sally.java:25)
	at sally.main.Main.<init>(Main.java:17)
	... 13 more

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':Launcher.main()'.
> Process 'command 'C:/Program Files/Java/jdk-11.0.13/bin/java.exe'' finished with non-zero exit value 1

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 15s
9:47:11 PM: Execution finished ':Launcher.main()'.
```

The main cause seems to be these 3 errors:
```
Caused by: java.lang.reflect.InvocationTargetException
Caused by: java.lang.NullPointerException: Input stream must not be null
> Process 'command 'C:/Program Files/Java/jdk-11.0.13/bin/java.exe'' finished with non-zero exit value 1
```

I am suspecting the `NullPointerException` to be coming from trying to fetch the image. But I am quite unsure on how to test it out. Would anyone perhaps have an idea on how to trace it back? Thanks!

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/190#issuecomment-1247584092" expanded>

It works! I overlooked that part. Thank you!!
</panel>

</panel>


<panel type="info" header="### 119. NG S.. JUN `@ngshijun` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Help with smoke test on Windows**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/195" expanded>

This is the [jar](https://github.com/ngshijun/ip/releases/download/v0.3/LaMDA.jar) file and [user guide](https://ngshijun.github.io/ip/). Appreciate for your help.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/25#issuecomment-1219794856" expanded>

Same issue happened to me. I think it's due to you not using the exact JDK specified by the teaching team (Azul build of OpenJDK 11). Issue should be resolved one the correct version of JDK is used.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/195#issuecomment-1247766773" expanded>

Noted. Thanks guys!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/196#issuecomment-1247768217" expanded>

Works fine on my Mac too. 💯 
</panel>

</panel>


<panel type="info" header="### 120. CHEE..HONG `@jhchee18` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Overriding method in abstract class**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/495" expanded>

The model answer for the practice paper part 2 shows that the abstract class of `ProgressWatcher` does not have an overriding `update()` method, while `UiWidget` has one. At the same time, the solution in part 3 also does not include the overriding method. Does anyone have any idea why?

![image](https://user-images.githubusercontent.com/99940180/203734204-1382fd67-4bae-44d8-bddc-9af7505d0ac9.png)


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/171#issuecomment-1242958942" expanded>

Hi, I think Prof Damith does address this in this [video](https://mediaweb.ap.panopto.com/Panopto/Pages/Viewer.aspx?id=7aefe728-a7ad-4871-86b8-ac3000bcf7d1&start=691.104055) 11:30, where he mentioned the constructor's activation bar is connected to the entity box.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/172#issuecomment-1242984450" expanded>

Hi, regarding the first issue, I think you should initialize the greeting by adding a new dialog box in the `public void initialize()` method in MainWindow.java.

For the second issue, when you construct the Duke instance, the Duke should read (by using `.load()` method in Storage class) the old task lists stored in the .txt file if the .txt file is not empty, else you should only initialize the taskList to be a new empty TaskList.
</panel>

</panel>


<panel type="info" header="### 121. SEAH..OLAS `@nseah21` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Dropping (half) a feature**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/401" expanded>

After last week's PE-D, my team has received feedback that two of our commands appear to be duplicate features with only minor differences between them. To elaborate:

1. `Command A` "overloads" the list command, which allows for users to include or exclude columns from the UI table when listing. It always causes the full list of persons to be displayed, resetting any effects of filter or find. 
2. `Command B` only allows users to hide columns from the UI table without affecting the residents listed. In addition, `Command B` can only be invoked on columns currently present in the UI table, while `Command A` does not have such a restriction. 

Some of the feedback received during PE-D was that the minute specification differences in both commands could be confusing, especially when users could easily chain `Command B` (vanilla column hiding) with other commands to achieve the same outcome. My team is currently leaning towards dropping `Command A`, i.e. the "overloaded" extension of the list command. 

Is it recommended to drop the feature provided by `Command A`, because its value-add can be obtained via chaining commands? 
Is there any reason ***not*** to drop a feature in v1.4?

We would appreciate any advice from @damithc, or any of the other tutors. Thank you. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/383#issuecomment-1297940734" expanded>

Are we allowed to change (shorten) just the command word for a particular command, but keep the rest of the inputs the same? 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/401#issuecomment-1297941107" expanded>

Thank you.
</panel>

</panel>


<panel type="info" header="### 122. GUAI..PHER `@ryanguai` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke test help (Windows/Linux/Mac)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/281" expanded>

My release can be found [here](https://github.com/ryanguai/ip/releases/tag/v0.3). Could you please help me test the jar file?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/281#issuecomment-1253518127" expanded>

> There seems to be an issue with the vertical height of the dialog box not expanding past its fixed height. It doesn't seem to be able to display more than 4 or 5 tasks, even though the tasks exist.

Thanks everyone! Any suggestions how to make the dialog box resize automatically? I'm not so sure how to implement this.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/281#issuecomment-1253535136" expanded>

Thanks Russell!
</panel>

</panel>


<panel type="info" header="### 123. SOH ..RIEL `@leirdas` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: [PE] Clarification on UG pdf conversion**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/473" expanded>

Hi,

I would like to clarify if the conversion of UG to pdf which results in certain command examples being invalid due to missing whitespace during the conversion process can be classified as a `DocumentationBug`.

Thanks
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/72#issuecomment-1228122374" expanded>

Hi, as suggested in the module’s coding conventions website, you could configure IntelliJ to save and format your code in accordance to the coding standard. For example, if i’m not wrong, you could configure switch cases such that the case keywords are not indented. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/473#issuecomment-1318359906" expanded>

Thank you! @kxrt @damithc 
</panel>

</panel>


<panel type="info" header="### 124. REAG..IANG `@ReaganTan00` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request smoke test for MacOS/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/245" expanded>

Hi, would appreciate help with running smoke test for MacOS and Linux users. The jar file is [here](https://github.com/ReaganTan00/ip/releases/tag/A-Release) and the user guide is [here](https://github.com/ReaganTan00/ip/blob/master/docs/README.md).

Thank you!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/244#issuecomment-1250054097" expanded>

Works fine on windows!

![image](https://user-images.githubusercontent.com/97376457/190854276-23b22180-5cec-4678-a9dc-56cccc106789.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/245#issuecomment-1250327328" expanded>

@zhongfu @seetohjinwei Thank you both!
</panel>

</panel>


<panel type="info" header="### 125. KOK ..SUAN `@ee-suan` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: PlantUML Sequence Diagram sd tag**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/384" expanded>

Hi everyone, I am trying to use a ref frame in my sequence diagram, but I can't seem to find a way to get the sd 'tag' for the separate diagram shown [here](https://nus-cs2103-ay2223s1.github.io/website/schedule/week6/topics.html#tools-uml-sequence-diagrams-reference-frames) using PlantUML. Has anyone using a ref frame managed to figure this out? Thanks in advance!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/384#issuecomment-1300023959" expanded>

It seems that this is the best we can do. Thanks for sharing!




</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/427#issuecomment-1304589164" expanded>

Not sure if it will work here, but I managed to declutter the arrows pointing to UiPart by specifying direction of a newly added class as 'up'
</panel>

</panel>


<panel type="info" header="### 126. NG J.. MAX `@maxng17` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Class not found in module error in Run/Debug Configurations**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/53" expanded>

As seen in the picture below, it pops out the problem where the class Blink is not found in the run application. Although I can still run the program and run the test file, I am afraid if this would affect future code when more things are implemented, so I am wondering if this requires fixing and how to do so. 

For the context, 
I have renamed duke package to blink and Duke file to Blink, so I assume blink.Blink is looking into the blink package for Blink file.
Also that the module is ip, which is the name of the repository I have saved the project under.

This problem first arise when I was doing A-Gradle, since I missed reading the part where we have to merge with the add-support-gradle branch, leading to me making the build.gradle file myself. Halfway through, upon realizing the beforementioned error, I went to delete gradle from my project and this lead to my files no longer being in the root source. Searching online, led to me trying a solution for others which was to configure the project structure settings. I set the ip repository as the module (unsure if this was the right thing to do) and also reinstalled gradle by directly copy-pasting the build.gradle file from add-support-gradle branch. 
This allowed me to run the program and test file again but the issue below was still not solved. Although not causing any problems now, I am afraid if it will.


![2103_askForHelp_pic](https://user-images.githubusercontent.com/97393375/186072295-b88a8e4a-7c1f-4e83-b728-c5d08672b863.png)


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/53#issuecomment-1223642687" expanded>

> In your `build.gradle` file, the `shadowJar`'s `archiveBaseName` is still named duke. That might be the issue.

I have changed this but the problem still persist. Yet, thank you for pointing out this error.

> Alternatively, clone the repo to a new location and open the project in Intellij again

Also could I clarify how this should be done as to my understanding, I will need to make another local repository for my github ip repo. From there, I will have 2 local repos for the same github repo am i correct to say? Then would this cause problems if one local repo is updated but the other is left untouched?


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/53#issuecomment-1223861894" expanded>

Thank you, after cloning into a new local repo, intellij setting has been reconfigured and no problems like the abovementioned persist. 
</panel>

</panel>


<panel type="info" header="### 127. DESM..TIAN `@desmondyst` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is it a must for the person who implemented the feature to do the UG/DG for this particular feature?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/365" expanded>

n/a
</panel>

<panel  header="**2. :fas-info-circle: Is it a must for the person who implemented the feature to write about it in DG/UG? Provided that the person already written the UG/DG for another feature**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/364" expanded>

n/a
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/365#issuecomment-1287038965" expanded>

Thanks prof
</panel>

</panel>


<panel type="info" header="### 128. CHIU..KUAN `@zlimez` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/206#issuecomment-1248906468" expanded>

Works fine on Mac aside from the resizing problem pointed out. 👍 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/207#issuecomment-1248908529" expanded>

Works fine on Mac, though GUI gets distorted when resized. 
<img width="494" alt="Screenshot 2022-09-16 at 12 31 54 PM" src="https://user-images.githubusercontent.com/39835365/190557499-5c4a4fa7-b40d-4b2a-9c17-b2ef1717f143.png">


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/203#issuecomment-1248913523" expanded>

Works fine on Mac 👍 
</panel>

</panel>


<panel type="info" header="### 129. SOO ..A XI `@joosxi` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: (JavaFX) Labels not showing full text once the messages exceed size of window and scrollbar appears**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/128" expanded>

Hello! Is there a way to show full text in a label all the time? Thank you!!

Here's a screenshot of when there is no need for the scrollbar. The full text of each label can be seen!
<img width="307" alt="ss1" src="https://user-images.githubusercontent.com/64764352/188140398-e2927243-2fa7-452a-991f-e333eac6c0bc.png">

And here's a screenshot of when the scrollbar appears! The labels no longer show the full text!
<img width="310" alt="ss2" src="https://user-images.githubusercontent.com/64764352/188140490-02fed711-ba0e-48cd-a377-dc6fddf5f0b8.png">

Below is the code for my fxml files:

DialogBox.fxml:
'<fx:root alignment="TOP_RIGHT" maxHeight="1.7976931348623157E308" maxWidth="1.7976931348623157E308" prefWidth="400.0" type="javafx.scene.layout.HBox" xmlns="http://javafx.com/javafx/18" xmlns:fx="http://javafx.com/fxml/1">
    <children>
        <Label fx:id="dialog" style="-fx-background-color: yellow; -fx-background-radius: 20; -fx-label-padding: 8;" text="Label" wrapText="true">
         <HBox.margin>
            <Insets />
         </HBox.margin></Label>
        <ImageView fx:id="displayPicture" fitHeight="99.0" fitWidth="99.0" pickOnBounds="true" preserveRatio="true">
         <HBox.margin>
            <Insets left="5.0" right="5.0" />
         </HBox.margin></ImageView>
    </children>
    <padding>
        <Insets bottom="5.0" left="15.0" right="5.0" top="15.0" />
    </padding>
</fx:root>'

MainWindow.fxml:
'<AnchorPane maxHeight="-Infinity" maxWidth="-Infinity" minHeight="-Infinity" minWidth="-Infinity" prefHeight="600.0" prefWidth="400.0" xmlns="http://javafx.com/javafx/18" xmlns:fx="http://javafx.com/fxml/1" fx:controller="duke.MainWindow">
    <children>
        <TextField fx:id="userInput" layoutY="558.0" onAction="#handleUserInput" prefHeight="41.0" prefWidth="324.0" style="-fx-background-radius: 20;" AnchorPane.bottomAnchor="1.0" />
        <Button fx:id="sendButton" layoutX="324.0" layoutY="558.0" mnemonicParsing="false" onAction="#handleUserInput" prefHeight="41.0" prefWidth="76.0" style="-fx-background-color: yellow; -fx-background-radius: 20;" text="Send">
         <opaqueInsets>
            <Insets />
         </opaqueInsets></Button>
        <ScrollPane fx:id="scrollPane" hbarPolicy="NEVER" hvalue="1.0" prefHeight="557.0" prefWidth="400.0" vvalue="1.0">
            <content>
                <VBox fx:id="dialogContainer" prefHeight="552.0" prefWidth="388.0" style="-fx-background-color: #FEFFBA;" />
            </content>
        </ScrollPane>
    </children>
</AnchorPane>'
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/128#issuecomment-1235443632" expanded>

Ohhh thank you so much! Can I just ask what does adding that setting do to the DialogBox and why it makes things work HAHA 

Does it like set the minimum height of the DialogBox to negative infinity and does that mean like infinitely small
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/128#issuecomment-1235679927" expanded>

Ah ok thank you Russell and Prof! I'll close this issue now :)
</panel>

</panel>


<panel type="info" header="### 130. LING..MING `@CeereeC` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Do bugs in these pages in the DG count as part of the scope?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/470" expanded>

![Screenshot 2022-11-15 at 7 00 18 PM](https://user-images.githubusercontent.com/90279138/201903644-d266e86e-ebdb-40a3-8e54-daea95ef88c1.png)

</panel>

<panel  header="**2. :fas-info-circle: Help for smoke test for WIndows and Linux users**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/194" expanded>

Hello, here is my [Jar](https://github.com/CeereeC/ip/releases) and [User Guide](https://ceereec.github.io/ip/), would appreciate help to test if the jar file works on Windows and Linux. Thank you!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/470#issuecomment-1315167219" expanded>

Alright got it. Thank you
</panel>

</panel>


<panel type="info" header="### 131. LIU ..IJUN `@L1uY1jun` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke testing help on Mac/Linux OS**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/204" expanded>

Hello, would appreciate if any Mac/Linux users can help me test my JAR file. The release can be found [here](https://github.com/L1uY1jun/ip/releases/tag/A-Release). Thanks!

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/204#issuecomment-1248695829" expanded>

@RezwanArefin01 Yep it is correct behavior because i set the text bubble to have a minimum width. Thanks for the smoke test on linux, much appreciated!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/204#issuecomment-1248719072" expanded>

Thanks for pointing it out though, I have fixed the stage so it does not go below minimum width
</panel>

</panel>


<panel type="info" header="### 132. QI Z.. ZHI `@riccqi` (3 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/84#issuecomment-1229177708" expanded>

This article from could be useful: https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/
> Beginning August 13, 2021, we will no longer accept account passwords when authenticating Git operations on GitHub.com

GitHub now recommends you to either use SSH, or generate a PAT (personal access token) to authenticate your git actions. Personally I got it to work by generating a PAT, and using that as my password.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/146#issuecomment-1236877834" expanded>

It is displayed when there are checkboxes added to the PR description, and will update as you check items off. GitHub is quite smart with this haha
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/498#issuecomment-1326623874" expanded>

You're right, the * multiplicity can be seen as marking the association optional, as the table can exist without a door.
</panel>

</panel>


<panel type="info" header="### 133. ZHAN..IANG `@WWEQG` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request smoke test for MacOS/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/248" expanded>

Hi, I need help to test my [app](https://github.com/wweqg/ip/releases/tag/v0.2) on Mac/Linux. The user guide is [here](https://wweqg.github.io/ip/).
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232696928" expanded>

Here is my GUI. Exactly the same as the JavaFX tutorial.
<img width="296" alt="image" src="https://user-images.githubusercontent.com/89072240/187646403-f97ad987-9bbc-48e6-9e02-97774013bbe4.png">

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/248#issuecomment-1250234743" expanded>

> looks ok on Linux (sway), except for the font size of the "Send" (?) button being a little too big. (scaling issue?)
> 


Thank for check, I will fix the font size issue 👍 
</panel>

</panel>


<panel type="info" header="### 134. EK W.. RUI `@ekweirui` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is treating names as case-sensitive a bug?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/389" expanded>

The module website gives an example stating how person names should be case-insensitive, and failure to do so can be considered a feature flaw.
<img width="409" alt="image" src="https://user-images.githubusercontent.com/95850532/198816587-6d4b4b09-76d3-4590-8767-c9d5444b5b9c.png">

However, my team feels that treating names as case-sensitive should not be a bug.
Here are our reasons:
* Some names (especially surnames) has upper-cases in the middle. In such instances,  case-sensitivity of names has meaning in the real world and should be reflected in code as well. For eg, [Colin McRae](https://en.wikipedia.org/wiki/Colin_McRae) should be treated differently from someone who (although however unlikely, is entirely possible) is named Colin Mcrae.
* Usages of adjectives in names. For eg, a person could be called "George the Third" or [Cléo de Mérode](https://en.wikipedia.org/wiki/Cl%C3%A9o_de_M%C3%A9rode). In such cases, the presence of these **non-capitalized** adjectives in their names differentiates them from people that (although however unlikely, is entirely possible) are actually named "George The Third" or "Cléo De Mérode".
* Give full control and more freedom to the user

In conclusion, as there are proper usages of case sensitivity when it comes to names in the real world, we feel that treating names as case-sensitive in code should not be considered a bug despite what the module website suggests. Perhaps we could also make it explicit in our user guide that names are case-sensitive.

Are these valid enough reasons to say that treating names as case-sensitive is not a bug?

</panel>

<panel  header="**2. :fas-info-circle: How do we hide the attributes box in a PlantUML object diagram?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/370" expanded>

Currently, I am having difficulty with hiding the attributes box in a PlantUML object diagram.
<img width="107" alt="image" src="https://user-images.githubusercontent.com/95850532/197375746-4824d7d3-ed9d-459e-8acf-7a85fbe74d63.png">

I have tried several methods such as 
* `hide private members`
* `hide private fields`
but to no avail.

Could I ask if this is a PlantUML limitation, if not, could I have a tip going forward?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/370#issuecomment-1292412105" expanded>

@damithc Hi prof, I have tried `hide empty members` but to no avail as well.
It's either the case of me doing something wrong or that the [bug](https://forum.plantuml.net/6248/hide-empty-members-bug) was not fixed properly.

*I also tried `hide empty methods` and `hide empty attributes` which were specified in the website but to no avail.* 
</panel>

</panel>


<panel type="info" header="### 135. SEAN..ANIK `@seanmanik` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Overlapping arrows and lines in PlantUML generated diagram**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/427" expanded>

Are overlapping arrows and lines as seen in this diagram a valid bug to report? If so, what are some ways we can consider to prevent this? (I've tried to extend certain arrow lengths, but that leads to the entire diagram being very messy)
![UiClassDiagram](https://user-images.githubusercontent.com/52826683/200128261-ac11298c-f981-4bb0-b205-144b9e5831f9.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/427#issuecomment-1304812468" expanded>

> @seanmanik It's not always possible to get the exact layout you want with PlantUML. Keeping that restriction in mind, overlapping lines in not necessarily a bug unless it makes the diagram ambiguous or misleading. Some PlantUML tips/tricks https://se-education.org/guides/tutorials/plantUml.html#tips-and-tricks Using different colors might help to differentiate between overlapping lines too.

Thank you for the response
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/427#issuecomment-1304812530" expanded>

> Not sure if it will work here, but I managed to declutter the arrows pointing to UiPart by specifying direction of a newly added class as 'up'

Thank you for the tip, it helped to declutter the diagram a bit.
</panel>

</panel>


<panel type="info" header="### 136. CUI ..N YI `@ShenyiCui` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Java Code-Style XML**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/122" expanded>

Hi! Does anyone have a Java Styling XML they can share that abides by the CS2103T coding standards? Thanks!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/122#issuecomment-1234502393" expanded>

thanks for your response @teekaytai! I was thinking something more like this
<img width="912" alt="Screenshot 2022-09-02 at 12 17 23 AM" src="https://user-images.githubusercontent.com/29945147/187963364-99a9b2fd-0824-4369-8166-55464565911d.png">
so that I can just save and have my code formatted properly like "Prettier" with JavaScript on VSCode

Thanks in advance!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/123#issuecomment-1234633068" expanded>

hi! Did you tag your merge commits in master?
<img width="846" alt="Screenshot 2022-09-02 at 2 23 56 AM" src="https://user-images.githubusercontent.com/29945147/187985942-b3b34b11-7b04-4325-98bc-1dd3c80c1b1a.png">

</panel>

</panel>


<panel type="info" header="### 137. LIAN..YANG `@LianGuoYang` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Help for smoke test for Mac users**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/196" expanded>

Here is my [jar](https://github.com/LianGuoYang/ip/releases/download/A-Release/duke.jar) file and user [guide](https://lianguoyang.github.io/ip/). Can someone help for smoke test please. Thanks for your help.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/195#issuecomment-1247672692" expanded>

Your jar file is working on my Windows 10. I like how you have LAMDA as your header, looks really cool!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/196#issuecomment-1247834761" expanded>

Appreciated. Thanks guys.
</panel>

</panel>


<panel type="info" header="### 138. CHUA..AITH `@boredcoco` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Checkstyle is not working**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/114" expanded>

Checkstyle does not seem to be working as my gradle cannot build with the checkstyle plugin. 
<img width="1347" alt="Screen Shot 2022-08-31 at 6 12 45 PM" src="https://user-images.githubusercontent.com/75612806/187655782-93efc82c-d883-4a40-bccb-bc85db1de9c1.png">

I would appreciate any help given, thanks in advanced!
</panel>

<panel  header="**2. :fas-info-circle: Weird characters in GUI**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/104" expanded>

## Weird characters appear whenever I run a Jar app or the launcher in the terminal
:bulb: You can use [Markdown](https://guides.github.com/features/mastering-markdown/) to format your text
![Screen Shot 2022-08-30 at 10 29 52 AM](https://user-images.githubusercontent.com/75612806/187335345-4a357a1e-6be1-450f-9600-c4b1c3ee565b.png)
![Screen Shot 2022-08-30 at 10 30 18 AM](https://user-images.githubusercontent.com/75612806/187335351-fa990d21-a3ef-4d24-8f06-cb68db932f18.png)

For context:
1. I have not used any special characters, every single one of my characters are from the english alphabet
2. My terminal's encoding is set to UTF-8, which I presume should work for the language I am using (Java 11)
3. my locale's language is also set to UTF-8 (so I assume this is not really the issue)
4. this issue props up whenever I run anything Java related not in the terminal

Not really sure what the issue is here, but I would greatly appreciate any help anyone can offer. Thanks in advanced!

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/104#issuecomment-1231121928" expanded>

Thanks for your help guys, I fixed the issue!
</panel>

</panel>


<panel type="info" header="### 139. JOVI..RSON `@jovitaanderson` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Help for smoke testing (MAC OS)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/191" expanded>

Hello! I need some help with smoke testing for my JAR file (preferably with macOS) as me and my friends are all Windows users. :sweat_smile: The link to my ip JAR for download is [here](https://github.com/jovitaanderson/ip/releases/tag/A-Release). Here is the [user guide](https://jovitaanderson.github.io/ip/) as well.

Any feedback is appreciated, Thank you :blush:
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/191#issuecomment-1247566440" expanded>

Okay, thank you for the help! @yuehernkang 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/194#issuecomment-1247758470" expanded>

Hello @CeereeC , you application works fine on my Windows as well!
</panel>

</panel>


<panel type="info" header="### 140. STEV..AWAN `@gerardstevan` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Do rejecting an issue assigned to me might affect the rest of my team in the tutor moderation phase?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/456" expanded>

If the assignee of an issue is me and I decided to reject it, can it affect my teammates in the tutor moderation phase if the tutor decided to accept the issue?
</panel>

<panel  header="**2. :fas-info-circle: Request smoke test for MacOS/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/247" expanded>

Hi all, I need help to test my [app](https://github.com/gerardstevan/ip/releases) on Mac and Linux. 

Would appreciate any help. Thank you!


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/456#issuecomment-1313339825" expanded>

Ok, thanks prof!
</panel>

</panel>


<panel type="info" header="### 141. JASO..PHER `@jasonchristopher21` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: [Spoiler Warning] Practice Exam Part 2 - Multiplicity (Static Array) Dependent on Attribute**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/487" expanded>

Hi, I'd like to ask regarding the practice exam part 2, I'm curious on why the value of `10` is being used as the multiplicity for Watcher. I believe that this is due to the `static int MAX = 10` being set as the default value, and since the class diagram is not concerned with the behaviour, we might omit the possibility of changing MAX. (I think?)

![image](https://user-images.githubusercontent.com/96954436/203554951-c4e51c72-34b4-47a2-a18c-0fac92c4f6b4.png)

But what if the implementation of `Activity` class is changed as follows:  
  
```java
class Activity {
    Integer max;
    Watcher[] watchers;

    Activity(int n) {
        max = n;
        watchers = new Watcher[max];
    }
}
```

In this case, how can I model the multiplicity for the association between Activity and Watcher? Since there is no default value for the length of watchers in this case, and I'm not sure if placing a `*` multiplicity is appropriate in this case. 

Thank you in advance!
</panel>

<panel  header="**2. :fas-info-circle: [A-TextUiTesting] FC: Cannot open ACTUAL.txt**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/30" expanded>

Hi, I currently encounter a problem with the automated text UI testing, when I run the `runtest.bat` file in the IntelliJ terminal, it displays an error message that the system cannot find the file specified. I have tried by changing the path of the `..\src\main\java\*.java` to using the absolute path, but now it seems that the ACTUAL.txt file cannot be found.-

The problem that made me confused, is that when I actually run the runtest.bat by executing it from file explorer, the application runs for a short while before exiting the terminal on itself. In that case, the ACTUAL.txt file was actually generated. I am not quite sure why I can't run it on IntelliJ terminal to get the success/fail message.

I have deleted JDK 17 and currently only use Java 11, but the problem still persists.
IntelliJ version: 2021.3.1, OS version Windows 10 Home 21H2.

Thank you in advance!

![image](https://user-images.githubusercontent.com/96954436/185428861-89f33bc1-6ca7-4b51-b6d7-792b15824869.png)


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/30#issuecomment-1219630481" expanded>

Hi Edbert @Berted, the problem was solved with your method. Thank you very much for your help!
</panel>

</panel>


<panel type="info" header="### 142. MAHE..RAHA `@anuanas2007` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Clarification regarding number of tasks done in PR**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/146" expanded>


![photo_2022-09-05_19-17-16](https://user-images.githubusercontent.com/97455187/188437204-1969ddf3-b451-490d-ae0a-5af81c3a4028.jpg)
![photo_2022-09-05_19-17-29](https://user-images.githubusercontent.com/97455187/188437212-1384d9f1-5de1-4793-8d43-8576eb5605be.jpg)
![photo_2022-09-05_19-25-55](https://user-images.githubusercontent.com/97455187/188438286-ca3c71ce-3500-4cbf-94e3-0af0fd57798d.jpg)

Could someone explain what the number of tasks represents in the PR? For a few students it's shown tasks are done and for a few, there is nothing written.

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/146#issuecomment-1236880531" expanded>

Thank you for the clarification.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1243365967" expanded>

THE BRO BOT!!

<img width="302" alt="image" src="https://user-images.githubusercontent.com/97455187/189603596-b20f03c2-e64d-41c5-883e-61ba8d6dd966.png">

</panel>

</panel>


<panel type="info" header="### 143. WU H..OHUI `@WuHaohui1231` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoketest on Windows and Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/261" expanded>

Anyone with Windows or Linux machine can help test my JAR? Here is the [release](https://github.com/WuHaohui1231/ip/releases/tag/v1.0)
You can try resizing the window
Thanks in advance!

</panel>

<panel  header="**2. :fas-info-circle: UnsatisfiedLinkError: Cant load library when running addressbook.jar on M1 Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/25" expanded>

I followed this guide to check the compatibility of my M1 Mac to the JAR files.
<img width="655" alt="image" src="https://user-images.githubusercontent.com/95847459/185327793-85ed1dc7-f70a-4b30-b8ab-d416bccb2af4.png">

The Java 11 on my Mac works well when I am doing the iP. But this issue happened when I run `java -jar addressbook.jar`.

<img width="1077" alt="image" src="https://user-images.githubusercontent.com/95847459/185325493-41e478a9-adc6-4686-b758-d9573ab17b93.png">
Is this the expected behaviour of incompatibility? However, it seems the guide means that a GUI should be launched without error, in which some text (whether garbled or not) will appear, even when there is incompatibility.<br/>
Or is this associated with some problem in my dependencies setup?<br/>
Thank you!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/260#issuecomment-1250680099" expanded>

![Screenshot 2022-09-19 at 3 43 46 PM](https://user-images.githubusercontent.com/95847459/190971382-a6456a2a-c436-40ac-be62-a07bc03c6bba.png)
Works well on my Mac!
</panel>

</panel>


<panel type="info" header="### 144. ONG ..RCUS `@lfrostbytee` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/67#issuecomment-1227346055" expanded>

Is it okay if you were to post your code here using the "Add code" function instead of the screenshot?
This will make it easier for others and myself to debug with the actual code that you have at hand (otherwise we will need to generate our own text logos".
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1237197661" expanded>

I encountered an error (though I'm not sure if it has the same error code as yours). Just like the others, I shifted my `start` method to a separate class called `Main` instead of leaving it in `Duke`.
</panel>

</panel>


<panel type="info" header="### 145. JAMI..XUAN `@jamietan2002` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/176#issuecomment-1243375588" expanded>

&hat;I agree, I think you need to make sure your Windows machine has the correct Java version installed. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/335#issuecomment-1279684205" expanded>

U can try rerunning the job, it worked for me
</panel>

</panel>


<panel type="info" header="### 146. MARC..YANG `@marcuspang` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Library Request: picocli**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/354" expanded>

## Library

[picocli](https://github.com/remkop/picocli)

## Purpose

A CLI command parsing library instead of using AB3's parsing, as it has support for subcommands, optional/required, as well as interactive commands. While commons-cli and JCommander have already been approved, we realised that support for subcommands were lacking in these libraries. Specifically, the picocli library has great flexibility in allowing users to create commands with the syntax we wish to achieve (similar to `git` and `docker` style commands).

## License

[Apache License 2.0](https://github.com/remkop/picocli/blob/main/LICENSE)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/310#issuecomment-1259579115" expanded>

Ah yes, the issue is resolved after running the lint job again. Thanks!
</panel>

</panel>


<panel type="info" header="### 147. ARNA..RWAL `@arnav-ag` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1236391209" expanded>

changes made:
- Scrollbar CSS
- Scrollpane CSS
- Background colours for all objects
- Added prompt to userInput
- Various padding/margin issues
- Crop images to circle with stroke
 
![image](https://user-images.githubusercontent.com/65700476/188327826-8d6936e7-de02-4285-a15a-f0fc130e3702.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/486#issuecomment-1325080244" expanded>

I actually had the same question when looking at the ExamSoft report! Would it be possible to release a full answer key with the options specified?
</panel>

</panel>


<panel type="info" header="### 148. LEE ..IUAN `@ish1506` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke test help (Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/263" expanded>

Hi, could someone with Linux help me test my [app](https://github.com/ish1506/ip/releases/tag/A-Release) please.
User guide [here](https://ish1506.github.io/ip/).

Thanks!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/263#issuecomment-1251840503" expanded>

Thank you!
</panel>

</panel>


<panel type="info" header="### 149. TEO ..U QI `@teoyuqi` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/15#issuecomment-1217991851" expanded>

I encountered this issue as well, and it turned out that ```javac``` wasn't added to ```Path``` *(i.e. your computer doesn't know where to find the ```javac``` command)*

You can set up your Path using the steps shown [here](https://www.delftstack.com/howto/java/add-javac-to-windows-path/).

Oh and remember to **restart Intellij afterwards**. :)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/389#issuecomment-1295849624" expanded>

> Regardless, making the current behavior clear to the user (e.g., mention it in the UG) is a good thing.

Suppose we decide to make it clearer to the user by updating the application's error message. E.g., when the user requests to edit a non-existent `colin` contact instead of `Colin`, we now explicitly display a note to remind users that names are case sensitive (on top of the current implementation of only indicating that `colin` does not exist). 

Would that be considered a feature modification?
</panel>

</panel>


<panel type="info" header="### 150. TAN ..EONG `@tantzeyeong` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Query on time-sensitive deadlines for project tasks**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/348" expanded>

For this week's project tasks below, the website says they are time-sensitive and should not be done later than the deadline. There's a similar description for Week 11's "Update user docs" task as well. Can I check when are these deadlines referring to? Is it by the end of each respective week, or by the end of v1.3?

![image](https://user-images.githubusercontent.com/87800869/196158279-cabac21b-c582-4b97-b012-9a4b798709c2.png)
![image](https://user-images.githubusercontent.com/87800869/196158346-26c28185-a272-401e-ab0f-bd42a69da5c0.png)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/348#issuecomment-1280936017" expanded>

Thanks!
</panel>

</panel>


<panel type="info" header="### 151. LAN ..NGBO `@Lan-Jingbo` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How to change the name to a old fork**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/22" expanded>

I delete my original IP folders in my computer and create a new one with different name, and I re-fork with the nus-cs2103-AY2223S1 and completed codes and pushed them into github. I am able to see the code updating but the prof cannot see the updated version -- but the version with old name.

Could anyone teach my how to change name in fork and make it available to grader?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/22#issuecomment-1219160232" expanded>

Thank you Hikoya, and by the way, how to send photo in this forum?
</panel>

</panel>


<panel type="info" header="### 152. GAVI..IBIN `@Gavzzz` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Location is not set error**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/255" expanded>

Hi I have changed my mainclassname in build gradle to the GUI launcher and the fx:controller input to the correct package and file names but it seems that I am still encountering the Location is not set error and the Launcher fails to start. 
<img width="463" alt="image" src="https://user-images.githubusercontent.com/91276149/190915789-ba3fc1cf-4dcf-4188-87b7-e0c73afae4fc.png">

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/255#issuecomment-1250773348" expanded>

> Hi, maybe you could try and refer to this link for help? https://stackoverflow.com/questions/43721851/javafx-java-lang-illegalstateexception-location-is-not-set

I have checked my paths in the gui/Main folder and the gui/MainWindow folder and the view/MainWindow.fxl folders and the path naming conventions seem to be in order but the error is still occurring. Not sure what the root of the error is as stack overflow suggested that the path is wrong.
</panel>

</panel>


<panel type="info" header="### 153. DAVI.. ONG `@vvidday` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Codecov bot not commenting on TP pull request**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/154" expanded>

Hi all,

The Codecov bot didn't comment on [our team's PR](https://github.com/nus-cs2103-AY2223S1/tp/pull/9) (this is true for a few other teams as well).

The [Codecov page](https://app.codecov.io/gh/nus-cs2103-AY2223S1/tp/pulls) seems to not identify the affected PRs correctly (empty avatar & no title), and clicking on the PR displays "CI Failed" with no further information, even though the CI passes on github actions.

Would appreciate any help on this issue!

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/154#issuecomment-1240466367" expanded>

Thanks Prof! Will close the issue for now.
</panel>

</panel>


<panel type="info" header="### 154. GUO .. WEI `@guowei42` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Access is denied error when running batch file**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/16" expanded>

Currently on windows using WSL for the iP project. When I try to run the batch file, I get the following error. It was working a moment ago though, not sure what I did that caused this now.

```
Access is denied
<path to ACTUAL.TXT>
Access is denied
FC: cannot open ACTUAL.TXT - No such file or folder
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/16#issuecomment-1221546356" expanded>

Thanks for the help everyone! Yeah, using wsl and was running the `runtest.bat` file, needed to run the `runtest.sh` file instead. Also needed to do a `$ chmod 744 runtest.sh` and installing `dos2unix`.

</panel>

</panel>


<panel type="info" header="### 155. TAN .. ZHI `@TanPingZhi` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Failing junit tests on windows only**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/341" expanded>

## Junit test fails most of the time on windows. Ubuntu and MacOS consistently passes
![image](https://user-images.githubusercontent.com/46480755/195294360-f44a29c8-eca9-407d-975b-5cecbd09b7cc.png)

### Here is the error message shown on github
![image](https://user-images.githubusercontent.com/46480755/195287696-b9370d8a-675c-4599-b0c3-8da1ef826fb4.png)

[link to EditCommandTest code](https://github.com/AY2223S1-CS2103T-T17-2/tp/blob/fa8793e23d1057f85e79ef1da9698181a82b44ff/src/test/java/seedu/nutrigoals/logic/commands/EditCommandTest.java#L73)
![image](https://user-images.githubusercontent.com/46480755/195294889-14b9a775-5ac0-4b56-a1bd-5de87d0dab94.png)

[link to FoodComparatorTest code](https://github.com/AY2223S1-CS2103T-T17-2/tp/blob/fa8793e23d1057f85e79ef1da9698181a82b44ff/src/test/java/seedu/nutrigoals/model/meal/FoodComparatorTest.java#L18)
![image](https://user-images.githubusercontent.com/46480755/195294998-3359e935-660d-45e6-925c-a43500063737.png)
[link to src code branch that causes odd test results](https://github.com/AY2223S1-CS2103T-T17-2/tp/tree/test-CI-fail)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/188#issuecomment-1246220059" expanded>

I have looked through your repo and don't find anything wrong but I guess this bug is probably not pushed. Does this [link](https://stackoverflow.com/questions/30474767/no-tests-found-for-given-includes-error-when-running-parameterized-unit-test-in) help? 
</panel>

</panel>


<panel type="info" header="### 156. MAI .. KAI `@Ferusel` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: How do we attribute code contributions after continuous refactoring?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/413" expanded>

How do we attribute code contributions after continuous refactoring in RepoSense?

Following the usual PR workflows, our team performs a lot of refactoring, especially after a PR is merged.

For example:
* Person A works on a certain feature and creates a PR.
* Person B reviews and requests changes, and suggests changes as well to that PR
* Person A makes those changes (which can be argued to be attributed to Person B)
* Person B approves the PR and merges to master
* Person C refactors the code made by Person A and B

Another example:
A particular line can be made by three different people.  

As we observe from this example, the code evolves multiple times across different people. How to attribute the code to is made even murkier by constant refactoring, especially if entire files are deleted or renamed. 

In this case, how should we attribute the code contributions in different lines of code?

This may be related to #397 and #412.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/491#issuecomment-1326000566" expanded>

I believe package private visibility is the default access modifier if you do not provide one when defining a class/method.

Taken from https://idratherbewriting.com/java-access-modifiers/#:~:text=package%2Dprivate%20(often%20just%20called,for%20a%20class%20or%20interface.:

![image](https://user-images.githubusercontent.com/53888954/203707180-3d91ffa9-b75a-46a0-8190-3bff59842345.png)

According to [CS2103T website](https://nus-cs2103-ay2223s1.github.io/website/se-book-adapted/chapters/uml.html#what-2), we represent package private classes/methods with `~`, while private is simply represented with `-`.


</panel>

</panel>


<panel type="info" header="### 157. LOO ..EVAN `@Evande1` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/192#issuecomment-1247515264" expanded>

Hello @clarence-chew, tested it on macOS and it works. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/197#issuecomment-1247732131" expanded>

Hello @RussellDash332, all your commands in your UG works on macOS, just remove the comma for deadline and event example in your UG and should be good to go.
``` 
event Go to Jurong /at Aug 10 2022 13:30
```
</panel>

</panel>


<panel type="info" header="### 158. CADE.. KAI `@cadencjk` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: CheckStyle named constants warning**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/141" expanded>

I'm in the midst of converting magic numbers/Strings into [named constants](https://nus-cs2103-ay2223s1.github.io/website/se-book-adapted/chapters/codeQuality.html#avoid-magic-numbers) using the recommended naming convention:

```
private final int MINIMUM_COMMAND_LENGTH = 9;
```

However, CheckStyle raised many warnings with this convention.

![image](https://user-images.githubusercontent.com/63772723/188278868-7cc4e137-6cd9-4f52-9325-96fe0108d32a.png)

Is there a way to disable this particular warning?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/141#issuecomment-1236157567" expanded>

> Hi! Constants require the `static` keyword too.

Oh right! Thanks for the swift reply!  😄 
</panel>

</panel>


<panel type="info" header="### 159. XAVI..HENG `@xav168` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Issue when running .jar file after implementing GUI**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/138" expanded>

Hi, so I first encountered this issue after I tried to create a new .jar file using gradle. Running my code through gradle works fine, and the GUI will appear. However, once i made it into jar file I get this error. I have ensured my build.gradle has the required dependencies and my .jar file size is 11mb so it should have the javaFX dependencies inside. Any help would be appreciated thanks!

```java
Exception in thread "main" java.lang.RuntimeException: No toolkit found
	at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:833)
```


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/138#issuecomment-1242788384" expanded>

Hi all, thank you for your help. I figured out that the problem was because I did not install javaFX in my build.gradle file, furthermore i read up online that javaFX 11 had issues with m1 macs which was what I was using and hence specified to use javaFX 18. Once I had done so I managed to create the .jar file and run it successfully.
</panel>

</panel>


<panel type="info" header="### 160. LEE ..RCUS `@marclzh` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke testing help (Mac/Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/203" expanded>

Hello, would appreciate if any Mac/Linux users can help me test my JAR file. The release can be found [here](https://github.com/marclzh/ip/releases). Thanks!

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/203#issuecomment-1248832667" expanded>

Thanks for the smoke test @RezwanArefin01! I've made some changes to the scripts, hopefully its working fine now.
</panel>

</panel>


<panel type="info" header="### 161. SAMU.. TAN `@tsammeow` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke test help (Linux, MacOS, Windows)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/295" expanded>

I would appreciate help in smoke testing my [release](https://github.com/tsammeow/ip/releases/tag/v0.3) on Linux, MacOS and Windows. Thank you in advance!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/295#issuecomment-1258304713" expanded>

Thank you everyone!
</panel>

</panel>


<panel type="info" header="### 162. JOEL.. HAO `@Jo3LW` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Test case passed but with dos2unix: command not found error (MAC OS)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/20" expanded>

<img width="1512" alt="Screenshot 2022-08-18 at 10 29 57 AM" src="https://user-images.githubusercontent.com/97379359/185279771-47d38576-cd7f-4317-b5c5-f415a5fed454.png">


The test case passes but it comes with this line ./runtest.sh: line 27: dos2unix: command not found. Is this alright or is there some issue with the runtest.sh file. Thank you :) 

This is my runtest.sh file below.

<img width="1512" alt="Screenshot 2022-08-18 at 10 29 00 AM" src="https://user-images.githubusercontent.com/97379359/185279548-8b27d5d6-734d-40f7-bb7a-4f7163f812da.png">
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/20#issuecomment-1218961575" expanded>

Thanks it works :)
</panel>

</panel>


<panel type="info" header="### 163. TEY .. JUN `@Cjun1039` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Copied ACTUAL.txt to EXPECTED.txt but still fails test.**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/19" expanded>

I am working on the iP on Windows using IntelliJ.

My actual.txt and expected.txt are the same but the test still fails. Tried converting both files to unix format using the dos2unix on git-bash but got the same result.

![image](https://user-images.githubusercontent.com/89005851/185279281-b78f68d0-cb08-41e4-b7c5-174359c21c24.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/19#issuecomment-1219013763" expanded>

Thanks for the replies!

@damithc I first tried using the terminal on IntelliJ but it did not work. The reason I used git-bash is because of this part under troubleshooting (from the testing tutorial).
![image](https://user-images.githubusercontent.com/89005851/185289770-11110ed5-03b3-4dfc-abe1-833056e34ac2.png)

@huzaifa1712 The -w option worked for me! 
</panel>

</panel>


<panel type="info" header="### 164. KOK ..NIEL `@danielk0k` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/492#issuecomment-1325983863" expanded>

Same here, was going to submit an issue as well.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/492#issuecomment-1325986990" expanded>

<img width="1512" alt="Screenshot 2022-11-24 at 1 41 38 PM" src="https://user-images.githubusercontent.com/70556073/203704125-d1291375-7407-4fcb-b567-edbf45055382.png">

I get this double tick boxes whenever I select the "Request Feedback" box. Not sure if that's the reason...
</panel>

</panel>


<panel type="info" header="### 165. YAP ..HENG `@Polygonalr` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/143#issuecomment-1236263866" expanded>

**Update:** Nevermind, I managed to build and run your project on my machine. I believe from the error messages it looks like your JRE may be 32-bit. Do let me know what you see when you execute `java --version` on your command prompt.

---

Original answer:

I haven't tried building your project, but I think you can take a look at my [build.gradle](https://github.com/Polygonalr/ip/blob/branch-Level-10/build.gradle) which works for my project.

Notably:
1. Try adding `id 'org.openjfx.javafxplugin' version '0.0.10'` to your plugins section within your build file.
2. Configure javafx to use JDK 11 and install the controls and fxml modules by adding the following section to your build file:
```
javafx {
    version = "11.0.2"
    modules = [ 'javafx.controls', 'javafx.fxml' ]
}
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/143#issuecomment-1236269006" expanded>

@clarence-chew Alright I think one more think to check is your `%JAVA_HOME%` env variable. Quickest wayy to do so is to just enter `echo %JAVA_HOME%` in command prompt.

If it is configured wrongly (i.e. pointing to a 32-bit JDK), you can correct it by just searching up `Edit the system environment variables` in your start menu and setting the `JAVA_HOME` variable to point to the correct Java folder.
</panel>

</panel>


<panel type="info" header="### 166. SHAW.. HAN `@snigloo` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: If a the bug reported is an extension of a current feature, can it be counted as NotInScope?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/445" expanded>

The `find` command searches for all task names or tags that contain the keywords, which when the user input is parsed, separates keywords by spaces as specified by the UG. As given by the tester, `find halo hi` searches for all task names with either halo or hi. But the tester would like the find command to find only the task with the task name `halo hi`, which unfortunately contains a space which the command would split up into two keywords.

Even without the requested feature, the app is reasonably useful and rectifying the feature is less important than the work that has been done already. Implementing this would require a lot more work, as a different parsing method would be required. 

Refer to the issue here: https://github.com/nus-cs2103-AY2223S1/pe-dev-response/issues/5628
</panel>

<panel  header="**2. :fas-info-circle: When using a new font, where should a link to its Open Font License be located at?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/422" expanded>

Should the OFL link be on the DG, UG or ReadME? Or is there another option?
</panel>

</panel>


<panel type="info" header="### 167. QUAH..EONG `@KIANSEONG` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Change repo name to original?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/237" expanded>

I have renamed my forked repo to something else not iP. Should I change it to iP or leave it?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/237#issuecomment-1249665452" expanded>

Thank you @RussellDash332! But I was wondering if this was a CS2103T requirement? 
</panel>

</panel>


<panel type="info" header="### 168. XU Y..U YI `@optionalemon` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/260#issuecomment-1250599841" expanded>

<img width="401" alt="Screenshot 2022-09-19 at 13 58 21" src="https://user-images.githubusercontent.com/86706511/190957322-74711c13-84fd-436f-90d9-bad1252c9e00.png">
Works on Mac, but is the right sidebar intended to have a gap over there?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/256#issuecomment-1250603121" expanded>

Works fine on Mac (Doesn't have the font for user input and enter button if that matters)
<img width="401" alt="Screenshot 2022-09-19 at 14 04 15" src="https://user-images.githubusercontent.com/86706511/190957880-743431c4-e656-40fd-8838-f7f49d0f402e.png">

</panel>

</panel>


<panel type="info" header="### 169. FANN..JIAN `@fannyjian` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Can I make the following UI change?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/406" expanded>

Hi Prof, can I also ask if I am allowed to make changes to the UI as the copy button (on the bottom left of the screen) was truncated in v1.3 and was reported as a bug?
![image](https://user-images.githubusercontent.com/97325835/199152514-202b854f-dd23-4ad9-b1cf-0c4101f984cf.png)

</panel>

<panel  header="**2. :fas-info-circle: Are we allowed to make changes to these UI components that could possibly be bugs?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/405" expanded>

1. Can I make changes to the css and javafxml files as some styles are causing warning messages to be displayed in the terminal?
<img width="564" alt="Screenshot 2022-11-01 at 11 06 21 AM" src="https://user-images.githubusercontent.com/97325835/199149964-e9a77945-01d1-47a8-880d-49b9b4de2373.png">

2. As there were bugs reported in PED that the help table was unclear, we were wondering if we could change it too?
<img width="544" alt="Screenshot 2022-11-01 at 11 07 34 AM" src="https://user-images.githubusercontent.com/97325835/199150089-f5d10f9e-1cd9-478b-a401-5cb60f3905eb.png">

</panel>

</panel>


<panel type="info" header="### 170. SHEN..NBEI `@ichigh0st` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Would the following issues be considered bugs and the proposed fixes valid bug fixes?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/420" expanded>

1. Currently, in the case there is integer overflow for the index number, our application will display an incorrect error message. For this issue, the website states that 

> A product is allowed to have 'known limitations' (e.g., a daily expense tracking application meant for students is unable to handle expenses larger than $999) as long as they don't degrade the product's use within the intended scope.

Would it be considered a bugfix to change the error message (by changing how the index is parsed) that is shown upon identifying an index that is too large? Or would it be sufficient to mention this limitation in our user guide?

2. As our application allows for profiles to have the same name with the exact same spelling and capitalization, this causes ambiguity when adding profiles with the same name to the same event. An example is shown below:

<img width="589" alt="Screenshot 2022-11-03 at 6 51 53 PM" src="https://user-images.githubusercontent.com/90245904/199706825-789472cd-2604-43c0-8853-4871006293db.png">

Would it be allowed to change the UI such that a distinguishing field is shown beside the names, such as the phone number of the profile?

3. This issue is similar to the first one. Another bug we noticed is that the phone number in the UI is truncated when users enter a very long phone number. Again, the website states that 

> Only if the behavior hinders normal usage i.e., not showing the text fully/properly under normal usage can be considered an 'incorrect' behavior, and hence, a bug.

May I know if we need to clarify what we consider "normal usage"? And if so, can we clarify it via error messages i.e. changing the parsing of phone numbers, or is the user guide sufficient?

4. Just to double confirm, would the following bugfix be allowed? Currently, when the user enters an email of an incorrect local domain, this error message is shown

> The local-part should only contain alphanumeric characters and these special characters, excluding the parentheses, (+_.-). The local-part may not start or end with any special characters.

However, our regex does not allow for consecutive special characters so we feel that our error message is incorrect and we would like to modify it.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/420#issuecomment-1302013293" expanded>

Thank you prof for the prompt reply. 😊
</panel>

</panel>


<panel type="info" header="### 171. TAN .. WEI `@junwei-tan` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Library requested: ControlsFx**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/380" expanded>

## Library

[ControlsFx](https://github.com/controlsfx/controlsfx)

## Purpose

Easily add autocomplete feature to text box.

## License

[BSD 3-Clause](https://github.com/controlsfx/controlsfx/blob/master/license.txt)
</panel>

<panel  header="**2. :fas-info-circle: Library request: mockito**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/379" expanded>

## Library

[mockito](https://github.com/mockito/mockito)

## Purpose

Framework will be used for testing a class that uses static method java UUID::randomUUID.

## License

[MIT](https://github.com/mockito/mockito/blob/main/LICENSE)

</panel>

</panel>


<panel type="info" header="### 172. MARC.. JIE `@Marcusgwj` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Deadline for DG**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/359" expanded>

Can I check whether the deadline for the first draft of DG is this week or by v1.3?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/359#issuecomment-1285057524" expanded>

Thanks prof
</panel>

</panel>


<panel type="info" header="### 173. TAI .. JIE `@TJun-Jie` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: JavaFx version 11 causes error for M1 Mac**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/96" expanded>

Hey everyone, I was following the guide for JavaFX and the app crashes whenever I run the main method for launcher class. The error I'm getting is `CoreText note: Client requested name ".SFNS-Regular", it will get Times-Roman rather than the intended font. All system UI font access should be through proper APIs such as CTFontCreateUIFontForLanguage() or +[NSFont systemFontOfSize:].` 

I managed to fix this error by changing the version of JavaFX file in build.gradle to 17. I saw some post about it [here](https://www.reddit.com/r/JavaFX/comments/pvpngx/how_do_i_set_the_default_font_to_be_used_for_my/) with someone facing the similar issues.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/96#issuecomment-1229828909" expanded>

Oh sorry I have not! 
</panel>

</panel>


<panel type="info" header="### 174. STEV.. LIM `@stevenlimhw` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Testing Duke only using JUnit and not text-ui-test**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/65" expanded>

As we make progress with our iP project, can we not touch text-ui-test anymore and just create tests using JUnit only? Thanks!!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/65#issuecomment-1226761675" expanded>

Ahh I see what you mean, thank your Prof!
</panel>

</panel>


<panel type="info" header="### 175. GUI ..IANG `@mjgui` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Bug when double clicking vs launching the jar using the terminal**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/458" expanded>

### Question

Hi CS2103T team! Our team was wondering whether the following scenario would be considered a bug:

For reference, here is the original bug report
https://github.com/nus-cs2103-AY2223S1/pe-dev-response/issues/2713

After a (extremely interesting) debugging deep dive where we attempted to replicate the issue, we identified the issue to be our cli library (`picocli`) **outputting escape characters for text formatting** (bold/colors) on certain machines. With the assistance of the [documentation](https://picocli.info/#_heuristics_for_enabling_ansi) and according to our testing, this will happen if

1. The user is running a non-Windows system (most commonly MacOS, but we have not tested it on linux systems)
2. The user **does not double click the program**, but instead **runs it via the terminal** (i.e. `java -jar truthtable.jar`)

We did not catch this during our testing as the problem **does not occur** when running the program via IntelliJ or via double clicking the jar file. (We have confirmed this by installing Java 11 from scratch and double clicking the jar file on a new Mac system)

We refer to the CS2103T website here:
<img alt="image" src="https://user-images.githubusercontent.com/9080115/201629614-c601810a-5f72-4277-a84b-f484d9e6087c.png">

In particular, our user guide also states:
<img alt="image" src="https://user-images.githubusercontent.com/9080115/201630092-e9509938-9fa8-4b2f-88e6-32e184c500a4.png">

Note that we do not support running the jar file via the command line. **Would it be valid to therefore reject this bug?**

### Summary of Original Problem

To restate the problem, there is weird output when the `help` command is run

![image](https://user-images.githubusercontent.com/9080115/201628345-d5195f09-d9bd-484c-ba21-f25aa7e58c59.png)

**Expected:**
![image](https://user-images.githubusercontent.com/9080115/201628383-a806929d-5489-44a7-9408-a3f9a63f0a89.png)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/404#issuecomment-1301060248" expanded>

Not sure why everyone is awake at this hour, but just wanted to chime in that I managed to replicate the bug as well (Windows 11 x64)

@nitant-p in case you're facing trouble replicating the bug, I decided to step through the debugger to take a look and the issue seems to be a miscapitalized string. In particular, in `CommandTestUtil.java` line 72/73, "pm" should be capitalized to "PM"

For future reference, in case you can't replicate test conditions on your local machine, you can consider re-running Github actions using debug mode to get slightly more helpful output. 
<img width="128" alt="image" src="https://user-images.githubusercontent.com/9080115/199574106-e63f01eb-1ef7-4550-a6a6-a7af4a5ea746.png">

If the output is too dense, a quick hack you can also consider is making a dummy branch, modifying the Github Actions workflow on that branch to only run the tests that are failing, then pushing it (which will trigger the workflow). You can add debug outputs to that branch that will print as long as you run the tests with `--debug` (I believe ticking the checkbox above should work as well).

Hope this is helpful!
</panel>

</panel>


<panel type="info" header="### 176. DAMI..JING `@Ssatu` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Query on substituting long command input in DG diagrams with placeholder text**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/425" expanded>

This query is about the use of placeholder text to substitute loooong commands in DG diagrams in order to increase readability.

Taking sequence diagrams for example, certain commands tend to clutter the limited space for method calls between objects as seen below.
![image](https://user-images.githubusercontent.com/69383469/200107911-4ff32944-685f-42a0-b633-8413034a8c16.png)

I would like to ask if it would go against any good practices to substitute the command text with something like `command details`
It would look something like this.
![image](https://user-images.githubusercontent.com/69383469/200107985-cf4cd507-3ba9-48a9-8538-4de95baa4ff6.png)

This would have to be accompanied by a small explainer on what it substitutes i.e.:
![image](https://user-images.githubusercontent.com/69383469/200108012-cec4a3a2-506c-4da6-a886-f38caf148c2a.png)

Hopefully this makes sense! Is this practice acceptable?

</panel>

<panel  header="**2. :fas-info-circle: Clarification on how to qualify the boundaries of behavior that differs from the user guide (Input validation)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/408" expanded>

One of our testers for PE-D reported a bug regarding input restrictions which brought up a concern: **What qualifies as “Behavior that differs from the User Guide.”?**

![image](https://user-images.githubusercontent.com/69383469/199173555-1a0261f7-5797-4d8d-8300-dbd2a4d6b801.png)


For example, when handling input for positive integers, we specify in our user guide:
  
![image](https://user-images.githubusercontent.com/69383469/199172601-9c317271-6811-4ade-9450-3000f2678335.png)


In this case, the tester tried the input `+1` which was **rejected** as our code only allows nonzero unsigned integers.
Furthermore, a positive example was given "1, 2, 3 ... " (although _negative_ examples were not), does this still qualify as a positive integer (i.e. behavior in line with the user guide)

We could easily solve this by changing the restrictions to be "unsigned, nonzero integer" but we believe that affects readability for our users. Similarly, we could also specify that inputs with a positive sign e.g. "+1" is not allowed - strictly specifying the negative cases.

However, we think that there is value in clarifying the degree to which a user can interpret instructions - especially given positive examples! 

(Rather than trying to create a patchwork of constraints to cover loopholes. Some perhaps more extreme interpretations than `+1` might be inputting the string `"a positive integer"` for example. Other, different kinds of inputs can be similarly exploited in this manner.)

</panel>

</panel>


<panel type="info" header="### 177. JONA..GUNA `@JonathanWiguna` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for smoke test help (Windows, Mac, and Linux)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/289" expanded>

Hi, can anyone help me test out my JAR file? My release can be found [here](https://github.com/JonathanWiguna/ip/releases/download/v0.2/duke.jar) and the User Guide [here](https://github.com/JonathanWiguna/ip/blob/master/docs/README.md). 

Thank you in advance!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/289#issuecomment-1255020911" expanded>

Thanks for the help @RussellDash332 and @RezwanArefin01! I have fixed the bug in "find", disabled resizing, and changed the Duke image to .png. Do you guys mind helping me check one more time to see if all's good? The newest release is [here](https://github.com/JonathanWiguna/ip/releases/download/v0.2/duke.jar). 
Thank you so much!
</panel>

</panel>


<panel type="info" header="### 178. WONG..ENDE `@WR3nd3` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request for Smoke Test Help on Mac and Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/256" expanded>

Hi guys,

Can I have help with testing my jar file on Mac and Linux?
The release can be reached [here](https://github.com/WR3nd3/ip/releases/tag/v0.2) and my user guide can be reached [here](https://wr3nd3.github.io/ip/). 
Thanks so much!

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/256#issuecomment-1250975187" expanded>

Thanks for helping me out guys!
</panel>

</panel>


<panel type="info" header="### 179. JIAN..MENG `@asaierika` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Questions regarding correcting major flaws/bugs in Ui for 1.4**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/390" expanded>

Specifically, there are a few things in Ui that I believe would affect the functioning of the application.
1. The Ui components do not resize when the user enters fullscreen. This should be a behaviour that a user expects when entering the fullscreen as if the components do not resize automatically, the fullscreen would be quite useless. Thus, as we are allowing the user to enter the fullscreen, I think it should be expected that the components should resize. I am wondering if we are able to correct this in 1.4.
<img width="951" alt="Screenshot 2022-10-29 at 2 32 05 PM" src="https://user-images.githubusercontent.com/97216090/198817529-0ba4f6f2-4c2c-4ba3-85d2-114a8f5bddcb.png">
<img width="1280" alt="Screenshot 2022-10-29 at 2 32 11 PM" src="https://user-images.githubusercontent.com/97216090/198817532-7a25979e-a4df-4bfe-819c-e1bccf761654.png">

2. The help window text is editable. The user can delete and edit the text in the help window and this should not happen in any case for a real product. So may I know if this is considered a bug and can be corrected in 1.4?
<img width="728" alt="Screenshot 2022-10-29 at 2 37 30 PM" src="https://user-images.githubusercontent.com/97216090/198817727-ce6703fc-9bfc-4c6c-801f-f3a6bc1a3d32.png">
<img width="733" alt="Screenshot 2022-10-29 at 2 37 34 PM" src="https://user-images.githubusercontent.com/97216090/198817733-902d71cf-49c5-4e27-be65-0d0cef4cfa65.png">

3. Ui is not updated when user edits the details. The current Ui displaying a certain information of an entity is not updated when the user edits a certain detail, which only updates when the user triggers it by clicking the entity. May I know if this is considered a bug and can be fixed in 1.4?

4. Long names are cut off in Ui. May I know if I am able to modify the Ui to add new lines for the name, or modify the command to not allow names longer than a certain length?
<img width="732" alt="Screenshot 2022-10-29 at 2 34 33 PM" src="https://user-images.githubusercontent.com/97216090/198817869-3f89a304-bdcf-4609-9910-5a97b893ebcb.png">

5. Long tags can exceed the boundary of the panel. Similarly, may I know if I can correct this by limiting the length of the input tag?
<img width="394" alt="Screenshot 2022-10-29 at 2 41 24 PM" src="https://user-images.githubusercontent.com/97216090/198817921-97c4bb57-834c-46c7-aee9-a5f3ecca5bb6.png">

These are the bugs/flaws that I would want to change in 1.4 and it is ambiguous just by referring to the project requirements. So may I clarify here for each of them if I can correct them in 1.4?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/390#issuecomment-1295776474" expanded>

> 

Thank you for your reply! That answers my question :)
</panel>

</panel>


<panel type="info" header="### 180. MARC..LIAM `@midnightfeverrr` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is this considered as a bug or a UI enhancement?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/393" expanded>

<img width="590" alt="image" src="https://user-images.githubusercontent.com/97276815/198866064-f0a11579-ca8b-4331-b87f-b39af158b0c3.png">

User cannot read task description when the description is too long. Our team is planning to use the 'Wrap text' for this issue. Is this allowed in v1.4?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/393#issuecomment-1296155920" expanded>

@damithc 

<img width="249" alt="image" src="https://user-images.githubusercontent.com/97276815/198868255-2bbf7f93-bd3f-4f6a-ab9f-f9939657d4ad.png">

This problem will still occur when the description is long, even though it is not one super long word. Does this mean that my team can fix this (since this is a bug)?
</panel>

</panel>


<panel type="info" header="### 181. ELBE..DICT `@Elben85` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request smoke test for MacOS/Linux**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/250" expanded>

Hello, I need help testing my [app](https://github.com/Elben85/ip/releases/tag/A-Release).

Any help would be appreciated. Thank you!!

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/250#issuecomment-1252006964" expanded>

> Working as expected on Linux (Arch). But resize doesn't work properly. You may disable it by `stage.setResizable(false);`. 

Thanks!! appreciate the help.
</panel>

</panel>


<panel type="info" header="### 182. KOK ..KHAI `@avock` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1250565249" expanded>

Late to the party but here's a Harry Potter-themed chatbot with a mock iMessage layout
![Ui](https://user-images.githubusercontent.com/76562757/190951145-f38d2539-fa48-4960-87a3-16472f87449e.png)


Changes made: 
 - separate colors for user and application chat bubble
 - resizable chat bubble according to response
 - limiting chat bubble size to prevent text overflow
 - custom command button to allow users to get list of available commands
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/335#issuecomment-1274241084" expanded>

The way our group solved it was by re-running the job. Maybe you'll find [this](https://github.com/codecov/codecov-action/issues/598) thread helpful

Alternatively you can try a dummy commit to re-trigger codecov, that worked for us too
</panel>

</panel>


<panel type="info" header="### 183. ZHAN..UHAO `@YH-15` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1236137661" expanded>

sry I am also not very sure about this (but i guess it might be cos JavaFX packages are not loaded properly), cos I did not run into this error b4, 
but in the end, we will be required to switch to use fxml (which is the 4th part of this tutorial), and sample code is given in the 4th part tutorial, you may take a look if applicable, essentially we don't need to change our initial implementation of Duke class if we use fxml.  
</panel>

</panel>


<panel type="info" header="### 184. ANG ..OUNG `@kynapy` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/176#issuecomment-1243394430" expanded>

Ran the 8mb jar file on my M1 Macbook, works fine for me!
</panel>

</panel>


<panel type="info" header="### 185. SIEW..SUNG `@eesung00` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/49#issuecomment-1222499759" expanded>




> > the result of the quizzes are inconsequential, only the attempt matters?
> 
> Yes, that's right. For in-video quizzes, correctness doesn't affect the participation points. Nevertheless, resubmission should be allowed. Let me know which ones doesn't allow so that I can update their settings to allow resubmission.

For me, I cannot resubmit the quiz in video in W3.6b and W3.7
</panel>

</panel>


<panel type="info" header="### 186. MENG..ORAN `@Qiaoran-M` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: No response from Dev team**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/474" expanded>

Hi, I have a question about PE tester response

If the dev team only changed the severity level, but didn't give any other response (the bug report is neither accepted nor rejected), how should I reply since I don't really know the bug is accepted or not?
</panel>

</panel>


<panel type="info" header="### 187. LEE ..RYAN `@ryanlml` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/199#issuecomment-1248110059" expanded>

I offer an ad-hoc solution: making a directory and the data file if it doesn't exist.
```
try {
    if (!file.exists()) {
        Files.createDirectories(Paths.get(filePath).getParent());
        file.createNewFile();
    }
} catch (IOException e) {
    //...
}
```
</panel>

</panel>


<panel type="info" header="### 188. YEE .. HAO `@yeehaoo` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/234#issuecomment-1250903383" expanded>

> @RezwanArefin01 @yeehaoo @johnbenedictyan Hi, I think I fix the problem alrdy, but can help me check again whether it works in linux /macs ? Thank you! The jar file is [here](https://github.com/xhphoong/ip/releases/tag/A-Release) and the [user guide](https://xhphoong.github.io/ip/). Thank you!

works fine on my side! (fedora linux)
</panel>

</panel>


<panel type="info" header="### 189. PEI ..G YI `@SeekSaveServe` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Library Request: commons-cli**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/319" expanded>

## Library

[commons-cli](https://commons.apache.org/proper/commons-cli/usage.html)


## Purpose
commons-cli: A library for CLI command parser instead of using the current command parser in AB3 to allow for more flexible parsing. Our project requires a more flexible use of command line flags and arguments and we intend to use commons-cli to parse commands.
 
## License
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

</panel>

</panel>


<panel type="info" header="### 190. DONO..INGH `@Donovan9617` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/140#issuecomment-1236125981" expanded>

I moved the `start` method to another class `Main` as well, then I created the Duke object containing the file path from there!
</panel>

</panel>


<panel type="info" header="### 191. TAN ..IANG `@tanhl2000` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/306#issuecomment-1261672918" expanded>

@junlee1991 
For Mac side, I had to change my JavaFX version to 17 in order to fix some errors on my end (fonts not showing etc), might want to try upgrading to 17 or 18 at least especially if on the new M1/M2 chips.
</panel>

</panel>


<panel type="info" header="### 192. SHEN..HONG `@shenyih0ng` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Library Request: `swagger-codegen`**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/318" expanded>

## Library

[swagger-codegen](https://github.com/swagger-api/swagger-codegen)

> This is more of a CLI tool rather than a project dependency.

## Purpose

Due to goal of our `tp` project, we will need to interface with NUSMods' API. `swagger-codegen` is used to generate the necessary `.java` files for the data models used in the API. It also provides a convenient way to generate boiler code for network requests etc. 

## License

Apache License (https://github.com/swagger-api/swagger-codegen/blob/master/LICENSE)

</panel>

</panel>


<panel type="info" header="### 193. LINU..FENG `@zupey` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/150#issuecomment-1239105028" expanded>

Hi misterpuffin,

I have faced a similar issue when setting up the GUI for my Duke.
This is the stackoverflow [page](https://stackoverflow.com/questions/69171337/javafx-error-in-wsl-2-java-lang-unsupportedoperationexception-unable-to-open) that I referenced. I followed the guide from the 0 upvote post to setup an X server on wsl.

All the best for your GUI. 😄 

</panel>

</panel>


<panel type="info" header="### 194. CHEW.. JIN `@sarrrdin` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/179#issuecomment-1244023031" expanded>

Hello! Hmm that error indicates that the execution has failed for Gradle. However, was having a quick glance at your code and I notice that there are two 
```
public static void main(String[] args){}
```
in your Duke class and Launcher class respectively. Potentially, you can try the stacktrace debugging option, it may be due to an error in the path for the Main class. 

Hope this helps!
</panel>

</panel>


<panel type="info" header="### 195. JOHN..AOYI `@johnbenedictyan` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/55#issuecomment-1225092724" expanded>

Hi @Hikoya thanks for the answer, I ran into some errors just using the git merge command but I managed to find a workaround and I'll share it with other users.

1. `git remote add upstream https://github.com/nus-cs2103-AY2223S1/ip.git`
2. `git fetch upstream add-gradle-support`
3. `git merge upstream/add-gradle-support`

This is how I got it to work on my machine (M1 Mac), in case it's an OS thing.
</panel>

</panel>


<panel type="info" header="### 196. CONN.. LIM `@connlim` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/316#issuecomment-1263147169" expanded>

Your logs were deleted so we can't see the error. Try changing your log retention settings to a least a month so you can see what went wrong. [You can follow this guide here.](https://docs.github.com/en/organizations/managing-organization-settings/configuring-the-retention-period-for-github-actions-artifacts-and-logs-in-your-organization) After that try rerunning the build to generate a new log.
</panel>

</panel>


<panel type="info" header="### 197. NGUY..OANG `@hoang227` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/180#issuecomment-1244971607" expanded>

In your main method, we know that the reading of the user input is a loop, just think about every step that happens in a single iteration of the loop and go from there. 

Think of the process like some sort of baton passing (so one person is holding the baton at one time). 

For example, when the user input a command, the baton will be passed to the parser with will try to comprehend what the user is trying to say and communicate that to the next person. 

Once the parser is done it will pass the baton to someone else. If the parser detected an add command , there should be some sort of task list manager taking the baton and help you add this new task into the list. 

Then once the adding is done the baton is passed to the UI which will print the out put on the screen to communicate with the user the status of his request. Then you can pass the baton back to parser to read the next input.



Hope this helps!
</panel>

</panel>


<panel type="info" header="### 198. JERO..IXUN `@jeromepui` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/196#issuecomment-1247740978" expanded>

Your application works fine on my Mac 👍
</panel>

</panel>


<panel type="info" header="### 199. ASHI..AMED `@AshiqurRah` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/307#issuecomment-1258849885" expanded>

The way I created packages in my test.java folder is by creating a test file first. I included at the top of the file,  `package duke;` and IntelliJ alerted me with a red lightbulb at the start of the line (when hovered over the squiggly red-lined code) to create a package named duke. 

You could try re-creating another file in test.java and try the above steps and see whether it works as well
</panel>

</panel>


<panel type="info" header="### 200. KOH ..MUEL `@Samsation` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232522455" expanded>

Here is my GUI. Did not change anything from the JavaFX tutorial except for the profile image for Duke. 🐧 

![Screenshot 2022-08-31 085917](https://user-images.githubusercontent.com/88918588/187609818-e809e50f-1e45-499c-99ad-5ada1f267c53.png)

</panel>

</panel>


<panel type="info" header="### 201. SU P..GENG `@Bacon-Strips` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/169#issuecomment-1242936696" expanded>

Thanks @zbz-lvlv , managed to get my Jar file working after fixing the 2nd point.
</panel>

</panel>


<panel type="info" header="### 202. TAN ..RCUS `@emptygx` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/303#issuecomment-1258955998" expanded>

Works fine on mac with similar issues as mentioned by @RussellDash332. Reply issues verified to be fixed.

Resize issue:
<img width="616" alt="Screenshot 2022-09-27 at 12 30 21 PM" src="https://user-images.githubusercontent.com/88984742/192432555-a692a67d-2086-444c-bd9e-48b4e4f59b6e.png">

</panel>

</panel>


<panel type="info" header="### 203. KAVA.. TAN `@kavantan` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Auto-Formatting in IntelliJ**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/72" expanded>

Hi, I don't think this is an issue but basically I am using IntelliJ and as of right now I am using the default key-bind to 'Reformat Code', but I am wondering if it possible to enable some form of auto-formatting in IntelliJ. For instance in VS Code, there is an option to enable auto-format every time you save a code file. I have definitely been spoilt by VSCode's auto-reformat, so if anyone has any suggestions or better approaches to reformatting code and doesn't mind sharing, please do! Thank you
</panel>

</panel>


<panel type="info" header="### 204. ZSIG..IYOU `@zsiggg` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Refactoring TP**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/500" expanded>

Does anyone know when we can start to refactor our TP repository (e.g. change the repository name)? 
</panel>

</panel>


<panel type="info" header="### 205. CHEN..ZHOU `@guanzhou03` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232495681" expanded>

Here's my GUI which is basically the one given in the JavaFX tutorial, with some slight adjustment to paddings around the pictures. 
<img width="398" alt="Screenshot 2022-08-31 at 1 54 25 PM" src="https://user-images.githubusercontent.com/35629932/187604459-929a1217-d82d-442a-a2f3-739231528d7c.png">

</panel>

</panel>


<panel type="info" header="### 206. LIM ..GLAS `@dlimyy` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Can this bug be considered as response.NotInScope?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/457" expanded>

Our group has received a bug report on write-only json files and we would like to clarify with regards to the handling of write-only json files:

<img width="834" alt="image" src="https://user-images.githubusercontent.com/97420966/201611179-8da46807-b050-4853-8c20-1bdbd5399140.png">

Given that the json file created by our application is by default granted with both write and read permissions, would it be fine to consider this as notInScope as it is unusual for the file to be changed to be only write-only and the console does still throw a warning that the file cannot be read.
</panel>

</panel>


<panel type="info" header="### 207. LEE ..G DA `@chengda300` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1234036767" expanded>

![image](https://user-images.githubusercontent.com/97393284/187884846-3052e8ad-94ba-4fbb-b391-a06efc5bf4b5.png)
Here is a lazy mode GUI with resizing bugfix (credits to malwaregarry)

And SceneBuilder does not have all the available properties, resulting in text being cut off after a certain height. It requires the tag minHeight="-Infinity" which is not found in SceneBuilder
</panel>

</panel>


<panel type="info" header="### 208. AARO.. JUN `@turretDive` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/255#issuecomment-1250339688" expanded>

Hi, maybe you could try and refer to this link for help?
https://stackoverflow.com/questions/43721851/javafx-java-lang-illegalstateexception-location-is-not-set
</panel>

</panel>


<panel type="info" header="### 209. NEO .. HAN `@neosunhan` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1219394822" expanded>

Try removing the empty lines at the bottom of your EXPECTED.TXT.
</panel>

</panel>


<panel type="info" header="### 210. TAN ..RONG `@Tan-Jia-Rong` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/188#issuecomment-1246656046" expanded>

I have looked through you repo as well, everything looks fine. Perhaps you could consider the following solution provided [here](https://stackoverflow.com/questions/60228404/no-tests-found-for-given-includes-when-running-gradle-tests-in-intellij-idea)

## Solution 1

1. Go to Preferences -&gt; Build, Execution, Deployment -&gt; Gradle -&gt; change "Run tests using" to "IntelliJ IDEA".
Run your test.
2. Go again to Preferences -&gt; Build, Execution, Deployment -&gt; Gradle -&gt; change "Run tests using" to "Gradle (default)".
3. Keep running your test, it is working now.

Hopefully it works for you 😃 
</panel>

</panel>


<panel type="info" header="### 211. LAM ..N YU `@gunbux` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/24#issuecomment-1219685669" expanded>

I think the issue here is that both `diff` and `fc` are really not suited to comparing differences between the two .txt files. What I found worked for me is right clicking the file in intellij, then select `Compare With`, and compare the ACTUAL.txt to EXPECTED.txt
![image](https://user-images.githubusercontent.com/46131429/185444280-b99256df-4b1f-40db-a056-3e364b05c5a2.png)

</panel>

</panel>


<panel type="info" header="### 212. LEON..NIEL `@leongdl135` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/107#issuecomment-1231109673" expanded>

Hi, I managed to resolve this issue by creating a default constructor in my Duke class! 
``` java
public Duke() {}
```

</panel>

</panel>


<panel type="info" header="### 213. BENJ..KANG `@bensohh` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Bug: Cannot retake failed attempt (Week 5.4 Video)**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/134" expanded>

I am unable to retake the In-Video Quiz after a failed attempt. 
![Screenshot 2022-09-03 at 12 35 01 AM](https://user-images.githubusercontent.com/97374822/188199368-40a76dad-b6fc-440f-b98b-1dad7468d312.png)

</panel>

</panel>


<panel type="info" header="### 214. ERVI..HENG `@ErvinK123` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Unable to retake in-video quiz for Week 5.**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/139" expanded>

Hi Prof, I am unable to resubmit the in-video quiz for Week 5.4. This issue is similar to issue #49. Thanks!
![image](https://user-images.githubusercontent.com/65859484/188263077-338dbf43-f998-4c3c-ac72-e76400d51d4c.png)

</panel>

</panel>


<panel type="info" header="### 215. ONG .. WEI `@rexong` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Bug rated is lower than expected.**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/453" expanded>

Suppose the tester rated the bug lower than what our group expects, can we keep the rating as it is?

For example, if our group feels that the rating should be `low`, but the tester rated `veryLow`
</panel>

</panel>


<panel type="info" header="### 216. FUNG.. REN `@fungusta` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/106#issuecomment-1232849911" expanded>

Here is my GUI for duke with:

- New picture icons for duke and user
- Color scheme
- Different font for send button

![image](https://user-images.githubusercontent.com/69900761/187674533-31954e17-3b70-40c8-a7c7-16a344d552ad.png)

</panel>

</panel>


<panel type="info" header="### 217. CHAN..INUS `@linuschancs` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/100#issuecomment-1230489545" expanded>

Perhaps you could check if you have `useJUnitPlatform()` in your build.gradle file under tests. Or try changing your Gradle settings to run tests using intellij instead!
</panel>

</panel>


<panel type="info" header="### 218. CHEN..TING `@lyuting47` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/16#issuecomment-1219639113" expanded>

Hi you can try right clicking the batch file and run as administrator. I also got the access is denied error when I tried to run it in command prompt window.
</panel>

</panel>


<panel type="info" header="### 219. HO J.. HAO `@HoJunHao2000` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Commit and pushed Level-10 into master without making branch first**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/103" expanded>

I am in a bit of a dilemma, so i did my Level-10 on the master branch, instead of creating another branch, and pushed it to the remote repository already.

What should I do? Should I revert my repository back to before (the previous commits will still be there) and start again or just leave it as it is.

![image](https://user-images.githubusercontent.com/84698566/187333415-718428b3-1c80-42c5-8889-746fc8304b9b.png)


</panel>

</panel>


<panel type="info" header="### 220. LAU .. JIE `@BlopApple` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Library request: SnakeYAML**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/182" expanded>

### Library
[SnakeYAML](https://mvnrepository.com/artifact/org.yaml/snakeyaml)

### Purpose
To use the yaml parser provided to load a yaml file containing all preset phrases for the chat bot.

### License
Apache 2.0 - See [https://bitbucket.org/snakeyaml/snakeyaml/src/master](https://bitbucket.org/snakeyaml/snakeyaml/src/master/LICENSE.txt)
</panel>

</panel>


<panel type="info" header="### 221. RAMA..ESTU `@rama-pang` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Ambiguous instructions for BCD-Extension**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/127" expanded>

Hi, I would like to ask for `BCD-Extension`, are we supposed to:
1. Pick one extension from any category (B, C, or D), and implement it; or,
2. Pick one extension from each category, for a total of three extensions.

Thanks in advance!
</panel>

</panel>


<panel type="info" header="### 222. PONT..TSUK `@peppapighs` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/12#issuecomment-1217586944" expanded>

If you really need to edit the previous commits, you may follow this [guide](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase), though I do not recommend doing so since it might cause merge conflicts to the subsequent commits.
</panel>

</panel>


<panel type="info" header="### 223. YU K..TELL `@chantellyu` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Text in chatbot getting cut off even though minHeight=-Infinity and maxHeight=Infinity in DialogBox.fxml**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/233" expanded>

The text in my chatbot gets cut off after a certain point, I've tried playing around with both minHeight and maxHeight and it still ends up getting cut off no matter what.

Example (the ellipses are where it gets cut off):
<img width="261" alt="Screenshot 2022-09-16 at 10 50 02 PM" src="https://user-images.githubusercontent.com/88767281/190667500-f2a6b547-fbaa-4c6b-9203-10fd26db5f37.png">

The code for DialogBox.fxml:
```java
<fx:root alignment="TOP_RIGHT" maxHeight="1.7976931348623157E308" maxWidth="1.7976931348623157E308" prefWidth="400.0" type="javafx.scene.layout.HBox" xmlns="http://javafx.com/javafx/8.0.171" xmlns:fx="http://javafx.com/fxml/1">
    <children>
        <Label fx:id="dialog" text="Label" wrapText="true" minHeight="-Infinity" maxHeight="Infinity">
        <HBox.margin>
            <Insets left="10.0" right="10.0" />
        </HBox.margin>
        <padding>
            <Insets bottom="10.0" left="10.0" right="10.0" top="10.0" />
        </padding>
        </Label>
        <ImageView fx:id="displayPicture" fitHeight="99.0" fitWidth="99.0" pickOnBounds="true" preserveRatio="true" />
    </children>
    <padding>
        <Insets bottom="5.0" left="5.0" right="5.0" top="5.0" />
    </padding>
</fx:root>
```

</panel>

</panel>


<panel type="info" header="### 224. MAX ..IEN `@maxtance` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/498#issuecomment-1326375841" expanded>

Option 1: The table can be linked to 0 or **1** chair. The table can be linked to **0** or more tables. Hence, option 1 is correct. (Edit: The bolded text suggests why the option is correct.)

Option 4: A table has to be linked with exactly **1** door. Since the object diagram doesn't show an association between table and door, option 4 is incorrect. 
</panel>

</panel>


<panel type="info" header="### 225. ASHE..M YI `@doimoiboi` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Do the Use Cases in the DG have to be comprehensive?**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/444" expanded>

A bug was reported for my team's project claiming we had a documentation bug because we omitted a use case. Is this considered a bug?
</panel>

</panel>


<panel type="info" header="### 226. ZHU ..ANXI `@yuanxi1` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/492#issuecomment-1325984418" expanded>

Same but I only did the 2 practice paper instead of the mock. Might be because the teaching team only checked the mock paper instead of the practice paper.
</panel>

</panel>


<panel type="info" header="### 227. LU Y..TING `@LuYiting0913` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Running Junit test on Duke**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/50" expanded>

As per the title, How could I test with assertEquals as Duke only accept command through the keyboard? 
</panel>

</panel>


<panel type="info" header="### 228. BRAN.. KAI `@beetee17` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Library Request: PrettyTime NLP for natural language dates parsing**" popup-url="https://github.com/nus-cs2103-AY2223S1/forum/issues/350" expanded>

## Library

[PrettyTime NLP](https://www.ocpsoft.org/prettytime/nlp/). [Github link](https://github.com/ocpsoft/prettytime)

## Purpose

For an improved user experience as it allows users to specify dates in plain English. We intend to use this for users to easily set deadlines for tasks without the need to follow specific date formats e.g. DD-MM-YYY etc.

## License

[Apache License 2.0](https://github.com/cbeust/jcommander/blob/master/license.txt)

</panel>

</panel>
