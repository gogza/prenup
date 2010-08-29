# prenup

<img src="http://imgur.com/L0iQo.gif" border="0"/>

prenup is a [node.js][11] web application (<i>protip: it kinda works without node.js if you just open index.html in your browser</i>) project planning tool that allows you to meaningfully engage your clients and convert their domain knowledge into tangible milestones, features, scenarions, and unit tests.

## Features

- Scenarios are created using [Kyuri][1], a custom dialect of [Gherkin][12] geared towards asynchronous programming
- Intuitive and friendly user interface that takes the frustration out of Behavior Driven Development
- Generates [VowsJS][3] testing stubs (Vows is a well established node.js testing framework)
- Milestones, Features, Scenarios, Points
- Support for 160+ languages
- Heavily influenced by Cucumber. If you know [Cuke][10], you know prenup.


## things that would be implemented if we didn't build this in 48 hours

- real-time project management collaboration using [socket.io][9]
- user accounts using [roles.js][7]
- automated billing using [paynode][8]
- native mobile app (iPhone / iPad / BlackBerry) using [Titanium AppCelerator][6]

## Using prenup

prenup can be used as a software as a service located @ http://foo.com.

prenup is also open-source, so you can run your own customizable version (see below)


## Installation

If you want to run your own prenup instance (instead of using the free service available at http://foo.com), you will need to install prenup via npm.


### Installing npm (node package manager)
<pre>
  curl http://npmjs.org/install.sh | sh
</pre>

### Installing prenup
<pre>
  npm install prenup
</pre>


## VowsJS

[VowsJS][3] is a popular behavior driven development framework for node.js. Vows was built from the ground up to test asynchronous code. It executes your tests in parallel when it makes sense, and sequentially when there are dependencies.

Instead of crafting your [Vows][3] code from hand (using JavaScript and node.js), prenup allows you to auto-generate Vows stubs using [Kyuri][1] and an intuitive user interface. 

For further information about [Vows][3], please visit it's repository here. 

## Kyuri

[Kyuri][1] comes pre-bundled with prenup. [Kyuri][1] is the language used to describe your Features and Scenarios. [Kyuri][1] is a dialect of Gherkin, a well establish BDD language made popular by [Cucumber][10]. 

For further information about [Kyuri][1], please visit it's repository here.


## Authors
### Created for Node Knockout 2010 by The NYC Nodejitsu Ninjas
#### Charlie Robbins, hij1nx, Matthew Bergman & Marak Squires

### Acknowledgments
Heavily inspired by Sean Cribbs' [Lowdownapp][4], an entry in the 2009 Rails Rumble

Cucumber works via plain text descriptions of how your software should work. 
Learn more about [Cucumber][2].

Think testing business logic with all the tastiness of organizing via easily readable steps.

[1]:  http://github.com/nodejitsu/kyuri  "Kyuri"
[2]:  http://cukes.info/    "Cucumber"
[3]:  http://vowsjs.org/  "Vowjs"
[4]:  http://lowdownapp.com/  "Lowdownapp"
[5]:  http://foo.com/ "prenup"
[6]:  http://www.appcelerator.com/ "Titanium AppCelerator"
[7]:  http://github.com/marak/roles.js/ "roles.js"
[8]:  http://github.com/jamescarr/paynode "paynode"
[9]:  http://socket.io/ "socket.io"
[10]: http://cukes.info "Cucumber"
[11]: http://nodejs.org "node.js"
[12]: http://wiki.github.com/aslakhellesoy/cucumber/gherkin "gherkin"
