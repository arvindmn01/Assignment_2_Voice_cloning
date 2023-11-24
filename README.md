# RVC Inference for Elon musk voice (assignment 2)
This is the repo for cloning anyone voice to the Elon musk voice. 
<br>
<br>
# Steps to start the application.
**1.** I would recommend that you create a new Python environment and then install the required Python packages using the following command <br>
 **Note.** this application supports the python versions less than `python 3.11`, you can use `python 3.10` for this application. 
                 `pip install -r requirements.txt`
<br>
**2.** Download the `hubert_base.pt` model from the given drive link.

**Hubert Model link** - https://drive.google.com/file/d/1sGolIaW7Rc_8hNUy3_PUbpNH0xJ3wdIM/view?usp=drive_link
  after downloading the hubert base model, copy the model to the same project folder.
<br>
<br>
**3.** Dowload the Elon Musk pretrained RVC model and index file using the link given below.

**Model Link** - https://drive.google.com/file/d/15Pq8WnOCFUNZVIxOWBgVXwSOcVlUWB1E/view?usp=drive_link <br>
**Index file link** - https://drive.google.com/file/d/1dS86FM2PCHn_6DfND6L86nPxiapCS8-2/view?usp=drive_link <br>
after downloading the model ( `.pth` file) and index file ( `.index` file) copy `.pth` file to the `weights` folder and `.index` file to the `weights\index` folder.
<br>
<br>
**4.** run the application using this command<br>
               `python infer.py` 
<br>
Copy the provided local host URL and paste it into any web browser. This will launch the application, where you can select the appropriate model and index file. Next, drag and drop the input voice file, adjust the hyperparameters, and configure the pitch extraction algorithm.<br>
Once you click the 'Convert' button, you'll be able to monitor the progress. Upon completion, the resulting audio file will be displayed. You can then download the converted audio file
<br>
<br>
application Screenshot.
<br>
![image](https://github.com/arvindmn01/Assignment_2_Voice_cloning/assets/100796728/b8972a69-0523-4fd6-b452-74d5ec86318d.png)
<br>
<br>

To evaluate the model's performance, navigate to the results folder. There, you can find the input and output audio files.
<br>
The input file contains my voice, while the output file contains the cloned Elon Musk voice.
<br>
<br>