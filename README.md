# TODO App with React-like Reconciliation

## Overview

This project is a front-end TODO app that implements a reconciliation process similar to React. The app efficiently updates the DOM based on changes in the state, making it both responsive and performant.

## Key Features

- **Dynamic Reconciliation:** The `updateState` function calculates the difference between the new and old states and triggers appropriate DOM updates.
- **Unique Identification:** Each TODO item is uniquely identified by an `id`, ensuring precise updates.
- **Efficient Updates:** Only the necessary changes are applied to the DOM, improving performance.

## Functions Implemented

### `addTodoToDom(todo)`
This function adds a new TODO item to the DOM.

### `removeTodoFromDom(todo)`
This function removes an existing TODO item from the DOM.

### `updateTodoInDom(oldTodo, newTodo)`
This function updates an existing TODO item in the DOM when its title or description changes.

### `updateState(newTodos)`
This function calculates the differences between the new and old states and triggers the appropriate functions (`addTodoToDom`, `removeTodoFromDom`, `updateTodoInDom`) based on those differences.
