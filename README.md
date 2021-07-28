# bot-o-mat project

**Project structure.**

1. reports :- Folder for reports generation
2. config file
3.  get_efficient_roborepo_name
4.  get_efficient_robotype
5.  main
6.  summary_report
7.  view_detail_report
8.  view_report

**1. Instruction to Run the project:**
1. Download this folder to your local directory.
2. Open Command Line Interface.
3. cd  'path to the directory where you have download this project'


**2 . How to use this application**
1. Run 'python main.py' command

Enter robot name:Larry
select robot type:
1) Unipedal
2) Bipedal
3) Quadrupedal
4) Arachnid
5) Radial
6) Aeronautical


Enter number: 3

Roboname "LARRY(Quadrupedal)" Executing Task "MAKE A SAMMICH" [==============================] 100% Completed

Roboname "LARRY(Quadrupedal)" Executing Task "RAKE THE LEAVES" [==============================] 100% Completed

Roboname "LARRY(Quadrupedal)" Executing Task "GIVE THE DOG A BATH" [==============================] 100% Completed

Roboname "LARRY(Quadrupedal)" Executing Task "BAKE SOME COOKIES" [==============================] 100% Completed

Roboname "LARRY(Quadrupedal)" Executing Task "SWEEP THE HOUSE" [==============================] 100% Completed


**2. How to Run reports **
 1. Run 'python view_report.py' command

select report type:
1) View detail report
2) View report by RobotType
3) View report by RobotName
4) Summary Report


Enter number: 1
-----------------------------------------------------------------------
Robot Name | Type        | Task                | ETA(ms) | Status    |


-----------------------------------------------------------------------
Larry      | Quadrupedal | make a sammich      | 7000    | Completed |


-----------------------------------------------------------------------
Larry      | Quadrupedal | rake the leaves     | 18000   | Completed |


-----------------------------------------------------------------------
Larry      | Quadrupedal | give the dog a bath | 14500   | Completed |


-----------------------------------------------------------------------
Larry      | Quadrupedal | bake some cookies   | 8000    | Completed |


-----------------------------------------------------------------------
Larry      | Quadrupedal | sweep the house     | 3000    | Completed |



**Reports populated Under Reports folder:-**

We can view this data in CSV format too.

detail_task_records.csv

robot_name.csv

robot_type.csv




