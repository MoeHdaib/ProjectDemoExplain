# Project Demo | Detecting Covid-19 from x-ray images:
* train_covid19.py is done by [Adrian Rosebrock](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/).

* X-ray images datasets from Dr. Joseph Cohen [GitHub](https://github.com/ieee8023/covid-chestxray-dataset).


-------
#### Notes:

1. Put all the code files and the dataset file in the same directory.

1. First, you need to train the model by executing the **train_covid19.py** script with `python train_covid19.py --dataset dataset`
(after you already downloaded tensorflow and keras on your computer).
    
1. After you execute it successfully (it will take some time) a new **covid19.model** file should appear in the directory file.

1. Flash the **Particle_code** file to your particle device.

1. Open the **GUI_code.py** file and Replace **your-device-ID-goes-here** with your **actual device ID** and replace **your-access-token-goes-here** with your **actual access token**, in line **52** and **57**.

1. Transfer the **GUI_code.py** and the **covid19.model** file to your Raspberry Pi device.

1. Connect to your Raspberry Pi remotely and then execute the **GUI_code.py**.


-----


> If you are having problems downloading tensorflow and keras on your Raspberry Pi device, try follow my guide [here](https://www.hackster.io/moe-hdaib/detecting-covid-19-from-x-ray-images-d4fd38).

-----
![Deakin][logo]

[logo]: https://d1yjjnpx0p53s8.cloudfront.net/styles/logo-thumbnail/s3/042014/deakin_univerity_0.png?itok=FRUYHSNi "Deakin University"


### SIT210 - Embedded Systems Development
