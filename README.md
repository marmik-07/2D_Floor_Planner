2D Floor Planner

A Java Swing-based desktop application that enables users to create, customize, and visualize 2D floor plans interactively. Designed as part of an Object-Oriented Programming (OOP) project, this tool helps simulate floor layouts by allowing users to add rooms, place furniture, and include doors and windows — all with proper overlap and alignment checks.

-> Features

1) Room Creation with Color Coding
Add rooms like Bedroom, Bathroom, Kitchen, etc., with distinct floor colors
No room overlap — strict validation during placement

2)Relative Positioning & Alignment
Position rooms to the North, South, East, or West of existing rooms
Options for left, right, or center wall alignment
Automatic wall generation between connected rooms

3)Drag & Drop Editing
Click and drag rooms to reposition them on the canvas
Overlap validation with automatic "snap back" if invalid

4)Doors & Windows Placement
Add doors between rooms (represented by gaps in walls)
Add windows on external walls (represented by dashed lines)
Rules enforced: No overlapping, and no windows between rooms

5)Furniture & Fixtures Support
Add common furniture: bed, sofa, table, chair, etc.
Add basic fixtures: washbasin, commode, shower, kitchen sink
Rotate furniture in 90-degree increments
Images used for furniture to improve visual quality

6)Save & Load Functionality
Save floor plan layout in a custom format
Reload the exact state of the plan from saved files

-> GUI Overview
Canvas Panel: Occupies ~75% of the screen, used for floor drawing
Control Panel: Occupies ~25% of the screen, used for input, room/furniture selection, and operations
Fullscreen Mode: Optimized for large layouts and immersive editing

-> Room Color Codes
Room Type	          Color
Bedroom	            Green
Bathroom	          Blue
Kitchen	            Red
Dining/Drawing	    Yellow/Orange
Walls	              Black
Outside/Background	Light Gray

-> Technologies Used
Java
Java Swing (GUI framework)
Object-Oriented Design Principles

-> Project Structure
Main.java — Main entry point and GUI initializer
TFrame.java — GUI layout: canvas and control panels
Room.java — Room representation, alignment, and validation logic
Door.java / Window.java — Elements to manage openings
Furniture.java — Handle placement, rotation, and image rendering
SaveLoad.java — File operations to persist and retrieve floor plans

-> Future Enhancements Goals
Snap-to-grid or wall features
Custom wall drawing (non-orthogonal walls)
Undo/Redo support
Export plan as PNG/PDF

