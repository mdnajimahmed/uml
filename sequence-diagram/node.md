## Intro:
Use case and class diagrams are static diagrams, they are good to explain the structure of our system. But what if we want something more, we want to show the behavior, how the objects interact with each other.  When are objects created and how long they are around. We need a dynamic diagram to represent bahavior. 

*Sequence diagram is the most common dynamic diagram*
- Describes the flow of logic in one particular scenario.
- Sequence diagram starts by drwing boxes at the top of the page.
- Each box represents an object. Example: aCow: Cow, aDog:Animal, aBus:Bus - these are objects in the reactangle.
- An arrow goes from one thread of one reactangle to the thread of another rectangle. This is how we show communication between two objects via
messages. A message is nothing but a functional call with a parameter, and parameter is the actual message.  

# Notes : -
- Sync message return type is implicit
- Sync message has bold arrow head, async message has empty arrow head.
- We can use stereotype for further clarification.
