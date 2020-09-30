In this repository sits the code as part of the technical experiment we ran in our MSc Dissertation.

I built this code to run exclusively on a Google Colab environment and would recommend if you do not have already to run this code as a Google Colab project. (Although the code should run in a Jupyter environment too but may need some tweeking as I used a magic function which may not be compatable in a Jupyter environement.)

To create a Google Colab environment, you will need a Google account and can access the Google Colab environment using the following link:

https://colab.research.google.com/notebooks/intro.ipynb

Once you are in Google Colab, you will need to upload all the files to the drive but after this the process should be self explanitory.

We have provided two datasets for you to investigate for yourself the effectiveness of our system. You can also tweak the number of times you iterate the model (We have set this to a default of 4), alongside the size of the batch you wish to process (We have set the default size to 5).

If you do extend the batch size, make sure you have enough ram in your device so that the enviorment does not crash while running the model.

In short, we have used the ALBERT model to output an accuracy score and an interpretation of a dataset containing real and fake information on the Coronvirus. As the first model of its kind it is difficult for us to effectively benchmark this model but from our perspective it seemed to run accurately most of the time. Where possible, we have given credit to external sources utilized in the code.

Any trouble running this model, please do not hesitate to contact me.

Arron Hovingham
