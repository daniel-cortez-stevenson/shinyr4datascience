# shinyr4datascience

### Usage

1. Place your Shiny app in the ./shiny-server/app directory

* Build/Run from Docker Hub
<pre>docker run -v "`pwd`/shiny-server/":/srv/shiny-server/:ro \
        -name shiny \
        -p 3838:3838 \
        danielstevenson/shinyr4datascience:latest
</pre>
* Find your app at http://localhost:3838
