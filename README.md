This project contains example data for a merger and aquisition scenario in the `data_room/` folder.  We focus on the `data_room/people` folder more closely.  Here, you will find the initial output of the instructor's AI in `people_headcount_app.py`.

To run the Streamlit app:

```bash
streamlit run people_headcount_app.py
```

The app loads the roster from `data_room/people/employee_roster.csv`. Use the sidebar slider to set a target headcount and choose compensation prioritization.

SCREENCAPTURE: To make screencapture for Unit 2.2.2 easier, copies of `people_headcount_app.py` from `m02-[c-e]` have been added to this repo and named `pha-[c-e].py`. In this way, we can run the app for all 4 code versions without restarting a CodeSpace each time, which takes a long time. This works because the browser doesn't show the program name in the address bar.
