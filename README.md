# B11-What-About-Asynchronous-Callbacks-And-Types
<p>A deep dive into the strange world of JavaScript.</p>

<h1>What Was Learned</h1>
    
 <ul>

  <li>Asynchronous</li>
  <li>Event Queue</li>
  <li> Dynamic Typing<li>
  <li>Primitive Type<li>
 </ul>
 
<h1>Notes</h1>
Asynchronous - more than one at a time.
When the execution stack is empty, the javascript look at the Event Queue. If something is their javascript waits for the event to be triggered when that happens the execution context for the event is  created. Javascript is not asynchronous the broswer Asynchronous put things into th event queue. 

Dynamic Typing: You don't tell the engine what type of data a variable holds, it figures it out while the code is running.

Variables can hold different types of values because it's all figured out during execution.

Primitive Type: A type of data that repersents a single value. That is, not an object.

Primitive Types:
1. Undifined - reresents lack of existence.(you shouldn't set a variable to this)

2. Null - reresents lack of existence (you can set a variable to this)

3. Boolean - true or false

4. Number - floating point number (there's aways some decimals.)

5. String - a sequence of characters (both '' and "" can be used)

6. Symbol - Used in ES6