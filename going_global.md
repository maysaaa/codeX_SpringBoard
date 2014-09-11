#Going global

At this stage you might want to look into HTML POST and GET requests - there’s more where these two are coming from this but those two will serve you well for now.

Some people at codeX had foresight and created an REST API (yes go and google!)  for your blog posts - this will help you a lot to store and share your blog posts with the world.

There are 3 parts to the API:

Get all posts:
Http GET : api.projectcodex.co/blog/<user_name>

Get a specific blog post:
Http GET: api.projectcodex.co/blog/<user_name>/post/<post_id>

Create a new entry for a specific user:
Http POST:  api.projectcodex.co/blog/<user_name>/post

This will help you to store your posts online - go and try it out by opening this URL in a browser: api.projectcodex.co/blog/andre

Tip: at this stage JQuery Ajax support will serve you well. Go and speak to google and your fellow codeXers about his. Ajax is not a wash powder brand or a football club by the way.

Change your blog to display all the blog posts from this URL: on its home page. api.projectcodex.co/blog/andre

Now using your newly found Ajax knowledge start creating blog posts under your own name using this url:

api.projectcodex.co/blog/<user_name>/post

Remember to put your name in the place of <user_name>

Once you created a few blog posts look at them using this URL:

api.projectcodex.co/blog/<user_name>

Change your blog now to display your own blog posts.

Use the this url to look at a specific blog post: 
api.projectcodex.co/blog/<user_name>/post/<post_id>
