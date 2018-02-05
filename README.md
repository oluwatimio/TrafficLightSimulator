# TrafficLightSimulator

To start the simulator run Main.java in .\core and enter argument lowTraffic, moderateTraffic and highTraffic.

This is Documentation -- 


In order to implement lowLight,Moderate and High, I made different classes that represent each. These classes LowTraffic, ModerateTraffic and HighTraffic
   * have their own classes that implement ther own timers. The classes with timers are (TrafficLightLow,TrafficLightHigh and TrafficLightModerate). I have done it this way because
   * the timer for the default TrafficLightX kept interfering with the timing event I wanted for low, moderate and high. Therefore, I decided to seperate each event into a different class.
   * 
   * In order to start low traffic, a low traffic object is made and it uses its own low traffic timing class (TrafficLightLow)
   * In order to start high traffic, a high traffic object is made and it uses its own high traffic timing class (TrafficLightHigh)
   * In order to start moderate traffic, a moderate traffic object is made and it uses its own timing class (TrafficLightModerate)
   * 
   * This method also allowed me add more timing events as I wanted without interferance to the default TrafficLightX
   * 
   * To start each traffic event run this Main File with an argument for the event you want to start. E.g java Main argument (lowTraffic)
   * 
   * If you want to run the default, just start the program E.g java Main. There is no argument in this case.
   * 
   * Please note: Do not enter multiple arguments!
   * 
   * Thank you for your time. :D
   * 
   * The code for how each traffic event is started is seen below.
   * 
* */
