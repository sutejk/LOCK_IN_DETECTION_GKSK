# LOCK-IN DETECTION

The pulse oximetry experiment relies on light measurement, and the signal received from the photodetector is very small. The operation was done at near DC frequency and noise levels are significant at low levels.
Earlier in the part-I of this project, we derived the noise floor of the system shown in figure 1. From figure 1, it is evident that the noise floor was very high due to operating at a frequency closer to 0Hz. Therefore, to reduce the noise floor of the system and create robust heartbeat detection, we need to shift the process in higher frequency domains. This will, in turn, increase the Signal to noise ratio, improving the system’s ability to detect the lower signals.
In this milestone, we modulate the heartbeat signal with the higher carrier frequency, and this modulated frequency is used to derive the final heartbeat of the person.

## "Heartbeat Detection using Lock in amplifier" YouTube video.
[Link](https://youtu.be/3yoKhLjXUSQ).

### Note:
TO create the MATLAB Square wave use this function.
 t = 0:1/481.88:8.5;
 sq_wav = square(2*pi*230*t,50);



