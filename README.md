TechSavvy API
=============

The TechSavvy API is simple, free, and open. <br/>
Response formats can be either <b>JSON</b> or <b>JSONP</b>. <br/>
For now there are <b>NO</b> rate limits. <br/>

<h1>GET /jobs/{search}/{format}</h1>
<h3>{format} is optional and defaults to JSON</h3>
<h3>{search} is required and should be URL encoded</h3>

<h1>Parameters</h1>
<ul>
<li>limit - The number of results to return</li>
<li>callback - Required for JSONP responses</li>
</ul>

<h1>Examples</h1>
<ul>
<li>http://api.techsavvy.io/jobs/javascript+san+francisco</li>
<li>http://api.techsavvy.io/jobs/javascript/jsonp?limit=200&callback=mySuperNeatCallback</li>
</ul>