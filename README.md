# NCTU new_e3 captcha_verify

scrape.py is a Web Crawler program to download huge training captcha file.<br>
tt3.py is a background noise reduction program.<br>
tt44.py is a digit location detection program.<br>
tt55.py is a size normailizing program.<br>
train.py is a traning CNN model program.<br>
predict.py is a predict captcha program.<br>
selepublic.py is a final intergrating login program.<br>
selepublic_v2.py is multi-thrading implemented version.<br>
split_digits_in_img.py is a neccessary code file for selepublic.py and selepublic_v2.py make sure you are downloaded.<br>
<br>
1. In selepublic.py you should input your own username and password in advanced(#215,216), then selepublic.py will input them in execution step.<br>
2. You only need to download selepublic.py and cnn_model.h5. ##NOTICE you should put those two files in same directory make it can load model. <br>
3. NOTICE you should install the chrome driver of selenium.<br>
4. You should check the path setting in the code and make the properly setting.<br>

Demo video
https://youtu.be/KA4EvdrpzaM
