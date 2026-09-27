# Rust Neural Network Core

Educational project for studying the fundamentals of neural network computation and implementing core tensor and matrix operations in Rust.

## 🎯 About

This project is being developed as a practical study of the computational foundations of neural networks.

The main goal is to understand how data is represented and processed inside neural network systems by implementing fundamental operations at a lower level rather than relying entirely on high-level machine learning frameworks.

## 🛠️ Technology Stack

* **Rust**
* **Cargo**
* **Rayon** — parallel computations
* **rand / rand_distr** — random data generation
* **Git**

## 🧮 Current Implementation

The project currently contains a basic `Tensor` structure with support for:

* tensor creation;
* zero and one initialization;
* random initialization;
* indexing;
* shape information;
* flattening;
* summation;
* matrix multiplication;
* transpose;
* addition;
* scalar multiplication;
* element-wise mapping;
* ReLU;
* exponential function;
* bias addition;
* reshape;
* row-wise softmax.

Matrix multiplication and selected operations are implemented with parallel processing.

## 🧪 Testing

The project includes unit tests for the implemented tensor and matrix operations.

Example matrix multiplication:

```text
[1 2 3]   [7  8]
[4 5 6] × [9 10]

        [11 12]
        [13 14]
```

The project uses Rust's built-in testing framework.

## 📚 Learning Goals

The project is being developed to gain a deeper understanding of:

* tensors and multidimensional data;
* matrix operations;
* neural network computation;
* numerical data processing;
* memory representation;
* parallel computation;
* the relationship between mathematical operations and neural network layers.

## 🚧 Development Status

**In development**

The project is primarily educational and is being expanded incrementally.

Planned areas include:

* additional tensor operations;
* improved memory management;
* neural network layers;
* forward propagation;
* activation functions;
* loss functions;
* backpropagation;
* optimization algorithms;
* model serialization;
* performance optimization.

## 👤 Author

**Ivan Repin**

IT student focused on system analysis, databases, software development and AI/ML.

GitHub: [ivan-repin](https://github.com/EggZechnick)
