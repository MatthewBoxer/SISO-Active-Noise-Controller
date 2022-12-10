# SISO-Active-Noise-Controller

Secondary path code can be run separately before running the active noise cancelling code, but hardware delay might make it difficult. Current version of the secondary path code runs the measurement 20 successive times to observe if each audio stream has the same delay. The ANC code combines the secondary path measurement code with the noise cancellation code, with delay in between to start the disturbance signal. Multi-tone cancelling can be achieved using the same method in parallel for any amount of tones, but does not perform as well as single tone. Note that the frequency finding code does not return accurate frequency values but does get the right transfer function components, so the frequencies are hard coded in.

![image](https://user-images.githubusercontent.com/49496665/206829814-1c917060-522f-4fed-99e7-4a0ad6a59e52.png)
