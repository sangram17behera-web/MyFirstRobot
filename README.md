How To Create

--------------------

Open Ui_path Studio, create a new process

Give a name ex:MyFirstRobot  and hit enter

Now you can see a blank page

Goto Activity Panel and search for use application/browser activity drag and drom to the blank page

Open a notepad and save it first keep it open so that the robot can read it correctly

Now open ui-path studio and click on indicate target and selet the notepad that opened in background.

it will automatically copy the path of the fine where it is saved.

Now click on activity panel and search for TypeInto activity now drag and drop the activity inside the application activity

click on "indicate target" to identify the place where to write 

now close the notepad, there is a option "type this" is side type into activity

write your own prompt with in a "" as you are inputing a string

we can search for message box in activity panel and drag it indide the sequence to show a message box which will appear after completation of the process

in Text option in message box type anything like ex: "thank you" inside "" as we are giving a string.

How to Run

-------------------

Click On debug file button

we can see that the Notepad open and closes quickly

After sucessful run when we open the note pad manually we  can see that the prompt is written inside the note pad.

Now to keep the notepad open after running the robot click on the application/browser activity  inside the sequence select proporties

Search for option close , click on the drop down option and select never option.

Now the Notepad will keep opened after the debug and run and you can see that the robot is automatically writing your prompt.

