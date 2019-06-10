### Execution Context  

It is an abstract concept of an environment where javascript code gets executed. When you run Javascript code, it gets immediately evaluated and executed. 

There are a few types of execution contexts - Global, Functional, and Eval.

### Execution Stack

AKA call stack. When you run javascript code, the code gets pushed onto the execution stack. As the code encounters new methods/functions they get pushed on top of the stack, and poped when they are executed. 

### Execution Context Lifecycle

1. Creation Phase
2. Execution Phase


#### Creation Phase

This phase consists of two parts. 1. Lexical Environment Component 2. Variable Environment Component

ExecutionContext = {
  LexicalEnvironment = <ref. to LexicalEnvironment in memory>,
  VariableEnvironment = <ref. to VariableEnvironment in  memory>,
}



