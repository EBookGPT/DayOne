# Chapter 2: What is Day One?

*As I sat down with my quill to write about Day One, I knew I needed to answer one fundamental question: what is Day One, and why is it important?*

To help us understand the significance of Day One, we invited a special guest to this chapter, Jeff Bezos, the founder of Amazon. In a 2016 letter to shareholders, Jeff explained, "Day One is shorthand for the approach we take to everything, and it's the way that Amazon has stayed vibrant for more than two decades." 

In essence, Day One is about never becoming complacent or content with your achievements. Even though Amazon has grown into one of the world's largest corporations, Jeff still operates the company with the mindset of a startup. He believes that staying true to Day One will help Amazon continue to innovate and delight customers for years to come.

So what does all of this have to do with software engineering? In the context of code, Day One is about constantly learning and improving your craft. It's about writing code that is maintainable, scalable, and adaptable—code that can evolve and grow with the changing needs of your users.

To get started with Day One programming, let's take a look at some code examples:

```python
# This is a simple Python function that adds two numbers together
def add_numbers(x, y):
    return x + y
```

This code works fine for adding two integers or floats together, but what if we wanted to add two lists instead? Instead of writing a new function, we could modify the existing one to accept any iterable data type:

```python
# This is an improved version of our add_numbers function that accepts any iterable data type
from collections.abc import Iterable

def add_numbers(x, y):
    if isinstance(x, Iterable) and isinstance(y, Iterable):
        return [a + b for a, b in zip(x, y)]
    else:
        return x + y
```

By making this small change, we've made our code more flexible and adaptable. This is Day One thinking in action—it's about being open to new ideas and constantly striving to improve.

In the next chapter, we'll explore some of the practical applications of Day One thinking, including continuous integration and delivery. Stay tuned!
# Chapter 2: What is Day One? - A Greek Mythology Epic

*In the land of West Africa, there was a great tribe known as the Igbo. They were known for their ingenuity and resourcefulness, and they were always seeking new ways to improve their way of life.*

One day, a young Igbo warrior named Nkem stumbled upon a wise old man in the bush, who introduced himself as Jeff Bezos, the founder of Amazon. Intrigued, Nkem asked the wise man what he could teach him about the art of warfare.

"War, young warrior, is not about brute force and strength alone," Jeff replied. "It is about strategy, ingenuity, and always seeking to stay one step ahead of your adversary. I challenge you to adopt a Day One mindset, to approach each day as if it were your first, and always be willing to learn, adapt, and improve."

Nkem was intrigued by Jeff's words, and he set out to apply the Day One mindset to his battles. He sought out new techniques, learned from his mistakes, and constantly innovated in his craft.

As a result, Nkem became one of the greatest warriors in all of West Africa. His enemies could never predict his next move, and he always seemed to have the upper hand in battle.

When he was asked how he did it, Nkem replied, "I owe it all to the wisdom of a great man named Jeff Bezos, who taught me the importance of a Day One mindset. By always being willing to learn and improve, I have become more than I ever thought possible."

And so, the legend of Nkem and Jeff Bezos was born. From that day forward, the Igbo people embraced the Day One mindset, constantly seeking to improve and innovate in all aspects of their lives.

In the world of software engineering, the Day One mindset is just as important. By always being open to new ideas, staying curious, and learning from failure, we can create software that is truly innovative and impactful. As Jeff Bezos once said, "If you're not stubborn, you'll give up on experiments too soon. And if you're not flexible, you'll pound your head against the wall and you won't see a different solution to a problem you're trying to solve."
In the Greek Mythology epic for Chapter 2, we learned about Nkem, a young Igbo warrior who adopts the Day One mindset and becomes one of the greatest warriors in all of West Africa. This mindset emphasizes continuous learning, innovation, and improvement, which are all key tenets of software engineering as well.

To illustrate this concept in code, we provided two examples of a Python function that adds two numbers together. The first example is a simple function that works for adding two integers or floats together:

```python
def add_numbers(x, y):
    return x + y
```

However, what if we wanted to add two lists together? This is where the Day One mindset comes in. Instead of creating a completely new function, we can modify our existing function to make it more flexible and adaptable:

```python
from collections.abc import Iterable

def add_numbers(x, y):
    if isinstance(x, Iterable) and isinstance(y, Iterable):
        return [a + b for a, b in zip(x, y)]
    else:
        return x + y
```

This updated function uses the built-in `isinstance()` method to check if both `x` and `y` are iterable, and if so, zips them together to produce a new list. If not, it simply returns the sum of the two numbers.

By making this small change to our function, we've made it much more versatile and capable of handling a wider range of input types. This is exactly the type of adaptable and flexible code that exemplifies the Day One mindset.

In software engineering, the Day One mindset is all about continuous integration and improvement. We should always strive to learn new techniques, challenge our assumptions, and look for ways to innovate and improve the software we build. By doing so, we can create software that truly meets the needs of our users and delivers value to our customers.


[Next Chapter](03_Chapter03.md)