# solved-cs6300-assignment-4-sdpencryptor-spring-2026
**TO GET THIS SOLUTION VISIT:** [[SOLVED] CS6300 Assignment 4: SDPEncryptor Spring 2026](https://www.ankitcodinghub.com/product/cs6300-assignment-4-sdpencryptor-spring-2026-solved/)


---

📩 **If you need this solution or have special requests Email:** ankitcoding@gmail.com 
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;145078&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6300 Assignment 4: SDPEncryptor  Spring 2026&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In this assignment, you will develop a simple Android app, <em>SDPEncryptor</em>, that encrypts messages using a simple <a href="https://en.wikipedia.org/wiki/Affine_cipher">affine cipher</a>. Before you make an Ed post or communicate with your peers about this assignment, read <a href="#_mn8ur8uv0qnv">‘Guidelines for Communicating’</a> near the end of this assignment spec; <strong>failure to follow said guidelines may result in points deduction</strong>. Configuring your Android&nbsp;Studio development environment is itself a key learning objective; it lays the groundwork for the group project. Spending 70% to 90% of your time on this setup is normal.

<h2>INPUTS:</h2>
<ol>
<li><em>Message Text:</em> message to be encoded.</li>
</ol>
<ul>
<li>This input should be a <strong>non-empty string </strong>and must contain <strong>at least one letter or number</strong>.</li>
<li>This input should be provided to the app through an <a href="https://developer.android.com/reference/android/widget/EditText">EditText</a> widget,<strong> initially blank</strong>.</li>
</ul>
<ol start="2">
<li><em>Key1</em><em>:</em> first encryption parameter.</li>
</ol>
<ul>
<li>This input should be an integer <a href="https://en.wikipedia.org/wiki/Coprime_integers">coprime</a> to 62 between 0 and 62: <strong>1, 3, 5, 7, 9, 11, 13, 15, …</strong></li>
<li>This input should be provided to the app through an EditText widget,<strong> initially set to ‘1’</strong>.</li>
</ul>
<ol start="3">
<li><em>Key2</em><em>:</em> second encryption parameter.</li>
</ol>
<ul>
<li>This input should be an <strong>integer &gt;= 1 and &lt; 62.</strong></li>
<li>This input should be provided to the app through an EditText widget,<strong> initially set to ‘1’</strong>.</li>
</ul>
<h2>OUTPUT:</h2>
<ol>
<li><em>Output Text</em>, the text resulting from applying the following cipher:</li>
</ol>
<ul>
<li>Each character in the alphabet is assigned a numeric value between 0 and 61 based on its position in the alphabet (i.e., “a”=0, “b”=1, … “z”=25, “A”=26, “B”=27, … “Z”=51, “0”=52, “1”=52, … “9”=61). Note that the alphabet contains letters and numbers.</li>
<li>For each character in the alphabet, where the numeric value is , the encoded value of the letter is defined as where <em>&nbsp;</em>and <em>&nbsp;</em>are the values of <em>Key1 </em>and <em>Key2</em>, respectively, as in an <a href="https://en.wikipedia.org/wiki/Affine_cipher">Affine Cipher</a>.</li>
<li>The encoded character for the input character is calculated by taking the encoded number, which is a value between 0 and 61, and translating it back into a character (again, where “a”=0, “b”=1, … “z”=25, “A”=26, “B”=27, … “Z”=51, “0”=52, “1”=52, … “9”=61).</li>
<li>All non-alphanumeric characters must remain unchanged.</li>
<li>The output should be shown using a <em>non-editable</em> <a href="https://developer.android.com/reference/android/widget/TextView">TextView</a> that is initially blank and (re)computed when the “Encode Message Text” button is pressed. If any input is invalid when the button is pressed, the output should then be set to “” (i.e., the empty string), and all applicable error messages should be generated (see below).</li>
</ul>
<h2>EXAMPLE</h2>
<ul>
<li>Inputs:
<ul>
<li><em>Input Text</em> = “Cat &amp; 5 DogS”</li>
<li><em>Argument1 </em>= 5</li>
<li><em>Argument2 </em>= 3</li>
</ul>
</li>
<li>Output:</li>
<li><em>Output Text</em> = “tdK &amp; O ylHL”</li>
<li>Explanation:
<ul>
<li>“C” has a value of 28, (28 * 5 + 3) % 62 = 19, 19 corresponds to “t”.</li>
<li>“a” has a value of 0, (0* 5 + 3) % 62 = 3, 3 corresponds to “d”.</li>
<li>…</li>
<li>” “, “&amp;”, ” ” are unchanged.</li>
<li>“5” has a value of 57, (57 * 5 + 3) % 62 = 40, 40 corresponds to “O”.</li>
<li>” ” is unchanged.</li>
<li>…</li>
</ul>
</li>
</ul>
<h2>ERROR MESSAGES</h2>
The app should generate suitable error messages by calling <a href="https://developer.android.com/reference/android/widget/TextView.html#setError(java.lang.CharSequence)">EditText’s setError method</a> (inherited from TextView) on the appropriate EditText widget when the computation is triggered (i.e., the button is pressed). If done correctly, this will result in (1) an error mark () on the right-hand side of the text field and (2) a floating error message whenever the field has focus, as shown in the error screenshots below. It is possible to have more than one error active at the same time, as shown in the screenshots below.

&nbsp;

There are three error situations:

<ol>
<li>“Invalid Input Text”, related to the <em>Input Text </em>field, for any entry both letter-less and number-less. (Examples: “”, “&amp;$%#^$&amp;^”)</li>
<li>“Invalid Key1”, related to the<em> Key1 </em>field, for a blank or unacceptable value

(i.e., not coprime to 62).</li>
<li>“Invalid Key2”, related to the <em>Key2 </em>field, for a blank or out-of-range value.</li>
</ol>
<em>&nbsp;</em>

<em>&nbsp;</em>

For illustration, we are providing several mockups for a possible implementation of the app

&nbsp;

We suggest that you try to generate a user interface (UI) similar to the one shown above, but you don’t have to. However, you must make sure to use the exact same identifiers we provide below for your widgets. This is very important, as we will use these identifiers to check and auto-grade your app.

&nbsp;

<h2>IDENTIFIERS</h2>
<table width="624">
<tbody>
<tr>
<td width="262">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; plainTextInputID

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; key1InputID

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; key2InputID

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; generateCipherTextButtonID

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cipherTextOutputID

&nbsp;

&nbsp;
</td>
<td width="362"><strong><em>PRO-TIP: The identifiers are typed here for you. Just copy and paste them to be safe!</em></strong>

&nbsp;

For example, in the XML layout file for your app, the entry for the field used to input <em>Message </em>should have the following ID: android:id=”@+id/plainTextInputID”
</td>
</tr>
</tbody>
</table>
<h2>INSTRUCTIONS</h2>
<ol>
<li>Make sure to watch the <a href="https://www.youtube.com/watch?v=jqB3r_16WqA">Android Studio demo</a> (part of the lessons on Android).</li>
<li>In the root of the assigned private GitHub repository that we made for you (https://github.gatech.edu/gt-omscs-se-2026spring/6300Spring26&lt;your GT username&gt;.git), create a directory called “Assignment4”. Hereafter, we will refer to this directory in your local repo as &lt;dir&gt;.</li>
<li>Copy and paste (appending) the following into your .gitignore file in the root (&lt;dir&gt;/..)of your repo:

*.iml

.gradle

properties

.idea/workspace.xml

.idea/libraries

.idea

.DS_Store

build

captures

.externalNativeBuild</li>
<li>Create an Android app project called “SDPEncryptor” in &lt;dir&gt;. (<strong>Make sure that this results in a directory called </strong><strong>SDPEncryptor</strong><strong> in </strong><strong>&lt;dir&gt;</strong>, as shown in the “Configure Your Project” snapshot below–you will likely need to manually modify the “Save location” entry for this to happen.)
<ul>
<li>Choose “Empty Views Activity” as your project template.</li>
</ul>
</li>
</ol>
<strong>Note:</strong>

The screenshots in this document are taken using “Android Studio Otter 2 Feature Drop | 2025.2.2 Patch 1”.

&nbsp;

Note the package name: “edu.gatech.seclass.sdpencryptor”

Note the language: “Java” (Kotlin is allowed, but our ability to support problems you may encounter will be limited)

Note the minimum SDK: “API 35: Android 15”

Note the build configuration language: “Groovy DSL (build.gradle)” <strong><em>(You must use this exact build configuration language)</em></strong>

<ol start="5">
<li>You should test your app against a virtual “Pixel 9a with API 35 (VanillaIceCream) Installed.” You can add this device in the ‘device manager’ view.</li>
<li>Ensure you are using Gradle and Android Gradle Plugin versions compatible with Java 17. Go to File &gt; Project Structure &gt; Project and select 8.13.2 for the Android Gradle Plugin Version and 8.13 for the Gradle Version</li>
<li>Choose Modules in the Project Structure dialogue and check to see that you are using a Compile SDK Version of 35 and Source Compatibility and Target Compatibility of Java 17.</li>
</ol>
&nbsp;

&nbsp;

<ol start="8">
<li>In the same dialogue, choose the Default Config tab and ensure the Target SDK version is 35.</li>
<li>Check the build.gradle file for <strong><em>module app</em></strong> to see that the settings were applied:</li>
</ol>
&nbsp;

android {

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // …</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CompileSdk = 35</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; defaultConfig {</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;&nbsp;&nbsp; // …</strong>

<strong>&nbsp;&nbsp;&nbsp; minSdk = 35</strong>

<strong>&nbsp;&nbsp;&nbsp; targetSdk = 35</strong>

<strong>&nbsp;&nbsp;&nbsp; // …</strong>

<strong>&nbsp; }</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // …</strong>

<strong>&nbsp; compileOptions {</strong>

<strong>&nbsp;&nbsp;&nbsp; sourceCompatibility JavaVersion.VERSION_17</strong>

<strong>&nbsp;&nbsp;&nbsp; targetCompatibility JavaVersion.VERSION_17</strong>

<strong>&nbsp; }</strong>

&nbsp;

}

<ol start="10">
<li>Make sure that your build.gradle file for <strong><em>module app</em></strong> contains the following dependencies (<strong>including the specific versions listed</strong>):</li>
</ol>
implementation ‘androidx.appcompat:appcompat:1.7.1’

implementation ‘com.google.android.material:material:1.13.0’

implementation ‘androidx.constraintlayout:constraintlayout:2.2.1’

testImplementation ‘junit:junit:4.13.2’

testImplementation ‘org.robolectric:robolectric:4.15’

&nbsp;

<ul>
<li>If some dependencies are missing, make sure to add them.</li>
<li>There may be newer versions of some of the dependencies available, but you should use the ones we recommend anyway.</li>
<li>You will have to rebuild the project if you added dependencies (the IDE should let you know through a banner notification).</li>
</ul>
<ol start="11">
<li>To ensure compatibility with the tests used in autograding, add the following in the build.gradle for the <strong><em>module app</em></strong>:</li>
</ol>
&nbsp;

android {

// …

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; testOptions {</strong>

<strong>&nbsp; unitTests {</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp; includeAndroidResources = true</strong>

<strong>&nbsp; }</strong>

<strong>}</strong>

// …

}

&nbsp;

<ol start="12">
<li>Implement your solution based on the requirements provided above using <strong>Java 17</strong>. Be sure your app includes both the semester and year in the Title as seen in the wireframes above.</li>
<li><strong>Mandatory:</strong> <strong>check your solution before submitting it by following these directions</strong>. Download <a href="https://gtvault-my.sharepoint.com/:u:/g/personal/stran63_gatech_edu/IQALhGLJWuqeR4uMC1HumHqWAZT9GR5HwGG2-SShKBZIHfI?e=7U5lak">this archive</a> and unpack its contents in &lt;dir&gt;,<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> which should create the following files:
<ul>
<li>SDPEncryptor/app/src/main/java/edu/gatech/seclass/sdpencryptor/SanityCheck.java: This file prevents your app from compiling if the identifiers, activity name, or package name are incorrect. <strong>Do not edit this file. If compilation fails after you add this file, it is indicative of a bad project structure. Carefully follow direction 1-4 again.</strong></li>
<li>SDPEncryptor/app/src/test/java/edu/gatech/seclass/sdpencryptor/RobolectricViewAssertions.java: This file contains a helper library to run Robolectric tests and enrich their output.</li>
<li>SDPEncryptor/app/src/test/java/edu/gatech/seclass/sdpencryptor/SmallTestExamples.java: This file contains a set of Robolectric tests similar to those we will run on your code for grading, for your convenience. Run the tests on the command line by executing “./gradlew test” in the project directory (you may have to install gradle to do so). During development and before submission, you can also run the tests from within Android Studio, by selecting “Run Tests in…” as shown below in the image to follow:</li>
</ul>
</li>
</ol>
&nbsp;

<ul>
<li>One key learning outcome of this assignment is to develop the skills to read, interpret, and resolve failed test cases. If you encounter failing test cases, it is <em>your responsibility</em> to determine the issue and implement a solution. Should you ask a question on ED, our guidance will often be consistent: “What do you understand about the output? Why do you think this assertion is being made? How does it align with the specifications?” If an assertion appears unexpected, your first reference should be the specifications rather than posting a query on ED. Below is an example of the “Expected” and “View Details” sections from the test failure output, along with some guidance on how to interpret them:
<ul>
<li><em>Expected: </em><em>“wBM8B lBG”</em><em> but was: </em><em>“v6SF6 b6B”</em>

<em>View Details: ID: 2131231064, res-name: messageTextID, visibility: VISIBLE, enabled: true, focusable: false</em></li>
<li>In this case, the test is saying that the text in the field corresponding with the “<em>messageTextID” </em>identifier is “<strong>v6SF6 b6B</strong>” but should have been “<strong>wBM8B lBG</strong>“. In this case, the most likely cause is that your affine cipher code isn’t working properly, as the cipher should be what populates that ‘<em>messageTextID’ </em></li>
</ul>
</li>
</ul>
<ol start="14">
<li>If your build fails with an error “Task :app:lint FAILED” or similar, you should be able to fix the issue by “inferring constraints” for your layout. Android Studio will do it for you automatically, just go to your activity_main.xml file, hover over the error reported, and the IDE should give you the option to fix it. Alternatively, you can also disable the lint task for your project by adding the following to gradle:</li>
</ol>
android {

//…

lintOptions {

tasks.lint.enabled = false

abortOnError false

}

}

&nbsp;

<ol start="15">
<li>For automated testing, check out <a href="https://robolectric.org/">Robolectric</a>. Here are some Robolectric tips, based on past experience:
<ul>
<li>Make sure your unit test config is set up so that Android resources are included. (See step 11 of these instructions)</li>
<li>Avoid using buttons that call private methods, as Robolectric may be unable to click them.</li>
<li>Avoid elements that cover your fields or buttons, even if these elements are invisible, as they may result in tests that fail to complete.</li>
<li>You may need to turn off the autofill feature or spellcheck in your AVD if your tests fail due to auto-completion of text input.</li>
<li>Do not add extra field labels or text into the designated EditText fields. Each EditText field should contain only the relevant input or output. You may use other fields for optional labels or UI elements.</li>
</ul>
</li>
<li>Commit the gradle-wrapper.jar, &lt;dir&gt;/SDPEncryptor/gradle/wrapper/gradle-wrapper.jar. If, for whatever reason, this file doesn’t exist run the following in &lt;dir&gt;/SDPEncryptor:

gradle wrapper

and include it in your private GitHub repository. If your .gitignore excludes jar files, you will need to force-add it.</li>
<li>Include two screen captures of the build result of the app (app_compile.png) and of the app running in the emulator (app_run.png). Put both image files in your “Assignment4” folder (see below). The name must be exact and all lowercase. Every semester our image validation process has improved – if the auto grader tells you there’s a problem, there’s a high likelihood that there’s a problem – follow these steps carefully.
<ul>
<li>png must be taken from a stand-alone terminal/CMD (not Android Studio built-in terminal) and must show both the “./gradlew build” (or “gradlew build”) command with “BUILD SUCCESSFUL”, as seen from the example below. Ensure that you terminal window is 100% opaque (i.e not translucent/transparent/see-through), the color difference between background and the text is significant, the window size is wide enough, the font size is appropriate (not too big, not too small); all of this is to ensure that we can easily read the content of your screenshot. Failure to do so will result in a points deduction. Example Image:</li>
</ul>
</li>
</ol>
&nbsp;

<ul>
<li>png must show the semester and year in the app title, as seen in the example below. Failure to adhere to the app title format text will result in a points deduction. Example Image:</li>
</ul>
&nbsp;

Note: “SDPEncryptor” (without space) and “SDP Encryptor” (with space) are both acceptable

&nbsp;

<ul>
<li>Hints for passing the image capture portion of the autograder (<strong>Do not open an ED post</strong> <strong>asking us to prevalidate any images</strong> – the previous instructions and what follows is the only advice we have on the matter): To pass the app_run image process, consider factors like <a href="https://support.google.com/accessibility/android/answer/7158390?hl=en">contrast</a>, resolution, the size of the image. For the app_compile image process, ensure you don’t have a partially transparent terminal, ensure you follow directions to the letter, it’s best if your view is large enough that you don’t have wrapping text, and lastly don’t take your image so close to the text block as to cut off edges or to make part of the output unreadable.</li>
</ul>
<h2>SUBMISSION</h2>
<ol>
<li>Add/commit/push your app to your assigned, <em>private</em> repo (the one we made for you). To do so, and make sure that all the necessary files are committed, do the following:
<ul>
<li>Go to &lt;dir&gt; and execute:
<ul>
<li>git commit -a</li>
<li>git push</li>
</ul>
</li>
</ul>
</li>
</ol>
<ol start="2">
<li><strong>As an alternative to Item 1, and only if you know what you are doing,</strong> you could also commit and push your app from within Android Studio, which should actually give you an option to do so:
<strong>But please use the instructions in Item 1 if you need clarification.</strong><strong></strong>
<strong>
</strong><strong></strong>
</li>
<li><strong>Submit on Gradescope a file, called </strong><strong>txt</strong><strong> that contains, in two separate lines (1) your GT username and (2) the commit ID for your submission.</strong> For example, the content of file submission.txt for George P. Burdell could look something like the following:

submission.txt</li>
</ol>
<table width="101">
<tbody>
<tr>
<td width="101">gpburdell1</td>
</tr>
<tr>
<td width="101">81b2f59</td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<ul>
<li><strong>As soon as you submit, your assignment will be scored</strong> by compiling it and running it against a set of test cases written by the instructors.</li>
<li><strong>You can resubmit as many times as you want before the deadline</strong>. However, we would not recommend a trial-and-error process, as Gradescope takes a non-negligible amount of time even to compile and check your code. You may want to complete and submit the assignment sooner rather than later and avoid rushing at the end (when the autograder may also be overloaded).</li>
</ul>
<h2></h2>
<h2>GUIDELINES FOR COMMUNICATING</h2>
<ol>
<li>Should my post be public or private?
<ol>
<li>You can only post publicly about environment-related questions (failure to launch Android Studio, the emulator, or build the project etc.) or questions related to failing <em>tests that you run on your local machine. </em>(eg. SmallTestExample)</li>
<li><strong><em>You cannot under any circumstance share or discuss any gradescope output publicly</em></strong>, you may only do so privately. If you share output of failed tests on ED with your peers, the minimum deduction will be a failure of each test case shared. This includes discussing the tests by their ‘name’ in Gradescope. These names are there to help guide you, but not to be used in discussion.</li>
<li>When in doubt, post privately – we’ll let you know if it can be public.</li>
</ol>
</li>
<li>What should be in my private post?
<ol>
<li>A link to the Gradescope result</li>
<li>If you are asking about a failed autograder test, give us a demonstration that you:
<ol>
<li>Tried to understand the test results (see <a href="#xvfakow74ksh">this section from the assignment spec</a>)</li>
<li>Confirmation that you’ve taken that understanding back to the assignment spec to see if there is anything you missed.</li>
</ol>
</li>
<li>any information that may be relevant (e.g., inlined snippets of relevant code–no screenshots or commit IDs, please).</li>
</ol>
</li>
</ol>
&nbsp;

<a href="#_ftnref1" name="_ftn1"><sup>[1]</sup></a> Be careful when extracting the files, as a conservative program may create a second “SDPEncryptor” directory (e.g., “SDPEncryptor 2”). If that happens, make sure to move the files to their right location.
