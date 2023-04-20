# Fashion_MNST

Given the \href{https://github.com/zalandoresearch/fashion-mnist}{Fasion-MNIST dataset}, \textbf{train} an unsupervised learning neural network that gives you a lower-dimensional representation of the images, after which you could easily use tSNE from \texttt{Scikit-Learn} to bring the dimension down to 2. \textbf{Visualize} the results of all 10000 images in one single visualization.


First I used Autoencoder with linear model reducing the dimensions to 2. Then added linear model reducing the dimension to 8 and applied TSNE. Both of these approach give poor classification results. So, at last, I changed autoencoder model to include convolution layers which can capture the features better and applied TSNE. Following figures show each step's results 


<p float="left">
  <img src="https://user-images.githubusercontent.com/57395643/233425046-378293ca-0ae5-4c6c-bd69-480efddad9e3.png" width=300 height=200 alt="Linear"/>
  <img src="https://user-images.githubusercontent.com/57395643/233425090-c98509d9-54b8-492b-98da-5cebc327c9f5.png" width=300 height=190 alt=""/>
</p>

<img src="https://user-images.githubusercontent.com/57395643/233425046-378293ca-0ae5-4c6c-bd69-480efddad9e3.png" width=300 height=200 alt="Linear"/><img src="https://user-images.githubusercontent.com/57395643/233425090-c98509d9-54b8-492b-98da-5cebc327c9f5.png" width=300 height=200 alt=""/>

<img src="https://user-images.githubusercontent.com/57395643/233425151-5b068830-6308-4528-82c4-24dcf9803102.png" width=300 height=220 alt=""/><img src="https://user-images.githubusercontent.com/57395643/233425219-a6820f15-00f7-4c51-8132-392ad1f578ef.png" width=300 height=200 alt=""/>

<img src="https://user-images.githubusercontent.com/57395643/233425443-5d32e070-9b17-44ee-8f02-2f9bfdb354e0.png" width=300 height=220 alt=""/><img src="https://user-images.githubusercontent.com/57395643/233425373-6ddd9f26-d55b-4919-b7ff-698cd5e1e120.png" width=300 height=200 alt=""/>
