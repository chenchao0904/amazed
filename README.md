# amazed
hashmap hashtable   传播机制
   跨域问题来自于浏览器同源策略的限制，包括DOM同源限制和ajax同源限制，本文探讨的是ajax跨域。ajax跨域指的是一个页面的ajax只能请求和当前页面同源的数据，如果发现请求到的数据不符合要求，浏览器就会阻止返回的数据。所谓同源，指的是协议、域名、端口号都必须完全相同（同一ip的不同域名也是跨域）。同源策略的主要目的是防止csrf攻击，它可以有效地避免由于恶意攻击带来的危险，浏览器器同源策略使得网络访问更加安全。

        但是，实际开发与生产中，常常获取使用来自其他站点的资源，这时候就需要发起跨域请求，这时候就需要使用特殊的方法来处理，使得我们能够获得想要的数据。

        由此可知，跨域仅限于浏览器中，是由于浏览器对不同源数据的拦截产生的，跨域有时候是不可避免的，我们需要采取措施实现跨域请求
