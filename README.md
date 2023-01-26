# Smart-Handwash-System-to-Overcome-SSI-problem-in-Hospitals
To avoid Surgical Site Infections (S. S. I), it is vital to wash  hands adequately for at least 3 minutes using the World  Health Organization's standard guidelines. To guarantee adequate hand hygiene, the World Health  Organization has given six alternative hand washing routines.


The smart hand wash system will properly monitor hand 
positions in accordance with World Health Organization 
recommendations. With the help of deep learning and 
image processing, the camera module will scan the 
positions of the hands and match the exact positions with 
the fetched images in the code. If any of the users' or 
hospital staff's hand positions are not correctly recognized
or go wrong in any way, the buzzer will sound, alerting the 
user, and the image of the incorrect hand position will be 
placed in the database for proper monitoring and action.



![flowchart of ssi](https://user-images.githubusercontent.com/73397818/214876406-425ff147-174e-4714-be85-5219e442bca0.png)
Since we are deploying a Continuous Monitoring Unit (C. M. 
U.) that will continuously monitor the user's hand locations 
for three minutes, someone will need to wash their hands for 
three minutes.
The World Health Organization has established six distinct 
hand washing strategies, each of which should take no more 
than 30 seconds. A camera will now capture the hand process 
every 5 seconds for the next 30 seconds. If the participant 
fails to apply the proper hand technique, the camera will 
observe and give them an extra 10 seconds to alter their hand 
position in accordance with the requirements. If the person's 
hand placements remain unchanged, the buzzer will sound.
After the first 30 seconds have gone, the machine will 
continue with the next hand process for another 30 seconds.
The software element of the system is built with the strong 
Open CV library. The library includes around 2500 
algorithms, including a variety of computer vision and 
machine learning methods. These algorithms can be used to 
track camera movements, identify moving objects, classify 
human actions, and detect and recognize a variety of faces, and recognize items. It is compatible with Windows, 
Linux, Android, and Mac OS, and it includes C++, Python, 
Java, and MATLAB interfaces.
The doctor's arrival and leave timings, as well as the overall 
amount of time spent hand cleaning, will be recorded in the 
database. This project is being tested in real time
