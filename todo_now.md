# FQM 0.7

### To Fix :

- [x] ~~Fix common task tickets bread crumbs counter~~ (2020-01-31)
> Default tickets incrementing behavior was altered which resolved the issue
- [x] Refactor `manage` and `core` endpoints (2020-02-07)
- [x] Always hit tasks with office id to fix possible random redirection (2020-02-02)
- [x] ~~Arabic GUI fonts on Windows~~ (2020-02-09)
> Only effects Windows 10 with high DPI
- [x] Fix multimedia unused files always showing up as used (2020-02-17)
- [x] Fix video none-responsive resolution (2020-02-17)

### To Add :

- [x] Add flag setting to enable or disable common office strict tickets pulling (2020-02-05)
- [x] Add migration setup with `flask-migrate` to avoid dropping tables with each release (2020-02-09)
- [x] Pre-load waiting tickets from `/feed` to reduce text-to-speech generation latency (2020-02-09)
- [x] Add option to disable all the transition effects and reddit-wallpapers (2020-02-10)
- [x] Pull random ticket from `tasks` or `offices` (2020-02-10)
- [x] Option to display ticket number beside name on `display` screen (2020-02-12)
- [x] Put random ticket on-hold (2020-02-10)
- [x] Add time-spent-waiting column in `tasks` and `offices` (2020-02-15)
- [x] Add printed ticket font size scaling (2020-02-16)

- [x] Multiple Touch screen support **based on offices** (2020-02-13)
- [x] Multiple Display screen support **based on offices** (2020-02-13)
> - [x] Add multiple display screen routing
> - [x] Add dynamic `/feed` to handle any office
> - [x] ~~Refactor display customization to handle multiple offices~~ **Move to backlog**

- [x] Add `core` and `manage` full test coverage (2020-02-07)
- [x] ~~Add windows build automation script~~ **Move to backlog**
