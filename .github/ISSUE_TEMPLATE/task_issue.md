---
name: Task Issue
about: Describe the task and the context

---

**Context**
A clear and concise description of what the background is.
What is this task about and what problem does it solve.


**Task**
- [ ] 1. '...'
- [ ] 2. '...'


**Pseudo Code (optional)**
Optional: Describe the implementation, function or outcome as pseudo code. Keep it super simple (its a non working code, just for explaination)! 
e.g.: Write a function that takes in a path str and outputs processed image and the shape
```
def get_img(pathstr):
   img = load_from_full_path(Path(pathstr))
   img = preproc_image(img) # do RGB->BGR color conversion
   return img, img-shape
```
or: loop over a list and print content if the condition is met
```
for item in list:
    if conditon:
        print(content(item))
```


**Final goal of task/feature**
Outlook on what the task/feature will do and impact our product.


**Checklist for review**
Always keep in mind that the review is not there to fix your code or to finish your task. It's just there to ensure that the code is ready to merge and to point out things you can improve on for next time!

- [ ] Task (every sub-task) is fully done
- [ ] The usage (how to run) is fully documented in the readme.md \
   Exception: The task is part of the existing code, and the documentation is already in place
- [ ] The code is tested 
   - if there are dependency changes, the installation process is tested (reinstallation)
   - the code runs without any errors
   - the output is validated \
     e.g. output images should be viewed and judged, the type (str, np.array), shape (len(), shape()) and the content should be computed and compared with the expected output
