# Book - Marstering Dart

_-- Marter the art of programming high-performance application with Dart_

Author: Sergey Akopkokhyants

## 1. Beyond Dart's Bascis

### Benefits of Modularity in Software Development

During Development Phase:

- Each module requires less code
- New features or changes can be introduced to modules in isolation, separate from the other modules
- Errors can be easily identified and fixed in a modules
- Modules can be built and tested independently
- Programmers writing the modules can collaborate on the same application
- The same modules can be reused in many applications
- Applications have a main module and many auxiliary modules. Each module encapsulates a specific functionality and each one is integrated through loosely coupled communication channels provided by the main module

During Post-Production Phase:

- Modules kept in a versioning system can be easily maintained and tested
- Fixed and noninfrastructural changes in a module can be done without affecting other modules

### One significant Disadvantage of Modularity

It increases complexity when managing many modules, especially when each one is individually versioned, updated, and has dependencies on the other modules.

### Modularity in Dart

Modularity in Dart is realized through __Packages, Libraries, and Classes__.

| Module Components | Definition |
| :---: | :--- |
| library | A __library__ exposes functionality as a set of interfaces and hides the implementation from the rest of the world. A library can be implemented as a simple function, a single class, several classes, or a collection of parts representing the entire API of a library. The Dart application is a library as well|
| package | A

## 2. Advanced Techniques and Reflections

## 3. Object Creation

## 4. Asynchronous Programming

## 5. The Stream Framework

## 6. The Collection Framework

## 7. Dart and JavaScript Interoperation

## 8. Internalization and Localization

## 9. Client-to-Server Communication

## 10. Advanced Storage

## 11. Supporting Other HTML5 Features

## 12. Security Aspects
