# HouseChores

Works on automating house chores for the common room of four campus hostel.
For this given room,the tasks for allocation are: Cleaning the room(mopping),Dishes and buying greens.
The script runs with an already made xlsx template file wit the following weeks timetable relying on the previous week.
The chores run on a repetitive loop every week.

Once a timetable is made on the running machine,it is(by choice) sent to the respective room members whos email addresses are kept in a csv file as a contacts file

### Usage
```sh
python complete_chores.py -i HouseChores.xlsx -o Updated_HouseChores.xlsx
```

### To-do
- Add text message functionality
- Allow new timetable(for new room) to be made without knowledge of the past
