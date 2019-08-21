# <b> iHearIT - the world's first intelligent hearing aid </b> 

## Note to readers
The version of the project showcased here is an abstract version of the real product but highlights the origin and thought process of the product.

<b> IPR 
This project has been presented at multiple platforms and has been endorsed by various govenment and private estblishments like GE Healthcare and VIT-TBI (Department of Science and Technology, Govt. of India). It is under developnment and is funded by VIT-TBI. The product is patented.
The purpose of this repository is to help readers gain technical insights over various domains of technology that intersected here and NOT to be considered as free for development at personal level.
</b>

## Working of conventional hearing aids:


Hearing aids are tuned finely based on the audiogram.

  

Audiogram is a graph which has the data of how a person hears a sound for different intensities and frequencies of sound.

  

Audiogram is made as a result of a clinical procedure called audiometry which is performed by specialists at clinics.

  

Generally, patients are recommended to visit the clinic once a month so that their hearing conditions can be checked again and their hearing aids can be fine tuned again based on the audiogram.

  

This process of treatment seems to be almost perfect but the acceptance rate of even the latest hearing aids seems to be low.

  

## Some factors which result in low acceptance rate of hearing aids as recognized by patients:

<b> Problem 1: </b>
Modern hearing aids which are tuned using audiogram are expensive.  
 
 <b>Problem 2: </b>
Signal to noise ratio is low which makes it difficult for the patient to use.

  

<b>Problem 3:</b>   
Hearing condition of the patients changes more frequently than every month which means audiometry and fine tuning of hearing aid needs to be done more frequently.
Since doctors to patients ratio is low, it’s generally not feasible for the doctors or patients to increase frequency of these appointments.

## Proposed solutions to the above mentioned problems:

  
Starting with Problem 3, the entire process of audiometry can be incorporated into a mobile phone based app and some minimal hardware such that the patient can do audiometry for themselves sitting at home.

The audiogram will be uploaded on a database which can be accessed by the doctor also.

About the process expected on app:

<b>Step 1:</b>
 
Login as a patient with the credentials.

<b> Step 2: </b>

On the headphone provided(or any of the prescribed headsets), various sounds will be played on the app ranging from frequencies of 250Hz to 8KHz and intensities of 10dB to 60dB. The patients can tap on the button ‘heard’ if they were able to hear the sounds clearly.

<b> Step 3: </b>

The audiogram will be generated on the app and will be uploaded on cloud. Throughout the process, a chatbot will guide the patients for different steps.

## Processing of data of audiogram:

 
Once the audiogram is on cloud, with the patients’ feedback as data points on the data space of frequencies and intensities.
CART, Random Forests and Prescriptive analysis algorithms can be used.
Once the analysis is done online, the patient will get the updates on the present fine tuning scheme on the app.

  <b> Tuning the hearing aid: </b>
  
A hearing aid is basically a system of ergonomic earphones and microphones. This system will be connected to the app via bluetooth.

The data of audio will be sent to microphone will be sent to the mobile phone in real time.

The audio will be processed by tuning scheme on phone and will be sent to the speakers (headset).

<b>Signal to Noise Ratio:</b>

Since the data of sound is being sent, it’s possible to have a intensity to frequency graph of the audio.


By analysing sound samples collected, it’s possible to use unsupervised learning algorithms like self organizing maps, it is possible to find and eliminate spectral components which are categorized as noise.

This way since there is no computation performed on the headset, the cost will be reduced significantly.

## The Cost: 

Since most of processing hardware is not required anymore, hearing aid which is generally around Rs.20,000 can be brought down to around Rs.5000, 25% of the original cost, hence solving Problem 1 mentioned in the previous section.
