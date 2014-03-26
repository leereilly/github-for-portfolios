---
layout: lesson
title: "Lesson 2. Create and Deploy a Github Page"
---


## About Github Pages

<section class="row">
<div class="col-sm-6">
In the previous lesson, we created a README.md file, and Github turned it into a webpage, _technically_. And it's just a quickie-homepage for our repo, with a URL that looks like just some normal file (which, well, it is...):

`https://github.com/your_username/your_username.github.io/README.md`


But we want a "real" homepage, which, at the very least, has a URL that _looks_ like a proper


According to the [Github Pages documentation](//pages.github.com), if you
visit `your_username.github.io`, you

To the __right__ of the repo name is a little __paper-plus icon__. Click on it to create a new file.
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/github-create-new-file.png)
</div>
</section>



## Create index.html

<section class="row">
<div class="col-sm-6">
According to the [Github Pages documentation](//pages.github.com), if you
visit `your_username.github.io`, you

To the __right__ of the repo name is a little __paper-plus icon__. Click on it to create a new file.
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/github-create-new-file.png)
</div>
</section>


<section class="row">
<div class="col-sm-6">
Go back to your repository homepage, e.g. your_account_name.github.io

To the __right__ of the repo name is a little __paper-plus icon__. Click on it to create a new file.
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/github-create-new-file.png)
</div>
</section>


<section class="row">
<div class="col-sm-6">
This will take you to the Github file editor. This time, you'll have to specify a filename.

Name your filename: `index.html`

Then type in some __plain-text__ nonsense, like: `Hello world this is my portfolio homepage!`
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/github-create-new-index.html-helloworld.png)
</div>
</section>


<section class="row">
<div class="col-sm-6">
TK
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/github-hello-new-index.html-post-create.png)
</div>
</section>





<section class="row">
<div class="col-sm-6">
Commit the file. You can add a __commit message__ if you wish.

Your repo file listing should now contain two files:

- `README.md`
- `index.html`

And the repo page that consists of the README file should be unchanged because you didn't touch the `README.md`
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/github-create-new-index.html-commit.png)
</div>
</section>


<section class="row">
<div class="col-sm-6">

- `README.md`
- `index.html`

And the repo page that consists of the README file should be unchanged because you didn't touch the `README.md`
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/github-create-new-index.html-commit.png)
</div>
</section>






<section class="row">
<div class="col-sm-6">
So what changed? Believe it or not, _you've published your own webpage_.

As per the Github Pages convention, your new webpage exists at: 

`https://your_username.github.io`

And if you visit that address, you should see a very unimpressive page.
</div>
<div class="col-sm-6">

Behold, your new webpage:

![howto]({{ site.baseurl }}/images/lessons/)
</div>
</section>



## Web Publishing 101

If you've ever written a webpage from scratch, i.e. from the `<html>` to the closing `</body>` tag, you might already know the concepts (and can skip ahead). But if your Web publishing experience has been confined to posting in an "update status" box, or through your company's content-management system, or even on your own WordPress/Tumblr, then what you've just done with Github Pages __should seem very underwhelming__.

And that's OK. It's underwhelming because Github Pages merely took the simple text you wrote:

    hello world TK

And put it on a public web server. Check out the source of the page with your browser's View Source (which you can access by Right Clicking on the page TK:

![TK IMG](TKIMG)

Unlike the social networks and blogging software you may have used, Github basically did nothing. It didn't publish your page, so much as it just dropped it somewhere on the Internet.

If you want a properly published page, then you're going to have to write some actual code yourself, do some extra work.

So why even use Github Pages, especially if you have no intention of becoming a web developer? Good question, and one I answered in the AboutTK.

The tradeoff for extra work on our part is total freedom in publishing, which, if your intent was to make a special portfolio page for yourself, is something that you _think_ you want.

To see what I mean by "freedom", go to your favorite Wikipedia page. Here's the one for GIF:

http://TK


Now __view the source__; what you should see should be _text_, but the jumble of code that defines not just the content but the positioning and arrangement, i.e. the HTML.

Now highlight and _copy the entire thing_

And Go back to your portfolio repo and __create a new file__. You can call it something like `gif.html`

And then just paste the _entire HTML source_ of the Wikipedia page into the Github file editor. That's right, the whole thing, because Wikipedia says you can.

Commit the file and now go to the applicable address:

username.github.io/gif.html

Github Pages, again, just puts the file, as is, onto the Internet. Your page at the given address now looks like a carbon-copy of Wikipedia's entry.


If it isn't clear how different this is than publishing through a web service, you can test it out on your own blog. Here's me pasting the contents of that page into a Wordpress blogpost:


Wordpress is designed to handle posts, articles, not entire webpages.



------------



## Edit the index.html

So let's end the lesson with a proper webpage at index.html. You can just copy the html below and add your own text. Below is the code for a very bare webpage, with a couple of headlines, a cat photo, and an embedded YouTube video:


















It doesn't seem like much, but this is quite a bit different than what you've done before.

<section class="row">
<div class="col-sm-6">
lorem ipsum
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/)
</div>
</section>





<section class="row">
<div class="col-sm-6">
lorem ipsum
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/)
</div>
</section>








## Auto-generate index.html and template


### Introduction to Markdown



## Change up the template



## Manually edit the HTML



## Create index.html




Add some text



Add a commit message if you want

![howto]({{ site.baseurl }}/images/lessons/github-create-new-index.html-commit.png)


Look at the non cool webpage 

    TK



Revise the index.html

![howto]({{ site.baseurl }}/images/lessons/github-revise-index.html.png)


Show the index html

![howto]({{ site.baseurl }}/images/lessons/github-show-revised-index.html.png)



Show the source








<section class="row">
<div class="col-sm-6">
lorem ipsum
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/)
</div>
</section>



<section class="row">
<div class="col-sm-6">
lorem ipsum
</div>
<div class="col-sm-6">
![howto]({{ site.baseurl }}/images/lessons/)
</div>
</section>