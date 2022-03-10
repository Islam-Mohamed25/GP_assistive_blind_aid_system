# GP_assistive_blind_aid_system
This repo is about my final year graduation project.
The project is aiming to provide a means for visually impaired and blind people to navigate in indoor environment safely.

The prototype in its simplest form is an assistive system for the visually impaired through wearable attachments.

- We will consider two main subsystems to provide the aid:
A) Object detection system: Utilizing a camera which takes a live video (frame images) and send them to the Raspberry Pi, then
the Raspberry can process these frames applying a deep learning model on them. and therefore, camera detect each object in 
each frame, now, we have got the information from the image signal. We will consider a simple feedback mechanism for this 
sub-system. So, the feedback output can be made via converting object name to speech that visually impaired people can hear 
it through a speaker (hand free).
B) Distance measuring system: Utilizing an Ultrasonic to provide the signals for near objects and obstacles distances. Those signals 
can be processed and translated through haptic motors feedback which can indicate the relative position of the obstacle.
Our scenario case, we are considering right now is helping visually impaired to navigate and recognize objects at indoor (enclosed)
environments. This can be developed further for including outdoor environment as a future plan by developing the deep learning model.
How we can measure the performance?
- System accuracy: by achieving the project goal actually helping the visually impaired people to navigate safely recognize objects correctly
- System quality: this can be measured as customer satisfaction on the usage.
- System robustness: easy to maintain and operate.

The team worked on this:
1- Islam Mohamed Kamal
2- Karam Nasser El Dien
3- Mohamed Fareed Gad
4- Mohamed Saber El Sayed
5- Mahmoud Ahmed Ibrahim
6- Romany Tawfeeq Aziz

Supervisored by :
Dr. Mostafa Salah
Dr. Ahmed Farghal
Eng. Khaled Abd El Gaber

Sohag University
