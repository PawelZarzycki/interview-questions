List of interview questions for Android Developer role
------------------------------------------------------

- What's the difference between Activity Context and Application Context? When to use which?
- How can you persist data in the Activity after the screen rotation?
- What is Retained Fragment?
- Can you describe Activity Lifecycle?
- Can you describe Fragment Lifecycle? (side note: IMO it's too complicated to know it by heart)
- How do you consume web services in Android?
- How do you handle multithreaded operations in Android?
- What are possible methods of concurrent programming in Android?
- Do you think that using AsyncTask is good practice? Explain your question?
- How can you test mobile applications?
- What classes derives from `Context` class?
- How can you handle background operations?
- How can you pass data between Activities?
- How can you pass data between Activity and Service?
- What is the difference between Service and IntentService?
- What are news introduced in the latest API?
- Do you know RxJava and RxAndroid? How can you use it?
- What's the difference between RxJava 1 and RxJava 2?
- What build systems do you know?
- How can you use Gradle to automate and improve your work?
- How can you wake device uo, when it's asleep? (e.g. while creating an alarm or phone app)
- Have you written any annotation processor? Do you know, how to do this?
- How will you create logs for LogCat in your application to make them unavailable in the production app?
- Tell a few words about Dalvik
- Tell a few words about ART
- What is `.dex` file?
- What needs to be done to publish app in the Google Play Store?
- What do you know about ProGuard
- How can you deal with `OutOfMemoryError` while loading large images?

1- what are the latest Android versions? The most important Marshmallow new features?
2- what is the purpose of the Activity?
3- what is the purpose of the Fragments?
4- explain the lifecycle of the Activity?
5- explain the lifecycle of the Fragment?
6- you’re using a traveling app then you clicked settings button, Settings Activity opened, then you clicke Android back, what’s the lifecycle of the Settings Activity and the Home Activity when you did that?
7- what do you know about Material design?
8- what’s the difference between Abstract class and Interface in Java?
9- what’s the interface in Java?
10- what’s Abstract class in Java?
11- why you couldn’t create an instance from an abstract class?
12- what’s the difference between Dialog and AlerDialog in Android?
13- what’s the difference between LinearLayout and RelativeLayout?
14- which has better performance, LinearLayout or RelativeLayout?
15- given a simple contact item, with image and name and number, how could you implement it in XML?
16- what’s the Service, which thread it operates on?
17- what’s the difference between Service and IntetntService?
18- what’s ANR message?
19- explain the BroadcastReciever job and implementation?
20- can you use a Fragment with no UI? What cases could make you use this pattern?
21- explain the Java access modifiers?
22- what’s the difference between Default and Protected access modifiers in Java?
23- what do you know about AsynTask?
24- what’s the difference between Parcelable and Serializable? Which one is better? why?
25- how to access a variable in Activity from fragment?
26- you have one Activity with two fragments, one has a button and the second has a TextView, clicking the button change the TextView, how do you implement it?
27- how to make a variable thread safe?
28- what strategies we can use to achieve thread safety?
29- what is the purpose of “static” keyword in Java?
30- how could you initialize a static variable in Java?
31- what design patterns you know?
32- explain the builder pattern?
33- when do you use an observer pattern?
33- what’s the Singleton, when do you use it in Android?
34- what’s the difference between the LinkedList, ArrayList and Arrays?
35- what projects currently you work on? What is your workflow to implement a specific feature?
36- how do you handle Firebase push notifications?
37- how do you implement Firebase realtime Database?
38- you have a big project, and you have a login screen requirement, what processes you will follow to ship it?
39- what’s an eventbus?
40- what the thread that onRecieve method of a BroadcastReceiver operates on?
41- how to implement a custom BroadcastReceiver?
42- what’s the difference between MVC and MVP?
43- could you explain MVVM?
44- what’s the M in MVP? Answering … could it be a something else?
45- what’s the purpose of Content Provider?
46- what Sqlite library do you use?
47- what libraries do you use for Networking, Image loading, Database?
48- what do you use to handle a very fast Sensor that emit many readings at a time in Rx way?
49- what’s the difference between map and flatMap() in Rxjava?
50- how to create parallel Network calls with Rxjava?
51- if you have one request from the network and you want to call the cache if Network throw an error … how to achieve that via Rxjava?
The funny thing that I’ve read Dan lew blog post about this case, implemented it twice before, but couldn’t answering this question during the interview … bad things happen.
52- what’s the difference between concatMap() and flatMap() in Rxjava?
53- what do you know about Intents? What is the purpose of categories in Intents?
54- what’s the purpose of FrameLayout?
55- how to compare between Two objects?
56- Java is pass by Value or pass by Reference?
57- when you use observeOn() and subscribeOn()?

Well that’s all I can remember for now, usually the OOP, Android components and Design patterns stuff are common among most of the interviews I had.
Luckily the Android dev challenge course has the answers of many of the questions above, just don’t rush … take your time to understand the basics. Don’t jump into things like Rxjava or Dagger without a good playground of the basics and the platform apis.
