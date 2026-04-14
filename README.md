# TypeScript Project

This repository contains my solutions for the **TypeScript** project in the `holbertonschool-web_react` repository.  
Through these tasks, I practiced core TypeScript concepts and learned how to write safer, more structured, and more maintainable code using interfaces, classes, namespaces, declaration files, and nominal typing.

## Learning Objectives

Through this project, the following TypeScript concepts are practiced:

- Basic types in TypeScript
- Interfaces
- Classes
- Functions
- DOM manipulation with TypeScript
- Advanced types
- Namespaces
- Declaration merging
- Ambient namespaces
- Nominal typing

## Requirements

- All files use the `.ts` extension where applicable
- Each task contains its own configuration files when required
- Webpack is used to compile the TypeScript code
- Code is written with TypeScript typing whenever possible
## What I Learned

By completing this project, I learned how to:

- define and use **TypeScript interfaces**
- describe object shapes with required and optional properties
- use **readonly** properties for values that should only be set during initialization
- create and use **function interfaces**
- build **classes** and describe them using interfaces
- extend interfaces with **inheritance**
- work with **union types** such as `number | string`
- write **type predicates** for better type narrowing
- use **string literal types**
- create and use **ambient declaration files (`.d.ts`)**
- import types into declaration files and main files
- organize code with **namespaces**
- use **declaration merging**
- apply **brand convention / nominal typing** to distinguish similar types

## Tasks Overview

| Task | Title | Main Concepts Covered |
|------|-------|------------------------|
| `task_0` | Creating an interface for a student | Interfaces, typed objects, arrays, DOM manipulation, rendering data in a table |
| `task_1` | Teacher interfaces and class writing | Readonly properties, optional properties, index signatures, interface inheritance, function interfaces, classes, constructor interfaces |
| `task_2` | Advanced types | Classes implementing interfaces, union types, type predicates, string literal types |
| `task_3` | Ambient Namespaces | Type aliases, declaration files (`.d.ts`), importing types, working with external JS modules |
| `task_4` | Namespace & Declaration merging | Namespaces, declaration merging, extending interfaces across files, subject-based class structure |
| `task_5` | Brand convention & Nominal typing | Branded interfaces, nominal typing, strongly distinguishing similar number-based types |

## Detailed Task Summary

| Task | Description | Files |
|------|-------------|-------|
| `task_0` | Created a `Student` interface, defined two student objects, stored them in an array, and displayed their first names and locations in an HTML table using TypeScript and DOM manipulation. | `task_0/js/main.ts`, `task_0/package.json`, `task_0/.eslintrc.js`, `task_0/tsconfig.json`, `task_0/webpack.config.js` |
| `task_1` | Built the `Teacher` interface with readonly and optional properties, extended it with `Directors`, created a `printTeacher` function interface, and implemented a `StudentClass` described through interfaces. | `task_1/js/main.ts`, `task_1/package.json`, `task_1/tsconfig.json`, `task_1/webpack.config.js` |
| `task_2` | Created `Director` and `Teacher` classes with interfaces, implemented `createEmployee`, added a type predicate with `isDirector`, created `executeWork`, and used string literal types in `teachClass`. | `task_2/js/main.ts`, `task_2/package.json`, `task_2/tsconfig.json`, `task_2/webpack.config.js` |
| `task_3` | Defined `RowID` and `RowElement`, created an ambient declaration file for a CRUD library, and used imported types with external functions inside `main.ts`. | `task_3/js/interface.ts`, `task_3/js/crud.d.ts`, `task_3/js/crud.js`, `task_3/js/main.ts`, `task_3/package.json`, `task_3/tsconfig.json`, `task_3/webpack.config.js` |
| `task_4` | Organized subject-related files inside the `Subjects` namespace, used declaration merging to extend the `Teacher` interface, and created `Cpp`, `React`, and `Java` classes with specialized methods. | `task_4/js/subjects/Teacher.ts`, `task_4/js/subjects/Subject.ts`, `task_4/js/subjects/Cpp.ts`, `task_4/js/subjects/React.ts`, `task_4/js/subjects/Java.ts`, `task_4/package.json`, `task_4/tsconfig.json` |
| `task_5` | Implemented `MajorCredits` and `MinorCredits` using brand properties, then created functions to sum credits while preserving their nominal types. | `task_5/js/main.ts`, `task_5/package.json`, `task_5/tsconfig.json`, `task_5/webpack.config.js` |

## Notes
- Each task includes the configuration files required by the project instructions.
- TypeScript typing was applied whenever possible.
- The project focuses on understanding TypeScript design patterns and architecture, not only syntax

