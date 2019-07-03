
# Timeline Visualization

The purpose of this Excel sheet is to plot parallel timelines. 
It could be adapted to suit a set of courses you are enrolled in, or sprints in a scrum activity. 

The sheet file is called `Timeline Viz.xlsx` and can be found in this repository's main directory.  

![Snapshot of the timeline sheet](https://github.com/alkashef/timeline-visualization/raw/master/Snapshot.png)

## Elements of the Sheet

The sheet consists of two sections: A table and a chart.

### The Table

- Each row in the table represents a task.
- Each column represent a property of that task (e.g. when it starts, when it ends, etc.).
- Yellow cells (columns) are calculations. You don't need to put values in them manually. The values will be automatically calculated.

### The Chart

- The timeline (horizontal axis) is divided into weeks. 
- The vertical axis represent the span of each task. So each horizontal bar represents where a specific task starts and where it ends.
- The red portion of the bar represents the past (before the current date) and the black portion of the bar represents the future.

## Future work

- Let the horizontal axis minimum and maximum values automatically adjust themselves to accommodate the data entered in the table.
- Let the width/color of the horizontal bar reflect task properties (e.g. category).

## License 

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Courses Timeline Sheet by Ahmad Al-Kashef is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
