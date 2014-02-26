#ivan the terribles blog (performance improvements)
* Using [multi_fetch_fragments](https://github.com/n8/multi_fetch_fragments) to cache partial rendering which drastically improved load performance.

* Implimented eager loading to reduce queries.

#How to Run

  rake db:setup
  rake load:blog
  rails s

#Load Impact Results
Full 10mb slug of 100 posts with 100 comments per post and

![example](http://f.cl.ly/items/431U3i0h2G341i1C3w45/load-impack-10x-px-dynos.png)


##[MIT License](http://johnjensen.mit-license.org)
