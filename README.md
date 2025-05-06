# TIMER LIBRARY

A simple C++ library to create a timer, use this library to simplify the process of timer implementation with 2 code lines.

### How to use?

The first step is clone the repository in your machine using the following command:

```bash
  git clone https://github.com/leonard-soft/timer-cpp-library.git
```
Once you have the repository, copy the header file and its corresponding implementation into your project. I will assume that your project has the following structure:

```bash
├── include
│   └── timer
│       └── timer.hpp
└── src
    ├── main.cpp
    └── timer
        └── Timer.cpp
```

### Adjust the path into the implementation file

```cpp
  #include "../../include/timer/timer.hpp"
```

### Use the the timer library

```cpp
  // Currently, we are using the main.cpp file, which is not the implementation file.

  #include <iostream>
  #include <string>
  #include "../include/timer/timer.hpp"

  int main()
  {
      std::string time;
      Timer timer;

      std::cout << "enter a time in minutes: ";
      std::cin >> time;

      // you need to validate if the `time` is a number
      timer.startTimer(time);
  }  

```

### that's all we planed

# Thanks :)
