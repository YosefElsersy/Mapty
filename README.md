---

# Mapty

Mapty is a JavaScript web application that helps users track their workout activities such as running and cycling by marking them on a map. Users can log workout details including distance, duration, pace, and speed, and visualize these workouts directly on an interactive map. The app stores data locally, allowing workouts to be persistent across sessions.


## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Track workouts with details like distance, duration, pace (for running), speed (for cycling), and elevation gain.
- Mark the exact location of the workout on an interactive map.
- Persistent data storage using localStorage to retain workouts across sessions.
- View workouts in a list and on the map.
- Different forms for running and cycling.
- Ability to click on a workout and move to its location on the map.

## Demo

You can check out a live version of Mapty at: **[[Demo Link](https://mapty-lemon.vercel.app/)]** (Add your deployed link here).

## Technologies

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Leaflet.js** for interactive maps.
- **LocalStorage API** for data persistence.

## Getting Started

### Prerequisites

To run this project locally, you will need:

- A web browser that supports JavaScript ES6.
- An internet connection to load Leaflet.js maps.

### Installation

1. **Clone the repository**:

```bash
git clone https://github.com/YosefElsersy/Mapty.git
```

2. **Navigate into the project directory**:

```bash
cd Mapty
```

3. **Open `index.html` in your browser**.

Alternatively, you can use a local server (like Live Server in VS Code) to serve the files.

## Usage

- **Start a workout**:
    1. Allow the app to access your location.
    2. Click on the map to specify the location of your workout.
    3. Fill in the workout form (choose between running or cycling).
    4. Submit the form to save your workout.

- **View saved workouts**:
    - Workouts are displayed in the sidebar as a list. You can click on any workout to move the map to its location.

- **Store workout data**:
    - Your workout data is stored locally in the browser's localStorage, so the next time you load the app, your workouts will still be there.

## Contributing

If you'd like to contribute to this project, you can follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.

---
