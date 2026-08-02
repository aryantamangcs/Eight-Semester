## Reference Model

Reference model is the framework or blueprint that acts as a standard guide to how a system is organization and how it's components interact with each other.


Data -> Sorted -> Arranged -> Presented Visually


## Process in Visual Reference Model

The visual reference model explicitly breaks the process into following steps

- Data cleaning and Structural organization.
- Mapping data features to physical geometric properties (shapes, colors, properties)
- Rendering pixels, and managing User Interactions.

## INFOVIS Reference Model (Information Visualization Reference Model)

It is a visual reference model designed by Card, Mackinlay and Shneiderman that maps how raw data gets mapped into interactive visual image.

![[../../../Inbox/Pasted image 20260802193458.png]]


## Stages Of The Model

#### 1.1 Raw Data
- The original, unprocessed, messy data 

#### 1.2 Data Tables
- A table where the raw data is cleaned and organized and put in terms of rows, columns and relations.

#### 1.3 Visual Structures
- The stage where the data items gets mapped to the physical geometric properties such as line, color, shape etc

#### 1.4 Views
- The final rendered graphic images on the screen. In this stage, the pixels are rendered and user interactions are managed.

## Transformation and Control

#### 1.1 Data Transformation 

The process which converts raw data into the organized tabular data via data cleaning, sorting, filtering and organization.

#### 1.2 Visual Mapping

Transforms data items into geometrical graphical properties like position, color and size.

#### 1.3 View Transformation

Renders the visual structures into the canvas

#### 1.4 Human Interaction

Allows human to interact with the graphics by zooming, filtering or re-encode what they see.


## Reference model for Adaptive Visualization System

It is a conceptual framework that explains how a visualization system automatically changes it visual presentation based on the user, data or task.

## Components of the Reference Model

### 1. User

The system first considers **who is using it**.

Examples:

- Beginner
- Student
- Data analyst
- Business executive

Different users require different visualization styles.

**Example**

A beginner may need:

- Labels
- Explanations
- Simple bar charts

An expert may prefer:

- Scatter plots
- Interactive dashboards
- Multiple linked views

---

### 2. User Characteristics

These describe the user's profile.

They include:

- Experience level
- Domain knowledge
- Preferences
- Cognitive ability
- Goals

**Example**

Two users are viewing sales data.

Student:

- Wants simple graphs.

Manager:

- Wants KPIs and summary dashboards.

---

### 3. Data Characteristics

The system analyzes the data before selecting a visualization.

Characteristics include:

- Data type
    - Numerical
    - Categorical
    - Temporal
    - Spatial
- Number of variables
- Data size
- Data quality

**Example**

|Data|Best visualization|
|---|---|
|Monthly sales|Line chart|
|Product categories|Bar chart|
|Market share|Pie chart|
|Height vs Weight|Scatter plot|

---

### 4. Task Characteristics

The visualization depends on **what the user wants to do**.

Possible tasks:

- Compare values
- Find trends
- Detect outliers
- Find relationships
- Show distribution
- Monitor performance

**Example**

If the task is:

- Compare products → Bar chart
- Show change over time → Line chart
- Show correlation → Scatter plot

---

### 5. Adaptation Engine

This is the **brain** of the adaptive visualization system.

It combines:

- User characteristics
- Data characteristics
- Task characteristics

Then decides:

- Which chart to use
- Colors
- Layout
- Labels
- Level of detail
- Interactivity

---

### 6. Visualization Generator

This component creates the actual visualization based on the adaptation engine's decisions.

It may generate:

- Bar charts
- Line charts
- Pie charts
- Scatter plots
- Heatmaps
- Dashboards

---

### 7. Adaptive Visualization

This is the visualization presented to the user.

It adapts automatically.

Examples:

- Large dataset → Zoomable chart
- Mobile device → Simplified layout
- Color-blind user → Accessible color palette
- Beginner → Detailed labels and explanations

---

### 8. User Interaction

The user can interact with the visualization by:

- Zooming
- Filtering
- Sorting
- Selecting data
- Drilling down
- Changing parameters

---

### 9. Feedback Loop

The system observes the user's interactions and updates future visualizations.

For example:

- If the user frequently switches to line charts, the system may recommend line charts by default.
- If the user often zooms into detailed views, the system may present more detail automatically.

---

