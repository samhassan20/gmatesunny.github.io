A beginner's guide to jekyll by Roshan.

Website for Samreen Hassan:

1. Install jekyll: https://jekyllrb.com/docs/installation/
2. Clone this website:  git clone https://github.com/samhassan20/samhassan20.github.io.git
3. Add jekyll path to system path and for easy edit, install vs code [https://code.visualstudio.com/] as it will make your life easier.
4. edit all *.yml [/samhassan20.github.io/_data/] file according to your needs, remember not to touch html files. They are auto generated. 
5. To change the design or color, edit samhassan20.github.io/_site/css/main.css
6. To add a blog see _drafts directory for sample but basically you need to add your posts in _posts directory. The formatting over there is same as this [https://help.github.com/articles/basic-writing-and-formatting-syntax/] but you can also mix html formatting in there. You place your pictures at /samhassan20.github.io/img/blog_img, check for height-width of the image if it doesn't look good. 
7. Do all your local changes and in terminal/cmd prompt, do jekyll serve to check it locally in browser and once you are confirm with your changes, then commit and push to github.
[
    git add --all
    git commit -m "your message"
    git push
]

Bonus Tip: When you website is running on browser, you can do ctrl+shift+i to see the elements and then change the elements of the css file.