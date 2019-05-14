Create a function called giveSpeedingTicket that requires three arguments: currentSpeed, speedLimit, isSchoolZone.
The function returns either True or False. It returns True if isSchoolZone is true and the currentSpeed is above the speedLimit.
It also returns True if isSchoolZone is false and the currentSpeed is more than 10% above the speedLimit. Otherwise it returns False.

Input &rarr; Output

giveSpeedingTicket(21, 20, True) &rarr; True

giveSpeedingTicket(19, 20, True) &rarr; False

giveSpeedingTicket(999, 55, False) &rarr; True

giveSpeedingTicket(59, 55, False) #above the speed limit but not 10% above &rarr; False
