
Chapter 1
1. What is horizontal stacking and how does it relate a lamda layer?
It refers to a system scale up by adding more machines instead of upgrading them, it relates because of we must parellize our computation.

2. What is the purpose of a speed layer? 
The speed layer must use low complexity algorithms in order to process realtime data for it to be later updated by the batch layer. This ensures no data is lost or corrupted.

3. Why is a queue needed for scability? 
Because without a queue we would overflow and our application will crash, losing valuable data, because requests would time out.

4. What advantages does a lambda layer provide?
Scaling, Robustness and Predictability: your system will be able to collect more data and maximize its value, you can easily fix problems and build from the master.


Chapter 2 
1. What happens if the master gets corrupted?
Although it must be protected from it, because it is where all the information will derive, this is usually handled by master backups or several master datasets.

2. How does the fact based model stores raw data?
As atomic facts, because they can't be divided into useful components.

3. Are timestamps needed for the fact-based model? If so, why?
Yes because he timestamps make each fact immutable and eternally true.

4. What is the difference between information and data? 
Data is raw information that can't be derived from anything else, information is a collection of knowledge , take for example a birthdate is data and a age is information, because you can tell how old is somebody by calculating it.
