# BrainTumorClassification
<h2>Overview</h2>
<p>
The important factor in the medical diagnosis include the medical image data obtained from various biomedical devices that uses different imaging techniques like X-ray, CT Scan, MRI. The conventional method for tumor detection in MRI image is human inspection. This method is very time consuming. It is not appropriate for large amount of data. In this model an efficient automated classification technique for brain MRI is proposed using machine learning algorithms. The CNN machine learning algorithm is used for classification of brain MR image.
</p>
<p>
<b>Project Link Online Deployed on Heroku : <a href="https://brain-tumor-classifier1.herokuapp.com/">https://brain-tumor-classifier1.herokuapp.com/</a></b>
</p>
<hr>
<h2>Dataset and Libraries</h2>
<p>
<b>Dataset : <a href="https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection">https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection</a></b><br>
<b>Libraries : </b>Python , Numpy , Pandas, Sklearn , Node.js , Tensorflow.<br>
<b>Frameworks : </b>VScode , jupyter Notebook , Heroku.<br>
</p>
<hr>
<h2>Project Methodology</h2>
<p>
In this project I have developed a machine learning model to detect the presence of tumor in MRI scans of different people. The steps used in developing the machine learning model are of the one that are used in CNN.<br><hr>
<b>Below is brief description of every step and technique used for CNN based Classification:</b><br>
In the training phase, preprocessing, feature exaction and classification with Loss function is performed to make a prediction model. Initially, label the training image set. In the preprocessing image resizing is applied to change size of the image.<br>
Finally, the convolution neural network is used for automatic brain tumor classification. The brain image dataset is taken from image net. Image net is a one of the pre-trained model.Convolution filter is applied in the first layer and the sensitivity of filter is reduced by smoothing the convolution filter (i.e) subsampling. Then we fasten the training period by using rectified linear unit (RELU). The neurons in proceeding layer is connected to every neuron in subsequent layer<br>  
</p>
<hr>
<h2>Screenshots of the working Webapp</h2>
<b><p>Initial Page.</p></b>
<img src="img/the1.png">
<b><p>After uploading the MRI scan.</p></b>
<img src="img/the2.png">
<b><p>Getting the required result after classification.</p></b>
<img src="img/the3.png">
<hr>
<h2>Running the Project</h2>
<p><b>1. Accesing the website online </b></p>
  <p> To access the website and check its working you can visit this link <a href="https://brain-tumor-classifier1.herokuapp.com/">https://brain-tumor-classifier1.herokuapp.com/</a> <br>
 <p><b>2. Copying to local repository </b></p>
  <p> In your terminal run the following commands : <br><br>
     <b>
     git clone https://git.heroku.com/brain-tumor-classifier1.git<br>
     cd brain-tumor-classifier1<br>
     python app.py<br>
     Open https://localhost:3000 <br>
     </b>
  </p>
 <hr>
 <h2>Methodology</h2>
 <img src="img/the5.jpg">
 <hr>
 <h2>Contributors</h2>
 <p><a href="https://github.com/ElvisSethi">Elvis Sethi</a></p>
 <hr>
