# Github Docs Example to Write Good Documentation!
## Step 1- Using Codeblocks

Codeblocks in markdown make it *very easy* for a __Cloud Engineer__ to share with other devs. 
It allows others to code/paste to replicate the code

```python

def thank_you_message(name):
    print(f"THANK YOU {name.upper()}!!")

thank_you_message("Andrew Brown")
```

Do not get confused! A code block needs 3 back ticks at the beginning and the end. __Do NOT use qoutation marks!__

When should we use Syntax highlighting? Let's add it for Python above so that it adds an ease of readability.

Remember adding images to the Hackbright project? It's not too hard!
![image](https://github.com/ameliasheppy/gituhb-docs-example/assets/98853049/c34b716e-a19a-4e41-b89d-ee6a303bf6c3)

##Traceback Errors:
```python
def divide(a, b):
    return a / b

result = divide(5, 0)
print(result)
```

```bash
$ python example.py
Traceback (most recent call last):
  File "example.py", line 4, in <module>
    result = divide(5, 0)
  File "example.py", line 2, in divide
    return a / b
ZeroDivisionError: division by zero
```

>Use code blocks for code AND errors.
  
## Use GFM Task Lists 
From my internships, we worked with lists that we could check off. Here is how to make them!

-[x] Finish Step 1
-[ ] Finish Step 2
-[ ] Finish Step 3


Lets make some emoji tables:
(Notice that to show the short code, we add some fencing on to the code)
|Name | Shortcode | Emoji |
| --- | --- | --- | 
| Clouds | `:cloud:` | :cloud: |
| Favorite Weather! | `:cloud_with_snow:` | :cloud_with_snow: |

Do NOT paste screenshots from a phone. Take a screenshot of your screen with the correct way for your computer. Or use a code block as defined above.



## References:
-[Github Flavored Markdown ](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>1</sup>

-[Emojis in GFM] (https://roachhd.gitbooks.io/master-markdown/content/cheatsheets/github.html) <sup>2</>


