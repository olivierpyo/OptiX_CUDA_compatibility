# OptiX compatibility

OptiX 9.x
- Driver :
	- OptiX 9.0 : R570+
	- OptiX 9.1 : R590+
- GPU :
	- min : Turing 7.5+
	- officially supported : Blackwell 10.0+
- CUDA :
	- min : 12.0
	- recommended :
		- OptiX 9.0 : 12.8
		- OptiX 9.1 : 13.0
	- max : 
		- OptiX 9.0 : 12.8
		- OptiX 9.1 : 13.x

OptiX 8.x
- Driver :
	- OptiX 8.0 : R535+
	- OptiX 8.1 : R555+
- OS : win 8.1+ or linux rhel 4.8+ or ubuntu 10.10+
- GPU :
	- min : Maxwell 5.0+
	- officially supported : Ada Lovelace 8.9+
- Compute capability : 5.0+
- CUDA :
	- min : 11.x
	- recommended at OptiX 8.0: 12.0
	- max : 12.x

OptiX 7.x
- Driver :
	- OptiX 7.0 : 435.80+
	- OptiX 7.3 : 465.84+
	- OptiX 7.4 : 495.89+
	- OptiX 7.5 : 515.48+
	- OptiX 7.6 : 522.25+
	- OptiX 7.7 : 530.41+
- GPU :
	- min : Maxwell 5.0+
	- officially supported :
		- Optix 7.0 : Turing 7.5+
		- Optix 7.3 : Ampere 8.6+
		- Optix 7.4 : Ada Loveace 8.9+
- Compute capability : 5.0+
- CUDA :
	- min : 7.0
	- recommended :
		- OptiX 7.0 : 10.1
		- OptiX 7.3+ : 11.1
	- max : 12.x

## GPU 

"officially supported" means features are supported, but a higher/newer GPU can still be used

GPU version quickly summarized for GeForce :
Maxwell = GTX 750-980
Pascal = GTX 1010-1080
Volta = TITAN V
Turing = GTX 1350 - RTX 2080ti
Ampere = RTX 3050-3090ti
Ada Loveace = RTX 4050-4090
Blackwell = RTX 5050-5090

# CUDA to GCC compatibility 

| CUDA family | GCC supported range |
|---|---|
| **7.x** | **4.8 – 4.9** |
| **8.x** | **4.8 – 5.x** |
| **9.0** | **4.8 – 6.x** |
| **9.1** | **4.8 – 6.x** |
| **9.2** | **4.8 – 7.x** |
| **10.0** | **5.x – 7.x** |
| **10.1** | **5.x – 8.x** |
| **10.2** | **5.x – 8.x** |
| **11.0–11.1** | **6.x – 9.x** |
| **11.2–11.4** | **6.x – 10.x** |
| **11.5–11.8** | **6.x – 11.x** |
| **12.0–12.3** | **6.x – 12.x** |
| **12.4–12.6** | **6.x – 13.x** |
| **12.8** | **6.x – 14.x** |
| **13.0–13.1** | **6.x – 15.x** |
| **13.4** | **6.x – 16.x** |
