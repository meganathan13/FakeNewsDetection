# FakeNewsDetection

Multilingual Fake News Detection Using Ensemble Learning.
-----------------------------------------------------------------------------------------------
Short Note:
 we used ensemble method to predict whether the given news text is true or fake. Here we used it for multiple languages
and rather than using runtime to predict test datas we used website which is done using flask to predict the output.


URL/Source Dataset links:

1.The Following Link consists of dataset for English language:

2.The Following Link consists of dataset for Hindi language:

3.The Following Link consists of dataset for German language:

4.The Following Link consists of dataset for Bangla language:

5.The Following Link consists of dataset for French language:

-------------------------------------------------------------------------------------------------
Software/Hardware Requirements:

Software requirement: Colab Notebook(for ipynb file)
                      Flask(for web intergration)
                      Ngrok(used to run flask in runtime in colab itself rather than deploying in separate server)

Hardware requirement: 
--------------------------------------------------------------------------------------------------
Detailed Instructions to execute source code:

1. Import the fake_news.ipynb file in colab notebook.

2.Import all dataset in drive link so that we can access the dataset everytime without importing evertime in colab runtime. 

3. Create a folder named "templates" in colab and import "index.html" file in the templates folder.

4. Create a folder named "static" in colab and create another folder inside the static folder named "images" 
and import all images(which is inside the templates folder now) in the images folder.

5.run the file in colab notebook as it run for multiple languages it will create different pickle file in
runtime as it is used in web intergration.

6.login into ngrok website using the mail id and copy the authentication link for that particular mail id.

7.Copy that authentication link and paste in the last second cell of colab notebook

i.e., !ngrok authtoken <your authentication link>

8.Atlast the flask will create multiple links in runtime ,click the second link as it will open new web page in new tab. 

9.The webpage consists of text area where we have to enter text of any given languages.For testing purpose we kept a separate file named "test"
to predict the outputs.
-----------------------------------------------------------------------------------------------------
