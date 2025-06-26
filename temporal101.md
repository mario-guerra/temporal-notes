# Notes on my experience with Temporal 101 Python training

The video intro led me to believe this would be a video walkthrough, so I was surprised to find out it's all a self-contained GiHub project. Not necessarily a bad thing, just a misalignment of expectations vs implementation. Might be user error on my end.

Some minor nits:
- The README says "make sure to run <temporal server command>..." but as far as I can tell that was already done for me when I launched the Codespace.
- Suggest launching the "preview" option for the README to improve readability.

## Exercise 1: Hello Workflow

- Where is the `practice` directory? Where is the `solution` directory? 
I had to hunt for them, two levels deep under `exercises\hello-workflow]`. The path should be added to reduce cognitive load, we want devs focused on the actual learning rather than path hunting.
- Command for python virtual environment using `env` as path, but the setup script used `.env`. These should be consistent, again to avoid extra cognitive load.
- maybe install a plugin that enables copying of code blocks to make it easier to copy/paste the commands to be run.

### Part B
- "Review the input parameters, business logic, and return value". There's not much here, what am I supposed to take from this? What does "review" mean in this context? What constitutes the business logic, is it just the "Hello {name}!" portion of the code? 

### Part C
- Okay, there's stuff in the worker.py file, but no explanation for any of it. Am I expected to already understand this code? If so, how, why, and where? Can I change the `default` namespace? I already know I can't because it causing a failure, but I don't know why.

### Part E
- Open a termanal in _which_ environment? The root of the project or in the `exercises\hello-workflow\practice\` folder?
- Why is the rest optional? At this point I've run some stuff but I'm no closer to understanding how any of it works than I was before starting.
What happened??

### Part F

I ran the command and I see output, but there's no explanation of what I'm looking at so it's not super informative.





