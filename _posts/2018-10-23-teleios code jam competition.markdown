---
layout: post
title:  "Teleios Code Jam Competition"
date:   2018-10-13 19:10:37 -0400
categories: jekyll update
---

<center><img src="/assets/teleios.jpg" width="300" height="300"></center>

Today my colleague [Omari Lawrence](https://github.com/OmariLawrence) and I participated in the [Teleios Code Jam](https://www.teleioscodejam.com/) Competition located at the DCIT Conference Room at UWI St.Augustine. 

We had five(5) problems to solve in an hour, and we solved all of them with time to spare. One such problem is:

"Given a case-sensitive word of only letters, find the sum of its ASCII values."

This is our solution to this problem in python:
{% highlight ruby %}
def sumOfCharacter(word):
  count = 0 
  for i in word:
    count+=ord(i)
  return count

print(sumOfCharacter('Character'))
print(sumOfCharacter('characters'))
print(sumOfCharacter('Worcestershire'))
{% endhighlight %}