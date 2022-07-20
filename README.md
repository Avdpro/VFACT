# VFACT
**V**ariable **F**aced **A**bstract **C**ontrol **T**ree
## Basic concept
VFACT is focused on pratical UI control layout and transition define and description. It use a standard JSON/Javascript object define UI components' layout, state and transition. The component definitions are abstract, variables supported, and platform independent. So it's easy to implement, VFACT UI on different platmforms.
## Key rules:
- Components:
    - User interface is composed by tree-structured hierarchical components.
    - Each component is defined by a JSON/Javascript object.
    - Component use properties to define/control it's layout and appearence.
    - Properties naming should be intuitive and can be understanded by the first eye.
    - Set/Change component's properites will affect the component's layout and appearence, but can be asynced
    - Properties can be defined as statement that tracing state-object.
    - Each property statement can only trace **one** state-object at a time.
    - Sub hierachical components are defined in component's **children** property as an **Array**.
