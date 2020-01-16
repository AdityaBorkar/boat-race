## সময়-সংরক্ষককে যোগ করা

এখন আপনি আপনার খেলার একটি টাইমার যোগ করুন, যাতে প্লেয়ার যত তাড়াতাড়ি সম্ভব দ্বীপে পেতে হবে।

\--- কাজ \---

আপনার স্টেজে `সময়`{: class = "block3variables"} নামে একটি নতুন পরিবর্তনশীল যুক্ত করুন।

![screenshot](images/boat-variable-annotated.png)

[[[generic-scratch3-add-variable]]]

আপনি কিভাবে আপনার নতুন পরিবর্তনশীল প্রদর্শন করা হয় পরিবর্তন করে আপনার টাইমার জন্য একটি চেহারা চয়ন করতে পারেন।

\--- /কাজ \---

\--- কাজ \---

এখন আপনার স্টেজে কোড ব্লক যোগ করুন যাতে নৌকাটি দ্বীপে পৌঁছা পর্যন্ত টাইমার সংখ্যা বেড়ে যায়।

\--- hints \--- \--- hint \---

On the Stage, `when the green flag is clicked`{:class="block3control"}, `set the time to 0`{:class="block3variables"}. Inside your `forever`{:class="block3control"} loop, you'll need to first `wait 0.1 secs`{:class="block3control"}, then `change the time by 0.1`{:class="block3variables"}.

\--- /hint \--- \--- hint \---

Here are the code blocks you'll need:

![stage](images/stage.png)

```blocks3
পরিবর্তন [সময় V] দ্বারা (0.1)

যখন ফ্ল্যাগ

চিরকালের জন্য ক্লিক করে
শেষ

অপেক্ষা (0.1) সেকেন্ড

সেট [সময় v] থেকে [0]
```

\--- /hint \--- \--- hint \---

Here's what your new code should look like:

![stage](images/stage.png)

```blocks3
যখন পতাকাটি
সেট [সময় v] থেকে [0]
পর্যন্ত ক্লিক করে
অপেক্ষা করুন (0.1) সেকেন্ড
পরিবর্তন [সময় v] দ্বারা (0.1)
শেষ
```

\--- /hint \--- \--- /hints \---

\--- /task \---

\--- task \---

Test out your game and see how quickly you can get the boat to the island!

![screenshot](images/boat-variable-test.png)

\--- /task \---