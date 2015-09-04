---
layout: post
title:  "test github blog!"
date:   2015-09-02 20:49:32
categories: test
---

test github blog


`c`

{% highlight c %}

#define ABC 1
#include <stdio.h>

void main()
{
  int i = 1;
  printf("hello world!");
}

{% endhighlight %}


`cpp`

{% highlight cpp %}

#define ABC 1
#include <stdio.h>

void main()
{
  int i = 1;
  printf("hello world!");
}

{% endhighlight %}


try this at `console`

{% highlight console %}

ls

ps

whoami

{% endhighlight %}


`cmake`

{% highlight cmake %}

cmake_minimum_required(VERSION 2.8)
project( Test )
find_package( OpenCV REQUIRED )

add_executable( Test test_main.cpp )
target_link_libraries( Test ${OpenCV_LIBS} )

{% endhighlight %}


Check out [www.github.com/sshuh][sshuh].

Check out [sshuh.github.io][blog].

[sshuh]: http://www.github.com/sshuh

[blog]: http://sshuh.github.io
