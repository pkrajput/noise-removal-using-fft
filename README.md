# noise-removal-using-fft
experimenting with filters and space mappings to remove noise from images 
Random noise is added to a greyscale image 
experimenting with variables of gaussian and butterworth filter using fft maping to a different space while splitting it to amplitude and phase
translating this mapped space linearly to the high intensity regions and using inverse fft to get the the origional image back
compare the final image with the origional using SSIM and PSNR and finding the ideal values of these filters 
