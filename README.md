Blog
  title
  category

Post
  title
  author
  body: text
  
Blog has many post
post belongs to a blog

      index
        |
        app (nav routes )
        |
  home   about  Blogs(HOC)  noMatch
                  /\
        BlogForm    BlogList
                        blog
                BlogForm    Posts (HOC)
                        PostForm    Post List
                                     Post
                                  PostForm
