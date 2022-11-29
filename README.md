# House-Price-Prediction
This is Bengaluru House Price Prediction model.
After uploading the dataset I removed few columns because we only require location,size,total_sqft,bath,price.
When null values were calculated columns bath and size had null values. So the null values of column size were droped and the null values of column bath were replaced by median of it. The file from which i took reference dropped all null values of both columns.
Now for removing the outliers I used median and standard deviation and the reference file used mean and standard deviation. I also tried of using median and variance but it decreased by accuracy from 84%(reference file) to 73% so the changed variance back to standard deviation
The final accuracy that I got is 88.24% which is higher than accuracy of the file I referred which had accuracy 84%.
According to me accuracy has improved because median is more precise value than mean. Also I got more values because i didn't dropped the null values but interchanged them with median.
