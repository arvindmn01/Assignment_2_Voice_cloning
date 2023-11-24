# RVC Inference for Elon musk voice (assignment 2)
This is the repo for cloning anyone voice to the Elon musk voice. 
<br>
<br>
# Steps to start the application.
1. I would recommend you to create new python environment and then install the required python packages using the below command. <br>
 **Note.** this application supports the python version less than `python 3.11`, you can use `python 3.10` for this application. 
                 `pip install -r requirements.txt`
<br>
2. Download the `hubert_base.pt` model from the given drive link.
**Huber Model link** - https://drive.google.com/file/d/1sGolIaW7Rc_8hNUy3_PUbpNH0xJ3wdIM/view?usp=drive_link
  after downloading the hubert base model, copy the model to the same project folder.
<br>
<br>
3. Dowload the Elon Musk pretrained RVC model and index file using the link given below.
**Model Link** - https://drive.google.com/file/d/15Pq8WnOCFUNZVIxOWBgVXwSOcVlUWB1E/view?usp=drive_link <br>
and **Index file link** - https://drive.google.com/file/d/1dS86FM2PCHn_6DfND6L86nPxiapCS8-2/view?usp=drive_link
   after downloading the model ( `.pth` file) and index file ( `.index` file) copy `.pth` file to the `weights` folder and `.index` file to the `weights\index` folder.
<br>
<br>
4. run the application using this command
`python infer.py` it will give you local host URL copy and paste that url to any browser,
there you can see the entire application you just need to select the model and index file, and then after drag and drop the input voice file and set the different hyper parameters and also set the pitch extraction algorithm.


after that click on convert button, you will see the progress and at the end can download the file.
<br>
application Screenshot.
<br>
![image](https://github.com/arvindmn01/Assignment_2_Voice_cloning/assets/100796728/b8972a69-0523-4fd6-b452-74d5ec86318d.png)
<br>
<br>

You can see the performance of model, go to the result folder and there you can see the input and output audio files.
<br>
Input file contains my own voice and output file contains the cloned Elon musk Voice.
