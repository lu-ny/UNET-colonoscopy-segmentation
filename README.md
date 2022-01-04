# biweekly-report-5-sgreenlund3
biweekly-report-5-sgreenlund3 created by GitHub Classroom

In these notebooks, I explore implementing segmentation with UNET for biomedical data. I am using colonoscopy images from the kvasir-seg dataset. These are comprised of colonoscopy images with polyps with corresponding masks made by doctors. 

I first worked on the unet-50epoch workbook, and found that the model had better results at lower epochs. So, I duplicated the ontebook and ran 10 epochs, which was also beneficial for speed to better look at my results. Lastly, I try implementing a UNET++ model to see if it gets better results. 

I compare my results primarily by binary cross entropy loss, which seems to be common for segmentation work. I plotted the training and test loss per epoch, and also displayed an example image of the prediction. I had some trouble with getting the prediction image to display correctly. At times, it would appear as what would be expected (black with white segmentation), at other times it would be nonsensical, and I'm not entirely sure why. 
Despite this, I had fun learning to implement segmentation, and would love to have spent more time on optimizing my models. 
