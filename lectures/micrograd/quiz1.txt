1. What is the purpose of `numpy.arange` in the context of this code?
    a. It generates a sequence of numbers from -5 to 5 with step 0.25.
    b. It computes the derivative of the function.
    c. It is used to plot the function.
    d. It is used to evaluate the function at certain points.

2. What does the `f(x)` function do in this code?
    a. It returns the square of `x`.
    b. It computes the derivative of `x`.
    c. It computes and returns the value of a quadratic function at `x`.
    d. It generates an array of values from `x` to 5.

3. How does the "more complex" section of the code demonstrate the concept of derivatives?
    a. It computes the derivative using the limit definition.
    b. It applies the power rule for derivatives.
    c. It applies the product rule for derivatives.
    d. It computes the derivative using the chain rule.

4. What is the purpose of class `Value` in this code?
    a. It stores a number and its derivative.
    b. It represents a neuron in a neural network.
    c. It generates an array of numbers.
    d. It computes the derivative of a function.

5. Explain the `backward` function in the `Value` class.
    a. It computes the derivative of a function.
    b. It initializes the gradient to zero.
    c. It traverses the computational graph and applies the chain rule to compute gradients.
    d. It generates an array of numbers.

6. Why do `a.data`, `b.data`, `c.data`, `f.data` get incremented by `0.01` times their gradient after `L` is computed?
    a. It is the implementation of the gradient descent optimization algorithm.
    b. It is used to calculate the second derivative.
    c. It is a way to calculate the integral of the function.
    d. It is a part of the backpropagation algorithm.

7. What is the purpose of the `lol` function in this code?
    a. It visualizes the computational graph.
    b. It computes the value of a complex function.
    c. It verifies the computed gradient with numerical differentiation.
    d. It initializes the gradients of `a`, `b`, `c`, and `f` to zero.

8. What is happening in the code block that begins with `# inputs x1,x2`?
    a. It is initializing the inputs and weights of a neuron.
    b. It is training a neural network.
    c. It is implementing a feedforward step in a neural network.
    d. It is calculating the loss of a neural network.

9. How is the concept of a neuron in a neural network represented in this code?
    a. With the `lol` function.
    b. With the `Value` class.
    c. With the combination of `Value` objects and their methods like `__add__`, `__mul__`, and `tanh`.
    d. With the `backward` function in the `Value` class.

10. Explain the purpose of the `build_topo` function and what "topo" represents in this context.
    a. `build_topo` generates an array of numbers; "topo" represents the derivative.
    b. `build_topo` represents a neuron; "topo" represents the weights of the neuron.
    c. build_topo performs a depth-first search on the computational graph and "topo" is a list that stores the graph in topological order.
    d. build_topo calculates the loss function; "topo" represents the loss.
