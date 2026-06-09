---
layout: essay
type: essay
title: "Asking Smart Questions about Technology - Stack Overflow"
# All dates must be YYYY-MM-DD format!
date: 2026-06-08
published: true
labels:
  - Stack Overflow
---

## Technology Issues - The History

While my dad is very technologically savvy, given his age, the rest of my family members and even some of my friends are significantly less so. Many people have come up and asked me things like “Kelly, the mail app won’t let me open any of my emails,” or “Kelly, the printer in the math lounge isn’t working, can you please fix it?” So, at least around general technological things that don’t involve code so much, I’m very used to doing research on the internet to try and fix things. My dad taught me the importance of doing research, just in general. As the times change, so do the methods, but the internet is a very important tool, and so it’s important to know how to use it effectively for anything.

Today I read the article “How To Ask Questions The Smart Way,” written by Eric Steven Raymond, and I thought it contained a lot of good advice, as well as important tips for new beginners who want to enter these worlds and are seeking help but don’t know the proper way to communicate. It’s advice that I’ve given my friends, so that they have a backbone to solve their technology problems in the future. Specifically, to use key words in the internet search (like the make, model, and OS version) and to post the specific error code given, when applicable. If they have to email someone else, I tell them to attach pictures of the error message, status and stats of the device, if applicable (things like when it was last turned on, when it was last active, etc.), and to try and tell them about a possible solution.

For example, one time the printer in the Math Undergraduate Lounge wasn’t working. Once I eliminated any hardware malfunctions (like jammed paper or missing ink cartridge), checking on the computer showed that a reboot would require an administrative password, as the printer had somehow disconnected from the network. Once I knew the person to email, I gave them the problem, as well as the potential solution in a relatively concise manner and attached images of the status paper showing when the printer last did a job (a few days ago), as well as showing that the printer had been disconnected with an administrator password requirement. After that day, more people were willing to learn about my thought process. While I solved the problem the first time, I gave the other students important steps to follow so that they could solve it themselves even if I wasn’t there. Once I told them, they were able to solve most of the problems themselves, like a paper jam here and there, sometimes a disconnected cable, etc. 

> "Give a Man a Fish, and You Feed Him for a Day. Teach a Man To Fish, and You Feed Him for a Lifetime."
> - Anne Isabella Thackeray Ritchie

I have used Stack Overflow quite frequently to fix my own coding problems within projects, mostly by reading other users’ questions and the associated responses. However, I imagine as coding will become more difficult for me in the future, knowing how to ask a question, especially on a site as well-known as Stack Overflow, is an important skill for my career. I learned a lot of new things from this reading, specifically that there is a sweet spot between being concise and showing that you’ve tried to fix the problem already. I also thought that at least for software issues, the specifics on how to make a good title were interesting. Although I didn’t know about this method, I generally agree with the practices. If I were on the other side helping someone with a question, I would much prefer the smart title, as it’s concise and gets to the point. As a result, I’ve looked at some examples of Stack Overflow pages that follow, or don’t follow, the Smart Way of asking questions.

<img class="img-fluid" src="../img/E11/stackoverflow.png">

## Starting with the Bad

### i am new to c and not sure if i am using the right approach
Here is a link to the article [new-to-c](https://stackoverflow.com/questions/79954385/i-am-new-to-c-and-not-sure-if-i-am-using-the-right-apporach).

Beyond their title being not clear at all, this question talks about a structure that they are trying to build within C. The English in this post is quite broken. Separating things into more sentences would have helped, I think. Adding more clarity would have also helped. They say that they want to “write it into the buffer of bitwr_t: w->buf[7-bi%8]=thebit;”. What is the thing that they want to write into the buffer? I think that they say that they attempted using memcpy, but that it didn’t work because they wanted to specify the position. However, I only gleaned this information after reading it a few times, which I shouldn’t have to do if I want to answer a question. The post was taken down on account of the question not having enough details in it to be answered.

### Why is Java math not working as it should?
Here is a link to the article [math-not-working](https://stackoverflow.com/questions/79954296/why-is-java-math-not-working-as-it-should).

Firstly, their title doesn’t make sense, essentially implying that the math of a program doesn’t work, when it’s their code that doesn’t work. Their program contains a number of buttons and labels with certain values that are being assigned. One variable “Strike Damage” doesn’t update past 6, despite “Strength” and “Dexterity” increasing. While I think it’s not necessarily a terrible question, and at least the English is better, the code blurb that is given can’t run on its own. While many people do reply to the post, many ask for enough code so that they can run it on their own device. One person tries to post code fixes in the edits, which is confusing to read, but then the user ungratefully asks them to post it again in a better format. Many users also take note of the title and rightfully tell the poster that Java is a language that has been used for many years, and as a result if the math was truly off within the program, they would have noticed a long time ago. Most people eventually get fed up of trying to help the user, and the post is closed due to not having enough information on debugging.

## Ending with the Good

### All logs and auditing for storage account into event hubs using bicep
Here is a link to the article [logs-and-auditing](https://stackoverflow.com/questions/79954216/all-logs-and-auditing-for-storage-account-into-event-hubs-using-bicep).

Their title is clean, as well as their question being concise and precise. They also state that while they did manage to find an article that has information, it doesn’t clarify whether it can work for a storage account and that it’s related to key vault. It’s clear that the user here is striving more for precision by being so concise. Every detail is important and contributes to the post, as well as showing that they have put effort into finding a solution. Someone replied stating that it’s a resource type extension, provided a link as well as details for what this means, and provided a bit of sample code below. While the original poster hasn’t responded yet, it looks like this response can at least lead them in a direction to getting a more useful answer.

### What happens when JVM can't allocate native heap (e.g. malloc() fails)?
Here is a link to the article [malloc()-fails](https://stackoverflow.com/questions/79954293/what-happens-when-jvm-cant-allocate-native-heap-e-g-malloc-fails).

While this post has a lot more content in it, the user essentially asks this question in order to understand the workings of JVM and what happens if the scenario described above does occur. They essentially ask questions about when a malloc could fail and under what circumstances it may happen. They pose their own guess within the post and also clarify that they couldn’t find any language specific to the question they were asking about, presumably from their research. In the last sentence, they also clarify specifically what their question is about and why they’re asking it. There are many replies in the comments, some of which go back and forth, with the main poster replying. The main poster asks important questions about the content of the reply and also some follow up questions. I think at least they got some useful answers, or at least have been pointed in a direction for more material to look up.

## The Takeaway

Overall, while I did learn a lot specifically within forums and forum etiquette, a lot of this article enforced what I already know and practice when it comes to research on technological problems. It had a lot of the tips that I recommend to people in my daily life. I think it’s a very good read for people, not just those who are into programming, but also those who are learning how to interact with technology for the first time.
