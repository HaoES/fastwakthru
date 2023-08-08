### Key points:
- the distillation is a process when you have a teacher network (which is a network that knows how to do something but it is very big and/or slow) 
and a student network which tries to learn the same task but using less memory and faster.
- in imagic we take the average between the target emb and the optimized emb (interpolate) and it spits out the image we want
- we first take the prompt and tokenize it, then we encode it using the clip encoder, 
- python with close is called context manager: it runs the file and when done closes it
- we can turn any list to an iterator by passing it through "iter()"
- islice grabs the first n things from an iterable then raises stopiter
-  you can pass to iter() a list or a callable too
- iter(callable, sentinel) =>  calls the callable until the sentinel is returner
-  
### Advice

### TODO
- implement negative prompt
- implement callbacks
- implement image 2 image



### Reading and exploring

### Questions
