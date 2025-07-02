# CPU Scheduling Algorithms Visualizer

This project is a web-based visualizer and simulator for various CPU scheduling algorithms, including:

- **FCFS** (First-Come, First-Served)
- **SJF** (Shortest Job First)
- **SRTF** (Shortest Remaining Time First)
- **RR** (Round Robin)

It allows users to input process details, select an algorithm, and view the scheduling results along with a Gantt chart and summary statistics.

## Features

- **Interactive Input:**
  - Set the number of processes (up to 10).
  - Enter burst time and arrival time for each process.
- **Algorithm Selection:**
  - Choose from FCFS, SJF, SRTF, or RR (with configurable time quantum).
- **Output Table:**
  - Displays completion time, turnaround time, and waiting time for each process.
- **Gantt Chart:**
  - Visualizes the execution order and timing of processes.
- **Summary:**
  - Shows average turnaround time and waiting time.

## Usage

1. **Clone or Download the Repository**
2. Open `index.html` in your web browser.
3. Set the number of processes and input their burst and arrival times.
4. Select a scheduling algorithm and (if using RR) set the time quantum.
5. Click **Start Scheduling** to view the results.

## Technologies Used

- HTML5, CSS3, JavaScript (Vanilla)

## Project Structure

```
OS/
  ├── index.html
  └── README.md
```

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Created for Operating Systems coursework and educational purposes.*

## Developer

**Yahya Imthiyas**  
Contact: [yahyaimthiyas2005@gmail.com](mailto:yahyaimthiyas2005@gmail.com) 
