## 2.1 Java Basics

#### Everything is a Class

- **Classes** and objects are core constructs
- OO features: polymorphism, encapsulation, inheritance, ...
- Static member variables and methods
- Resembles C++ on the surface, but not the same
  - No pointers, all references
  -  No type ambiguity; classes resolved at runtime
  - No destructor (due to garbage collector)
  - No multiple inheritance (single only, but with class **Interfaces**)

## 2.2 Java GUI

#### Swing Component Hierarchy

- `java.awt.Window` is the base for all containers. `java.swing.Jcomponent` is the root for all widgets.

#### How to build a Swing UI

- Create a top-level application window, using a Swing container (`JFrame` or `JDialog`).
- Add Swing components to this window.
  - Typically, you create a smaller container (like a `JPanel`) and add comments to the panel.
  - This makes dynamic layouts easier.

#### Event handling

- Register for events: add listeners, like keyboard (press), mouse (down, up, move)
- Write code to respond to these events.
- Make components update and paint themselves base on events.

#### Java Listener Model

- Java has interfaces specialized by event type.
  - Each interface lists the methods that are needed to support that device's events.
- To use them, <u>write a class that implements this interface</u>, and override the methods for events you care about.
- Because it's an interface, you have to override all of these methods - even for events you don't care about!

#### Adapters vs. Listeners

- Java also has adapters, which are base classes with empty listeners.
  - Extend the adapter and override the vent handlers that you are about; avoid bloat.

#### Anonymous Inner Classes

## Drawing in Java

#### Graphics and Parinting

- Applications consist of a `JFrame` (window) containing one or more Swing components.
- We often define a top-level canvas (container)
  - This can hold other components.
  - We can also draw directly on this canvas.
- Each component has a `paintComponent()` method, which describes how it paints itself.
  - You can override this `paintComponent()` method and draw primitive objects using the `java.awt.Graphics` object (basically, the Graphics Context).
  - This is a common technique for defining drawables in Java.

## Widgets

## 2.6 Layout

#### Responaive vs. Adaptive

- Responsive: universal design reflows spatial layout to fit width
- Adaptive: switch between optimized spatial layouts to fir deveices

#### Two Interface Layout Tasks

1. **Designing a spatial layout** of widgets in a container
2. **Adjusting that spatial layout** when container is resiced

- Can be done by hand (i.e. graphic design) or automatically (i.e. with algorithms).

#### Dynamic Layout

- If a window is resized, we want to:
  1. maximize use of available space for displaying widgets
  2. maintain consistency with spatial layoput
  3. preserve visual quality of spatial layout
- News to **dynamically** modify that layout:
  - re-allocate space for widgets
  - adjust location and size of widgets
  - perhaps even change visibility, look, and/or feel of widgets

#### Layout uses Composite Design Pattern

- Reat leaf objects and compositions of objects uniformly
- Creates a tree data structure

#### Widget Size

- To make a layout dynamic, widgets need to be "flexible"
  - x, y position may be changed
  - width and height may be changed
- Widgets give the layout algorithm a range of sizes as "hints"
- A containers size hints usually consider size hints of children

#### LayoutManager is a Strategy Design Pattern

- Factors out an algorithm into a separate object, allowing a client to dynamically switch algorithms

#### Java LayoutManager

- Container widgets can use different LayoutManagers
  - a LayoutManager is an "strategy" object that factors out the layout algorithm to size and position child widgets

### General Layout Strategies

#### Fixed Layout



## 3.0 Model-View-Controller

