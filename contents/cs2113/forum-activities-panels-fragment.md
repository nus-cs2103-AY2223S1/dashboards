%%[This page was last updated on Dec 03 2022]%% [**<span class="text-warning">:octicon-eye:</span> indicates those _watching_ the forum** (kudos :+1:)]


<panel type="info" header="### 1. JOSH..FENG `@joshuan98` (12 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Store database online and copy when program is run**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/38" expanded>

We are using our own database which is stored online. May we confirm that we can use java.net.URL to download said database when the .jar file is run? This allows the user to simply run the .jar file instead of having to download the database with it.

From the following link:
https://nus-cs2113-ay2223s1.github.io/website/admin/tp-constraints.html#recommendation-minimal-network
it appears that we are able to do so and our backup would be for the user to download the database when he/she downloads the .jar file.
</panel>

<panel  header="**2. :fas-info-circle: Multiple Association Classes**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/24" expanded>

Is it possible to have multiple association classes for one association link? If so, how should we draw such relationships in a class diagram?
</panel>

<panel  header="**3. :fas-info-circle: Accidentally merge without fast-forward**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/12" expanded>

Does anyone know how to revert a fast-forward merge? I accidentally selected the wrong checkbox.
</panel>

<panel  header="**4. :fas-info-circle: Alternative naming of iP fork ?**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/2" expanded>

Does the naming of the branch have to be "ip" or can we opt for our own naming? Would this affect the scripts?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/3#issuecomment-1214380918" expanded>

"""
If you are new to Git, we caution you against using Git or GitHub features that come with the IDE as it is better to learn Git independent of any other tool. Similarly, using clients provided by GitHub (e.g., GitHub Desktop GUI client) will make it harder for you to separate Git features from GitHub features.
"""
Seems like SourceTree is preferred

From https://nus-cs2113-ay2223s1.github.io/website/schedule/week2/topics.html#tools-git-and-github-init-getting-started
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/2#issuecomment-1215062224" expanded>

Clarification: Must the repo name be "iP"? Or can we choose our own repo name?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/2#issuecomment-1215079704" expanded>

Issue clarified, closing issue
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/8#issuecomment-1236323241" expanded>

Both "master" and "main" are names of the default branch. It depends on your setup during the creation of the repo. Could you share your steps to explain what you did?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/9#issuecomment-1237883772" expanded>

It seems like the teammates link was just sent out.
Opening time:
Tue, 06 Sep, 2022, 05:00 PM +08
Closing time:
Sun, 11 Sep, 2022, 11:59 PM +08
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/12#issuecomment-1243101001" expanded>

Not too sure if I did it right but it is reflected correctly in the IP dashboard so I will close this thread
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/22#issuecomment-1272326938" expanded>

From what I understand, I do not think you should remove the .seedu part of the structure because it is part of the JUnit convention (and might be checked for in CS2113 scripts)
You can refer to this for more information: https://se-education.org/guides/tutorials/junit.html
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/38#issuecomment-1304546151" expanded>

Yup, we are not using any DBMS (no SQL is used), its a pure .csv file
</panel>

</panel>


<panel type="info" header="### 2. THAN.. HUY `@Than-Duc-Huy` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Does failing CI/CD test affect the delivery of our program?**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/40" expanded>

Our program is a hybrid CLI-GUI program. The GUI component is only a simple text area for the user to key in the input. 
Rationale: we believe that for our application, it would be more convenient for the user to type freely instead of remembering the syntax

The simple GUI component is shown below
![image](https://user-images.githubusercontent.com/32756835/200153877-30e4f732-97ba-4f8b-9c0f-af1388f04364.png)

The simple implementation is approved by Prof Akshay
![image](https://user-images.githubusercontent.com/32756835/200153953-f48d6ce6-de27-455c-a6bd-dbe9f9b84311.png)

When we write the JUnit test for the GUI component, our computer can open the GUI.
However, we have trouble with the `test` task on Github because it is headless, there is no X11 display. The error is as followed.
![image](https://user-images.githubusercontent.com/32756835/200153851-756cf22b-0e37-417e-8cff-5d72039903ca.png)

I want to ask if we can ship the product with the CI/CD on github failing in this particular instance because of the GUI nature of the product. It is very near to the deadline (Monday) and the GUI is quite integral to our product.

</panel>

<panel  header="**2. :fas-info-circle: Testing the application data storage**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/36" expanded>

I would like to ask about the extent of testing for the PE, especially for the storage files generated by the program
For acceptance testing, we should behave like a user and should only do what was told in the UG. We shouldn't tamper with the storage files. But for system testing, we can tamper with the storage file to see how the program respond! 
Is my understanding correct? How do we know if the application has handle the tampering of the storage file elegantly so that we don't raise it as a bug!
</panel>

<panel  header="**3. :fas-info-circle: Unable to get RepoSense to recognize my contribution**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/33" expanded>

Previously, I incorrectly name my git `user.name` differently from my github username.
As seen here, I changed from `td_huy` to `Than-Duc-Huy` to match my github username and quickly merge a PR to test. 
The commit is `5281b6c` on 17 Oct (grayed out is a merge commit).
Before that I also did some non-merge commit under the correct username `82b1994`

![image](https://user-images.githubusercontent.com/32756835/196327103-08c56cf9-c670-47d5-9ae4-99e7c04dde72.png)
![image](https://user-images.githubusercontent.com/32756835/196326893-c3c4d5c0-547d-4097-a355-a3847375cecc.png)

However, the RepoSense update on 18 Oct still didn't recognize the code that I commited.
![image](https://user-images.githubusercontent.com/32756835/196326856-d23dad48-9463-4117-9a82-33c753c8fdef.png)
![image](https://user-images.githubusercontent.com/32756835/196326946-fd2df9ba-591d-4953-a088-a12331e4135f.png)



</panel>

<panel  header="**4. :fas-info-circle: JUnit test, Assert are not triggered in the tp progress**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/23" expanded>

We have tried implementing JUnit test, Assert by 
- create the mirror image of `main` folder in `test` with "Test" added to the end of each Class.java
- Import the relevant junit classes
    ```
    import static org.junit.jupiter.api.Assertions.assertTrue;
    import org.junit.jupiter.api.Test;
    ```
- Create @Test function and assert accordingly
- gradle `test` task also recognizes and runs 

But it does not trigger the tp progress check scripts? I wonder if we are doing it correctly?

This information might be relevant as it is mentioned in #22 
We removed the .seedu part of the folder structure: `src/main/java/tp`, `src/test/java/tp`. Is removing `.seedu` the reason?

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/22#issuecomment-1272326213" expanded>

What do you mean by project structure? can I remove the .seedu part of the structure?
Previously src/main/java/seedu/duke
Change to src/main/java/tp
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/23#issuecomment-1272499047" expanded>

https://github.com/AY2223S1-CS2113-T18-2/tp 
For the test, so far we have only make this test
https://github.com/AY2223S1-CS2113-T18-2/tp/blob/master/src/test/java/recipeditor/parser/ParserTest.java
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/23#issuecomment-1280634318" expanded>

This problem comes from me. I didn't change my `user.name` to match my github username. Hence the RepoSense noted that I haven't contributed any code at all. 
I am sorry for the inconvenience!
</panel>

</panel>


<panel type="info" header="### 3. CHIA..HONG `@wcwy` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Mock paper coding violation question**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/45" expanded>

Hi, regarding the coding violation for the below question, some possible answers I had/heard for line 10 are magic literals, missing fallthough comments, indentation should be 4 spaces and default branch should not be used to execute the last option. What should be the correct answer for this?

![image](https://user-images.githubusercontent.com/37980219/204225705-6a5fa010-9202-4c00-851f-f8412b085bc1.png)


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/8#issuecomment-1236301126" expanded>

I believed the "improved" branch cannot be found because you didn't uncheck the "Copy the main branch only" when you fork the repo (the same happen to me as well). 

![image](https://user-images.githubusercontent.com/37980219/188307209-3e986ba7-854b-4a2c-a675-a190f13bc954.png)
[](url)

Here's what I did to "fix" it (as far as I could remember):

1. Add the remote repo
![image](https://user-images.githubusercontent.com/37980219/188307316-aeee8ba3-5020-47f1-906a-33d6f7737d74.png)

2. Checkout at "Add trainer class" (I'm not 100% sure if this is the step I took)

3. Then pull the "improved" branch from the remote repo
![image](https://user-images.githubusercontent.com/37980219/188307360-ca0dc092-d3d4-4f4c-bfe3-6846023e65a2.png)

Personally I'm not 100% sure if this is allowed (since the improved branch is pulled from the remote repo to local repo instead of fork then cloning it) but I managed to merge the improved branch back successfully:

![image](https://user-images.githubusercontent.com/37980219/188307442-361b6024-0903-4a3b-9699-85d33a195637.png)

If you don't mind redoing all the steps in the video before merging the improved branch, you can re-fork the repo and just remember to uncheck the box (in first image) to pull all the branches too.

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/8#issuecomment-1236323125" expanded>

Sorry for assuming that simply reforking and unchecking "copy only the main branch" can work.

I just tried to fork with another account with unchecking that box. I can see both branches in the forked repo.
![image](https://user-images.githubusercontent.com/37980219/188311672-1b1f79c4-37c2-4808-b643-41114270f6e4.png)

However on cloning it onto my local repo, I encounter the same issue as yours.

While the improved branch is not shown on the local repo in source tree, it can actually be found under remote tab at the left. 
![image](https://user-images.githubusercontent.com/37980219/188312357-d9d42a13-c994-45f1-9df5-330ce970ccff.png)

Apparently git clone only clone a single branch to the local. You can take a look at this too: https://stackoverflow.com/questions/67699/how-do-i-clone-all-remote-branches

For sourcetree I tried doing these after cloning and it seems to work:
1. Click on the "improved" branch in the image above
2. Checkout the branch into a new branch
![image](https://user-images.githubusercontent.com/37980219/188312306-ef239941-ba55-42c6-bb34-0f679ff62d83.png)
3. "improved" branch is now on local repo too
![image](https://user-images.githubusercontent.com/37980219/188312448-4a89357d-4136-49e4-ba14-9f3ecd72baae.png)

Hopefully this helps now
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/37#issuecomment-1304422060" expanded>

Hi, AFAIK, in `nameList.getByIndex(2).getHeight()`, essentially what it does is to call `nameList.getByIndex(2)` first, and on the object returned it calls `getHeight()` method. 

You can picture `nameList.getByIndex(2).getHeight()` into something like this:
```
Person temp = nameList.getByIndex(2)
int height = temp.getHeight();

```

Since the method `getHeight()` is called on the object after the object is returned back to `main()`, the `getHeight` should be invoked by `Main` in sequence diagram.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/45#issuecomment-1328705539" expanded>

Closed as the answer is posted on Luminus
</panel>

</panel>


<panel type="info" header="### 4. CHUA..RREN `@chydarren` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Question regarding usage of @author tag in header comments**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/28" expanded>

Hello! My team wish to seek a clarification. May I please find out whether we are allowed to use the "@author" tag in header comments of our functions related to our user story to credit our original authors in our code? Thank you!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/6#issuecomment-1219989835" expanded>

Hello @NayChi-7 , if you are using SourceTree, you should see a "Tag" button at the top of the SourceTree. Click on your commit, then click "Tag" and tag it with the label, e.g. Level-X for each corresponding increment number. I don't think there is a need to submit the tag elsewhere (based on my interpretation) as the evaluator uses some script to grade our increments.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/7#issuecomment-1231422849" expanded>

Hello @indraneelrp , I'm not a prof but I think your repository name has to be titled as "ip" in order for the dashboard to detect the repository. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/28#issuecomment-1277794425" expanded>

Hello Prof, the team have just read your email about the steps available on the module [website ](https://nus-cs2113-ay2223s1.github.io/website/schedule/week10/project.html#4-ensure-the-code-is-reposense-compatible) and we will follow the convention introduced. Thanks for addressing the concern by the team.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/38#issuecomment-1304546261" expanded>

PS yes I realized it's not a DBMS / SQL

</panel>

</panel>


<panel type="info" header="### 5. NG D..E QI `@ngdeqi` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: UML diagram drawing for finals**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/42" expanded>

Hi Prof, 

May I know if we have to draw UML diagrams (on paper or examplify, not sure if the latter supports drawings) during finals?

If you have already mentioned it before in the past, thank you for answering this question again!


</panel>

<panel  header="**2. :fas-info-circle: How to draw PlantUML for chained method call**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/37" expanded>

Hi all, how should I draw a sequence diagram for the chained method call, `nameList.getByIndex(2).getHeight()` from `Main`?

```
public class Main {

    public static void main(String[] args) {
        NameList nameList = new NameList();
        int height = nameList.getByIndex(2).getHeight();
    }
}


public class NameList {
    :
    public Person getByIndex(int index) {
        : 
        return Person;
    }  
}


public class Person {
    :
    public int getHeight() {
        return this.height;
    }
}

```
I am not sure if `getHeight()` should be invoked by `Main` or `NameList` object.
</panel>

<panel  header="**3. :fas-info-circle: Import statement for importing all classes for a package**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/14" expanded>

Can we use a wildcard import statement if we are using all the classes in a particular package?

For example, I am importing ALL the exception classes I have created into my parser class, so it would be better for me to do this:
`import duke.exception.*;`
instead of
```
import duke.exception.exception1;
import duke.exception.exception2;
:
```
</panel>

<panel  header="**4. :fas-info-circle: Accidentally clicked Confirm Submission on Coursemology without finishing all Questions**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/1" expanded>

I accidentally clicked Confirm Submission on Coursemology for exercise 1 of the Week 2 coding exercises, thinking it only finalises the submission for that exercise.

I am no longer able to submit my code for the other exercises.

Prof, please help me undo this so I can attempt the other exercises. Thank you.

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/37#issuecomment-1309969116" expanded>

Thank you for the explanation! @wcwy  
</panel>

</panel>


<panel type="info" header="### 6. KWOK..ASEY `@kaseykwok` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Sequence diagrams passing actual values instead of variable names**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/41" expanded>

Can I ask if using dummy variable as the parameters for sequence diagrams a bug or is it accepted? 

Reference in AB3 DG:
<img width="756" alt="image" src="https://user-images.githubusercontent.com/86282300/201464856-0070f943-8f9a-4d0d-82e3-c850264883be.png">

Issue number: #476

</panel>

<panel  header="**2. :fas-info-circle: Week 10 Post-lecture quiz not found**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/31" expanded>

I could not see any new quiz on LumiNUS. Do we have any quiz this week? 
</panel>

<panel  header="**3. :fas-info-circle: Change of Main Class Name**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/22" expanded>

Should we keep the main class name to be Duke just like our ip? Will changing it affects the scripts?
</panel>

<panel  header="**4. :fas-info-circle: Configuration for protectecting the master branch in PR**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/20" expanded>

Can I know if this is the correct way to protect the PR from being merged in the master branch? I saw that there are no steps in the course website that told us to specify the required rules. The PR is allowed to merge despite failing the CI. So I fixed the configuration to this. Is it needed to configure it that way? 

<img width="784" alt="image" src="https://user-images.githubusercontent.com/86282300/193799262-9f9717da-e8cd-4d6a-a881-0f4800a72418.png">


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/41#issuecomment-1312630045" expanded>

Ok, thank you.
</panel>

</panel>


<panel type="info" header="### 7. WILS..G AN `@wilsonngja` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Typo Error in Class Diagram Slides**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/44" expanded>

![image](https://user-images.githubusercontent.com/31720838/204173032-3ed6e6c4-8e96-4a1e-a503-7c25b50089f5.png)

Hi prof, I was reading through the slides and I noticed that in the ppt slide entitled L7-L8-Models_Assertion, there seems to have a typo in slide 19. Should the object diagram be `r1:Route` and `r2:Route` instead of 2 of `r1:Route`?
</panel>

<panel  header="**2. :fas-info-circle: Regards to managing of user stories and milestones**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/21" expanded>

With regards to the creation of user stories and milestones, the one that will be creating these would be the one that is allocated to this task right? So for example if my role is to maintain the workflow, while my teammate's role is to maintain the documentation, then I would be the one assigning the issues, and approving the PR etc right?
</panel>

<panel  header="**3. :fas-info-circle: Improved branch is not seen in Sourcetree**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/8" expanded>

Hi, I was watching the video with regards to RCS and the 'improved' branch is not shown. This is what was done prior to reaching this step:

- I followed the activity during the lecture using Ubuntu.
- When I was trying to follow using the RCS exercise, I decided to switch to Windows as sourcetree is not supported on Ubuntu.
- Since the code on my windows does not have the updated code, i copied the files that I have on Ubuntu over to Windows.

I also tried to re-clone on a separate directory and opening on Sourcetree but it also does not show the 'improved' branch. How can I go about to solve this issue? Thank you.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/8#issuecomment-1236302673" expanded>

Alright thank you! :)
</panel>

</panel>


<panel type="info" header="### 8. DHAN..DALI `@dhanish265` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: TEAMMATES link for peer evaluation practice**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/9" expanded>

I just wanted to know if this link has been made available to us yet. I used the recovery option but the only surveys open to us are the project idea submission ones.
</panel>

<panel  header="**2. :fas-info-circle: about commits**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/3" expanded>

is it recommended to commit files through SourceTree or use the commit function provided in Intellij instead? or does it not matter at all?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/8#issuecomment-1236313477" expanded>

so perhaps thinking that the improved branch did not show because I had failed to click the checkbox at the start, I redid the entire thing, and the improved branch still fails to show. Moreover, I do not have a 'master' branch, only one that's known as 'main'. Please clarify.
</panel>

</panel>


<panel type="info" header="### 9. RACH..YUAN `@Franky4566` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Level-6 Jar file**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/18" expanded>

hi prof! sorry may I also my friend and I did not realise we needed to create a release for the ip week 6 jar file (Week-6-Jar). However, we uploaded our jar file during the time frame but created a release after the time frame. Would we still be penalised for this task?
</panel>

<panel  header="**2. :fas-info-circle: Merging-PR admin task**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/17" expanded>

Hi prof, may I clarify what we need to do to fulfill this ip admin task? As I cant seem to find the requirements on the module website. Thank you!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/17#issuecomment-1264294077" expanded>

oh i see, thank u prof!
</panel>

</panel>


<panel type="info" header="### 10. NAY ..AING `@NayChi-7` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: IP tags submission**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/6" expanded>

After I have committed my changes to the forked repository, am I supposed to get the git tag and submit that tag somewhere (Luminus/ IP tracking dashboard, etc)? I might have misunderstood or overlooked it while reading about IP but I am a bit lost with how the submission works. Thus, any help is appreciated.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/6#issuecomment-1220320223" expanded>

Ohhh I see I see... thank you very much.
</panel>

</panel>


<panel type="info" header="### 11. PARA..JEEV `@indraneelrp` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: iP dashboard not reflecting my tags**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/7" expanded>

Hi prof,

I have followed the appropriate steps- forking the repo, tagging the commits with the exact spelling, pushing the tags, and waiting an extra day as well. The tags can be seen on my fork. However, it does not reflect on the iP dashboard. What may be the cause of this issue and how could I rectify it?

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/7#issuecomment-1231487513" expanded>

O, that might have been the issue, thanks! I will check again tomorrow. If it is still not resolved, I'll email you as per the above

</panel>

</panel>


<panel type="info" header="### 12. KWUA.. REN `@JordanKwua` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/18#issuecomment-1264304986" expanded>

Hello prof, I am the friend mentioned in this thread. Instead of creating a release to upload the JAR file in Week 6, I pushed the JAR file into my repository instead. I pushed it on time but since it was not created as a release it still remains as red,  what could I do to resolve this issue?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/18#issuecomment-1264381809" expanded>

Prof I have released the Week 6 JAR and tagged it as v0.1. However, the source code attached with the JAR is the latest version in my repository. Do I have to make sure the source code reflects the code I had when I built Week 6 JAR and pushed it?
</panel>

</panel>


<panel type="info" header="### 13. ANG ..RCUS `@OVReader` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Implementation of Exception Handlers for iPs new features (level 6 onwards)**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/11" expanded>

Hi, do we need to implement exception handlers for new features (iP level 6 onwards)?

Thank you.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/11#issuecomment-1242623918" expanded>

Noted with thanks prof
</panel>

</panel>


<panel type="info" header="### 14. LEON..OWEN `@owenl131` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Can we use squashing when merging PRs for tP?**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/26" expanded>

Will it interfere with progress and contribution tracking?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/26#issuecomment-1274190361" expanded>

> In CS2113, recommended not to use squash and merge (and rebase) as it changes the commit time stamps that hamper the progress tracking.

Noted thanks!
</panel>

</panel>


<panel type="info" header="### 15. WANG..GJIA `@wangtingjia` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Fail CI checkstyle**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/35" expanded>

I am unsure of a CI check-style error as shown here. I suspect it has to do with the reading of files from a online URL. Snippet of code shown below as well.
![image](https://user-images.githubusercontent.com/54758778/198814477-2b435b8e-8f68-4ede-a71c-db47b07b2931.png)
![image](https://user-images.githubusercontent.com/54758778/198814484-67abb2c6-e53d-4184-8cd0-5a06b6da18e7.png)



</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/35#issuecomment-1295738184" expanded>

It seems to work when I do this (solution from stackoverflow)?
![image](https://user-images.githubusercontent.com/54758778/198815071-e0ff8ee9-940d-42be-b4f9-4568e689aa60.png)

</panel>

</panel>


<panel type="info" header="### 16. BIAN.. RUI `@Brominne` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Swap tutorials to T3/T4**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/4" expanded>

Hi friends, is there anyone from tutorial T3/T4 who can swap with me to T1/T2? I cannot enroll in T1/T2 due to timetable clash. Much appericiation for the help:) 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/4#issuecomment-1217752729" expanded>

My email is e0773671@u.nus.edu if anyone is interested in swapping tutorial with me!
</panel>

</panel>


<panel type="info" header="### 17. CHUA..RENE `@kyrenechua` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: IO Redirection test failure on CI/CD**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/27" expanded>

My team is running into issues with the Github Actions checks when making/merging pull requests. Specifically, IO Redirection is causing us issues - this is due to our error handling printing out filepaths. Since Paths.toString() uses the system-dependent name separator, the EXPECTED.txt is bound to not match with the ACTUAL.txt on either Mac/Linux or Windows. (See https://github.com/AY2223S1-CS2113-T17-4/tp/pull/47/checks - the Windows gradle test fail is unrelated and has been fixed) 

While we can remove the printing of filepaths, we feel this is a feature that improves user experience and helps users troubleshoot errors, and removing it for the sake of passing a test is counterintuitive to the project as a whole. Are there any ways we can make this test pass (or suppress the test for those lines) without removing functionality?
</panel>

<panel  header="**2. :fas-info-circle: Request for permission to use third-party API/Libraries**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/10" expanded>

Dear Prof,
Our group would like to use the following third-party APIs and libraries for our tP:

1. https://www.ura.gov.sg/maps/api/
-> we would like to use API to retrieve and store car park data for our tP.

2. https://datamall.lta.gov.sg/content/datamall/en.html
-> we would like to use API to retrieve and store car park data for our tP.

3.  https://github.com/fangyidong/json-simple
-> we would like to use this library to help us parse a JSON file into Java.

Thank you :D

</panel>

</panel>


<panel type="info" header="### 18. ZHOU..IWEN `@maanyos` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Formatting issues on GitHub Pages**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/15" expanded>

Hi, I've ran into the issue mentioned on the CS2113 website where the user guide doesn't render properly on html after conversion by GitHub pages.

I'm trying to use collapsible tabs to compress the elaborations for each command keyword and it's supposed to look like this, which seems correct in the preview:
> ### `hi` - to greet Slave Kai
><details><summary>details</summary>
>  
>Slave Kai will respond with a greeting  
>>Example of usage:  
>>`hi`  
>>  
>>Expected outcome:  
>>Slave Kai's response  
>>```  
>>Howdy!  
>>```  
>
></details>

However, after GitHub Pages converts to html, this is what it looks like on the website (screenshot below):
![Screenshot (159)](https://user-images.githubusercontent.com/88487166/191397660-9ddea81a-b297-43e9-94e1-ba6095756946.png)

I've tried using \<blockquote>, adding empty lines after \</summary>, changing the syntax, but they seem to either disjoint the collapsible tab or do nothing. Anyone knows other methods to deal with this?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/15#issuecomment-1253400884" expanded>

neither seems to work prof :( 
i tried using Jekyll minima and the website theme changes but same formatting error
i'll probably just remove the collapse feature
</panel>

</panel>


<panel type="info" header="### 19. IVAN..RONG `@ivanthengwr` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: give your chatbot another name**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/5" expanded>

Hi, if I were to change the name of the chatbot, do I need to change the class name & file name also? i.e. `public class Duke` change to `public class Flash` and file name `Duke.java` change to `Flash.java`

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/5#issuecomment-1218819949" expanded>

Ok thank you!
</panel>

</panel>


<panel type="info" header="### 20. JAVI..QUAN `@jeyvia` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Requesting permission to use third-party currency-api**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/32" expanded>

## Library

[Currency-api](https://github.com/fawazahmed0/currency-api) 

## Purpose

We would like to use it to store exchange rates, to convert between currencies in our application.

## License

Currency-api is open-source as stated [here](https://github.com/fawazahmed0/currency-api/blob/1/LICENSE).

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/32#issuecomment-1280582642" expanded>

Yes. To be exact, I will be using `latest/currencies/SGD.json` to get exchange rates with respect to The Singapore Dollar.
</panel>

</panel>


<panel type="info" header="### 21. LIM .. JIE `@xzynos` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Requesting permission to use Apache Commons Library**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/13" expanded>

## Library

[Apache Commons](https://commons.apache.org/)

## Purpose

I would like to request permission to use the Apache Commons library for parsing and logging purposes.

## License

This library is licensed under the Apache License v2. https://www.apache.org/licenses/

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/13#issuecomment-1250540723" expanded>

Thank you professor
</panel>

</panel>


<panel type="info" header="### 22. NG S.. IAN `@nshian` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Strange IO redirection test error for Windows**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/34" expanded>

![image](https://user-images.githubusercontent.com/75054373/196380699-e8039ee1-00b3-49b6-a637-c2c85cc8535b.png)

I have verified that the program output and EXPECTED.txt are identical but I seem to be having trouble passing the IO redirection test for Windows specifically. Can I get some help troubleshooting the error? Is it perhaps a difference in encoding for whitespaces in UNIX vs Windows? 

The commit is available here: https://github.com/AY2223S1-CS2113-W13-2/tp/actions/runs/3271835084/jobs/5382097301
</panel>

</panel>


<panel type="info" header="### 23. ONG ..HONG `@ongzhihong` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/38#issuecomment-1304705470" expanded>

Remember to create a resources directory in your main and add it in your project structure so that the resources folder is included when you build your jar file.

Also when you want to get the file from resource in your code, you can use either getResource() or getResourceAsStream() and becareful about the file paths! 

You can read up at this link: https://docs.oracle.com/javase/7/docs/api/java/lang/Class.html#getResource(java.lang.String) 
</panel>

</panel>


<panel type="info" header="### 24. JOHN.. JUN `@jjtoh` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request to use NUSMods API and FasterXML library**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/39" expanded>

 ## Library

[NUSMods API](https://github.com/nusmodifications/nusmods)
[FasterXML](https://github.com/FasterXML/jackson-core)

## Purpose

NUSMods API - To get information about modules and lessons
FasterXML - To parse the json response from the API

## License

NUSMods API is [licensed](https://github.com/nusmodifications/nusmods/blob/master/LICENSE) under MIT License
FasterXML is [licensed](https://github.com/FasterXML/jackson-core/blob/2.14/LICENSE) under Apache License 2.0

Sorry for asking so late into the project.
</panel>

</panel>


<panel type="info" header="### 25. CHAN..HONG `@eehongchan` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request for permission to use third-party library - FasterXML**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/19" expanded>

Dear Prof,

Our group would like to use the following third-party library for our tP:
1. https://github.com/FasterXML/jackson-databind/
    -&gt; to parse JSON files to Java Objects

Thank you!
</panel>

</panel>


<panel type="info" header="### 26. MALC..HUAN `@malcolmang` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/34#issuecomment-1282036101" expanded>

Hi Ian, I encountered something similar as well. Two things you can check: as you mentioned line spaces might be different (CLRF vs LF). Another thing was that if you print paths or directories anywhere in your code with the Paths module, this can result in a different file separator between the two OSes. 

For this reason I ended up axing the IO Redirection test altogether and focused on JUnit. 
</panel>

</panel>


<panel type="info" header="### 27. CHEA..O YI `@CheahHaoYi` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request to use JANSI Library for tP**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/30" expanded>

## Library

Jansi
[Github Repo](https://github.com/fusesource/jansi)
[Documentation](https://fusesource.github.io/jansi/index.html)

## Purpose

We could like to color code our User Interface to improve the aesthetics of programme and enhance the User Experience

## License

Jansi is an ASL 2.0 licensed Java library as stated on the library website [here](http://fusesource.github.io/jansi/)


</panel>

</panel>


<panel type="info" header="### 28. BUI ..HANH `@bdthanh` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: JavaCI Checks Failed**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/25" expanded>

May I ask what might cause those checks failed at "Perform IO redirection check test (*NIX/MacOS/Windows)"? They ran for more than 4 hours then failed. Thanks

</panel>

</panel>


<panel type="info" header="### 29. CAO ..IKAI `@nvknow` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/9#issuecomment-1237797661" expanded>

Same. None of my group members got the link, yet the deadline is due tomorrow according to Week5 Admin.
</panel>

</panel>


<panel type="info" header="### 30. VORA..MISH `@RiaVora` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Practice Exam**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/43" expanded>

Hello!

The module website says there will be a shorter practice exam released a week before the exam. I wanted to check if anything has been released? If not, no worries, I just wanted to make sure I didn't miss it :)

<img width="865" alt="image" src="https://user-images.githubusercontent.com/31297758/203538905-4be3ea9e-79e6-44c2-a602-5fafe448cc44.png">

</panel>

</panel>


<panel type="info" header="### 31. SHEN..HEQI `@zheqis12138` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: TP permission denied**" popup-url="https://github.com/nus-cs2113-AY2223S1/forum/issues/29" expanded>

I am running my tp on intellij, java11, macos.
The code run perfectly on my teammate's PC, but when I run the same project, it says /Users/zheqishen/Documents/tp/.gradle/6.2/fileContent/fileContent.lock (Permission denied).
The problem seems happen on file permission and I have not changed anything on gradle.
Thank you so much!
<img width="768" alt="Screen Shot 2022-10-14 at 11 06 52" src="https://user-images.githubusercontent.com/88580183/195753224-ae4a8fe5-1c8e-4eb6-a081-99e9bbbab2e4.png">

</panel>

</panel>
