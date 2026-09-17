# OptiX compatibility

| OptiX family | Driver | GPU min | GPU officially supported | CUDA min | CUDA recommended | CUDA max |
| --- | --- | --- | --- | --- | --- | --- |
| 9.1 | R590+ | Turing 7.5+ | Blackwell 10.0 | 12.0 | 13.0 | 13.x | 
| 9.0 | R570+ | Turing 7.5+ | Blackwell 10.0 | 12.0 | 12.8 | 12.x | 
| 8.1 | R555+ | Maxwell 5.0+ | Ada Lovelace 8.9 | 11.x | 12.0 | 12.x | 
| 8.0 | R535+ | Maxwell 5.0+ | Ada Lovelace 8.9 | 11.x | 12.0 | 12.x | 
| 7.7 | 530.41+ | Maxwell 5.0+ | Ada Loveace 8.9 | 7.0 | 11.1 | 12.x | 
| 7.6 | 522.25+ | Maxwell 5.0+ | Ada Loveace 8.9 | 7.0 | 11.1 | 12.x | 
| 7.5 | 515.48+ | Maxwell 5.0+ | Ada Loveace 8.9 | 7.0 | 11.1 | 12.x | 
| 7.4 | 495.89+ | Maxwell 5.0+ | Ada Loveace 8.9 | 7.0 | 11.1 | 12.x | 
| 7.3 | 465.84+ | Maxwell 5.0+ | Ampere 8.6 | 7.0 | 11.1 | 12.x | 
| 7.0 | 435.80+ | Maxwell 5.0+ | Turing 7.5 | 7.0 | 10.1 | 12.x | 

PS : at OptiX 8.0+, you need win 8.1+ or linux rhel 4.8+ or ubuntu 10.10+

# GPU

"officially supported" doesn't mean "max", it means features are supported and tested, but a higher/newer GPU can still be used

GPU version, summarized for GeForce category :

| Micro-architecture | Compute capability (version) | GeForce products |
| --- | --- | --- |
| Maxwell | 5.x | GTX 750-980 |
| Pascal | 6.x | GTX 1010-1080 |
| Volta | 7.0-7.2 | TITAN V |
| Turing | 7.5 | GTX 1350 - RTX 2080ti |
| Ampere | 8.0-8.7 | RTX 3050-3090ti |
| Ada Loveace | 8.9 | RTX 4050-4090 |
| Blackwell | 10.0-12.1 | RTX 5050-5090 |

# CUDA to GCC compatibility

| CUDA family | GCC min | GCC max |
| --- | --- | --- |
| 7.x | 4.8 | 4.9 |
| 8.x | 4.8 | 5.x |
| 9.0 | 4.8 | 6.x |
| 9.1 | 4.8 | 6.x |
| 9.2 | 4.8 | 7.x |
| 10.0 | 5.x | 7.x |
| 10.1 | 5.x | 8.x |
| 10.2 | 5.x | 8.x |
| 11.0-11.1 | 6.x | 9.x |
| 11.2-11.4 | 6.x | 10.x |
| 11.5-11.8 | 6.x | 11.x |
| 12.0-12.3 | 6.x | 12.x |
| 12.4-12.6 | 6.x | 13.x |
| 12.8 | 6.x | 14.x |
| 13.0-13.1 | 6.x | 15.x |
| 13.4 | 6.x | 16.x |