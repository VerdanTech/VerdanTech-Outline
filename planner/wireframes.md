# Planner - Wireframes

The Planner pages are split into two groups:
- *Verdagraph*: a combination of three different views of the model state, mainly Plants, PlantingWindows, and Actions.
- *Workbook*: a list-like view of Actions optimized for assigning Actions among Users and using as a reference when carrying out tasks more conveninent than the Verdagraph.

# Verdagraph

The Verdagraph is split into three main views into the model state:
- *Tree*: Displays model attributes into a directory-like tree structure, with the goal of simplicity and easy keyboard navigability.
- *Calendar*: Displays model attributes into a grid-like temporal view, where models are organized as rows, and days are organized as columns.
- *Layout*: Displays model attributes according to their spatial layout.

All three of these windows are toggleable. They are supported by the following additional UI elements:
- *Timeline Selector*: Allows selecting a range of dates easily with the mouse and keyboard. This range dictates which model elements are visible in the Tree and Calendar, with the center of the range being the "selected day" which controls the day displayed in the Layout.
- *Toolbar*: A horizontal toolbar.
- *Form* A reusable component for storing a list of active forms (ex. "Add Plant", "Record Observation"), allowing the resuse of functionality between Tree, Calendar, and Layout.

![Verdagraph Structure Wireframe](./wireframes/verdagraph_structure.excalidraw.png)

![Verdagraph Structure Filled Wireframe](./wireframes/verdagraph_structure_filled.excalidraw.png)

## Tree

![Tree Wireframe](./wireframes/tree.excalidraw.png)

## Calendar

![Calendar Wireframe](./wireframes/calendar.excalidraw.png)

## Layout

![Layout Wireframe](./wireframes/layout.excalidraw.png)

## Toolbar

![Toolbar Wireframe](./wireframes/toolbar.excalidraw.png)

## Form

![Form Wireframe](./wireframes/form.excalidraw.png)

## Timeline Selector

![Timeline Selector Wireframe](./wireframes/timeline_selector.excalidraw.png)

# Workbook
