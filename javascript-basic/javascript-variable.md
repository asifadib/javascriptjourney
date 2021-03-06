# জাভাস্ক্রিপ্ট ভ্যারিয়েবল

আজকের পর্বে আমরা জাভাস্ক্রিপ্টের ভ্যারিয়েবল নিয়ে বিস্তারিত জানবো এবং শিখবো।

জাভাস্ক্রিপ্টে যেকোনো ডাটাকে একটি ভ্যারিয়েবলের মধ্যে সংগ্রহ করে রাখতে পাড়ি।

ভ্যারিয়েবল কি ?

জাভাস্ক্রিপ্ট স্টেটমেন্ট কি?

আমরা জাভাস্ক্রিপ্টে ফাইলে যে কোড লিখি এগুলো এক একটা কমান্ড বা নির্দেশনা জাভাস্ক্রিপ্ট ইঞ্জিনের জন্য। এগুলি জাভাস্ক্রিপ্ট ইঞ্জিনকে বলে দেয় তাকে কি করতে হবে। বাংলা লেখার সময় আমরা যেমন একটা বাক্য লেখার শেষ করি দাঁড়ি বা পূর্ণচ্ছেদ \(।\) দিয়ে। জাভাস্ক্রিপ্ট স্টেটমেন্টেও এরুপ প্রতিটা এক্সিকিউটেবল কমান্ড বা নির্দেশনা লেখার শেষ করা হয় সেমিকোলন \(;\) দিয়ে। একটা জাভস্ক্রিপ্ট ফাইলের মাঝে এমন অনেক কমান্ড বা নির্দেশনা দেয়া থাকে এগুলো জাভাস্ক্রিপ্ট ইঞ্জিনকে নির্দেশনা দেয় কি করতে হবে।

যেমন:

var x, y, z;    // Statement 1

x = 5;          // Statement 2

y = 6;          // Statement 3

z = x + y;      // Statement 4

সেমিকোলন \(;\)

১। প্রতিটি এক্সিকিউটেবল স্টেটমেন্টের শেষে একটি সেমিকোলন যুক্ত করুন।

যেমন:

var a, b, c;     // Declare 3 variables

a = 5;           // Assign the value 5 to a

b = 6;           // Assign the value 6 to b

c = a + b;       // Assign the sum of a and b to c

২। সেমিকোলন না দিলেও প্রোগ্রাম কাজ করে, কিন্তু ভাল প্রোগ্রামিং এর জন্য সেমিকোলন অবশ্যই দেয়া উচিৎ। এছাড়া যখন সেমিকোলন দ্বারা পৃথক করা হয়, তখন এক লাইনে একাধিক স্টেটমেন্ট লিখা যায়।

যেমন:

 a = 5; b = 6; c = a + b;

// Assign the value 5 to a, Assign the value 6 to b, Assign the sum of a and b to c

জাভাস্ক্রিপ্ট কীওয়ার্ডস কি?

কি ধরনের কাজ সম্পাদন করতে হবে তা জাভাস্ক্রিপ্ট কীওয়ার্ডসের মাধ্যমে ডিফাইন করা হয়। var কীওয়ার্ডের মাধ্যমে নতুন একটি ভ্যারিয়েবল তৈরির নির্দেশনা দেয়া হয়।

যেমন:

var x = 5 + 6;

var y = x \* 10;

নিচে জাভাস্ক্রিপ্ট কীওয়ার্ডসের একটি লিস্ট দেয়া হলো আপনি এখান থেকে কীওয়ার্ড সম্পর্কে শিখতে পারবেন:

![](file:///C:/Users/ASIFAD~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)

জাভাস্ক্রিপ্ট কমেন্টস:

জাভাস্ক্রিপ্ট কমেন্টসগুলি জাভাস্ক্রিপ্ট কোড ব্যাখ্যা করার জন্য এবং এটি আরও পাঠ উপযোগী করার জন্য লেখা হয়।

বিকল্প কোড পরীক্ষা করার সময় জাভাস্ক্রিপ্ট কমেন্টসগুলি কার্যকারিতা রোধ করতেও ব্যবহার করা যেতে পারে।

জাভাস্ক্রিপ্টে দুই রকম কমেন্ট করা যায়

১। সিঙ্গেল লাইন কমেন্ট

সিঙ্গেল লাইন কমেন্ট Double Slash // দিয়ে শুরু হয়।  Double Slash // দিয়ে শুরু পর যে কোড লেখা হয় তা কমেন্ট হিসেবে বিবেচিত হয় আর এই কমেন্টের কোনো আউটপুট দেখা যায় না।

এই উদাহরণটি কোডটি ব্যাখ্যা করতে প্রতিটি লাইনের শেষে সিঙ্গেল লাইন কমেন্ট ব্যবহার করে করা হয়েছে:

var x = 5;      // Declare x, give it the value of 5

var y = x + 2;  // Declare y, give it the value of x + 2

আউটপুটে শুধু y এর মান 7 দেখাবে কমেন্ট গুলো দেখাবে না।

এই উদাহরণটি প্রতিটি কোড লাইনের আগে সিঙ্গেল লাইন কমেন্ট ব্যবহার করে:

// Declare name, give it the value of Asif Mahmud.

var name = "Asif Mahmud"; 

// Declare name Change, give it the value of A.M

var name = "A.M"; 

আউটপুটে নামটা পরিবর্তন হয়ে এর ভ্যালু  A.M দেখাবে কমেন্ট গুলো দেখাবে না।

২। মাল্টি লাইন কমেন্ট

মাল্টি-লাইন কমেন্টগুলি / \* দিয়ে শুরু হয় এবং \* / দিয়ে শেষ হয়।

/ \* এবং \* / এর মধ্যে যে কোনও লেখা জাভাস্ক্রিপ্ট ইঞ্জিন আউটপুটে দেখাবে না।

এই উদাহরণটি কোড ব্যাখ্যা করার জন্য একটি মাল্টি-লাইন কমেন্ট  \(একটি কমেন্ট ব্লক\) ব্যবহার করে:

/\*

Declare 3 variables

Assign the value 5 to a

Assign the value 6 to b,

Assign the sum of a and b to c

\*/

var a, b, c;    

a = 5;

b = 6;

c = a + b;

আউটপুটে শুধু C এর মান 11 দেখাবে মাল্টি লাইন কমেন্ট গুলো দেখাবে না।

জাভাস্ক্রিপ্ট সিনট্যাক্স কি?

জাভাস্ক্রিপ্ট সিনট্যাক্স হলো জাভাস্ক্রিপ্ট প্রোগ্রামগুলি কীভাবে তৈরি করা হয় এবং কীভাবে কাজ করে সিনট্যাক্সের সাহায্যে তাই নির্দেশ করা হয়। একলাইনে বলতে গেলে জাভাস্ক্রিপ্ট সিনট্যাক্স হলো কিছু নিয়মের সমষ্টি।

যেমন:

১। var x, y, z; // ভ্যারিয়েবল কীভাবে ঘোষণা করবেন

২। x = 5; y = 6; // মানগুলি কীভাবে নির্ধারণ করা যায়

৩। z = x + y; // মানগুলি কীভাবে গণনা করা যায়

৪। প্রতিটি জাভাস্ক্রিপ্ট লাইন সেমিকোলন \(;\) দিয়ে শেষ করতে হয় তবে বাধ্যতামূলক নয়। সেমিকোলন \(;\) দিয়ে শেষ করা গুড প্র্যাকটিস।

জাভাস্ক্রিপ্ট মান

জাভাস্ক্রিপ্ট সিনট্যাক্স দুটি ধরণের মান নির্ধারণ করে: স্থির মান এবং পরিবর্তনশীল মান।

স্থির মানগুলিকে আক্ষরিক বলে। পরিবর্তনশীল মানগুলিকে ভেরিয়েবল বলা হয়।

এইচটিএমএল এবং সিএসএসের নির্দিষ্ট কোড রয়েছে যা ঘন ঘন ব্যবহৃত হয়, জাভাস্ক্রিপ্টে কয়েকশ এবং কয়েকশ কোডিং অপশন রয়েছে যা আপনি ব্যবহার করতে পারেন।

যখন জাভাস্ক্রিপ্ট সিনট্যাক্সের কথা আসে তখন কোডের মধ্যে স্থির মানগুলিকে আক্ষরিক বলা হয়, অন্যদিকে ভেরিয়েবলের মানগুলি ভেরিয়েবল বলে।

লিটারেল

স্থির মান বা আক্ষরিক বিভিন্ন রূপে আসে। এগুলি সংখ্যা হতে পারে, দশমিক বা তার সাথে লেখা বা পাঠ্যের স্ট্রিং, ডাবল বা একক উদ্ধৃতি দিয়ে রচিত।

জাভাস্ক্রিপ্ট স্ট্রিংগুলি পাঠ্য সংরক্ষণ বা হস্তক্ষেপের জন্য ব্যবহৃত হয় এবং উক্তির ভিতরে লেখা অক্ষরগুলি থাকে। নীচের ক্ষেত্রে, জি 2 লার্নিং হাব একটি স্ট্রিং হিসাবে লিখিত স্থির মান।

var ব্লগনাম = ‘জি 2 লার্নিং হাব’;

