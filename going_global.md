#Going global

At this stage you might want to look into HTML POST and GET requests, there’s more where these two are coming from this but those two will serve you well for now.

We built a REST API (yes go and google!)for your blog posts, this will help you a lot to store and share your blog posts with the world.

There are 3 parts to the API:


Desciption    | URL         | Http Verb
--------------|-------------|----------
Get all posts | api.projectcodex.co/blog/<user_name> | GET
Create a new entry for a specific user | api.projectcodex.co/blog/<user_name> | POST
Get a specific blog post | api.projectcodex.co/blog/<user_name> | GET

This will help you to store your posts online - go and try it out by opening this URL in a browser: 

http://api.projectcodex.co/blog/andre

> Tip: at this stage understanding more about JQuery Ajax support will serve you well. Go and speak to google and your fellow codeXers about his. Ajax is not a washing powder brand or a football club by the way. We are interested in GET and POST http verbs

Now start using your newly found Ajax knowledge.

Change your blogs home page to display all the blog posts from this URL: http://api.projectcodex.co/blog/andre 

Start creating blog posts under your own name using this url:```http://api.projectcodex.co/blog/<user_name>/post```

> Remember to use your own name in the url above.

Once you created a few test blog posts look at them using this URL: ```http://api.projectcodex.co/blog/<user_name>```

> You might want to delete some of your test blog posts. Try to use the ```http://api.projectcodex.co/blog/<user_name>/post/<post_id>``` url with a DELETE http verb to delete entries. This part is totally optional at this stage. Talk to your mentor to help you to clean out your test blog posts alternatively.

Change your blog home page now to display your own blog posts.

Use the this url to look at a specific blog post: ```http://api.projectcodex.co/blog/<user_name>/post/<post_id>```

Publish your blog online.

Now to a triple back flip, be sure someones recording it and publish a blog entry on your new dynamic blog.

##Acceptance Criteria:
    * You can add entries to your blog using an HTML form and they are stored remotely
    * The dynamically created blog entries are listed on your blogs home and visible to others on the internet
    * Your blog entries are stored in the cloud somewhere
    * You've written a blog entry about REST and HTTP verbs
    * You tweeted your blog entry using the hashtag #builtbycodeX
