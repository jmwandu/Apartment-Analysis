# Apartment-Analysis

Download the chrome driver from here:
http://chromedriver.chromium.org/downloads
This is the one I choose to use but this can easily be replaced by any other browser withou issue. For the fastest execution speed I'd recommed using phantom.js since its headless and doesn't consume time rendering the page.

Other setup Information of Relevance:
I used anaconda python and downloaded the following depandancies through conda:
    *python Selenium 
    *pandas
    *numpy
    *matplotlib

It's considered best practice to use and enviroment of some kind when doing projects in python which is exeactly what I did in this project as well. For those that decided to setup enviroments in python heres a the sets that I took:

1) conda create --name myenv
2) when the following appears "proceed ([y]/n)?" press Y/y

Download the following package (Ipykernel) from anaconda with the following command:
    *conda install ipykernel

Then run the following command to create and eniviroment:
    *source activate <Your enviroment name>
   
After this is compeleted you'll be have an enviroment that can be assessed from a jupyter notebook 