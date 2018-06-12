# 🚙

# Data Analysis & Visualization of Uber Vienna from 7/3/2016 to 7/30/2016

For this capstone project i will be analyzing some Uber Vienna call data from [Uber Movement Vienna](https://www.uber.com/en-ID/cities/vienna/) in March 2016. 
____
This Uber analytical assessment is modeled after real-world challenges that the company faces. Read the following terms, and get a feel for how they relate to each other in the context of Uber’s business model. 
* **“Supply”** — The number of available Uber cars on the road.
* **“Demand”** — The number of users looking for a ride at any given time.
* **“Request”** — The number of people who have requested an Uber car within the app.
* **“Accept”** — The number of requests that were accepted by drivers
* **“Cancellation”** — an accept that is cancelled by the user before it is completed. Usually users can cancel requests for free within a certain period of time (often 5 minutes) after making them; afterwards, users are charged a nominal fee.
* **“Completed requests”** — The number of requests that were fulfilled (i.e., resulted in a completed ride). If not given, “completed requests” are usually equal to “accepts” minus “cancellations”.
* **“Eyes”** or **“eyeballs”** — The number of people who opened the Uber app within a given period of time.
    * If a single person opens the app twice within the given period of time, he or she is still only counted as one eyeball.
    * Eyeballs are not equal to requests. Remember, requests means the number of users looking for a ride; whereas eyeballs means the number of people who have opened the app.
* **“Zeroes”** — People who opened the Uber app but could not call a car because there were no available drivers within range.
    * A ‘zero’ usually occurs when demand exceeds supply within a given market.
    * With supply constant, as demand rises, more zeroes are likely to occur.
    * Zeroes are bad for Uber, because they mean lost revenue.
    * Whenever there is demand for an Uber car that the company is not able to fulfill, it means money lost.
* **“Utilization”** — A general metric that measures what percentage of driver time is being effectively utilized within Uber’s marketplace. Utilization can be measured a number of different ways, and you may be asked about the most effective way to measure it on your test.
    * One potentially useful metric to measure utilization is “driver time spent driving” divided by “total driver time”. This metric helps Uber measure whether drivers are spending a significant amount of time sitting around waiting for jobs. If they are, it’s poor driver experience — and it represents potentially lost profits for Uber.
* **“Fares”** — The total dollar value of fares paid to Uber by riders within a given period of time.
    * Remember, fares are not equal to Uber’s profit, since Uber has to pay its drivers a percentage of fares.
* **“Surge pricing”** — dynamic pricing that rises when demand is significantly greater than supply.
    * Surge pricing is used to make Uber (and drivers) more money during times in which many people want to call a car (i.e. there is significant demand).
    * Usually, surge pricing is activated when demand starts to exceed supply.
* **“Accept rate”** — The percentage of rides (i.e. driving jobs) offered to a given driver that the driver accepted.
* **“Rating”** — The average of all star ratings assigned to a driver by the users who have ridden with that driver; or, the average of all star ratings assigned to a user by the drivers who have served that user.
____
In this analysis, some notion of statistics and hypothesis test are used but are very easy to follow. This [handbook of statistics](http://www.biostathandbook.com/index.html) can be used as a reference to explain basics.

