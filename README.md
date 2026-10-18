# RoboDog_electronic
Components used: HC SR-04 module,ESP32,single horn servo motor

->The trig pin of HC SR-04 generates ultrasonic wave for certain time length calculated by echo pin which is used to find distance in centimeters for our task.
->Using the calculated distance tail is controlled, wagging alters with change of given parameters in task
->LED turns on if distance<=10 while the tail stops wagging
->the pushbutton freezes the tail in between for 3 seconds

Problems faced: As shown in the video the stoppage time of 3 seconds occurs when the button is released. I want it to work like the 3 seconds should start the 
                moment button is pressed but failed to achieve so.
