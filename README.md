# mcqoe
the QoE dataset， videos have been uploaded to Google Drive the link: 
https://drive.google.com/file/d/1mFytmSLLfnOv7nVS31fJIrLnmsMMRdsI/view?usp=sharing 

the .xlsx files are named by videoname+x+y, videoname represents the name of the video, x represents the total time of rebuffering in the video，y represents the total times of rebuffering in the video;
for example, sport42 means the video named sport has rebuffered 4 seconds while playing, each time of rebuffering lasts 2 seconds.

In the xlsx file, the 'time' column is in seconds, psnr, ssim, ms-ssim, and vmaf are measured using the MSU Video Quality Measurement Tool Free 14.1 software, and bitrate is in kbps; mos-tv, mos-phone, and mos-pc are the continuous MOS values corresponding to three devices, respectively. Nrebuffers indicates whether there is rebuffering during the video playback at the current time, and TSL stands for 'time since last rebuff'. CI-tv, CI-phone,CI-PC represents the upper and lower bounds of the 95% confidence interval corresponding to three devices, respectively.


H. Yang, T. Lin, Y. Zhang, Y. Xu, Z. Chen and J. Yan, "Enhancing QoE for Multi-Device Video Delivery: A Novel Dataset and Model Perspective," in IEEE Transactions on Broadcasting, doi: 10.1109/TBC.2024.3443544.
https://ieeexplore.ieee.org/document/10654321
