# mark-joshi-cpp

Summary notes on [Mark Joshi](https://en.wikipedia.org/wiki/Mark_S._Joshi)'s C++ Design Patterns and Derivatives Pricing

I was lucky to find this book in my journey to learn C++ programming in finance. This repo is an attempt to collect and share some notes and insights from the book. Please comment if you see any error or misconception. Thank you.

## Table of contents

1. A simple Monte Carlo Model
2. Encapsulation
3. Inheritence and virtual functions
4. Bridge with a virtual Constructor
5. Strategies, decoration and statistics
6. A random number class
7. An exotics engine and the template pattern
8. Trees
9. Solvers, templates, and implied volatitlites
10. The factory
11. Design patterns revisited


## Codes by Chapter
```
1. A simple Monte Carlo Model
  SimpleMCMain1.cpp
  Random1.h
  Random1.cpp

2. Encapsulation
  PayOff1.h
  PayOff1.cpp
  SimpleMC.h
  SimpleMC.cpp
  SimpleMCMain2.cpp

3. Inheritence and virtual functions
  PayOff2.h
  PayOff2.cpp
  SimpleMC2.h
  SimpleMC2.cpp
  SimpleMCMain3.cpp
  
  3.5. Not knowing the type and virtual destruction
  SimpleMCMain4.cpp
  
  3.6. Adding extra pay-offs without changing files
  DoubleDigital.h
  DoubleDigital.cpp
  SimpleMCMain5.cpp

4. Bridge with a virtual Constructor
  4.2. A first solution
  Vanilla1.h
  Vanilla1.cpp
  SimpleMC3.h
  SimpleMC3.cpp
  VanillaMain1.cpp
  
  4.3 Virtual construction
  PayOff3.h
  PayOff3.cpp 
  Vanilla2.h
  Vanilla2.cpp 
  SimpleMC4.h
  SimpleMC4.cpp
  VanillaMain2.cpp
  
  4.5 The bridge
  PayOffBridge.h
  PayOffBridge.cpp
  Vanilla3.h
  Vanilla3.cpp 
  SimpleMC5.h
  SimpleMC5.cpp
  VanillaMain3.cpp
  
  4.7. A parameter class
  Parameters.h
  Parameters.cpp
  SimpleMC6.h
  SimpleMC6.cpp
  VanillaMain4.cpp

5. Strategies, decoration and statistics
  MCStatistics.h
  MCStatistics.cpp
  SimpleMC7.h
  SimpleMC7.cpp
  StatsMain1.cpp
  
  5.4. Templates and wrappers
  Wrapper.h
  Wrapper.cpp
  ConvergenceTable.h
  ConvergenceTable.cpp
  StatsMain2.cpp

6. A random number class
  Random2.h
  Random2.cpp  
  ParkMiller.h
  ParkMiller.cpp
  AntiThetiic.h
  AntiThetiic.cpp
  SimpleMC8.h
  SimpleMC8.cpp
  RandomMain3.cpp
  
7. An exotics engine and the template pattern
  PathDependent.h
  PathDependent.cpp
  ExoticEngine.cpp
  ExoticBSEngine.h
  ExoticBSEngine.cpp
  PathDependentAsian.h
  PathDependentAsian.cpp
  EquityFXMain.cpp
  
8. Trees
  TreeProducts.h
  TreeProducts.cpp
  TreeAmerican.h
  TreeAmerican.cpp
  TreeEuropean.h
  TreeEuropean.cpp
  BinomialTree.h
  BinomialTree.cpp
  TreeMain.cpp
  PayOffForward.h
  PayOffForward.cpp
  
9. Solvers, templates, and implied volatitlites
  BSCallClass.h
  BSCallClass.cpp
  Bisection.h
  Bisection.cpp
  SolveMain1.cpp
  
  NewtonRaphson.h
  NewtonRaphson.cpp
  BSCallTwo.h
  BSCallTwo.cpp
  SolveMain2.cpp
  
10. The factory
  PayOffFactory.h
  PayOffFactory.cpp
  PayOffConstructible.h
  PayOffConstructible.cpp
  PayOffRegisteration.h
  PayOffRegisteration.cpp
  PayFactoryMain.cpp  
  
11. Design patterns revisited
  │
  ├─ Creational
  │   ├─ Virtual copy constructor
  │   ├─ The factory
  │   ├─ Singleton
  │   └─ Monostate
  │
  ├─ Structural
  │   ├─ Adapter
  │   ├─ Bridge
  │   └─ Decorator
  │
  └─ Behavioural
      ├─ Strategy
      ├─ Template
      └─ Iterator    
```
