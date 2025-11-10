# 💻 My C++ OOP Learning Repository

[](https://opensource.org/licenses/MIT)
[](https://www.google.com/search?q=https://github.com/your-username/your-repo-name/issues)
[](https://www.google.com/search?q=https://github.com/your-username/your-repo-name/pulls)
[](https://www.google.com/search?q=https://github.com/your-username/your-repo-name/network/members)
[](https://www.google.com/search?q=https://github.com/your-username/your-repo-name/stargazers)

> **Hey there\! Welcome.**
>
> I put this repository together as a hands-on guide for anyone (including my future self\!) trying to get a solid grip on **Object-Oriented Programming (OOP)** using **C++**.
>
> My goal was to create simple, clear, and well-commented examples that cut through the complex theory and show you how things *actually* work. Whether you're a student in a CS class or just brushing up on your skills, I hope you find this helpful.

-----

## 🧭 Quick Navigation

  * [What's OOP, Anyway?](https://www.google.com/search?q=%23-whats-oop-anyway-the-four-pillars)
  * [The C++ Basics (Gotta Start Here\!)](https://www.google.com/search?q=%23-the-c-basics-gotta-start-here)
  * [The OOP Good-Stuff](https://www.google.com/search?q=%23-the-oop-good-stuff)
  * [How to Run This Code](https://www.google.com/search?q=%23-how-to-run-this-code)
  * [My Recommended Learning Path](https://www.google.com/search?q=%23-my-recommended-learning-path)
  * [Want to Help Out?](https://www.google.com/search?q=%23-want-to-help-out)
  * [What I'm Adding Next](https://www.google.com/search?q=%23-what-im-adding-next)

-----

## 💡 What's OOP, Anyway? (The Four Pillars)

OOP is really just a smart way to organize your code. Instead of having a bunch of functions all over the place, you group your data and the functions that *use* that data into "objects."

Think of it as building with smart LEGOs. Each LEGO block (an object) knows its own color, shape, and how it can connect to other blocks.

It all boils down to these four big ideas:

  * **🔒 Encapsulation:** Think of this as a protective capsule. It bundles the data (like a car's `speed`) and the functions that change it (like `accelerate()`) together. This stops anyone from accidentally setting the `speed` to -100.
  * **👻 Abstraction:** This is the "keep it simple" principle. You hide all the messy internal details and just show the essential controls. When you press the gas pedal in a car, you don't need to know about fuel injection or spark plugs—you just know it will go. That's abstraction.
  * **🧬 Inheritance:** This is a huge time-saver. It lets you create a new class (like `SportsCar`) that *inherits* all the features from an existing class (like `Car`). You don't have to rewrite all the code for `steering` or `braking`—you just add the new stuff, like a `turboBoost()`.
  * **✨ Polymorphism:** This is a fancy word that means "many forms." It lets you treat different objects in the same way. For example, you could have a `draw()` function that works for a `Circle`, a `Square`, and a `Triangle`. You just tell it to `draw()`, and it knows how to do it correctly for each shape.

-----

## 📁 The C++ Basics (Gotta Start Here\!)

You've got to walk before you can run, right? Before diving into OOP, it's super important to be comfortable with the procedural building blocks. I've included folders for:

  * **Arrays**
  * **Character Array**
  * **Conditionals** (if/else, switch)
  * **Functions**
  * **Loops** (for, while, do-while)

-----

## 📘 The OOP Good-Stuff

Okay, this is what you're here for\! Each folder has examples to show you how these concepts work in practice.

  * **Classes and Objects:** The blueprints and the actual things you build from them.
  * **Constructors and Destructors:** The special functions that "build" and "clean up" your objects automatically.
  * **Encapsulation:** Using `private`, `public`, and `protected` to hide your data.
  * **Inheritance:** Examples of single, multiple, and multilevel inheritance.
  * **Polymorphism:** See both compile-time (overloading) and runtime (virtual functions) in action.
  * **Abstraction:** Building "abstract classes" that act as templates for other classes.
  * **Operator Overloading:** Making operators like `+` or `==` work with your custom objects (this one is pretty cool).
  * **Templates:** Writing generic code that can work with any data type.
  * **Exception Handling:** The "try/catch" way to handle errors gracefully without crashing your program.

-----

## 📁 Repository Structure (How I've Organized Things)

I've tried to keep this clean and simple. Each major topic gets its own folder.

```
/oops-cpp/
├─ README.md
├─ arrays/
│  ├─ array_operations.cpp
│  └─ array_search.cpp
├─ classes_and_objects/
│  ├─ class_demo.cpp
│  └─ object_usage.cpp
├─ inheritance/
│  ├─ single_inheritance.cpp
│  └─ multilevel_inheritance.cpp
├─ polymorphism/
│  ├─ function_overloading.cpp
│  └─ virtual_functions.cpp
... (and so on)
```

-----

## 🚀 How to Run This Code

So, you've got the code. How do you actually *run* it?

1.  **Open your terminal** or command prompt.
2.  `cd` (change directory) into the folder you want to run.
3.  **Compile** the `.cpp` file using `g++` (or any C++ compiler):

<!-- end list -->

```bash
# This command tells g++ to:
# - Use the C++17 standard (-std=c++17)
# - Show all warnings (-Wall)
# - Compile your file (filename.cpp)
# - Create an executable program named "output_name" (-o output_name)
g++ -std=c++17 -Wall filename.cpp -o output_name
```

4.  **Run** your new program\!

<!-- end list -->

```bash
./output_name
```

**For example:**

```bash
# Go into the inheritance folder
cd inheritance/

# Compile the file
g++ -std=c++17 single_inheritance.cpp -o single_inheritance

# Run it!
./single_inheritance
```

-----

## 🗺️ My Recommended Learning Path

Feeling a little overwhelmed by all the folders? No worries. Here’s the order I’d suggest you tackle them in:

1.  Arrays
2.  Character Array
3.  Conditionals
4.  Functions
5.  Loops
6.  **Classes and Objects** (This is the big jump into OOP\!)
7.  Constructors and Destructors
8.  Encapsulation and Abstraction
9.  Inheritance
10. Polymorphism
11. Operator Overloading
12. Templates
13. Exception Handling

-----

## 🤝 Want to Help Out?

This is a learning project, and I'm always open to making it better. If you find a bug, a typo, or have a better way to explain something, please get involved\!

  * **Found a bug?** 🐛 [Open an issue](https://www.google.com/search?q=https://github.com/your-username/your-repo-name/issues/new).
  * **Have a fix or a new example?** 💡 Fork the repo and [submit a pull request](https://www.google.com/search?q=https://github.com/your-username/your-repo-name/pulls).

-----

## 🧩 What I'm Adding Next

I'm not done yet\! This repo will keep growing. Here are a few things on my to-do list:

  * File Handling (I/O) using OOP principles
  * Examples of using the Standard Template Library (STL) with classes
  * A few simple Design Patterns (like Singleton or Factory)

-----

## 🧾 License

Feel free to use, modify, and share this code for your own learning or projects.

-----

> 💡 **Final Tip:** Seriously, don't just *read* the code. The real learning happens when you **clone this repo,** get your hands dirty, and **try to break things.** Change a `public` to a `private` and see what happens. Write your own class. That's how you'll really get it.
>
> Happy coding\!
