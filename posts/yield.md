**Semantic field**: Crop, return control, iterator, relent, defer, submit, return

conversational analysis

turn taking, placeholders, interruptions, overlapping, continuers, terminators, breaks,

non-verbal communication: body language, eye contact, intonation, 

backchannel or reactive tokens (aizuchi) - listener phatic responsers

Foucault power dynamics, hierarchy 

stop signs

lazy iterators

coroutines

backchannel communication

`yield` produces a value to be received by the caller of `next` and suspends execution of the generator

`yield` is the control flow device used to implement cooperative multitasking : each coroutine yields control to central scheduler so other coroutines can be activated (like a mutex?)

sentinel value (flag, trip, rogue, signal, dummy) to terminate recursive or infinite loop

```c++
int find(int arr[], size_t len, int val){
	for (int i = 0; i < len; i++)
		if (arr[i] == val)
      return i;
  return -1;  // not found
}
```



`yield from` open a bidirectional channel from the outermost caller to the innermost subgenerator so values can be sent and yielded back and exceptions thrown all the way without boilerplate 

