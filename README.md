# **Overview**

Advisory Services Team at Accountability Accounting is interested in offering a new cryptocurrency investment portfolio.  The requirement was to create a report that included which cryptocurrencies were on the market and how they could be grouped by creating a classification system for the new investment portfolio.

# **Results**

* First the data was cleaned and processed for PCA:

![Processed Data for PCA](https://user-images.githubusercontent.com/78942457/123572900-f331e180-d79a-11eb-9604-d45d5e25a044.PNG)

* The data dimensions were then reduced to three primary components by using PCA:

![Principal Components](https://user-images.githubusercontent.com/78942457/123573041-355b2300-d79b-11eb-939f-831d9eefa54c.PNG)

* Clusters were created using K-means:

* *K-means of 4 was found using the elbow curve:*

![Elbow curve](https://user-images.githubusercontent.com/78942457/123573181-79e6be80-d79b-11eb-9499-6f4c1e43d50c.PNG)

* *A new dataframe was created using the results of the k-means process:*

![kmeans df](https://user-images.githubusercontent.com/78942457/123573293-aa2e5d00-d79b-11eb-85cd-3a4b9bf59ec4.PNG)

* Finally a 3D visualization was created using the data:

![3d](https://user-images.githubusercontent.com/78942457/123573360-caf6b280-d79b-11eb-9af1-74ca1e654017.PNG)

* *A final dataframe and cluster plot were generated:*

![final df](https://user-images.githubusercontent.com/78942457/123573448-fd081480-d79b-11eb-8fa8-4a7bfc40accf.PNG)

![Final scatter](https://user-images.githubusercontent.com/78942457/123573454-fed1d800-d79b-11eb-80e4-fc78138406a9.PNG)

