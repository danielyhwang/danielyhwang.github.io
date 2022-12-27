---
layout: post
title: Birth of a Blog!
date: 2022-12-27 4:00:00-0400
description: the first post on this new website!
tags: formatting personal-update #TODO
categories: sample-posts external-services #TODO
giscus_comments: true
#you can also do redirect: some other place
---
This post marks the opening of my blog titled "Notes of a Graduate Student"! It is also the same name I gave to a series of journals, currently sitting at my desk, detailing my thoughts as a graduate student from "How could I have taught this class differently?" to "Oh god my midterm score just came out." I do not have a set plan for this blog but I did want to set it up over winter break. It does look nice. It's also funny that I basically am spending winter break replacing the website I just made via [sites.gatech.edu](https://sites.gatech.edu), but I think using this template will have more benefits than my sites.gatech.edu website. I can even do $$\LaTeX$$ in it!

\begin{equation} 
\label{eq:cutemessages}
\text{you} = \text{cutie} 
\end{equation}

and write some code:

{% highlight java linenos %}

public static void main(String[] args){
    %Code taken from https://www.programiz.com/java-programming/basic-input-output
    Scanner input = new Scanner(System.in);
    	
    System.out.print("Enter an integer: ");
    int number = input.nextInt();
    System.out.println("You entered " + number);

    // closing the scanner object
    input.close();
}

{% endhighlight %}

Not that I think I'm going to do code anytime soon... I am experienced in coding in Java and JavaScript, but I am taking time to focus on academic duties. I would like to do coding on the side if I get the chance.

Here are some images. The left one is zoomable, the right one is not.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/9.jpg" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/7.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A simple, elegant caption looks good between image rows, after each row, or doesn't have to be there at all.
</div>

Here's a quote that is completely unrelated to this blog but is helping me manage my pandemic-induced anxiety (and I try to think about when I get overwhelmed).
<blockquote>
    We suffer more often in imagination than in reality.
    —Seneca
</blockquote>

Finally, this blog post was meant as a writing exercise on how to blog - al-folio left a bunch of example posts and this post was a way for me to create a concise demo of al-folio posts so I'll be prepared to use them in the future.

<!-- Note to self: Look at 2018-12-22-distill.md (invisible) for an idea on how to write an academic blog. You could write a blog-post on chipfiring. Mainly it talks about different formatting (and plots/figures) and how to include citations.-->