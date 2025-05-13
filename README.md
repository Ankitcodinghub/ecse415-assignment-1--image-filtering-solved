# ecse415-assignment-1--image-filtering-solved
**TO GET THIS SOLUTION VISIT:** [ECSE415 Assignment 1- Image Filtering Solved](https://www.ankitcodinghub.com/product/ecse415-assignment-1-image-filtering-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92520&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECSE415 Assignment 1- Image Filtering Solved&nbsp;&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Thresholding

Thresholding is the simplest method of image segmentation. From a grayscale image, thresholding can be used to create binary images. Here, each pixel in an image is replaced with a foreground label (i.e. a white pixel with 255 value) if the image intensity Ii,j is satisfies some pre-defined condition (Ex. if Ii,j &gt; T ), or with a background label (i.e. a black pixel with 0 value) otherwise.

</div>
</div>
<div class="layoutArea">
<div class="column">
Simple Binary Thresholding:

Si,j = Inverse Binary Thresholding:

􏰀

Si,j = Window Binary Thresholding:

􏰀 255 Si,j= 0

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰀

</div>
<div class="column">
255 ifIi,j&gt;T; (1) 0 otherwise. (2)

255 ifIi,j&lt;T; (3) 0 otherwise. (4)

ifT1&gt;Ii,j &gt;T2; (5) otherwise. (6)

</div>
</div>
<div class="layoutArea">
<div class="column">
You are given an image named

multiple different multi-digit numbers. Your task is to threshold the image using the pre-defined conditions for thresholding defined above.

Note that you are not allowed to use the openCV cv2.threshold function for this task. Instead implement thresholding using basic python or numpy functions.

<ol>
<li>Threshold the image at three different thresholds 1) 55 2) 90 and 3) 150 us- ing simple binary thresholding and inverse binary thresholding as defined above. (3 points)</li>
<li>Write your observations about thresholded images at different thresholds. How many and which numbers are segmented at each threshold? (A num- ber is considered as segmented if all digits of that number are considered as foreground in the thresholded image) What else do you observe at each threshold? (3 points)</li>
<li>Threshold the image using Window binary thresholding using three dif- ferent range of thresholds. 1) T1=55 and T2=90, 2) T1=90 and T2=150, 3) T1=55 and T2=150. Write your observations. How many and which numbers are segmented at each threshold? (3 points)2</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
”numbers.jpg” (Figure 1(a)) which contains

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
(a) (b)

Figure 1: (a) Input image for thresholding, (b) Example of output image of thresholding. Note that only numbers ”123” and ”549” are segmented (fore- ground pixels).

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
4.

</div>
<div class="column">
In a practical application, we vary the value of the hyper-parameters (here, the threshold values) for any of the above mentioned thresholding meth- ods, such that we get the desired output. Find a threshold value such that only numbers ”123” and ”549” are segmented (i.e. considered as foreground – white pixel – 255 value). See Figure 1(b). Report your find- ing for at least three different threshold values, and write how it helped you in narrowing down the desired hyper-parameter value. (3 points)

Denoising

</div>
</div>
<div class="layoutArea">
<div class="column">
You are given a clean image named ‘lighthouse’ (Figure 2(a)) and an image corrupted by additive white Gaussian noise (Figure 2(b)). You are allowed to use OpenCV/Scikit-learn functions for this section.

Apply the following filtering operations:

<ol>
<li>Filter the noisy image using a 5 × 5 Gaussian filter with variance equal to2. (3 points)</li>
<li>Filter the noisy image using a box filter of the same size. (3 points)</li>
<li>Compare the Peak-Signal-to-Noise-Ratio (PSNR) of both of the denoised images to that of the clean image and state which method gives the supe- rior result. (Use the PSNR function provided by opencv) (3 points)</li>
</ol>
You are also given an image corrupted by salt and pepper noise (Figure 2(c)). Apply the following filtering operations:

<ol start="4">
<li>Filter the noisy image using the same Gaussian filter as used in the pre- vious question. (3 points)</li>
<li>Filter the noisy image using a median filter of the same size. (3 points) 3</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
(a) (b) (c)

Figure 2: Input images for denoising. (a) clean image (b) image corrupted with Gaussian noise (c) image corrupted with salt and pepper noise.

6. Compare the PSNR of both of the denoised images to that of the clean image and state which method gives a better result. (3 points)

3 Sobel edge detector (16 Points)

In this question, you will assess the effect of varying the kernel size on the results of an edge detection algorithm. You will detect edges in a clean image named, ‘cameraman’ (Figure 3(a)). You are allowed to use OpenCV/Scikit-learn

(a) (b)

Figure 3: Input image for edge detection. (a) clean image (b) image corrupted with Gaussian noise.

4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
functions for this section.

<ul>
<li>Apply a Sobel edge detector with the kernel size of 3×3, 5×5 and 7×7 to the image. Threshold the filtered image to detect edges. Use two values of thresholds: 10% and 20% of the maximum pixel value in the filtered image. (4 points)</li>
<li>Comment on the effect of filter size on the output. (2 points)

Next, you will evaluate the effect of denoising prior to edge detection. Forthe following questions, you will use noisy image as shown in Figure 3(b).</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
<div class="column">
<ul>
<li>Apply a Sobel edge detector with the kernel size of 3 × 3. Threshold the filtered image to detect edges. Use two values of thresholds: 10% and 20% of the maximum pixel value in the filtered image. (4 points)</li>
<li>Denoise the image with a 3 × 3 box filter and then apply the same Sobel edge detector, with the same values of the thresholds, from the previous question. (4 points)</li>
<li>Comment on the effectiveness of using denoising prior to edge detection. (2 points)</li>
</ul>
(a) (b)

Figure 4: (a) Input image for canny edge detection (b) expected output.

Canny Edge Detection (12 Points)

</div>
</div>
<div class="layoutArea">
<div class="column">
For this section, experiments will be performed on the ’dolphin.jpg’ (Figure 4(a)) image.

<ol>
<li>Briefly describe the 4 main steps of Canny edge detection. (2 points)</li>
<li>As you saw in Tutorial-2, the 3 main hyperparameters of Canny Edge detection are the Gaussian Smoothing Kernel size (K), and the Lower (L) and Higher (H) Thresholds used for Hysteresis. In this section, we will5</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
observe the effect of changing these hyperparameters. You will experi- ment on 3 different values for all 3 parameters (K = 5,9,13, L = 10,30,50, H = 100, 150,200). Vary the values of each hyper-parameter and keep other hyper-parameters constant. Do this procedure for all combination of hyper-parameters mentioned above. This should results in total 27 triplets of hyper-parameters. E.g. (K,L,U) = (5,10,100), (5,10,150), (9,10,200), …. Use canny edge detection (cv2.GaussianBlur and cv2.Canny) for each of these triplets. (4 points)

<ol start="3">
<li>Comment on how changing values of each hyper-parameters (K,L,U) ef- fects the overall edge detection. Is there is any relationship between any hyper-parameters? (3 points)</li>
<li>Find a value of each hyper-parameter such that only dolphin edges are detected. (Figure 4(b)) (3 points)(a)
(b)
</li>
</ol>
Figure 5: (a) checkerboard input image and expected harris corner output (red dots represents detecteed harris corners) (b) shapes image.

5 Harris Corner Detection (12 points)

Implement the Harris corner detector as described in class (lecture-5 slide-48 and tutorial-2) using numpy (5 points). This has the following steps:

1. Compute Image derivatives (optionally, blur first) 2. Compute Square of derivatives

3. Apply Gaussian Filtering on the output of step-2

6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>Get Cornerness function response (Determinant(H)-kTrace(H)2), where k=0.05. (You can vary value of k for your application)</li>
<li>Perform non-maxima suppression (as in the Canny edge detector)</li>
</ol>
You will apply Harris Corner Detector for three different images:

<ol>
<li>Checkerboard image Figure 5(a) (Input image). Change value of threshold to get detected corners similar to Figure (a) (Harris Corner). Observe and report affect of changing threshold values (3 points)</li>
<li>Shape image Figure 5(b). Try different value of thresholds and report your observations. (2 points)</li>
<li>Take any one face image from Google Face thumbnail collection dataset. Apply harris corner detector on this image. Try different value of thresh- olds and report your observations. (2 points)</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
