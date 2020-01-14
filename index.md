---
layout: default
---

<img class="profile-picture" src="{{site.baseurl}}/{{site.profile-picture}}">

​I am a Ph.D. student at the [Robotics Institute](https://www.ri.cmu.edu/), part of the [School of Computer Science]() at [Carnegie Mellon University](https://www.cmu.edu/), advised by Prof. [Ralph Hollis](http://www.cs.cmu.edu/afs/cs/user/rhollis/www/home.html) at the [Microdynamic Systems Laboratory (MSL)](http://www.msl.ri.cmu.edu). I work on whole-body optimal control for dynamic mobile manipulation. I use the CMU ballbot as my test platform for which I built a pair of 7DOF lightweight arms. 

I obtained my M.S. in Robotics at CMU advised by Prof. Koushil Sreenath. I obtained my B.S. in Mechanical Engineering and B.S. in Aerospace Engineering with minors in Mathematics and Multidisciplinary Design from the University of Michigan, Ann Arbor. 

<center> You can contact me at <a href="">rshum@cmu.edu</a></center>

<br/><br>

## Research
I am interested in the intersection of mechanical design of robots and optimal non-linear control to exploit the hardware to perform highly dynamic tasks.

<html>
	<table style="border:0px">
	    {% for post in site.posts %}
		    {% for category in post.categories %}
	          {% if category == 'research' %}
		        <tr>
		            <td style="padding:1%;width:25%;vertical-align:middle;min-width:120px">
		                <img class="project-image" src="{{site.baseurl}}/{{post.image}}"/>
		            </td>
		            <td class="post_test">
		                <h4>{{post.title}}</h4>
		                <br>
		                {{post.authors}}
		                <br>
		                <em>{{post.venue}}</em>, {{ post.date | date: "%Y"}}
		                <br>
			              {% if post.arxiv %}
			              <a href="{{post.arxiv}}">arxiv</a> /
			              {% endif %}
			              {% if post.pdf %}
			              <a href="{{post.pdf}}">pdf</a> /
			              {% endif %}
			              {% if post.video %}
			              <a href="{{post.video}}">video</a> /
			              {% endif %}
			              {% if post.code %}
			              <a href="{{post.code}}">code</a> /
			              {% endif %}
			              {% if post.poster %}
			              <a href="{{post.poster}}">poster</a> /
			              {% endif %}
			              {% if post.slides %}
			              <a href="{{post.slides}}">slides</a> /
			              {% endif %}
		                <p></p>
		                {{ post.excerpt }}
		            </td>
		        </tr>
	          {% endif %}
	    	{% endfor %}
	    {% endfor %}
	</table>
</html>


## Other projects

<html>
	<table style="border:0px">
	    {% for post in site.posts %}
		    {% for category in post.categories %}
	          {% if category == 'other' %}
		        <tr>
		            <td style="padding:1%;width:25%;vertical-align:middle;min-width:120px">
		                <img class="project-image" src="{{site.baseurl}}/{{post.image}}"/>
		            </td>
		            <td>
		                <h4>{{post.title}}</h4>
		                <br>
		                {{post.authors}}
		                <br>
		                <em>{{post.venue}}</em>, {{ post.date | date: "%Y"}}
		                <br>
			              {% if post.arxiv %}
			              <a href="{{post.arxiv}}">arxiv</a> /
			              {% endif %}
			              {% if post.pdf %}
			              <a href="{{post.pdf}}">pdf</a> /
			              {% endif %}
			              {% if post.video %}
			              <a href="{{post.video}}">video</a> /
			              {% endif %}
			              {% if post.code %}
			              <a href="{{post.code}}">code</a> /
			              {% endif %}
			              {% if post.poster %}
			              <a href="{{post.poster}}">poster</a> /
			              {% endif %}
			              {% if post.slides %}
			              <a href="{{post.slides}}">slides</a> /
			              {% endif %}
		                <p></p>
		                {{ post.excerpt }}
		            </td>
		        </tr>
	          {% endif %}
	    	{% endfor %}
	    {% endfor %}
	</table>
</html>
 
## Talks & Demos

<html>
	<table style="border:0px">
	    {% for post in site.posts %}
		    {% for category in post.categories %}
	          {% if category == 'talk' %}
		        <tr>
		            <td style="padding:1%;width:25%;vertical-align:middle;min-width:120px">
		            </td>
		            <td>
		                <h4>{{post.title}}</h4>
		                {{post.authors}}
		                <br>
		                <em>{{post.venue}}</em>, {{ post.date | date: "%Y"}}
		                <br>
			              {% if post.arxiv %}
			              <a href="{{post.arxiv}}">arxiv</a> /
			              {% endif %}
			              {% if post.pdf %}
			              <a href="{{post.pdf}}">pdf</a> /
			              {% endif %}
			              {% if post.video %}
			              <a href="{{post.video}}">video</a> /
			              {% endif %}
			              {% if post.code %}
			              <a href="{{post.code}}">code</a> /
			              {% endif %}
			              {% if post.poster %}
			              <a href="{{post.poster}}">poster</a> /
			              {% endif %}
			              {% if post.slides %}
			              <a href="{{post.slides}}">slides</a> /
			              {% endif %}
		                <p></p>
		                {{ post.excerpt }}
		            </td>
		        </tr>
	          {% endif %}
	    	{% endfor %}
	    {% endfor %}
	</table>
</html>
