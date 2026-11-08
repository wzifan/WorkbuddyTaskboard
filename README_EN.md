# WorkBuddy Taskboard

#### Concept and Highlights

- Tasks fall into three categories: Work, Study, and Life.
- The grouped task list is for everyday task capture.
- Every task supports fixed, earliest, or latest start and end times.
- Schedule near-term or predictable tasks, or temporarily schedule tasks to estimate when they will be finished.
- Each task's schedule is continuous and cannot be split. Work and non-work time are scheduled independently.
- Time is measured in 0.5 half-day units. Each task tracks completed time and total estimated time.
- A scheduled task is complete when its completed time equals its total estimate, and incomplete when its completed time is less than its total estimate.
- For a task currently on the schedule, completed time increases automatically as scheduled time passes. Once it reaches the estimate, the task is marked complete. If the work is not actually finished, increase the total estimate or reduce the completed time in the task's properties. Completed time cannot be edited for scheduled tasks with a fixed start time.
- Press and hold tasks in the calendar or task list to drag them.

#### Features

1. **Quick capture:** New regular tasks are not scheduled by default. No duration or date is required.
2. **Optional scheduling:** Choose whether each task participates in scheduling.
3. **Calendar dragging:** Move a task's calendar block as a whole. The task list updates its order and times accordingly.
4. **List and calendar updates:** Move tasks up or down in the schedule view to adjust their calendar positions.
5. **Navigation between views:** Click a calendar task block to locate its entry in the list. Click the task's time in the list to locate its calendar block.
6. **Calendar short names:** Give tasks a separate short name for display on the calendar.
7. **Fixed times:** Fix a task's start or end time. Fixed schedules cannot be changed by dragging or moving tasks up or down.
8. **Time constraints:** Both start and end times support "no earlier than" and "no later than." If a task cannot fit, the app explains why.
9. **Gaps and breaks:** Fixed time requirements may create gap entries ("空"). These can be converted into break tasks.
10. **Automatic completion:** See [**Concept and Highlights**](#concept-and-highlights).
11. **Working days and days off:** Click a date number to switch between a working day and a day off. You can also restore the official calendar.
12. **Archive and restore:** Archive completed tasks to keep their records, and restore them when needed.
13. **Mobile use:** The interface has been extensively optimized for phones.
14. **Cloud synchronization:** Automatically sync with the WorkBuddy Library and access the taskboard from multiple devices at the same time. **This took the most development time and has been extensively refined.**
15. **More details are to discover!**

#### Getting Started

##### 1. Download the project

###### Option 1 — Clone with Git

Run this command.

```shell
git clone https://github.com/wzifan/WorkbuddyTaskboard.git
```

###### Option 2 — Download a ZIP from the repository

- On Gitee, click **Clone/Download** (`克隆/下载`), then **Download ZIP** (`下载zip`).
- On GitHub, click **Code**, then **Download ZIP**.

###### Option 3 — Download a release ZIP

In the right sidebar, select a version under **Releases**, such as `v1.8.1`. Then choose **Source code (zip)** from the release downloads.

##### 2. Deploy the local files to the WorkBuddy Library for cloud synchronization and access across devices

In WorkBuddy, set the working directory to `WorkbuddyTaskboard/待办工作台_公开_云端同步/{版本号}` and select the `工作台搭建师` (Workbench Builder) expert. Use the prompt provided in `WorkbuddyTaskboard/待办工作台_公开_云端同步/{版本号}/加载到云端的提示词.txt`.

Replace `{版本号}` with the version folder you want to use.

#### License

Apache License 2.0
