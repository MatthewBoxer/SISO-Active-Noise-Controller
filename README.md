# SISO-Active-Noise-Controller

Description of project and results can be found in Active Noise Control Final Report.

To actually run the code it should be noted that:
Secondary path code can be run separately before running the active noise cancelling code, but hardware delay might make it difficult. The ANC code combines the secondary path measurement code with the noise cancellation code, with delay in between to start the disturbance signal. Multi-tone cancelling can be achieved using the same method in parallel for any amount of tones, but does not perform as well as single tone. Frequency values are currently hard-coded.

![image](https://user-images.githubusercontent.com/49496665/206829814-1c917060-522f-4fed-99e7-4a0ad6a59e52.png)
