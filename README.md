# Claude Skills

This is a library of my Claude skills I've made to help me in various ways. Below is an explanation of each category and sub category so that you can have a good understanding of each skill before you use it.

## Learning
The learning skills use re-enforcement learning. They don't hold your hand through everything and **are not** intended to be used as your main source of learning but rather a supplimental resource to use along with your main material. It will explain concepts to you briefly and then follow it up with questions until you are consistently getting answers right.

### Programming
Programming skills can assist with learning new programming languages and concepts. Inform it what you're learning, where you are and what material you're using (see the below example) and it will tailor a tutor experience to your current knowledge including questions for code review, fixing broken code and writing code yourself

## Examples

### Programming language
**Correct Prompt:**
```
user: I'm learning rust with rustlings and I'm on primitive types but I'm having a hard time understanding tuples and arrays. Can you help me with learning this concept?
```

**Incorrect Prompt:**
```
user: Can you teach me how to code in rust?
```

**Incorrect Prompt:**
```
user: I'm larning rust, can you help me understand primitive types?
```
While this one is not bad, it will ask more clarifying questions such as narrow down which primitive types you need help with and what study material you are using.

## Contributing
If you notice any issues with the skills in this library, please feel free to let me know in a github issue and I will work to fix it.

If you have a skill that you would like to contribute for the community, please feel free to open a pull request with your skill. I will review and test it and verify it's working and if I believe it could be useful to people, I will add it to the library. If you're doing this, however, please include what your skill does, how it help, the problem it solves, whether you have tested it or not aswell as some examples similar to the ones I provided above.
