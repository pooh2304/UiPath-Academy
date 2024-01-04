### UiPath Studio Interface
- Ribbon
    - Home (Backstage View), Design, Debug
- Designer Panel 
    - Variables, Arguments, Imports
- Left Side Panel
    - Project, Activities, Snippets
- Right Side Panel
    - Properties, Data Manager, Outline, Object Repository, Test Explorer
- Down Side Panel
    - Output Panel, Find References,  Error List, Breakpoints

<br>Q. <br>

| Capabilities                                                                                             | Description                                                                                                        
|----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| Identify and remove errors that prevent the project from working correctly:                              | By running the file or project in debug mode.                                                                  |
| Purposely pause the debugging process on an activity which may trigger execution issues:                 | From the context menu, right-clicking the activity and selecting Toggle Breakpoint.                            |
| Update a project dependency package:                                                                     | By right-clicking the dependency, selecting Manage, then updating to the needed version.                       |
| Show or hide messages that have different log levels, errors, or warnings in Studio:                     | From the Output panel by clicking the buttons in the panel's header.                                           |
| View and configure the properties of a selected activity:                                                | From the Properties panel.                                                                                     |
<br> 

#### Automation Implementation Process
- Capturing the 'as-is' and 'to-be' process steps (Business Analyst)
- Documenting the process steps (Solution Architect)
- Signing-off the PDD from Business Team (Project Manager)
- Designing the solution (Solution Architect)
- Developing the solution (Automation Developers) <br><br>


Q. What are some automation best practices to consider when automating a project? Choose all applicable answers. <br>
**Workflow files, activities, arguments, and variables should have meaningful names, to accurately describe their usage throughout the project. <br>
Choosing the appropriate layout type for the process we are building (sequences, flowcharts, state machines). <br>
Using a Version Control System to easily manage project versioning and sharing the work of more developers. <br>**
Making sure that output files are deleted at the beginning of processes before running. <br>
**Using Upper Camel Case naming convention for workflows. <br>** <br>


Q. How can we purposely pause the debugging process on an activity which may trigger execution issues? Choose one of the answers. <br>
**By right-clicking the activity, and selecting Toggle Breakpoint to add and enable the breakpoint. <br>** 
By using the Step Out button from the Debug tab while debugging. <br>
By enabling the Highlight Elements function from the Debug tab before debugging. <br>
By using the Step Into button from the Debug tab while debugging. <br><br>


Q. How can we publish to the 'Orchestrator Personal Workspace Feed'? Choose one of the answers. <br>
**By first enabling the option in Orchestrator and then selecting 'Orchestrator Personal Workspace Feed' when publishing in Studio.** <br>
By making sure that the user has the 'Automation Developer - Named user' license assigned in the Automation Cloud. <br>
By selecting the 'Assistant (Robot defaults)' option when publishing in Studio. <br>
By connecting to Orchestrator. <br>


### Check Your Understanding
1. How can we run the project in debug mode in Studio? Choose one of the answers. <br>
**By clicking Design or Debug ribbon tab, then clicking Debug File drop-down list and selecting Debug Project.** <br> 
By clicking Debug ribbon tab, then clicking Debug File drop-down list and selecting Run Project. <br>
By clicking Debug ribbon tab, then clicking Debug File drop-down list and selecting Run File. <br>
By clicking Debug ribbon tab, then clicking Remote Debugging. <br><br>

2. When should we use the 'If' activity within a workflow in Studio? Choose one of the answers. <br>
When we want to perform an activity or a series of activities, specified in the 'Body' section, on each element of a collection. <br>
When we want to rename a specified file. <br>
**When we want our process to take one of two different courses of action, depending on whether a specified condition is met. <br>**
When we want to write a specific message at the specified level.<br><br>

3. What is one way to add an activity to the workflow in Studio? Choose one of the answers. <br>
By right-clicking inside the workflow where we want to add the new activity and selecting Run to this Activity. <br>
By clicking the Project panel, typing in the Search bar the keyword, then just drag and drop it in the workflow. <br>
**By clicking the Activities panel, selecting the needed activity from the Available activities or just search for the keyword inside the Search bar, then drag and drop it inside the workflow. <br>**
By clicking the Project panel, then just right-click inside it, click Add and select the needed activity.<br><br>

4. What Studio activity can we use when working with files in a folder and want to repeat one or more activities for each individual file? Choose one of the answers. <br>
Use Excel File <br>
**For Each File in Folder <br>**
Delete File <br>
For Each <br><br>

5. For the following panels in Studio, what is their correct description? Match the description with the panel it corresponds to. <br>

| Panel                | Description                                                                                        |
|----------------------|----------------------------------------------------------------------------------------------------|
| Properties Panel     | It's contextual and enables us to view and change the properties of a selected activity.           |
| Project Panel        | We can manage project files, dependencies, and configure project settings.                         |
| Designer Panel       | We can manage the activities added to the current workflow file.                                   |
| Output Panel         | See log messages output, status information for the project execution, errors, and more.           |
| Activities Panel     | We can view all available activities and add activities to our automation.                         |
| Data Manager Panel   | Allows us to manage various types of data in our automation project.                               |
<br>

6. How do we open the project's location on the machine in Studio? Choose one of the answers. <br>
By clicking Project panel and selecting the Expand All option. <br>
**By clicking Project panel and selecting the File Explorer option.** <br>
By clicking Project panel and selecting the Project Settings option. <br>
By clicking Project panel and selecting the Show All Files option. 
