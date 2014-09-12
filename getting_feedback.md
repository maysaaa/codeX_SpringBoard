#Getting feedback

At this stage you should have a pretty decent blog and you should be able to blog to your hearts content. 
But you are leaving your audience in the dark, they are now way they can edit comments to your blog.

We are taking the side wheels here for a bit, if you tip over its no shame.

## Thinking it through

You will need to extend the back end and add some RESTfull HTTP Services

Desciption    | URL         | Http Verb
--------------|-------------|----------
Get all comments for a post | api.projectcodex.co/blog/<user_name>/post/<post_id>/comments | GET
Create a new comment for a post | api.projectcodex.co/blog/<user_name>/post/<post_id>/comments | POST

Ok so go and get the back end code from github at: ```http://www.github.com/...```

We will need to find a place to store comments and we will need to link this to the appropriate blog post.

You will need to change 


## Acceptance Criteria:
* Users can add comments to your blog
* At least one user have commented on a post of yours
* You have blogged about this using #builtbycodex
