# B11-What-About-Asynchronous-Callbacks
<p>A deep dive into the strange world of JavaScript.</p>

<h1>What Was Learned</h1>
    
 <ul>

  <li>Asynchronous</li>
  <li>Event Queue</li>
  <li> Dynamic Typing<li>
 </ul>
 
<h1>Notes</h1>
Asynchronous - more than one at a time.
When the execution stack is empty, the javascript look at the Event Queue. If something is their javascript waits for the event to be triggered when that happens the execution context for the event is  created. Javascript is not asynchronous the broswer Asynchronous put things into th event queue. 

Dynamic Typing: You don't tell the engine what type of data a variable holds, it figures it out while the code is running.

Variables can hold different types of values because it's all figured out during execution.