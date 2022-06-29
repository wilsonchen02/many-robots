## Table of Contents

[Project Overview](#project-overview) \
[Software Components](#software-components) \
[Usage](#usage)

---

## Project Overview
This project features a simulator for the navigation of multiple robots through a maze. The code shall be written in Python. This simulator is created as realistically to a real scenario so that any future projects using real hardware could potentially be made.

---

## Software Components

#### Maze
The maze is a 16x16 grid. There may be multiple layers and elevators.

#### Robots

There shall be multiple robots in a maze. Each robot may only see what is around it. Robots are controlled by the station. Each robot has a certain speed.

#### Cloud

The cloud stores all the data of the maze and controls the robots. It also sends data back to home. The cloud also controls the window/screen that show the robots in the maze and provides some insight on how the cloud is solving its algorithm. Realistically, this screen would not ever be made.

#### Home

Home receives data from the cloud to see what is going on in the maze at all times. The home also controls the window/screen that shows the actual locations of the robots in the maze. This is to reenact what an actual home would see. 

#### Creator

The creator loads in all the information of the maze and the robots as well as their starting positions. This also controls the window that lets you make the settings

#### Timer

The timer keeps track of time.

#### World

The world keeps track of all the objects

#### Direction

The directions are North, East, South, and West.

---

## Usage

Not ready to be used yet.
