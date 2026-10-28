# WorkBuddy Taskboard

#### Overview and Approach

WorkBuddy Taskboard is a web app that connects your task list with a calendar. It is designed for people managing work, study, and everyday commitments. Project tasks, courses, and planned activities each have their own details and timing requirements. The list holds what needs to be done, the calendar shows when it is scheduled, and each task retains the time already counted toward completion.

Loose ideas and tasks without a set date can stay in the list. Tasks coming up soon can be scheduled based on their estimated duration. Tasks with firm commitments can have date constraints, while longer-term items can be recorded now and scheduled closer to the date. Changes in the list and calendar stay in sync. As scheduled time passes, it is counted toward completion; if more time is needed, the estimate can be increased without losing the progress already recorded.

The app can be used to move projects forward, plan study sessions, or keep track of everyday errands and outings. It runs in a browser on both phones and computers. The cloud version synchronizes tasks, schedules, and progress so you can continue on another device. Open the app to explore the features with the sample tasks, or begin with your own first task.

#### Features

1. **Categories and groups**: Organize tasks into Work, Study, and Life categories, with groups for related items. Press and hold a task to change its position within a group.
2. **Quick capture**: New tasks stay in the list by default, with no need to enter a duration or choose a date right away.
3. **Optional scheduling**: Set an estimated duration and enable scheduling for tasks that need a place on the calendar. Work and non-work time slots are scheduled separately.
4. **Calendar dragging with a live list preview**: Drag calendar blocks to adjust the schedule. Irregularly shaped blocks spanning multiple slots, such as a task estimated at 1.5 half-day units, can be moved as a whole. The list previews the updated order and times during the drag, and both views update when the block is dropped.
5. **List reordering with calendar updates**: Move tasks up or down in the schedule view to change their order. The corresponding calendar blocks move with them.
6. **Navigation between views**: Click a calendar block to locate its task in the list. Click a task's time information to find it on the calendar.
7. **Calendar short names**: Keep a task's full title in the list and give it a separate short name for easier recognition in small calendar cells.
8. **Fixed start or end times**: Set a fixed start or end date and time slot to preserve an arrangement that has already been agreed upon.
9. **Time constraints and conflict messages**: Set constraints such as "no earlier than" and "no later than." If requirements conflict or a task cannot fit into the schedule, the app explains why.
10. **Future tasks**: Record future commitments or deadlines now and schedule them closer to the date, keeping distant plans from filling the calendar.
11. **Gaps and breaks**: Time constraints may leave gaps between scheduled tasks. These gaps can also be turned into break tasks.
12. **Automatic completion and extended estimates**: As scheduled time passes, the app accumulates time credited toward completion and marks the task complete once its scheduled time has elapsed. If the work is not actually finished, increasing the total estimate reopens the task while retaining the time already credited.
13. **Working days and days off**: Click a date number on the calendar to switch that day between a working day and a day off. Related schedules adjust accordingly.
14. **Archive and restore**: Archive completed tasks while keeping their records. Restore them to the list whenever needed.
15. **Mobile access**: View the calendar, organize tasks, adjust estimates, and set time constraints on a phone.
16. **Cloud synchronization**: Continue viewing and editing across devices. Cloud updates are coordinated with ongoing edits and drag operations; saved changes are checked, and sync errors are reported.

#### Getting Started

###### 1. Clone the repository

```shell
git clone https://github.com/wzifan/WorkbuddyTaskboard.git
```

###### 2. Sync the local files to the WorkBuddy Library for cloud synchronization and access across devices

In WorkBuddy, set the working directory to `WorkbuddyTaskboard/待办工作台_公开_云端同步/{版本号}` and select the `工作台搭建师` (Workbench Builder) expert. Use the prompt provided in `WorkbuddyTaskboard/待办工作台_公开_云端同步/{版本号}/加载到云端的提示词.txt`.

Replace `{版本号}` with the version folder you want to use.

#### License

Apache License 2.0
