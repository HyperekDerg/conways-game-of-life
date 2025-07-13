# Conway's Game of Life - RPLIFE

Conway's Game of Life in your terminal!

This Python project brings the classic Game of Life to life in a terminal-based application.
You can dynamically simulate patterns and observe the evolution of cells over generations.

## Features

- Interactive terminal simulation.
- Configurable patterns via patterns.toml.
- Lightweight and easy to set up.

## Installation and Setup

1. Clone the repository:

```bash
   git clone git@github.com:HyperekDerg/conways-game-of-life.git
```

2. Navigate to the repository:

```bash
   cd conways-game-of-life
```

3. Set up a virtual environment:

```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
```

4. Install dependencies and application:

```bash
   pip install .
```

## Running the Application

Activate the virtual environment (if not already active) and run the application.

Usage:
```
rplife [-h] [--version] [-p {Blinker,Toad,Beacon,Pulsar,Penta Decathlon,Glider,Glider Gun,Diehard,Bunnies,Beahive,MWSS,HWSS,Pentomino}] [-a] [-v {CursesView}] [-g NUM_GENERATIONS] [-f FRAMES_PER_SECOND]
```
Options:

- **-h, --help**: Show help message and exit
- **--version**: Show program's version number and exit
- **-p, --pattern** {Blinker,Toad,Beacon,Pulsar,Penta Decathlon,Glider,Glider Gun,Diehard,Bunnies,Beahive,MWSS,HWSS,Pentomino}: Select a pattern for the Game of Life (default: Blinker)
- **-a, --all**: Display all available patterns in sequence
- **-v, --view** {CursesView}: Select the visualization mode (default: CursesView)
- **-g, --gen** NUM_GENERATIONS: Specify the number of generations (default: 10)
- **-f, --fps** FRAMES_PER_SECOND: Adjust frames per second (default: 7)

## Customizing Patterns

You can modify or add new patterns by editing the patterns.toml file located in the rplife folder.


## MIT License

Copyright (c) 2025 Jakub Rudnicki

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
