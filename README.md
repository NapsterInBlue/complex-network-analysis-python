## Complex Network Analysis in Python

This repo is my companion to [the book of the same name](https://smile.amazon.com/Complex-Network-Analysis-Python-Recognize/dp/1680502697?sa-no-redirect=1). At the time of writing, I'm uncertain how stable the `requirements.txt` is, for all of the book's code.

The book was written nearly 3 years ago and thus on Python `3.4.5` (I'm on `3.8.3`, at the moment), and much older versions of various packages. Most-notably-- and hence going through the trouble to make/share this repo-- `networkx==1.11`, which has since bumped a whole major version, making much of the book not 1-1 to what you'd experience if you ran `pip install networkx` and tried to get going.

Will try and update as I figure out what works/doesn't work, and if the book proves useful, my thoughts on upgrading the codebase to `2.X`.

### Setup

I'm reasonably certain that my `requirements.txt` file is going to be unstable/incompatible with any Python version != `3.8.3`, so follow at your own risk.

If you're still here, then simply create and activate a new virtual environment with `virtualenv` and run `pip install -r requirements.txt` to get all the dependencies you need (in addition to the setup steps outlined on page 7 and throughout the book!)