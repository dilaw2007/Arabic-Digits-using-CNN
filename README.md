# Arabic-Digits-using-CNN
using deep learning approch to classify arabic digits using Convolutional Neural Betworks


You can download the dataset from this link:
http://datacenter.aucegypt.edu/shazeem/


I only used 25000 images from the 60000 images.

You can use all of them if you have a good computational resources.

Note: You have to alter the code in this section.

for f in range(1,6):  ####   change 6 to 14, and it will work fine.
	for w in range((50*(f-1))+1, ((50*(f-1))+1)+50):
		for i in range(1,11):
			for j in range(0,10):
