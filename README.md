# Web Development Concepts Explained
Here we will write the data that will be explained and build to be as minimal web reference. I will leave react and its pain aside.
___

## DOM And jQuery 
I would start with this becuase they are really one of the most important fundmatals. 
```
<html> 
	<body>
      <h1> Hello World </h1>
    </body>
</html>
```

The above code is a very HTML code snippet.
`DOM` is stands for Document Object Model. 
Assuming that you know the basics of jQuery.
`$('h1')` this will go through the DOM tree trying to find the element. Yes it is called tree becuase the html tag has one childe which is body and body has one childe which is h1 tag.

``<html> -> <body> -> <h1>``
this is the tree of the html or Document Object Model.

Is it clear?
 - Yes, I know this already
 - good, I will go through the others in a moment.

### jQuery 
As you mentioned in your document it has too many benifets. It is one of the most important 
libraries. 
____
As we said ysetrady the web application has 3 diffrent concpets or methodologies to work on.
- Classic web apps 
- jQuery based / MVC 
- RESTful APIs

![Web app archtectures](https://blog.octo.com/wp-content/uploads/2014/03/web-application-models-over-time.png")[take a deep look at this figure]


I will go through the RESTful APIs and explain it as I can go :)     

# RESTful APIs 
Based on Representational state (as you mentioned 😅)
But before we go to the RESTful API let's go through the api alone Watch this video:
https://www.youtube.com/watch?v=s7wmiS2mSXY

api (application programming interface )
has many types (classification ) such as:
web services which is a SOAP, XML-RPC, JSON-RPC, REST.

* api generally its allows softwares to communicate with each other.

____


A good case study, I remember there is something called *legacy code issues*. Where you have a code that written in a very old langauge like: Copol, ada, ALGOL... etc. 

What you'd do to interact with this old application(legacy code)?

One good solution is to build an API between this old app(which you can not re-wrtie it again from scratch) and our new application.


So, let's assume there is an old app called `x` it calculates the rate of oil price. And we need to get the rate of the oil price to be used in our applicatin. 

Basically, we would ask `x` to give us this data and we will continue the work in the new app which is called `y`.

the request would be just like this:
``
http://x.com/oil/price/today
``

Assuming the link of `x` app is as mentioned above. and the end point is `oil/price/today`.
What if we want the average price of the oil per month? Simply we would write an `endpoint` that gives us this specific data. E.g: `oil/price/month/[The_needed_Month]`

**Pop quiz: 📖** Where the code of the above endpoint will be written? And in which language will be written? if our `x` is running on `Algol`, and our `y` app is running on `Golang`?

**Answer: 📝**














































