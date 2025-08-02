# 🤖 Warehouse Robot Multi-Agent Simulation


## 🎯 Overview

This simulation models a warehouse environment where multiple autonomous robots coordinate to complete pickup/delivery tasks while managing battery levels, avoiding obstacles, and preventing collisions. The system uses a **decentralized auction mechanism** for task allocation, demonstrating how complex multi-agent coordination can emerge from simple local rules.

## ✨ Features

### 🤖 **Multi-Agent Coordination**
- 3 autonomous robots with different capacities (6-10 units)
- Decentralized decision making - no central controller
- Real-time collision avoidance and path replanning

### 🏭 **Realistic Warehouse Environment**
- 12x12 grid warehouse layout
- Randomly placed obstacles and tasks
- Multiple charging stations for battery management
- Dynamic task generation with weights and priorities

### 🧠 **Intelligent Behaviors**
- **A* pathfinding** for optimal route planning
- **Auction-based task allocation** - robots bid on tasks based on distance and battery level
- **Battery management** - automatic charging when power runs low
- **State machine** - idle/moving/charging states with smooth transitions

### 📊 **Real-time Visualization**
- Color-coded robots with unique identifiers
- Battery level indicators with low-power warnings
- Task completion tracking and robot status display
- Visual charging indicators and path planning

### 🎮 **Interactive Controls**
- **SPACE**: Pause/Resume simulation
- **R**: Reset simulation to initial state
- **ESC**: Exit application

#
