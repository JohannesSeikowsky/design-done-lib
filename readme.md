#### What does it do for me?
Design-done-lib provides a set of stylings and components that reduce the effort it takes to build a UI that doesn't suck to almost zero. The aim is not to be great, but to be pretty decent with almost no effort. It's meant for hackers, like myself, who don't like to spend much time and energy on interfaces, but who understand that presentation is important. A design-done-lib site: https://mynowpage.herokuapp.com.

#### How do I begin?
All stlyes are in the design-done.css.scss file above. You can download it, or just copy and paste the code. The code is kept as simple as possible in order to make adjusting it as painless as possible. I'm also planning to make it a ruby gem for easy use in Rails projects.

#### Any requirements?
Sass. The stylings use nesting, so sass is required. (or your favorite workaround)

#### 1-minute-use-guide
+ add code to project (download or copy and paste)
+ some styles are applied immediately as a result
+ wrap header in simple_header class: `<div class="simple_header"> ... </div>`
+ wrap elements of page in simple_container class: `<div class="simple_container"> ... </div>`
+ add header links within simple_header
+ add elements within simple_container 
+ be done with it

The only questions you have to answer are: what links go in the header? Which elements constitute the general page content and in which order? Optionally the styling are writte to be super-obvious to edit. If you want to do that, it's really not painful.


#### Inspiration
Full disclosure. The design-done-design is shamelessly stolen from http://yoshuawuyts.com/workshop-distributed-patterns
Knowing that I suck at UI design, I was looking for a UI to imitate pretty closely for my last Rails project. I stumbled upon this site and instictively loved its simplicity. Then it dawned on me that these styles could very simply be generalized and then be used in almost any project to generate a rather decent UI super duper quickly with almost no effort. Design-done-lib is the result.

**p.s** design-done-lib is ready for use, but it is also a work in progress. I will add (or substract) stuff as I use it in my own projects.

