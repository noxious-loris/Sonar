SONAR
	#DESCRIPTION
		this project uses an arduino uno and a sonar to calclate the distance between it and some other subject to move around it uses a servo
	#CODE DESCRIPTION
		the trigger pin is set to 8 and echo pin is 9
		in the frist line's of the code we initialize a vsriable from 15 to 165 the servo moves from 15 degrees to 165 degrees
		int second for loop the same angles are implemented but from 165 to 15 degrees both moving with a time ddelay of 30 sec
		in the function calculate distance the triggerpin is first set to low and if a subject is detected it sets it to high for 10 microseconds
		the distance is calculated by taking the duration and multiplying it with a factor of 0.034/2



