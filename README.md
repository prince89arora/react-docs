# React Documentation

## Reconciliation

- Its a strategy/algorithm that react uses to detect changes in virtual and actual dom elements.
- Virtual DOM is a json representation of DOM elements.
- React tries to reuse elements as much as possible.
- React matches element type to check if any change has happened.
- Best practice is to use key property for elements in JSX.

## Patterns

### HOC (Higher Order Component)

HOC is a component which can take a component as input and returns another component.
This can be used to develop shared functionality. The input component can work as expected but can have additional flavor that HOC provides.

### Custom Hooks

- Its not mandatory to start with use.
