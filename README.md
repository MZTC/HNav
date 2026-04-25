## 📁 Project Structure & Resources

The project consists of multiple components, including the navigation system, real-world dataset, and deployed models:

```
hierarchical_navigation/
├── dataset/
│   └── TR-SUB-125/              # Real-world rugged terrain benchmark (DEM-based)
│       └── https://huggingface.co/datasets/cbeat/TR-SUB-125
│
├── ros_pkg/
│   └── HRS_ROS/                 # Full ROS navigation system implementation
│       └── https://github.com/MZTC/HRS_ROS
│
├── planner/
│   └── (released with this repo) # Geometry-aware low-level planner
│
├── decision/
│   └── (coming soon)           # High-level RL policy (to be released)
```

### 🔗 External Resources

- **Real Terrain Dataset (TR-SUB-125)**  
  https://huggingface.co/datasets/cbeat/TR-SUB-125  

- **ROS Navigation Package (HRS_ROS)**  
  https://github.com/MZTC/HRS_ROS  

- **Low-Level Planner**  
  Included in this repository  

- **High-Level Decision Module**  
  Coming soon  
